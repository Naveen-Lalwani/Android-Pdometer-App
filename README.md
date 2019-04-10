# Android_Pedometer_App
The app uses phone's accelerometer values to predict the number of steps taken by the user. After some basic processing of the signals using low pass fiter and moving average filter. The data is passed through a threshold following which the number of peaks in the waveform are detected and the steps counted are displayed. The graph always show the values of accelerometer along the 3 axis. <BR>
Since, the vector sum of acceleration is taken for processing and calculating steps, the phone can calculate steps independent of the orientation of the phone.
