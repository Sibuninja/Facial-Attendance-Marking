
# Facial Attendance Marking System

A face recognition-based attendance system using Python, Tkinter, and OpenCV.

## Features
- Register new students with face images
- Save student profiles
- Mark attendance using face recognition
- Attendance records saved as CSV files
- Password-protected profile saving
- User-friendly GUI

## Requirements
See `requirements.txt` for dependencies.

## Interface Demo
![App Screenshot](assets/User%20Interface.png)

# Face Recognition Attendance System

Alt text: Screenshot of a Face Recognition Based Attendance System application interface. The interface is divided into two sections: For Already Registered and For New Registrations. The left section allows registered users to take attendance and displays an attendance table with columns for ID, Name, Date, and Time. The right section provides fields to enter ID and Name for new registrations, with buttons to clear input, take images, and save profiles. The interface shows the current date and time at the top, and indicates the total registrations as 2. The color scheme uses black, green, blue, yellow, and red, creating a functional and straightforward atmosphere. All visible text is transcribed in the description.

## Usage
1. Install dependencies:
	```
	pip install -r requirements.txt
	```
2. Run the application:
	```
	python main.py
	```
3. Use the GUI to register students, save profiles, and mark attendance.

## Folder Structure
- `main.py` : Main application file
- `StudentDetails/` : Student profiles (CSV)
- `TrainingImage/` : Training images for face recognition
- `TrainingImageLabel/` : Model and password file
- `Attendance/` : Attendance records
- `haarcascade_frontalface_default.xml` : Haar Cascade for face detection

## License
MIT License

## Author
[Sibuninja](https://github.com/Sibuninja)
