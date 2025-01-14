---
weight: 1
bookFlatSection: true
title: "PipeVision"
---

# **Week #1**

### **Team Members**

| Team Member            | Telegram ID   | Email Address       |
|------------------------|---------------|---------------------|
| Team Member (Lead) 1          | @a_n_a_s_t_a_s_i_a10 | a.barabanova@innopolis.university    |
| Team Member 2          | @mintnova | a.smirnova@innopolis.university    |
| Team Member 3          | @amirlansharipov | a.sharipov@innopolis.university     |
| Team Member 4          | @EveryoneHATEme | y.dementyev@innopolis.university   |
| Team Member 5          | @Guzel_Zakirova | guz.zakirova@innopolis.university    |
| (Optional) Team Member 6 | @sundariam | d.merzakreeva@innopolis.university     |
| (Optional) Team Member 7 | @shredding8 | e.zavrazhnov@innopolis.university     |


### **Value Proposition**
- The problem: 
Difficulty in rapidly and accurately recognizing the markings of pipeline elements based on their photo images.

- Solution Description:
Our project offers a video analytics module that automatically recognizes the marking of pipeline and metal elements.
The solution is unique within the projects we have been acquainted with.

- Benefits to Users:
Increased speed and accuracy of mark recognition, reduced errors, high productivity.

- Differentiation:
We did not find any similar projects in open sources. Anyway, here are selling points for our solution. Our system integrates with a database to store and retrieve the recognition results, which makes it a more comprehensive solution. Also, the solution has user-friendly interface that is appropriate to the customer.

- User Impact:
With this automated pipeline marking recognition system, professionals can significantly reduce the time and effort spent on manual and error-prone recognition tasks. This automation leads to higher productivity and cost savings.
Furthermore, the increased accuracy provided by our software reduces the risk of incorrect identification of pipeline markings, which could potentially lead to costly or even dangerous mistakes in pipeline construction or maintenance. Thus, our solution not only improves efficiency but also enhances safety in the industry.

- User Testimonials or Use Cases:
At this early stage of the project, we might not have real-world examples or user testimonials due to no interaction with the customer. But there is hypothetical use case based on our understanding of the industry and the problem we’re addressing:
"A pipeline construction company used our software to automatically recognize and catalog the markings on their pipeline components. They reported a 50% reduction in the time spent on these tasks, along with a significant decrease in recognition errors. This improvement allowed them to speed up their construction projects and reduce costs associated with errors."



## **Lean Startup Questionnaire**
1. What problem or need does your software project address?
2. Who are your target users or customers?
3. How will you validate and test your assumptions about the project?
4. What metrics will you use to measure the success of your project?
5. How do you plan to iterate and pivot if necessary based on user feedback?

### Answers
1. The need for rapid and accurate recognition of pipeline and metal marking based on photo images.
2. Workers of Gazstroyprom.
3. Gathering feedback from company, validation on dataset.
4. Speed and accuracy of mark recognition, user satisfaction.
5. Regularly conduct feedback sessions, and adjust our model and approach accordingly.

## **Leveraging AI, Open-Source, and Experts**
- AI (Artificial Intelligence): Image recognition with neural networks.
- Open-Source: Leveraging open-source machine learning libraries and frameworks for the system development.
- Experts in relevant domains: Professor from Innopolis university, Gazstroyprom mentor.

## **Inviting Other Students**
We have already formed a team of seven people from our course. Nevertheless, we are open for collabarations with other students, who are more expereinced, to create better solution.

## **Defining the Vision for Your Project**
- Overview: 
The project aims to develop an automated pipeline marking recognition system based on a neural network. The system addresses the challenge of manual pipeline and metal marking recognition, which is time-consuming, error-prone, and inefficient. Our solution provides automated, fast, and accurate recognition, enhancing productivity, reducing errors, and potentially improving safety in the pipeline construction and maintenance industry.

- Schematic Drawings:
![Schematic drawing](/PipeVision/schematicDrawing.png "Schema").

- Tech Stack:
The backend of the application will be developed using Python, leveraging its powerful libraries for image processing and machine learning, such as OpenCV and PyTorch or TensorFlow. The frontend will be built using a JavaScript framework React for its efficiency and flexibility. PostgreSQL will serve as the database management system due to its robustness and excellent performance. The neural network will be trained using YOLO, which is an efficient and effective object detection model.

- Anticipating Future Problems:
Obtaining sufficient high-quality data to train the neural network, ensuring the system can handle a large number of users or requests simultaneously, and ensuring the recognition accuracy is high enough to be useful in a real-world setting. Strategies to address these challenges could include data augmentation techniques, using a scalable backend framework, and continually improving and updating the neural network model based on user feedback and new data.

- Elaborate Explanations:
Our application can be divided into four main components: the frontend interface, the backend server, the database, and the neural network.
    1. The frontend interface allows users to upload images and view recognition results. It communicates with the backend server to send and receive data.
    2. The backend server handles requests from the frontend, processes images using the trained neural network, stores results in the database, and sends results back to the frontend.
    3. The PostgreSQL database keeps track of recognition results, allowing users to view past results and providing a source of data for further improvement of the neural network.
    4. The neural network is the heart of our system, responsible for recognizing pipeline markings in the images.
