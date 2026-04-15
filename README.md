# Unicorn Chasing Kit


## Features
**Rethonance Nozzle**
(picture)
V6 style nozzle with a built in ADXL 345 featuring non-zip (aka press-in) FFC connector. 

This was designed by Cyd0nian and Reth as currently the only know true nozzle ADXL (besides E3D's Revo Rethonance Nozzle). The thought process was simple... why use a seperate adxl board? Why not just put the adxl in the nozzle?
This spark of inginutity bubbled up inside them until the effervescence of creativity exploded. Needing someone to contain such sparks of the mind Reth turned to LDO. LDO was able to control and funnel this stampede of ideas to bring to us all a tool that can allow anyone to be a member of * *The Unicorn Chasing Club* * 

This Rethonance nozzle will fit any standard V6 hotened. The press-in FFC connector was chosen so that if by accident the FFC cable was pulled it would simply come out. In addition, it makes it easy to first screw in the Rethonance Nozzle and then add the FFC cable later. No need for that pesky latch.
On top of that we have added a thermister to the Rethonance Nozzle. This thermister with the recommended Klipper config will shutdown the printer before you fry the adxl345 on the Rethonance Nozzle. This is why the recommended config for the Rethonance Nozzle has the max temp at a low value. It is **strongly** recommended to **not heat the hotend** while using the Rethonance Nozzle.


**Rethonance Hub**
One of the biggest annoiances for Reth was flipping the printer upside down to connect an adxl. 
The fix to this issues was not as sparkling as the Rethonance Nozzle. He though why not just use a seperate board with a long USB cable. But, the little angel of Scope Creep was sitting on Reth's shoulder and did not let him just be happy with just a press-in FFC connector to USB. Oh no. Reth's Scope Creep angel decided lets add more, and lets add a mount with magnets so we can stick it on the bed. And thus, was born the Rethonance Hub. 

The Rethonance Hub has two press-in FFC connectors. The idea behind this was that one could be used for the Rethonance Nozzle and the other can be used with LDO's ADXL. Yup, they are pin compatible so you can use either the Rethonance Nozzle or LDO ADXL in either press-in FFC connector. 
But, what do we do with all the other pins on the GOB1? Why not add four thermisters so that when you are Chasing Unicorns on your LDO AWD you can attach a thermister to each of the motors. This could be used to determine if that run_current really is high by measuring the temperature of the motors. 
In the words of the Billy Mays "But wait, there's more!". We still had extra pins on the G0B1. What do we do with those. We had no idea what to do with those pins. So we decided to give them to you. We group some of the pins as a third SPI port, and the rest are in a GPIO header. That's right they are yours to do what you want with, and we can't wait to see what you come up with.

**Unicorn Chasing Kit contains**
Rethonance Nozzle
Rethonance Hub
(Dave add the rest here please)



