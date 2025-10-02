# ChannelPacker
A sbsar to pack textures into the RGBA channels, using the [Substance Player](https://helpx.adobe.com/substance-3d-player/home.html).

# 1 Open sbsar
Once you downloaded [Substance Player](https://helpx.adobe.com/substance-3d-player/home.html) and the latest release version you can open the ChannelPacker.sbsar with [Substance Player](https://helpx.adobe.com/substance-3d-player/home.html).<br>
<img width="3839" height="2076" alt="grafik" src="https://github.com/user-attachments/assets/a86351ee-c3e9-41ff-8bd4-7a1ee1477803" />
(The "3D View" can be hidden under "Window" for that as its not needed for this.)<br>

# 2 
There are two options to pack the channels.<br>

### 2.1 All Channels individually
<img width="1791" height="894" alt="grafik" src="https://github.com/user-attachments/assets/68be5adf-c60a-455b-aad4-074335c9adc3" />
First select your textures for R/G/B/A. This can be done by either clicking on the "None [...]" and then selecting your texture in the pop-up window or by just dragging the texture into the Substance Player directly.<br>
After adding the textures you want to pack intpo the channels you need to set the R/G/B/A Texture Channel of your textur which should be used. If its a grayscale texture just setting R,G or B will work.<br>

### 2.2 sRGB Texture + Alpha
Click on the **False** to the right of AlphaPacking to pack a texture into another sRGB texture.<br>
<img width="1798" height="478" alt="grafik" src="https://github.com/user-attachments/assets/9dea1585-3dba-47a6-8588-d0740485dedc" />
The Alpha is set like the other textures in 2.1.<br>
The sRGB texture can now be selected too, it will use the RGB values of the texture and add the Alpha to it.<br>

# 3 Export
In the 3D View you can Preview your channel packed texture. <br>
First step before export is to set the Output Size, you can select any size here but going for a higher resolution than your source textures will not increase the details and just be dumbly upscaled.<br>
Then you can click on "Export as Bitmap" in the top left and export your new channel packed texture. If you pack something in the alpha channel make sure your format supports transparency such as png or tga.<br>
<img width="3839" height="2073" alt="grafik" src="https://github.com/user-attachments/assets/51546a48-cd91-464c-ac17-49e26cffe29c" />
<img width="3839" height="2079" alt="grafik" src="https://github.com/user-attachments/assets/92605834-ad61-4e60-9fab-7424f3ace970" />
The RGBA.tga used as an example here is uploaded to the repo with a direct download link to it [here](https://github.com/DarkAt26/ChannelPacker/raw/refs/heads/main/RGBA.tga).
