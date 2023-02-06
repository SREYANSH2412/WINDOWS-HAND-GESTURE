
Developing a solution for Gesture enabled commands for operating Laptops/PCs for frequently used operations on daily basis.

- For any user, authenticated by face recognition, few gestures could be defined for frequently used tasks- save, exit, print, screen-lock, screen unlock, system shut down, system restart. 
- Save, print and exit operations are context sensitive meaning that it is applicable for current application. 
- For example, if word document is open and the gesture for save is done then the document will save, if print gesture is done then printer dialog will open etc. 
- Similarly, a gesture could be defined for close/exit which will close the current application. 
- If no application is opened, then it will work as system shut down. It is like Alt+F4 key press functionality on windows PC.


- Sample program
- Hand sign recognition model(TFLite)
- Learning data for hand sign recognition and notebook for learning

## Requirements
- mediapipe 0.8.1
- OpenCV 3.4.2 or Later
- Tensorflow 2.3.0 or Later
- scikit-learn 0.23.2 or Later (Only if you want to display the confusion matrix)
- matplotlib 3.3.2 or Later (Only if you want to display the confusion matrix)
