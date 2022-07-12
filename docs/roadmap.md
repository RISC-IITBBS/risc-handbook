# A Beginners Guide to Robotics

Robotics is actively engaged in the expanding problems of new developing sectors as it strives to reach the human frontier. The new generation of robots will increasingly interact, explore, and collaborate with humans, affecting people and their lives. 

The scientific endeavour of a half-century of robotic discoveries that created robotics as a contemporary scientific subject has resulted in the credible prospect of practical robots among humans. The field's vibrant expansion and robust growth over the previous decade has spurred our desire to innovate.

Following materials are compiled to help you get started in this field.

## How to Begin?

The most important thing for a novice is to begin learning a language since it opens up a world of possibilities in terms of projects to work on and activities to accomplish. Also bear in mind that after you've mastered one language, learning another is pretty simple. Different languages offer different benefits and could be use for a particular purpose respectively.

### Python

Python is also very popular due to its use in machine learning and also because it can be used to develop ROS packages.

*Resources*

* [Web Tutorial](http://introtopython.org/)
* [Youtube Tutorials](https://www.youtube.com/playlist?list=PL-osiE80TeTskrapNbzXhwoFUiLCjGgY7)

### C
C is a great way to learn the basics of this important language whilst doing hands-on robotics.

*Resources*

* [FreeCodeCamp Video Tutorials](https://www.youtube.com/watch?v=KJgsSFOSQv0)
* [GeeksforGeeks Resources](https://www.geeksforgeeks.org/c-programming-language/)
* [Beej’s Guide](http://beej.us/guide/bgc/html) 
* [Youtube Tutorial](https://www.youtube.com/watch?v=rLf3jnHxSmU&list=PLBlnK6fEyqRggZZgYpPMUxdY1CYkZtARR)

### C++
The Arduino microcontroller uses a programming language based on C++. C++ allows interaction with low level hardware, and also real time performance. C and C++ are very mature programming languages. To ensure the best performance of a robot, it will be better to use C++. As the robotics is very dependent on the real time performance, C and C++ are the best options.

*Resources*

* [YouTube Tutorials](https://www.youtube.com/playlist?list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb)
* [GeeksforGeeks Resources](https://www.geeksforgeeks.org/c-plus-plus/?ref=shm)
* [Web Tutorial](https://www.learncpp.com/)

### Elixir
*(for more advanced stuff)*

Elixir is a dynamic, concurrent, functional language designed for building scalable and maintainable applications.

*Resources*

* [Web Tutorial](https://elixir-lang.org/getting-started/introduction.html)
* [Youtube Tutorial](https://youtu.be/4W7AxdT3oe4)



## Development Environment

It's not as simple as entering into a text editor to write code. A compiler, external libraries, path environments, a terminal, version control, documentation, and other components are usually present. Don't worry if you don't understand what these terms signify; they collectively form your development environment. 
To begin, ensure that you are familiar with the following.

* *Linux Operating System*: The most well-known and widely used open source operating system is Linux. Linux is an operating system that lies beneath all of the other software on a computer, accepting requests from those programmes and transmitting them to the computer's hardware.One can use linux OS (either through ([dual booting](https://help.ubuntu.com/community/WindowsDualBoot)|[Youtube Tutorial](https://youtu.be/GXxTxBPKecQ)), [virtual machine](https://itsfoss.com/install-linux-in-virtualbox/) or [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10))

* *Linux Terminal*: The Linux terminal is a text-based interface used to control a Linux computer. It's just one of the many tools provided to Linux users for accomplishing any given task, but it's widely considered the most efficient method available.

    [YouTube Tutorial](https://youtu.be/oxuRxtrO2Ag)

* *Git & Github*: The Git version control system, as the name suggests, is a system that records all the modifications made to a file or set of data so that a specific version may be called up later if needed. The system makes sure that all the team members are working on the file’s latest version, and everyone can work simultaneously on the same project.
GitHub is a Git repository hosting service that provides a web-based graphical interface.

    [YouTube Tutorial](https://youtu.be/SWYqp7iY_Tc) | [Udemy Course](https://www.udemy.com/course/git-expert-4-hours/)


## Automation

### Robot Operating System (ROS)

The Robot Operating System (ROS) is not an actual operating system, but a framework and set of tools that provide functionality of an operating system on a heterogeneous computer cluster. Its usefulness is not limited to robots, but the majority of tools provided are focused on working with peripheral hardware.

*Resources*

Check out these Youtube Videos([Link 1](https://www.youtube.com/watch?v=N6K2LWG2kRI)|[Link 2](https://www.youtube.com/watch?v=LyC9RAYE96M))

* [ROS Tutorials](http://wiki.ros.org/ROS/Tutorials) 
* FAQ :- [ROS Answers](https://answers.ros.org/questions/)
* *Also refer* *[this blog](https://towardsdatascience.com/what-why-and-how-of-ros-b2f5ea8be0f3)*


### Path Planning

Path planning is the process of determining a path or trajectory for a robot by avoiding obstacles or adhering to set dynamic or kinematic constraints. It's something we do instinctively as humans, but robots find it difficult, so we try to make them intelligent by using path planning algorithms. Path planning is essential in robot automation because most robots must plan a path. Even in the case of robotic arms, moving the end effector from one spatial coordinate to another necessitates the planning of a trajectory that the arm must follow. The constraints and dimensions for planning the path or trajectory are different from those used in ground robot planning.

*Resources*

* [Book](http://msl.cs.uiuc.edu/planning/booka4.pdf) 
* [Open Motion Planning Library](https://ompl.kavrakilab.org/) (for implementation of algorithms in C/C++). 
* [GitHub Repository](https://github.com/zhm-real/PathPlanning) (in python)

### Simultaneous Localization and Mapping (SLAM)

SLAM (simultaneous localization and mapping) is a method used for autonomous vehicles that lets you build a map and localize your vehicle in that map at the same time. SLAM algorithms allow the vehicle to map out unknown environments. Engineers use the map information to carry out tasks such as path planning and obstacle avoidance.

*Resources*

* [Autonomous Navigation](https://www.youtube.com/watch?v=Fw8JQ5Q-ZwU&list=PLn8PRpmsu08rLRGrnF-S6TyGrmcA2X7kg) - playlist by  MATLAB
* [Youtube Course](https://www.youtube.com/playlist?list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_)

### Robot Perception

Robot perception is undervalued by beginners due to a lack of understanding of the difficulties involved. It's difficult to imagine how difficult it would be for a robot to observe, analyse, and extract usable data from a three - dimensional environment, because we're used to picking and putting objects with extreme precision in front of us. It's simple for us to stroll without stumbling over a branch. However, robots face a much more difficult situation. This element of developing intelligent robots is addressed in Robot Perception.

*Resources*

* [CS521 Notes](https://www.cpp.edu/~ftang/courses/CS521/notes/sensing.pdf)
* Checkout [Depth Maps Blog](https://medium.com/@Giscle/depth-map-depth-calculation-ce4d914c6afd)
* [The Robotics Institute Carnegie Mellon University](https://www.cs.cmu.edu/~mmv/papers/12icra-BiswasVeloso.pdf) paper.

Sensors play an important role in any robotic task. High-quality Cameras, LiDARs etc are used. To get started with perception by using images, OpenCV is a good starting point. For perception using Point Clouds, [Point Cloud Library](https://pointclouds.org/) is a good starting point(PCL can only be used via C++).

There are many advancements that are taking place. With the advent of Neural Networks, Convolution Neural Networks(CNN’s) are used to extract and analyse important information from depth maps thus enabling image and point cloud [segmentation](https://towardsdatascience.com/semantic-segmentation-with-deep-learning-a-guide-and-code-e52fc8958823), [classification](https://www.analyticsvidhya.com/blog/2019/01/build-image-classification-model-10-minutes/) tasks etc.

### Machine Learning / AI

Much of the computer based tools we use follow the same principle - they are a collection of  straightforward instructions for the computer to follow so that it can solve a task. Machine Learning on the other hand, is about how the computer can learn to solve a task from examples, much like we humans learn.

*Resources*

* Courses
    * [Machine Learning](https://www.coursera.org/learn/machine-learning)- by Andrew NG
    * [Deep Learning](https://www.coursera.org/specializations/deep-learning) - offered by DeepLearning.ai is a more advanced course by Andrew NG focusing on Deep Learning.
    * [Computer Vision](http://cs231n.stanford.edu/) (recommended to do this before the other two)
    * [Natural Language Processing](http://web.stanford.edu/class/cs224n/)
    * [Reinforcement Learning](https://www.youtube.com/watch?v=FgzM3zpZ55o&list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u) (also check out [this](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf) book)

* Software Tools & Framework
    * Numpy: Mathematics and Linear Algebra library for python.[YouTube Tutorial](https://www.youtube.com/watch?v=QUT1VHiLmmI) | [Documentation](https://numpy.org/doc/stable/)
    * Matplotlib: Python library for plotting.[YouTube Tutorial](https://www.youtube.com/watch?v=3Xc3CA655Y4) | [Documentation](https://matplotlib.org/)
    * SciKitLearn: Machine Learning toolkit in python. [YouTube Tutorial](https://www.youtube.com/watch?v=pqNCD_5r0IU) | [Documentation](http://scikit-learn.org/stable)
    * OpenCV: Computer vision toolkit [YouTube Tutorial](https://www.youtube.com/watch?v=oXlwWbU8l2o) | [Documentation](https://docs.opencv.org/master/)
    * Pytorch: Deep Learning framework [YouTube Tutorial](https://www.youtube.com/watch?v=GIsg-ZUy0MY) | [Documentation](https://pytorch.org/docs/stable/)
    * Tensorflow: Deep Learning framework [YouTube Tutorial](https://www.youtube.com/watch?v=tPYj3fFJGjk) | [Documentation](https://www.tensorflow.org/)

### Control Systems

Control systems aid in regulating the robot's actions and movements. Because the dynamics change over time, we require controllers. When the robot goes first on smooth concrete, then on carpeted flooring, or when it walks up a slope, then down it. Therefore, creating a good controller requires physical modelling of the system.

A controller receives a reference state from us. The controller also has sensor feedback, and it uses both to generate the control signal necessary to get to the reference state. The System receives this control signal. How the system responds to this control input is determined by the system dynamics. Hopefully, the System will reach our intended reference state if the controller is effective.

*Resources*

* [Control of Mobile Robots](https://www.youtube.com/playlist?list=PL2jykFOD1AWYvdLW6Alr55IydU_qFVe31) - course by Magnus Egerstedt (Georgia Tech)
* [Understanding PID Control](https://www.youtube.com/playlist?list=PLn8PRpmsu08pQBgjxYFXSsODEF3Jqmm-y) - Playlist by MATLAB explains PID control in detail.
* [Linear-Quadratic Regulator](https://youtu.be/E_RDCFOlJx4) - by MATLAB explains about LQR
* [Model Predictive Control](https://youtu.be/XaD8Lngfkzk) - by Lasse Peters is well explained.
* [Practical Control Systems](https://www.youtube.com/playlist?list=PLn8PRpmsu08pFBqgd_6Bi7msgkWFKL33b) - Playlist by MATLAB
* [State Space](https://www.youtube.com/playlist?list=PLn8PRpmsu08podBgFw66-IavqU2SqPg_w) - Playlist by MATLAB teaches State space equations, pole placement and concepts like controllability and is important for learning math behind Control Theory.


## Electronics

The electronics system of a robot is made up of sensors and actuators that are interfaced with the microcontroller using drivers. Interfacing is done with basic electronics components like as wires, resistors, and capacitors, and the whole assembly is installed on a breadboard, prototyping board, or printed circuit board (PCB).Single board computers (SBC) are used for advanced functioning.

### Single Board Computers
A single-board computer (SBC) is a complete computer built on a single circuit board, with microprocessor(s), memory, input/output (I/O) and other features required of a functional computer. Single-board computers are commonly made as demonstration or development systems, for educational systems, or for use as embedded computer controllers. 
[Rasberry pi](https://www.raspberrypi.com/) is good to start with.

### Microcontrollers 

[Arduino](https://www.arduino.cc/en/Guide/Introduction) is a low cost, open source and easy to learn microcontroller. The syntax used to program Arduino is similar to that of C/C++ and a software called [Arduino IDE](https://www.arduino.cc/en/software) is used to program it.
The Arduino IDE is open source software which is written in Java and will work on a variety of platforms: Windows, Mac, and Linux. The IDE enables you to write code in a special environment with syntax highlighting and other features which will make coding easier, and then easily load your code onto the device with a simple click of a button.

*Resources*

* [Web Tutorials](https://www.arduino.cc/en/Tutorial/HomePage) 
* [Youtube Tutorial](https://www.youtube.com/c/mcwhorpj) 
* [TinkedCad](https://www.tinkercad.com/)(for online simulation)


### Sensors

A sensor monitors environmental conditions such as fluid levels, temperatures, vibrations, or voltage. When these environmental conditions change, they send an electrical signal to the sensor, which can then send the data or an alert back to a centralized computer system or adjust the functioning of a particular piece of equipment. Ex. wheel encoders, temperature sensors, depth cameras (Kinect), LiDARs, Ultrasonic sensors, etc.

### Actuators

An actuator, on the other hand, causes movement. It takes an electrical signal and combines it with an energy source to create physical motion. An actuator may be pneumatic, hydraulic, electric, thermal, or magnetic. Ex. Motors (DC, Stepper, Servo, BLDC),Linear Actuators (Solenoid or a linear servo), etc.

### PCB Designing

[easyEDA](https://easyeda.com/) is good to start with. One could follow [official tutorial](https://docs.easyeda.com/en/FAQ/Editor/index.html) for better understanding. 
[Youtube Tutorial](https://www.youtube.com/watch?v=MsuR6W-jN5M&list=PLbKMtvtYbdPMZfzGuVTdc0MWKrFvU4nsu)

## Mechanical Designing

### CAD

SOLIDWORKS is a major CAD tool used to develop mechatronics systems from beginning to end. At the initial stage, the software is used for planning, visual ideation, modeling, feasibility assessment, prototyping, and project management. The software is then used for design and building of mechanical, electrical, and software elements. 
Finally, the software can be used for management, including device management, analytics, data automation, and cloud services.
 