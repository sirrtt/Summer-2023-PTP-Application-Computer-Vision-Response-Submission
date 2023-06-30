Requirement 1: Input Clip: https://drive.google.com/file/d/1-SDEzMYt4cBBVck6NRPHKzzvn3RW8hCH/view?usp=sharing

1a (Basic): Use any suitable library/framework to decompose the input clip into individual frames. Perform the following image processing operations on each frame:

-   Convert the frame to grayscale.

-   Flip the frame horizontally.

-   Rotate the frame by a random degree.

-   Add random noise to the frame.

After processing each frame, save them as individual image files in JPG format.

1b (Advanced): Utilize a pre-trained object detection model such as YOLO, SSD, or Fast-RCNN to detect objects in the input clip. Save the detected information of objects (FrameID, Object’s class, Object’s bounding box, Confidence) into a JSON file.

All the processed images are saved in the **processed_images** folder.
The JSON file contains the detected information of objects (FrameID, Object’s class, Object’s bounding box, Confidence) is **Detected_information_of_objects.json** file.
The code is in the Object_Detection.ipynb file.
