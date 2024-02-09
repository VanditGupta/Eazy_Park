# Eazy-Park 🚘

## Description

Eazy-Park is an advanced parking management system designed to streamline the parking process and enhance the user experience. Leveraging the power of Object Detection **(Masked R-CNN)** image segmentation technique, it offers an intuitive platform for users to monitor and manage parking spaces with enhanced accuracy and efficiency.

The application is designed to automate the parking process and provide real-time parking space availability information to users. It utilizes sophisticated image processing techniques for accurate analysis and offers a user-friendly interface for seamless interaction.

## Features

- **Automated Parking Management**: Quick and automated detection of parking spaces and vehicle occupancy.
- **Notification System**: Provides a simple text-based notification system to alert users about parking space availability.

## Technical Stack

- **Language:** Python
- **Machine Learning Model:** Mask R-CNN
- **Image Processing:** OpenCV, NumPy

## Usage

1. Provide the path to the video file to be analyzed in the **Hackathon (1).ipynb** file.
2. Run the notebook to initiate the analysis.
3. View the cell output to see the parking space detection and vehicle occupancy results.

## Screenshots

INITIAL STAGE: 

![](Images/Initial.png)

FINAL STAGE:

![](Images/Final.png)



<!-- Fast &amp; Efficient parking for users using Object Detection (Masked R-CNN)

The dataset used in this model is COCO Model (Common Objects in Context). COCO model helps in recognising 80 different types of objects.

A confidence score of the object detection is given. The higher the number, the more certain the model is that it correctly identifies the object.

The bounding box of the object in the image, given as X/Y pixel locations (Intersection over union) (IoU).

A bitmap “mask” that tells which pixels within the bounding box are part of the object and which aren’t. With the mask data, we can also work out the outline of the object. -->

## Team Members

This was a project made by the team **coding_capitals3**:\
                                    1. [Vandit Gupta](https://www.linkedin.com/in/vandit-gupta/)\
                                    2. [Akshit Diwan](https://www.linkedin.com/in/akshit-diwan/)\
                                    3. [Karan Garg](https://www.linkedin.com/in/karan-g-816b68114/)
                                    
for the hackathon : **Micrsoft** sponsored **Skillenza Student Hackday 2019, New Delhi**

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Please read the **CONTRIBUTING.md** file for more details.

## License

This project is licensed under the MIT License. Please read the **LICENSE.md** file for more details.

## Contact

For any inquiries or contributions, please contact me at [gupta.vandi@northeastern.edu](mailto:gupta.vandi@northeastern.edu)

## Project Status

Development for this project has completed. There are no plans for future updates or releases.
