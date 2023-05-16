

Hi,
Thank you for purchasing 'Light & Dark - Photoshop Actions' on Graphicriver.

This guide will cover the installation and usage of the package.
If you prefer the video tutorial here is the link:


https://www.youtube.com/watch?v=ICRSI0F10y8


---------------------------------------------------------------------------------------------------------------


This Action was tested on Photoshop CS3, CS4, CS5, CS6, CC+, English Version ONLY.
If you're using Photoshop in another language This video shows how to change it temporarily:


https://www.youtube.com/watch?v=GJAiu5W2gLE


---------------------------------------------------------------------------------------------------------------
 

------------
INSTALLATION
------------

1. Open Photoshop go to menu 'Window' then select 'Actions', the Actions panel will open.

2. On the actions panel click the arrow icon at the top-right corner, when the drop down 
   menu opens select 'Load Action'. Select the correct action file 'Light & Dark'
   for you version of Photoshop.


---------------------------------------------------------------------------------------------------------------


-------------------------
BEFORE PLAYING THE ACTION
-------------------------

1. Make sure your image is in RGB 8 bit color mode.

2. You're on the English version of Photoshop.

3. Your image has a good resolution, use images between 1000-5000+ pixels 
   (at least one of the axes should be in this range).

4. Make sure that the option 'Add copy to copied layers and groups' is active.
   To do it click on the arrow icon on the top-right corner of the 
   layers panel, then select 'Panel Options', select the option and click OK.

5. Make sure that the image has a nice contrast or at least that the part you're going to mask
   has some information inside. The actions will add some lights and some shadows and masking an area
   of the image that is completely black, like a shadows for example, will not give a proper result
   at the end of the playback.

   if needed a quick way to restore some of this information in the image is to
   apply an 'Auto-Contrast', to do it go to top menu 'Image'>'Auto Contrast'.

6. Some images are already well lit from just one side, the actions will give best results
   if you choose a similar direction to the one of the original light source.


---------------------------------------------------------------------------------------------------------------


---------------------
HOW TO USE THE ACTION
---------------------

1. Open an image to work with in Photoshop.  

2. Make sure that the image's layer is locked and it's set as 'Background'.
   To set a layer as Background go to menu 'Layers' -> 'New' -> 'Background from Layer'

3. Create a new layer above the Background layer and call it 'mask'.
   The name MUST be lowercase.

4. Select the mask layer and brush over the interested area of the image below.
   Use a hard or slightly soft brush.

   You can use your preferred method to make this mask (wand tools, magnetic lasso, pen tool...) just 
   make sure at the end that you have a nice mask of the image and the rest of the layer 
   has transparency.

5. Before playing the action make sure to have only 2 layers in your file 'mask' and 'Background'.

7. Open the Actions panel. There are 8 Action for 8 directions, 
   the light will be always directed towards the center of the image
   Each name of the actions stands for the position of the light source.
   So if you use the action 'TOPLEFT' it means that the action will create a light
   effect that goes from top left to bottom right.

   Select a direction and click play!

8. The playback will take about 3 minutes and it will generate many graphic elements
   that can be tweaked and combined to achieve different results.

   ONLY FOR CS3-CS4-CS5: on these versions during the playback, you'll need to press ENTER every time the
   action will make appear a layers styles panel or a transform tool.

9. When the playback finishes the message 'Render Completed' will appear, click 'Continue'.
   
   There will be many opened groups and layer styles in the layers panel and it'll look messy,
   to make a quick re-organization hold ALT (or OPTION on Mac) and click the arrow of the main group 
   'Light & Dark - OUTPUT', this will close the group, then release ALT.
   If you open again the group normally all the layers and groups will be re-organized.


---------------------------------------------------------------------------------------------------------------


----------------
LAYERS STRUCTURE
----------------

We'll see how to use the 'Color corrections' group in the later sections.
Inside the 'Light & Dark - OUTPUT' group there are different sub-groups, 
that can be recognized by the different color code.

List of sub-groups:

- Post FX
- Overlay FX
- Light FX
- Highlights & Shadows
- Sharpens
- Main Group
- Background Lights / Reveal Background / Black Background

Hide each sub-group starting from the top to see what each one does.

Here is a quick description of each sub-group and how it can be modified.
It starts from the bottom but there is not a predefined sequence do to the customization.
The most common things that you'll do on almost all the images is to 
adjust the main light source and the volumetric lights (or turn them off)
and also tweak a bit the mask of highlights and shadows.
Each customization depends on what you want to achieve, if you want a classic low key photo,
you probably don't need most of the 'Light FX' and 'Overlay FX'.

-------------------------------------------------------------------------

IMPORTANT (Customization methods that can be used by most of the layers)


Most of the layers have a basic help of what can be modified near their names,
but it is possible to customize them in many other ways,
here is a list of the customization methods used on most of the layers,
once you know these few easy steps you'll be able to customize the output easily:

1. For all the layers created by the action, it's possible to use the mask channel to hide or 
   show parts of the layer. 
   To do it select the mask channel, then select a black brush and paint over the area you want to hide.
   A black brush will hide parts of a layer and a white brush will reveal them.
   This is valid not only for the Layers but also for all the Groups.
   Some layers have a mask channel that affects the area of the shadows. You can double click this mask to open
   the property panel and change the slider Density to decide how much that layer/group is affecting
   the area of the shadows

2. Change opacity or fill, from the top of the layers panel.

3. Change blending mode. Alternative blending modes will be suggested for each layer.

4. Change color, many layers are provided of a Color Overlay layer style that you can use to modify the color.
   To use it double click on the layer to open the layer styles and edit the color of 'Color Overlay'.
   The blending mode is set to Color by default, but you can try also:
   Normal, Multiply, Screen, Color Dodge, Overlay, Soft Light

5. Edit Gradient. Some layers are gradients, to edit their parameters double click the thumbnail of the layer.
   On the panel that opens you'll mostly want to change the gradient itself, it's scale, and it's position.
   To reposition a gradient, open the gradient's panel by double clicking the thumbnail and then drag
   the gradient on the image.

6. Layers can be duplicated and transformed to suit your needs. To duplicate a layer press CTRL+j or CMD+j on Mac.

-------------------------------------------------------------------------


[BLACK BACKGROUND]
This is the base on which the effect works and should stay untouched, but you can change the color
from black to another dark tone to achieve a certain kind of effect. 
To change it's color double click the thumbnail of the layer, choose the color and click OK.

[REVEAL BACKGROUND]
If the background of the image has something nice to be shown this layer will reveal it.
The background is considered to be the part of the image that was not defined by the layer 'mask'.
To use it un-hide it and modify it's opacity and if needed the blending mode.
Remember that you can use any background from toher images, to do it just import the new images, 
and position it in the layer above the 'Reveal Background' layer. Then hold ALT or OPTION for Mac
and drag the mask channel from 'Reveal Background' to the new background to clone the masks.
Now you can use the new background.


[BACKGROUND LIGHTS]
Usually the background layers are the last that are modified during a customization phase,
the layers inside this group are all gradients and can be used as a secondary 
source of light/color in the background.

How to edit 'Background Lights':
-  Customize the mask channel
-  Change opacity
-  Change Color using layer style
-  Change blending mode if you use the 'Reveal Background' layer.
   In this case the best blending mode depends on the background of the image.
-  Edit the gradient



[MAIN GROUP]
Here you can find the part of the image that was defined when creating the 'mask' layer.
Starting from the bottom there is the 'Main' layer, the three layers above have a clipping mask on
this layer, so they are affecting only it. If 'Main' is hided also those three will be hided.

How to edit 'Main':
-  Change opacity
-  Un-hide the mask (by SHIFT+clicking it) and edit it. This is an important step, often you'll want
   the part of the image in shadow to completely or slightly disappear in the dark, 
   an easy way to achieve it is to use a black soft brush on the mask channel of this layer.
   The same thing can be done by painting the mask channel of the 'Main Group'.

Next there is the 'Main Color' layer, un-hide to activate the original color of the image.

How to edit 'Main Color'
-  Change opacity
-  Try different blending modes like Multiply, Screen, Color Dodge, Soft light, Overlay
-  Edit the mask channel

The last two layers of the group are two adjustment layers, you can use 'Main Hue/Saturation', 
to change the saturation and hue of the 'Main Color layer', or even Colorize the 'Main' layer.
Use 'Main Levels' to change the level of the 'Main' layer.
To edit these two layer double-click their thumbnails.



[SHARPENS]
These layers add some details to the main part.

How to edit 'Sharpens':
-  You can change the opacity of the main group or of each layer individually.
   Use the opacity of the sub-group 'Details'.
-  Edit the masks. Especially the mask of the main group 'Details', you can double click it to edit
   the Density parameter. 
-  Change the smart filter Surface Blur of 'Detail A' to change the type of detail it gives.



[HIGHLIGHTS & SHADOWS]
This set of layers creates the contrast between highlights on one side and
shadows on the on the main part of the image.

How to edit 'Highlights & Shadows':
-  Edit the masks. Especially the density parameter of the sub-groups 'Highlights' and 'Shadows',
   this is one the first thing that should be adjusted. By default both mask have a density of 50%.
   If you set the density of the mask of 'Highlights' to 100% and 'Shadows' to 0%, it means that the area in shadow
   will not have any highlight in it at it'll be almost black and the group 'Shadows' 
   is free to completely darken that area.
   This can be achieved by also manually brushing these two main masks or also each mask individually.
   Doing few things manually will give a better touch to the final result.

-  Edit the opacity of all these layers and groups.
-  Blending modes. You can try different combination of blending modes on both layers and groups.
   Use darkening blending modes on the shadows and lightening ones on the highlights.
-  Edit the gradients of 'Shadow 3' and 'Shadow 2'
-  Edit the layers style Inner Shadow of 'Shadow 1', Distance and Size parameters.
-  Edit the layers style Bevel Emboss of all the Highlight layers, Depth, Size and Soften parameters.




[LIGHT FX]
Here are grouped the lights created by the action which are the 'Light Source', 'Volumetric Lights'
and ' Highlight Blurs'.

How to edit 'Highlight Blurs':
-  Change opacity, of the layers and groups.
-  Try other lightening blending modes.
-  Change the smart filter 'Motion Blur' to make them more or less blurred
-  On some images it works better to hide one or both the 'Highlight Blurs'

The 'Voluemtric Lights' group adds the rays of light to the image and are highly customizable.
The first two are generated randomly and they'll change after each playback.

How to edit 'Volumetric Lights':
-  Change fill, and not opacity on these 3 layers, because fill simulates a higher image depth 
   on lights when lowering the values under 100%. 
   Instead use the opacity of the main group 'Volumetric Lights' if you want to decrease the 
   presence of these lights all at once.

-  Change blending modes. There are plenty of combinations of blending modes that work with these three layers
   and give different result. By default starting from the bottom the three layers are set to
   screen/linear dodge/linear dodge, but also screen/color dodge/screen or normal/linear dodge/screen  
   can work, try to experiment a bit with also other blending modes.

-  Masks. These are quite important, each layer has a pre-made mask that covers it in a part of the image.
   There's a lot of editing that can be done but these three masks should not be moved or distorted too much.
   You can select the three masks and paint on them, invert them to see if they give any interesting result
   (to do it select the mask and press CTRL+i or CMD+i on Mac).
   Also you can apply adjustment such as levels, making the mask more contrasted will make the light more
   visible in a side and less in the other.

-  Apply Transforms. Notice that the lights number 1 and 2 don't have a lock between the layer and the mask channel,
   that means that they can 'slide' under the mask. For example select the thumbnail of the layer 'Volumetric Lights 2',
   then press CTRL+t or CMD+t on Mac, to activate the Transform tool, as you can see the layer is already a bit distorted.
   You can apply any kind of transformation , to apply a distort keep pressing CTRL or CMD and drag the corners and midpoints
   of the Transform tool's bracket. 
   Big distortions don't always work, try to make the layer interact better with all the rest.
   Same thing can be done with light number 1. 

-  Change Color. Also you here there's a Color Overlay layer styles to decide the color, and you can try different combinations 
   of blending modes between the Color Overlays of this group. 
   Try Normal, Multiply, Screen, Linear Dodge, Color Dodge, Overlay, Soft Light, Color.

-  Gradient of 'Volume Light 3'. This gradient can be totally customized.

-  Duplicate and mask, use the layers as information. If for example a part of the image is lacking some detail,
   you could duplicate 'Volume Lights 1' or 'Volume Lights 2', reposition and tweak it's opacity and blending mode 
   to work good in the needed part. 
   Next delete the mask channel by right clicking on it and 'Delete Mask Channel',
   then apply an inverted mask, by keeping pressed ALT or OPTION on Mac and clicking on the 'Add layer mask' icon
   at the bottom of the layers panel. It will create a black mask and the layer will be hidden, 
   use a big soft white brush on the mask to reveal the interested area.


How to edit 'Light Source':
-  Change fill, like for the volumetric lights.
-  Apply Transforms, to do it press CTRL+t or CMD+t on Mac. Usually this light works better outside the canvas or near the corner.
   Making it really large will make the main element look surrounded by the light and will give a nice effect.
   You can also distort it.
-  Edit mask. The mask is white because usually this light is away from the main element, but if you need to put it near,
   a nice thing to do is to copy the mask from 'Volume Lights 2' to this layer. To do it keep pressing ALT or OPTION on Mac
   and drag the mask from 'Volmetric Lights 2' to 'Light Source'.
-  Change the smart filter Gaussian Blur, to make it more ore less blurred.
-  Change color, same as the volumetric lights.




[OVERLAY FX]
These layers add some environmental details.

How to edit 'Fog':
-  Change opacity.
-  Change blending mode and experiment with the modes.
-  Edit the mask.


How to edit 'Particles':
-  Change opacity.
-  Change blending mode and experiment with the modes.
-  Edit the mask.
-  Change Color. The blending modes that works here are similar to the one of the lights.
   An orange Color Overlay set to Color Dodge blending mode can make the particles looks like little sparks.
-  These layers are generated randomly, so for each one there is a version B that you can combine with the main ones
   after un-hiding them.


How to edit 'Grain' and 'Vignetting:
-  Change opacity.
-  Change blending mode and experiment with the modes.
-  Edit the masks.
-  You can change the color of 'Vignetting' by double clicking it's thumbnail. 
   Often this layer works better if the area were the lights come from is masked, to do it select the mask and a soft black brush
   and brush over the area of the lights.




[POST FX] 
Using these layers is possible to fine tune the look of the image.
The first three from the bottom are used only with parameter opacity. 'Tune Shadow' will add some contrast to the shadows,
'Tune Highlights' will add contrast to the highlights and 'Global Contrast' to the whole image.
'Colorize/Hue/Sat' is a simple Hue/Saturation adjustment layer, but it's useful both to apply a Colorize effect
and quickly make some sepia tones or other dramatic looks, 
or to used as normal Hue/Saturation by deactivating the Colorize option.



[COLOR CORRECTIONS]
These layer will give a final color grading and further control over the final look.
A color correction is not always necessary since if each component can be colorized individually,
but it can blend all the elements together and give a different tone to the image.

The first two layers are simple adjustment layers for Levels and Hue/Saturation.
Then there are the 20 color options, 15 colored and 5 black and white.
Un-hide one by one and choose your favorite, use the opacity parameter to tone it down if it's too aggressive.
For the grouped color options use the opacity parameter of the group.
You can also try to mix two color options by blending their opacity parameter.
Also you can try to mix the 'Colorize/Hue/Sat' layer of the 'Post FX' group in combination with
a color correction. 


---------------------------------------------------------------------------------------------------------------


If you need any further help please contact me through my profile page on Graphicriver:

http://graphicriver.net/user/BlackNull



Check also my other products at this link:

http://graphicriver.net/user/BlackNull/portfolio


---------------------------------------------------------------------------------------------------------------


Please don't forget to rate this product in your download section if you like it!


Thank you for the support,

BlackNull




