# Summer-2023-PTP-Application-Computer-Vision-Response-Submission
The challenge requires you to prove your skills in manipulating images using any computer vision libraries/frameworks. You also need to show your skills and understanding of basic deep learning algorithms. Please note that you can choose any programming language and tools that best align with your expertise and preferences for solving the questions.

Instructions: The topics in the training program for the computer vision major are developing tools and applications supporting society by leveraging the combined strength of computer vision techniques and deep learning algorithms. E.g., Building an application detecting deforestation with drones. Developing an application to enhance daily life support for individuals with visual impairments, etc.

Requirements: There are two requirements to identify your related skills to enter this training program.

Requirement 1: Input Clip: https://drive.google.com/file/d/1-SDEzMYt4cBBVck6NRPHKzzvn3RW8hCH/view?usp=sharing

1a (Basic): Use any suitable library/framework to decompose the input clip into individual frames. Perform the following image processing operations on each frame:

-   Convert the frame to grayscale.

-   Flip the frame horizontally.

-   Rotate the frame by a random degree.

-   Add random noise to the frame.
 
After processing each frame, save them as individual image files in JPG format.

1b (Advanced): Utilize a pre-trained object detection model such as YOLO, SSD, or Fast-RCNN to detect objects in the input clip. Save the detected information of objects (FrameID, Object’s class, Object’s bounding box, Confidence) into a JSON file.

Requirement 2: Create a tool to scrape and download 2000 images from any sources from the internet into 2 categories. Category 1 contains 1000 true images. Category 2 contains 2000 AI-generated images. Resize all images to 300 x 300.

Input: No

Output: 2 folders. Each folder contains 1000 images of true and AI-generated images.
