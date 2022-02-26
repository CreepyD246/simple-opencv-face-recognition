# simple-opencv-face-recognition
This is a basic real-time face recognition program written in Python, and it uses the OpenCV Library, as well as the Face Recognition Library.

This Repository was created to aid the tutorial video made along with it on creating Python face recognition programs - https://youtu.be/RrE7Ipr93SA


##PIP installs

OpenCV - ```pip install opencv-python```

face_recognition - ```pip install face-recognition```


##Notes
- The program is real-time and uses your webcam, so make sure you have an active one. It can also detect multiple different people and their faces, but the more you add the slower the program becomes so take note of that.
- The program has a function called ```get_face_encodings()``` and a variable called ```faces_path``` which was set at the start of the program. Make sure to read the comments in the code above these 2 mentioned items, because you'd need to specify your own path to a folder with all known faces that you want to look for.
