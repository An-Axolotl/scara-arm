# SCARA Robot Arm

<table>
  <tr>
    <td align="center" width="50%"><img src="images/scara_assembled.png" alt="The finished SCARA arm, background removed"></td>
    <td align="center" width="50%"><img src="images/scara_parts.png" alt="All printed parts laid out before assembly: base with linear rods, arm links, gripper and covers, background removed"></td>
  </tr>
  <tr>
    <td align="center"><sub>Finished arm</sub></td>
    <td align="center"><sub>Printed parts before assembly</sub></td>
  </tr>
</table>

<p align="center">
  <img src="images/arm_joints.gif" alt="Arm swinging on its shoulder and elbow joints" height="420">
  <img src="images/arm_wrist.gif" alt="Arm rotating while the wrist turns" height="420">
</p>
<p align="center">
  <img src="images/gripper.gif" alt="Close-up of the gripper rotating" width="480">
</p>

I built and wired this 4-axis SCARA robot arm from How To Mechatronics' open-source design: [SCARA Robot: How To Build Your Own Arduino Based Robot](https://howtomechatronics.com/projects/scara-robot-how-to-build-your-own-arduino-based-robot/) by Dejan Nedelkovski.

## Result

The arm was fully 3D printed, assembled, wired and **working**: all four axes and the servo gripper move under Arduino control (see the GIFs above).

- **4 degrees of freedom**: two arm joints, wrist rotation and a vertical Z axis on a lead screw with four linear rods
- **Motors**: four NEMA 17 steppers with belt reductions, plus a servo-driven gripper
- **Electronics**: Arduino UNO with a CNC shield and A4988 stepper drivers, on a 12 V supply
- **Build**: every structural part 3D printed in PLA

## Design and code

The design and code belong to How To Mechatronics. This repo only shows my build of it.

- **Build guide**: [How To Mechatronics SCARA tutorial](https://howtomechatronics.com/projects/scara-robot-how-to-build-your-own-arduino-based-robot/)
- **Code** (Arduino firmware and Processing GUI): [SCARA Robot: Arduino and Processing Codes](https://howtomechatronics.com/download/scara-robot-arduino-and-processing-codes/)
- **STL files for printing**: [Cults3D](https://cults3d.com/en/3d-model/various/scara-robot-arm)
