## STL Parts
This folder contains the STLs for the 3D parts that are necessary to build a PD1 robot.

The parts have been designed so that it makes the 3D printing as easy as possible and reduces the amount of support material needed. Some parts (ex. neck) are provided in two or more parts that can be easily printed without support and then glued together, reducing substantially the amount of time and the material required.

Many of the parts are based on the original Robotis 3D parts provided for Darwin Mini robot, but they have been customized to support the changes implemented in PD1 versus Darwin Mini.

The following table shows the parts, how many are needed to be printed and how they relate to the original Robotis parts.

Part                                                |  Prints |  Robotis Relation     |
----------------------------------------------------|--------:|-----------------------|
**Head**                                            |         |
[head - head](head%20-%20head.stl)                  |1        |modified DMF-F01(W) to accomodate the camera and the head tilt servo
[head - neck](head%20-%20neck.stl)                  |1        |new part
[head - head support](head%20-%20head%20support.stl)|1        |new part - needs to be glued to the neck
**Body**                                            |         |
[body - chest](body%20-%20chest.stl)                |1        |heavily modified part DMB-B02(W) to accomodate the new head pan servo, the NanoPi SoC together with the interface board as well as the two lateral fans
[body - skin front](body%20-%20skin%20front.stl)    |1        |modified DMF-B01(W) part to accomodate the OLED screen and split in order to allow easier assembly
[body - skin back](body%20-%20skin%20back.stl)      |1        |modified DMF-B01(W) part to accomodate the back connectors and split for easier assembly
**Arms**                                            |         |
[arm - left hand](arm%20-%20left%20hand.stl)        |1        |new part
[arm - right hand](arm%20-%20right%20hand.stl)      |1        |new part
[arm - hand base](arm%20-%20hand%20base.stl)        |2        |new part - needs to be glued to the left hand and right hand
[arm - connector](arm%20-%20connector.stl)          |2        |new part
[arm - shoulder](arm%20-%20shoulder.stl)            |4        |original DMF-B03(W); will be used for shoulders and elbows
**Legs**                                            |
[leg - foot](leg%20-%20foot.stl)                    |2        |modified DMF-B06(W) to accomodate the batteries, power cover and the hotswap board
[leg - sole](leg%20-%20sole.stl)                    |2        |modified DMF-B07(GR) to accomodate the batteries
[leg - power cover](leg%20-%20power%20cover.stl)    |2        |new part
[leg - lower leg](leg%20-%20lower%20leg.stl)        |2        |original DMF-B05(W)
[leg - upper leg](leg%20-%20upper%20leg.stl)        |2        |original DMF-B04(W)
[leg - lower joint](leg%20-%20lower%20joint.stl)    |2        |new part; simplifies the assembly 
[leg - upper joint](leg%20-%20upper%20joint.stl)    |2        |new part; simplifies the assembly 
**Other Parts**                                     |
[parts - SPO-5(GR)](parts%20-%20SPO-5(GR).stl)      |11       |original SPO-5(GR) horn idle for XL-320
[parts - SPU-5(W)](parts%20-%20SPU-5(W).stl)        |4        |original SPU-5(W)