TFT_ILI9163C



![BlackPCB](https://github.com/sumotoy/TFT_ILI9163C/blob/Docs/images/ILI9163C_blackPCB.png)

-------------------------------------------------------------------------------------------
<b>RED PCB with Black Pin</b> (common before 2016 but still around)<br>
This is the first display I put hands on, has a resistor for backlight already mounted so I can supply directly 5V (but please do a fast check, chinese are famous for changes without notice). This display has 3v3 regulator for supply the ILI chip but logic levels remain at 3V3 so you will need a level translator for connect 5V logic level CPU (as arduino UNO).<br>
![RedPCB1_](https://github.com/sumotoy/TFT_ILI9163C/blob/Docs/images/ored.jpg)
<br>Following image shows how the display it's mapped, for rotation 0 bring it in front of you, pins are at the top (thanks Gimpox for image)<br>
![RedPCB1](https://github.com/sumotoy/TFT_ILI9163C/blob/Docs/images/ILI9163C_blackPin.png)
-------------------------------------------------------------------------------------------
<b>RED PCB with Yellow Pin</b> (from Gen 2016)<br>
This is pretty similar to the display above but a bit smaller, however has different settings and offset is different. The Backlight led need a bigger resistor and cannot be connected directly at 5V.<br>
Rest of te connections are exact the same of the display above.<br>
Logic Levels are 3V3!<br>
![RedPCB2_](https://github.com/sumotoy/TFT_ILI9163C/blob/Docs/images/yell.JPG)
<br>Following image shows how the display it's mapped, for rotation 0 bring it in front of you, pins are at the top (thanks Gimpox for the image)<br>
![RedPCB2](https://github.com/sumotoy/TFT_ILI9163C/blob/Docs/images/ILI9163C_yellowPin.png)
-------------------------------------------------------------------------------------------
