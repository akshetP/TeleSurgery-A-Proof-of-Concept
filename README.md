# TeleSurgery-A-Proof-of-Concept

## Abstract
Telesurgery unites physicians and patients via wireless networking and robotics. Telesurgery uses wireless networking and robotics to operate on remote patients. This technology eliminates geographical limits that prevent prompt and high-quality surgical intervention, as well as expense burdens, issues, and risky long-distance travel. The gadget enhances surgical accuracy and safety. In this study, telesurgery is proven. A virtual environment with the Niryo One Robotic Arm has been designed for the Oculus Quest Head Mounted Display (HMD) Device. The Oculus (Meta) Quest Controllers are used to operate the arm in Virtual Reality (VR) and the arm moves in real-time in a Gazebo Simulation which represents a physical robotic arm. The communication between the HMD and the Robot Operating System (ROS) node is enabled over Wi-Fi.

## Acknowledgements
I am grateful to my project supervisor Assoc. Prof. Cai Yiyu, Associate Professor, School of Mechanical, and Aerospace Engineering (MAE), NTU Singapore for his inspiring guidance and advice throughout the project. I would like to thank him for his valuable suggestions and ideas during the project work and for all kinds of encouragement. I would like to pay my respectful thanks to IndiaConnect@NTU and the Nanyang Technological University for providing me this wonderful great opportunity. 
I would like to thank my parents without whom this would never have been possible and my friends for always providing the  support and motivation.
I would further like to thank my home university, Manipal University Jaipur for giving me a chance to experience and learn from this internship opportunity.
I would like to express my gratitude to Dr. Shahbaz Ahmed Siddiqui, HoD, Department of  Mechatronics Engineering for his constant support and motivation.
I take this opportunity to thank my internal guide and mentor, Dr. Princy Randhawa, Assistant Professor (Senior Scale), Department of Mechatronics Engineering, Manipal University Jaipur for her constant  help, guidance, and support without whom I would not have chosen this project research.
I would like to thank Dr. Raja Rout, Former Assistant Professor, Department of Mechatronics Engineering, Manipal University Jaipur for assisting me with the concepts of Robotics and ROS.
I would further like to thank and mention Mr. Siddharth Varshney,  Mr. Abhay Tripathi and Mr. Konstantinos Tsaramirsis and Mr. Vanshaj Arora, and Mr. Jasmeet Singh for their support and assistance  in the XR Domain.

## Motivation
Telesurgery allows patients who are unable to travel vast distances to get safe and precise surgical operations. This kind of surgery is becoming increasingly viable as robots and wireless communication technologies progres.
The advantages of Telesurgery are:
•	It can perform high-quality surgery in places that would otherwise be unable to afford it, including as remote rural regions, war zones, and even outer space.
•	Reduces or eliminates the necessity for long-distance travel, along with the financial load and potential risks associated with such travel.
•	With today's 3D display technology, surgeons working in separate hospitals may share the same high-definition visual input.
•	It enables surgeons from various medical institutes to collaborate in real time.
•	Accelerometer technology cancel out the operator's natural tremor in real time, enhancing surgical precision and decreasing tissue damage in the vicinity.
•	As a result, the patient's recovery time is sped up.

## Objectives
The five objectives of this research project are as follows:
1.	To develop a VR application for the Oculus Quest by importing the Niryo One Robotic Arm into a VR environment.
2.	To map the inputs with the Quest Controllers to actuate the arm in VR.
3.	To run a Gazebo Simulation of the Niryo One Robotic Arm which represents the physical arm.
4.	To Connect the HMD with the ROS Server over TCP Protocol over the same Wi-Fi network.
5.	To Create a ROS Package for simulating the simulated arm in Gazebo using the messages sent by the HMD.

## Methodology
The entire methodology followed for this research project is summarised in five steps and procedures.
1.	Importing the Niryo One Robotic Arm in Unity3D
2.	Mapping the Inputs with the Quest Controllers
3.	Run Gazebo Simulation of Niryo One Robotic Arm
4.	Connect the HMD with the ROS Server over TCP Protocol
5.	Creating a ROS Package for Simulating the Arm in Gazebo

## Implementation and Results

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/1.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/2.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/3.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/4.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/5.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/6.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/7.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/8.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/9.jpeg)

![](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/demo_images/10.jpeg)

## Conclusion
Using the entire system developed, the Niryo One Robotic Arm is visualised and controlled in the VR using the Oculus Quest controllers. The IP address of the ROS Server is entered using the keypad developed in VR. When the ROS Server is initialized, the HMD is connected to the laptop running the Gazebo simulation of the arm and ROS node over the TCP protocol on the same Wi-Fi network. The Arm moves in the exact same way as it is actuated using the controllers in the VR. In conclusion, 
1.	The VR application for the Oculus Quest was developed by importing the Niryo One Robotic Arm into a VR environment.
2.	The inputs were mapped with the Quest Controllers to actuate the arm in VR.
3.	A Gazebo Simulation of the Niryo One Robotic Arm which represents the physical arm was ran using the URDF file.
4.	The HMD was connected with the ROS Server over TCP Protocol over the same Wi-Fi network by using ROS-TCP Connector.
5.	A ROS Package was developed for simulating the simulated arm in Gazebo using the messages sent by the HMD.

## Limitations
Like any other work in this domain, this research work has many limitations. The first and the most crucial drawback is the latency. For this architecture to work in real time, the latency should be as close to zero as possible. This will only be possible after 5G or 6G rolling out for the public or enterprises. Since the simulated robotic arm is running, the hardware device errors are neglected. For this technology to be used on a human, it must be approved by many international standards and clear many tests. The cost of implementing this technology is extremely high and it will take many years for it to thrive in the developing and underdeveloped nations. Bandwidth, which refers to the data transmitted every second is also a major limitation as the current speeds are not enough to perform remote surgery overseas and continents. Telesurgery has uses for astronauts on the moon and aquanauts at underwater research facilities. Although an agreement on acceptable latencies for operating has not yet been achieved, latency is now the main obstacle facing telesurgery. Despite this, hundreds of successful telesurgeries have already been carried out in various parts of the globe. Additionally, many clinics today cannot afford the prohibitively costly telerobotic surgical devices and networking infrastructure needs. Telesurgery is projected to grow more popular as technology advance, particularly the creation of faster computer networks with more bandwidth capacity, and prices decrease.

## Future Scope
This is the Proof of Concept for tele surgery in a simulated environment. The same system can be scaled to operate on a human remotely by using high precision robotic arms and 5G or 6G network communications. The future of telesurgery will be driven by technology, both in terms of network infrastructure, and in terms of robotic-assisted surgery. The digital transition signifies a shift away from what has been the industry standard in robotic surgery and into a new age of Performance-Guided Surgery, which refers to next-generation technology that totally alters the concept of what is achievable in surgery. This VR app can be used when the world moves towards the metaverse, and it will facilitate the application of Digital Twins. It will provide a better viewing experience for remote operations.

## References
[1]	P. J. Choi, R. J. Oskouian, and R. S. Tubbs, “Telesurgery : Past , Present , and Future,” vol. 10, no. 5, pp. 7–8, 2018, doi: 10.7759/cureus.2716.
[2]	J. Minkel, “First Complete Trans-Atlantic Robotic Surgery - Scientific American,” 2001. https://www.scientificamerican.com/article/first-complete-trans-atla/ (accessed Jun. 13, 2022).
[3]	B. E. Barrow and B. E. Barrow, “ThinkIR : The University of Louisville ’ s Institutional Repository Design and development of a multifunctional surgical device for ground and space-based surgical applications . By Department of Bioengineering,” 2018.
[4]	S. B. Xia and Q. S. Lu, “Development status of telesurgery robotic system,” Chinese J. Traumatol. - English Ed., vol. 24, no. 3, pp. 144–147, 2021, doi: 10.1016/j.cjtee.2021.03.001.
[5]	D. J. Cahill, “Telesurgery : Surgery in the Digital Age Telesurgery : Surgery in the Digital Age,” Dartmouth Undergrad. J. Sci., vol. 19, no. 3, pp. 12–16, 2017.
[6]	“Robotic telesurgery - Benefits, and challenges,” Robotics Biz, 2021. https://roboticsbiz.com/robotic-telesurgery-benefits-and-challenges/ (accessed Jun. 13, 2022).
[7]	J. Marescaux and F. Rubino, “Transcontinental robot-assisted remote telesurgery, feasibility and potential applications,” Teleophthalmology, vol. 235, no. 4, pp. 261–265, 2006, doi: 10.1007/3-540-33714-8_31.
[8]	S. E. Butner and M. Ghodoussi, “Transforming a Surgical Robot for Human Telesurgery,” IEEE Trans. Robot. Autom., vol. 19, no. 5, pp. 818–824, 2003, doi: 10.1109/TRA.2003.817214.
[9]	R. M. Satava, “Virtual reality, telesurgery, and the new world order of medicine,” Comput. Aided Surg., vol. 1, no. 1, pp. 12–16, 1995, doi: 10.3109/10929089509106821.
[10]	T. Haidegger, J. Sándor, and Z. Benyó, “Surgery in space: The future of robotic telesurgery,” Surg. Endosc., vol. 25, no. 3, pp. 681–690, 2011, doi: 10.1007/s00464-010-1243-3.
[11]	J. Rassweiler, J. Binder, and T. Frede, “Robotic and telesurgery: Will they change our future?,” Curr. Opin. Urol., vol. 11, no. 3, pp. 309–320, 2001, doi: 10.1097/00042307-200105000-00012.
[12]	G. S. Guthart, “The IntuitiveTM Telesurgery System : Overview and Application The Intuitive TM Telesurgery System : Overview and Application,” Robot. Autom. 2000. Proceedings. ICRA’00. IEEE Int. Conf., vol. 1, no. February 2000, pp. 618–621, 2015, [Online]. Available: http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=844121%5Cnpapers2://publication/uuid/2772781E-2163-404C-8CE0-126B2E4BC987.
[13]	Q. Zhang, J. Liu, and G. Zhao, “Towards 5G Enabled Tactile Robotic Telesurgery,” pp. 1–7, 2001.
[14]	R. Gupta, A. Shukla, and S. Tanwar, “AaYusH: A smart contract-based telesurgery system for healthcare 4.0,” 2020 IEEE Int. Conf. Commun. Work. ICC Work. 2020 - Proc., 2020, doi: 10.1109/ICCWorkshops49005.2020.9145044.
[15]	E. Rodr, A. P. Kypson, S. C. Moten, L. W. Nifong, and W. R. C. Jr, “Robotic mitral surgery at East Carolina University :,” Int. J., no. April, pp. 211–215, 2006, doi: 10.1002/rcs.
[16]	“Unity (game engine) - Wikipedia.” https://en.wikipedia.org/wiki/Unity_(game_engine) (accessed Jun. 21, 2022).
[17]	W. D. S. Morgan Quigley, Brian Gerkey, Programming Robots with ROS. 2015.
[18]	“Facebook Announces Stand-Alone 6DoF HMD, Oculus Quest.” https://www.abiresearch.com/market-research/product/1032309-facebook-announces-stand-alone-6dof-hmd-oc/ (accessed Jun. 22, 2022).
[19]	“Niryo One.” https://robots.ros.org/niryo-one/ (accessed Jun. 22, 2022).
[20]	“Ned : robotics arm for education and research.” https://niryo.com/product/ned-education-research-cobot/ (accessed Jun. 23, 2022).
[21]	“Robotics Simulation | Unity.” https://unity.com/solutions/automotive-transportation-manufacturing/robotics (accessed Jun. 22, 2022).
[22]	“ROS–Unity Communication.” https://github.com/Unity-Technologies/Unity-Robotics-Hub/blob/main/tutorials/ros_unity_integration/README.md (accessed Jun. 23, 2022).
[23]	“MoveIT For Robotic Manipulation Application - Robotnik®.” https://robotnik.eu/moveit-manipulation-application/ (accessed Jun. 23, 2022).
[24]	“MoveIt Motion Planning Framework.” https://moveit.ros.org/ (accessed Jun. 23, 2022).
[25]	“Robotic simulation scenarios with Gazebo and ROS.” https://www.generationrobots.com/blog/en/robotic-simulation-scenarios-with-gazebo-and-ros/ (accessed Jun. 23, 2022).
[26]	R. A. Gondokaryono, A. Agrawal, A. Munawar, C. J. Nycz, and G. S. Fischer, “An approach to modeling closed-loop kinematic chain mechanisms, applied to simulations of the da Vinci surgical system,” Acta Polytech. Hungarica, vol. 16, no. 8, pp. 29–48, 2019, doi: 10.12700/APH.16.8.2019.8.3.
[27]	“Unity-Technologies/ROS-TCP-Connector.” https://github.com/Unity-Technologies/ROS-TCP-Connector (accessed Jun. 23, 2022).
[28]	“Unity-Technologies/URDF-Importer: URDF importer.” https://github.com/Unity-Technologies/URDF-Importer (accessed Jun. 23, 2022).
[29]	“Learn How to Code in C# for Beginners | Unity Learn.” https://unity.com/how-to/learning-c-sharp-unity-beginners (accessed Jun. 23, 2022).
[30]	“How to get started in programming for robotics.” https://www.futurelearn.com/info/courses/robotic-future/0/steps/29368 (accessed Jun. 23, 2022).

## License
[MIT](https://github.com/AkshetPatel/TeleSurgery-A-Proof-of-Concept/blob/main/LICENSE) <br>
© Copyright 2022 Akshet Bharat Patel. <br>
All Rights Reserved <br>

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://akshetpatel.tk/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshetpatel/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Akshet9)

## Feedback
If you have any feedback, please reach out to us at akshet.ap@gmail.com
