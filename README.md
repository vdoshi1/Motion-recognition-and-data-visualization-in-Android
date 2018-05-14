# Motion-recognition-and-data-visualization-in-Android
This project aims at creating a reliable motion recognition system in Android. The application allows user to record motion related accelerometer data during walking, running and jumping activities in an SQLite Database in mobile's internal storage. This data can then be visualised using a 3D plot and also be used to train SVM for classification of any random motion data in one of the 3 categories of motion namely 'Walking', 'Running' and 'Jumping'.

Android Version : 5 or above.

Installation instructions: After installation, you need to manually give permissions to the application to use device's internal storage. In order to do so, go to Settings->Application->Group27a3 and click on permissions and give storage permission. 

Run time instructions: On launching the application, the screen shows the following text box and buttons:

Top left text-box: Displays which motion data is being recorded i.e. W for Walking, R for Running and J for Jumping.

Top right text-box: Displays count number out of 20 number of a particular motion data recording (each motion is recorded 20 times)

Middle text-box: Displays whether Recording is ON or DONE and displays "Finished" at the end of all recording.

START button: Starts recording currently displayed motion data for 5 seconds.

RESET button: Resets data recording counts and motion type along with clearing database.

SVM train button : Trains SVM model with data to enable motion recognition.

PLOT : Plots 3D graph to help visualize data in the database.
