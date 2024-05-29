# Q-Octo CAD
This Repo is the official home of the design of the Q-Octo robot! All CAD is using `FreeCAD Link Branch 2024-01-23`, but STL and DXF files are also provided.

![img](img/cover.png)

## About Q-Octo
[Q-Octo](https://www.youtube.com/watch?v=2PIdxYJO_Ck) is an eight-quasi-wheeled robotics platform. It is designed to excel at forest traversal, easily being able to clamber over small logs and rocks due to its uniquely shaped wheels. However, due to each pair of neighboring wheels being 180 degrees out of phase, the robot can run smoothly as if it had circular wheels when on flat ground.

Q-Octo uses a pair of [CyberGear MicroMotors](https://www.aliexpress.com/item/1005005997659365.html), which provide not only high torque and speed but also feedback such as current amp draw and position. To power the motors, 4 [Parkside X20V](https://parkside-diy.com/gb/battery-technology/x20v-team) drill batteries are used, providing 6-hour continuous runtime paired with robust and safe recharging.

To build a Q-Octo, both a 3D printer and a laser cutter are required. It is sufficient to manufacture all 3D printed parts out of [Esun PLA+](https://www.esun3d.com/pla-pro-product/), providing excellent durability. All laser-cut parts (*except the front and rear battery cover) can be cut from 6 mm thick plyboard, which provides adequate rigidity and durability, assuming it is coated in outdoor paint.

## Parts List _(Incomplete at current time)_

### Parts to Purchase
> These are just the mechanical parts for building the chassis. All of the control electronics can be found in the electronic repo.
- 2x CyberGear MicroMotor (Robot Dog Motor)
- 12mm Square Tube, Aluminum, Hollow (~1 meter, you need to cut it yourself)
- Assorted M4 bolts, ideally low profile
- M4 threaded inserts, diameter 5.6mm
- 20x 61704 ball bearings (20x27x4mm)
- 4x 5mm HTD belts 285mm length, 15mm wide
- 4x 5mm HTD belts 225mm length, 15mm wide
- 4x Parkside X20V drill battery

### Parts to Lasercut
> All parts should be lasercut from a 6mm wide material (unless otherwise specified), plyboard should be strong enough. It is recommended not to use acrylic as it can be brittle.
- 2x dxf/ChassisInnerPlate.dxf
- 2x dxf/ChassisOuterPlate.dxf
- 1x dxf/ChassisUpperPlate.dxf
- 1x dxf/ChassisLowerPlate.dxf
- 2x dxf/ChassisMotorSplashPlate.dxf
- 2x dxf/ChassisBatterySplashPlate.dxf (Cut this from thinner material, the thinner the better as it is not structural)
