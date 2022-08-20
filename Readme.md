

## License Plate Detection And Recognition Using OpenCv And Pytesseract


## Introduction
Python gives us the ability to create our license plate detection and recognition program. We achieve this by using three of its libraries; pytesseract, imutils, and OpenCv.

License plate detection is identifying the part of the car that is predicted to be the number plate. Recognition is identifying the values that make up the license plate.

License plate detection and recognition is the technology that uses computer vision to detect and recognize a license plate from an input image of a car.

This technology applies in many areas. On roads, it is used to identify the cars that are breaking the traffic rules. In security, it is used to capture the license plates of the vehicles getting into and out of certain premises. In parking lots, it is used to capture the license plates of the cars being parked. The list of its applications goes on and on.

## The Process of application
|   **Steps**                       |  **Description**
|-----------------------------------|------------------------------------------------------------------------------------------------------------|
| Taking an image of a car as input | The program takes in the input of the car in which the license plate is to be detected.                    |
| Processing the input              | The image taken as the input undergoes processing to detect the part of the car that is the license plate. |
| Recognizing the number plate      | The values of the detected license plate are extracted from the number plate image.                        |


## Requirments installation

|  **library**                       |  **Description**                                                                                   |
|------------------------------------|----------------------------------------------------------------------------------------------------|
| pip install opencv-contrib-python  | We will use it to preprocess our image and also display the images that have undergone processing. |
| pip install imutils                | We will need this library to resize our images.                                                    |
| pip install pytesseract            | We will need this library to extract the license plate text from the detected license plate.       |