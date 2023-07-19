<h2 align="center">Demonstration Video</h2>
<p align="center">
<a href="https://www.youtube.com/watch?v=ohfX8vRgAaY&t=41s"><img src="images/thumbnail.jpg" height="60%" width="60%"></a>
</p>

## Contents:
<ol>
   <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#1-problem-statement">Problem Statement</a></li>
   <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#2-objectives">Objectives</a></li>
   <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#3-design-process">Design Process</a></li>
     <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#4-material-selection">Material Selection</a></li>
     <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#5-impact-of-solving-the-problem">Impact of Solving the Problem</a></li>
   <li><a href="https://s-nithish-kumar.github.io/Gripper-Part-Re-engineering-of-Kinova-Jaco-2-Robot-Arm/#6-results-and-conclusion">Results and Conclusion</a></li>
</ol>

### 1. Problem Statement:
- Due to wear and tear and ageing factors, the internal part of the Kinova Jaco 2 Robot Arm is damaged.
* The internal part has varying levels of flexibility in different regions and should be considered while designing and manufacturing. Fig shows the flexibility variations in different parts of the component.
<p align="center">
<img src="images/OEM_part_sample.jpg" height="70%" width="70%">
</p>

### 2. Objectives:
- To redesign the gripper part by measuring the part dimensions manually using a Vernier Caliper.
* Divide the part into two and design a hinge which will act as a replacement for the flexible portion of the component.
+ Select proper materials for 3D printing the part.

### 3. Design Process:
- Thermoplastic Polyurethane (TPU) with shore A hardness of 87 is chosen as the print material and printed with the 3D design below. But TPU being soft was flexible even in the longer part of the component which makes it incompatible for use with the gripper.
<p align="center">
<img src="images/single_piece_with_slot_no_hinge..JPG" height="70%" width="70%">
</p>
* To increase the flexibility of the longer part, a slot was provided in it which can be filled with a thin metal plate to increase the rigidity. But due to the printer’s limited accuracy and the smaller size of the component the finishing of the part was not good and cannot be used for assembly.
<p align="center">
<img src="images/single_piece_with_no_slot_no_hinge.JPG" height="70%" width="70%">
</p>
+ To overcome the problem with the above designs, the component has to be divided into two parts with different materials for each part. The material selection section shows the third design with two different materials each for smaller and longer parts.

### 4. Material Selection:
The printed component has two parts in total:
* The smaller part is printed with Thermoplastic polyurethane (TPU) with shore A hardness of 87
- The longer part is printed with Polylactic acid (PLA)
+ Figure below shows the 3D design of the component. The two different parts are combined with a stainless steel rod.
<p align="center">
<img src="images/redesigned_part.png" height="70%" width="70%">
</p>

### 5. Impact of Solving the Problem:
- The replaced part will be a temporary solution for the gripper to perform most of the tasks as how the gripper works with the OEM’s part.
+  The cost of the replaced part using 3D printing is 50 times less than the OEM’s product. This is because the entire finger has to be replaced and the damaged part alone can’t be replaced by the OEM.

### 6. Results and Conclusion:
- The gripper is found to perform well for grasping less weighed objects. Grasping heavy objects will damage the part as more tension acts on the gripper.
+ The gripper performed well for 2 months after which the part started to damage.
* The replaced part acted as temporary solution and supported to perform most of the gripper tasks.
