# Heart_Rate_Estimation-OpenCV
Estimate the heart rate of a person from a given video

Algorithm works on the concept of Principal Component Analysis. Firstly detects the moving face of the person from the video continuously. Further, it detects the RGB color flowing constantly through the forehead of the person and calculates the change in green color pixel intensity value continuously because green color is the only one where the change can be detected easily. Thus the heart rate is detected and contantly displayed on the screen.
