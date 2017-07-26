# Shake-FFT
Made for a competition - Does an FFT on an IMU and sends via bluetooth to a display/logic layer

Basically, I knew what I was measuring wasn't going to oscilate around zero (hence ignoring 0Hz).
I knew that I didn't care about lower frequencies due to what I was measuring (hence ignoring 0-1.25Hz)

I didn't care about anything above 10Hz, and regardless I was only sampling at 20Hz, so wouldn't have been able to resolve those frequencies anyway.
