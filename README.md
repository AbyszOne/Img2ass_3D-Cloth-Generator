# Img2ass_3D-Cloth-Generator
VRoid cloth asset creator. VRass 1.2
Model available at: https://huggingface.co/Abysz/VRass1.2_Img2ass

# Pure RAW results.
<img src=https://i.imgur.com/fk5KuCY.png width=100% height=100%>
<img src=https://i.imgur.com/4qXajhV.png width=100% height=100%>
<img src=https://i.imgur.com/DWa2Gd9.png width=100% height=100%>

# How to use:
This model was trained to recognize the asset format used by the VRoid program. So for it to work you need to export any clothing asset from there (PNG).
 
 Then you use it as a reference image in any Stable Diffusion GUI (Like Automatic1111 IMG2IMG).
 
 Start your prompt with vrass word (the model token).
 
 Thanks to the training, you will be able to apply textures and clothing styles, since it will try to respect the asset's format, instead of generating common clothing superimposed on the image like any other model.
 
 Give it a generous description. Very high CFG and denoising levels are recommended, as well as accentuating keywords liberally.
