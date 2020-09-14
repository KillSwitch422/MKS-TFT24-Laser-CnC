# MKS-TFT24-NEW-Theme
New Icon set for TFT24 display from MAKERBASE-MKS specific for Laser cnc, using Grbl.

I have included custom function buttons, please use the attached config file for them to work correctly.

<img src="https://github.com/KillSwitch422/MKS-TFT24-Laser-CnC/blob/master/Source_Images/bmp_custom1.png" /> This will enable the Laser @ S1 power for focusing purpose.\
`>moreitem_button1_cmd:M3;S1;G1 X0.1 F1000;`


 <img src="https://github.com/KillSwitch422/MKS-TFT24-Laser-CnC/blob/master/Source_Images/bmp_custom2.png" /> This will enable the Laser @ S1 power and draw a test rectangle.\
`>moreitem_button2_cmd:G0 X50 Y50 F1000 ;M3;S1;G1 X100 Y100 F1000;G1 X200 Y100;G1 X250 Y100;G1 X250 Y200;G1 X250 Y400;G1 X50 Y400; G1 X50 Y50 ;S0; G0 X0 Y0;`


 <img src="https://github.com/KillSwitch422/MKS-TFT24-Laser-CnC/blob/master/Source_Images/bmp_custom3.png" /> This will switch off the laser.\
`>moreitem_button3_cmd:M03;S0;G1 X0 Y0 F1000;`


##  <img src="https://github.com/KillSwitch422/MKS-TFT24-Laser-CnC/blob/master/Source_Images/bmp_custom4.png" /> &#x1F534; Fire Hazard use with care: This will set the laser to full power &#x1F534;.\
`>moreitem_button4_cmd:G0 X50 Y50 F1000 ;M3;S255;G1 X100 Y100 F1000;`
