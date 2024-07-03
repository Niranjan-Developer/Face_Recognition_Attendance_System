 
  📸 Face-Recognition-Attendance-Management-System

An Attendance Management System based on Face Recognition using Python and OpenCV.

   🔧 Code Requirements

- OpenCV: `pip install opencv-python`
- Tkinter: Available in Python
- PIL (Pillow): `pip install Pillow`
- Pandas: `pip install pandas`

   🛠️ Setup Instructions

    Steps to Follow

1.   Download the Repository:
   - Clone or download this repository to your local machine.

2.   Create a Training Image Folder:
   - Inside the project directory, create a folder named `TrainingImage`.

3.   Update Paths:
   - Open the `AMS_Run.py` file and update all file paths with the paths on your system.

4.   Run the Application:
   - Execute `AMS_Run.py` to start the application.

   📂 Project Structure

1.   Collecting Face Data:
   - Enter your ID and name in the provided fields.
   - Click the `Take Images` button to capture 200 images of your face. These images will be saved in the `TrainingImage` folder.

2.   Training the Model:
   - Click the `Train Image` button to train the model. This process may take 5-10 minutes for data from 10 people.

3.   Automatic Attendance:
   - After training, click the `Automatic Attendance` button. The system will recognize faces and fill in attendance using the trained model. The model is saved in the `TrainingImageLabel` folder.
   - Attendance records will be created as `.csv` files based on the time and subject.

4.   Manual Attendance:
   - Use the `Manually Fill Attendance` button to manually mark attendance without face recognition. This also creates a `.csv` file and stores it in the database.

   📝 Additional Notes

-   System Requirements:
  - This project requires a system with high processing power (e.g., 8 GB RAM).

-   Image Quality:
  - Ensure that the captured images are of high quality. Noisy images can reduce the accuracy of the face recognition system.

-   Database Integration:
  - You can store attendance data in a database. Install WAMPServer and update the database name in the `AMS_Run.py` file as needed.
 