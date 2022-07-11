# Face Detection and Record Maintenance  System 
 
 


A python GUI integrated attendance system using face recognition to take attendance with date and time.


## How does facial recognition work?

Many people are familiar with face recognition technology through the FaceID used to unlock iPhones (however, this is only one application of face recognition). Typically, facial recognition does not rely on a massive database of photos to determine an individual’s identity — it simply identifies and recognizes one person as the sole owner of the device, while limiting access to others.

**Step 1: Face detection**

The camera detects and locates the image of a face. The image may show the person looking straight ahead or in profile.

**Step 2: Face analysis**

Next, an image of the face is captured and analyzed. Most facial recognition technology relies on 2D rather than 3D images because it can more conveniently match a 2D image with public photos or those in a database. The software reads the geometry of your face. Key factors include the distance between your eyes, the depth of your eye sockets, the distance from forehead to chin, the shape of your cheekbones, and the contour of the lips, ears, and chin. The aim is to identify the facial landmarks that are key to distinguishing your face.

**Step 3: Converting the image to data**

The face capture process transforms analog information (a face) into a set of digital information (data) based on the person's facial features. Your face's analysis is essentially turned into a mathematical formula. The numerical code is called a faceprint. In the same way that thumbprints are unique, each person has their own faceprint.

**Step 4: Finding a match**

Your faceprint is then compared against a database of other known faces. For example, the FBI has access to up to 650 million photos, drawn from various state databases. On Facebook, any photo tagged with a person’s name becomes a part of Facebook's database, which may also be used for facial recognition. If your faceprint matches an image in a facial recognition database, then a determination is made.

Of all the biometric measurements, facial recognition is considered the most natural. Intuitively, this makes sense, since we typically recognize ourselves and others by looking at faces, rather than thumbprints and irises. It is estimated that over half of the world's population is touched by facial recognition technology regularly.


## Features

- Easy to use with interactive GUI support.
- Password protection for new person registration.
- Creates/Updates CSV file for deatils of students on registration.
- Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
- Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.


## Technology Used

- tkinter for whole GUI
- OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
- CSV, Numpy, Pandas, datetime etc. for other purposes.

## Screenshots

**Main Screen:**

![Screenshot (1)](https://user-images.githubusercontent.com/105539158/170645830-f9f31882-e399-4ece-acab-3c9f22e14220.png)


**Taking Attendance:**




**Showing Attendance Taken:**


