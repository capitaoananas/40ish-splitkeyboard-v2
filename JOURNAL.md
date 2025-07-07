---
title: "40%ish split keyboard v2"
author: "Lukas Reis"
description: "V2 of my split keyboard and it will be wireless"
created_at: "2025-05-30"
---

# May 30th: Started making the actuall project + a bit of reserch!

First im deciding if i should use a Xiao nrf or a nice nano v2 so i started testing which one would work better for my keyboard design also im going to use in this version solder jumpers so that the reversing part works better.

![PCB Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/095640c8be91cadb640723673e960285e6a39357_screenshot_20250530_161515.png)
![PCB Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a858827925cc827f60649567fa250b228190e578_screenshot_20250530_161506.png)

**Total time spent: 1:30h**

# June 1st: Getting the rest of the schematic done!

I think that im going to use the nice nano as its easier to make the pcb and schematic because the xiao-nrf-plus does not have a symbol to use in the schematic so most of the work would be on the PCB editor and that would take more work and its just not so pretty and organized.

Got almost almost the schematic done but its quite hard!

![PCB Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6876ec6468606facc6fd5928c0ef354766d43747_screenshot_20250601_132314.png)

**Total time spent: 1h**

# June 2nd: Schematic done and PCB almost!

## Today i made the schematic untill the end! Which is really cool one more step into being done!

**in the schematic i:**
  - Wired the rest of the pins!
  - Added rotary encoder with a switch which they are going to be one on top of each other becase like that you can choose between a extra switch or rotary encoder which is a ec11 which has a switch so you are only winning with the rotary encoder.

Here is a photo of the schematic finnished!
![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/9fbb77426b4825ca356e344af6a9c1b08c81db1b_screenshot_20250602_181458.png)


Then in the PCB i also did a great part of it!

**in the PCB i**
  - Wired the solder jumpers which was time consuming even tought it does not look like.
  ![solderjumpers](https://hc-cdn.hel1.your-objectstorage.com/s/v3/589fcdb464c81dc1e592a9e40315c1d9eca2ba40_screenshot_20250602_181319.png)

  - Arranged the keys in the layout that i really like.
  - Added the edge cuts.
  - Somehow the switch and the rotary encoder work really well when they are one on top of each other

Photo of the WIP PCB
![PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/74ccf48eb57b8f6e26eb956aebd7dca3b59b55a9_screenshot_20250602_183218.png)

also here is the rotary encoder
![PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/80ddf41bc9bef5bb97d3526e36137420d803b19e_screenshot_20250602_181337.png)

**Total time spent: 3h**

# June 3rd: PCB almost done! Added mounting holes and put the nice nano inside the PCB.

Today i added mounting holes into the PCB for the screws also then i already added the Nice nano and the rotary encoder to the PCB and routed some of the connections but that is one of the last things i have to do in the PCB route it all so the PCB is ready!

While i was making the PCB i saw that the bridge jumpers where filped so they where not in the right direction and then i started remaking it so it was right side up but in the middle of that i realized that actually like that it was better so i actually made something better accidently!

![PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d79806022b9edf9e8859842ea95c26b55c54f02c_screenshot_20250603_105227.png)

**Total time spent: 1h**

#June 30th: PCB done! Almost ready to submit.

So today i felt really productive and made the PCB untill the end! which is really cool because like that i can submit it!

I made some changes also to the PCB 
- Took the rotary encoder out.

Also wired everything diffrently so yeah its ready!

![schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d6a854c8c6da6bb1c9380820ec224b703f8cc25e_screenshot_20250630_132012.png)

![PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a61bb108c3db1bfa30c15f1a1ea8f8c805aac363_screenshot_20250630_131115.png)

**Total time spent: 2h**

# July 6th: Write code

So today i wrote the code for the keyboard i used RMK which in my opinion is easyer and better the QMK or KMK so yeah its really cool it was actually really easy becasue it was not my first time using RMK but if you want to see their website is rmk.rs 

But yeah just finnishing a few things on the BOM and i'm done to submit!

**Total time spent: 1h**

# July 5th: Making the case!

So i saw online the corne keyboard case that was sandwich style and i really like it becasue it was so minimal! so i started by exporting the User.Drawing from Kicad becasue my plate is a bit complicated and it would be even harder if i tried to use one of those plate genarators so yeah i exported it as a dxf and imported onto a sketch and deleted useless elements and then i had a general plate which was exactly th size of my pcb it was easier then the first time i did it (made it for the v1 of the keyboard) yeah so it was already looking good so i reversed the desing for the right side which is exactly the same besides the little standoffs that i added
After that i went onto the bottom part which was really easy because i already had the shape of the keyboard because of the plate! so what i only needed to do is make the bottom standoffs the right size and it was done! But then i rememberd a really cool keyboard which the case was really slim because the bottom part had holes for the hotswap sockets so that was a bit tedious becasue i had to recreate the shape of the hotswap socket but when everything was done it was worth it i really like how it turned out in fact the PCB of the keyboard has those holes in it because i already had in mind of making a case like this so yeah! here is the finall result

 Plate             |  Bottom | Full Case
:-------------------------:|:-------------------------:|:-------------------------:
![Plate](https://hc-cdn.hel1.your-objectstorage.com/s/v3/9d5c25676295558a3f1919c0c8d7e697f13226de_40_ish_v2_case_2025-jul-05_04-50-05pm-000_customizedview3364258380.png)  |  ![Bottom](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0deb7f7d5099e66774debaf48bba5fec7e5f670f_40_ish_v2_case_2025-jul-05_04-50-41pm-000_customizedview27644930984.png) | ![full case](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a89094f09b81e580b9727a2726056a9d8fe39cb4_40_ish_v2_case_2025-jul-07_08-16-01pm-000_customizedview278695978.png)

Finall renders

Side             |  Top
:-------------------------:|:-------------------------:
![Side](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6fa489d54e0352336db987841671457d9239b8cf_40_ish_v2_case_2025-jul-05_04-20-08pm-000_customizedview622321217.png)  |  ![Top](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b43d0dbd81ab2dcbb0810d2a18a2dffbfb5b2c52_40_ish_v2_case_2025-jul-05_04-23-28pm-000_customizedview28197339788.png)


