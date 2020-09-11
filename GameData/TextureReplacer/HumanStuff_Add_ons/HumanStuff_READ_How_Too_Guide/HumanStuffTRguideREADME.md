
HumanStuff Layered Component Workshop For Texture Replacer Guide 
============================================================
My conversion from TRR to TR & continuation of updated "TRR guide", no longer maintained, by @HaArliNsH via CC (0)
============================================================

# Note on file formats, namely .DDS vs PNG ** 

KSP supports others image file formats, but these are are focus, for these uses)

PGN files are shadowed in ram, DDS is not, so in basic terms "DDS files load faster & use less ram"

"Basic" DDS files are DXT1 and are 100% fine, "Some" files need DXT5, if so it will be noted in guide.

KSP does support more than DXT5 (BC3) as DDS files. As the "RGB colour space" across DXT1(BC1), 3(BC2) and 5(BC3) is the same. What changes is how "alpha channels" are handled. In this sense, DXT5 offer the "best" compression method for the alpha channel, out of those 3. If you don't need information in the alpha (typically specular data), then you can still use DXT1

=================================================
=====================================

# Note amoun amount of suits, heads etc:

Try to use the same "standard rank" suits etc, as much as possible! Unless you "REALLY NEED" ranked suits, etc.
This can save alot of space & memory!

If you want to lower the number of "Textures/NRM Maps" used, try to only 1 "item(s)" & "NRM map(s)" for each used per save.

AS:

For "GalaxyTex" (skybox) and "EvnMap" (refections) YOU SHOULD ALWAYS BE USING ONLY 1 "SET" OF EACH AT ONCE
You can lower the GalaxyTex to 2048x2048, down to 1536x1536 for "low ram", Env to 32x32 (or just set to "off")

1 male head NRM map (& just 1 head per active kerbal, if you are desperate 384x384 is as low as I'd go for head

1 female head NRM map (& just 1 head per active kerbal, if you are desperate) 384x384 is as low as I'd go for head

1 suit map NRM map (& just 1 IVA & 1 EVA "worn suit" in total, with no rank or vetern suit, if you are desperate, 2048x2048, down to 1536x1536 is as low as I'd go for suit

1 visor NRM map (& just 1 IVA & 1 EVA "worn visor" in total, if you are desperate 384x384 is as low as I'd go for visor 

Optionally 1 of each of the 3 "Backpack" type, if you are desperate 512x512 is as low as I'd go
Optionally 1 Parachute Canopy, if you are desperate 512x512 is as low as I'd go


======================================================


# KEEP THE FILES SAFE > always open and "save as" a new name like "WorkingOnType.png", with type being suit or head etc. This will prevent you from accidently overwriting your "template" files (do the same when editing your suits or anything...its a good pratice!) **

==================================================


# LCW_Guide is a collection of textures made to be used with TextureReplacer

All of these textures are made in a bigger format than the stock textures. The originals size for suit/skyboy textures was usually 1024x1024 or "1K", try to make that your MINIMUM, we can use average textures sized 4096x4096 or "4K",... and even 8192x8192 or 8K, UP TO A AMAZING 16384x16384 if your system can run it with out issues :) 

ENJOY 1K Min Res set, 2K Low Res set, 4K Std Res set, 8K High Res set & 16K Ultra High Res set TEXTURES !  

********************************************************

# Notes on image and file sizes 

High Res set, or higher, textures can quickly use a lot of memory and you need to make lag or even crash.

My advice for the sizes of your SR or "4K set" texture set is to use differents sizes for the diffrent items:

EnvMap (Visor reflextions): 512x512
Faces/visors: 1024x1024
Cargo packs, Jetpacks, Parachute packs & Parachute canopies: 2048x2048
Suits & Galaxy Tex (Skybox): 4096x4096



You can go for bigger but here is some number to help you understand what I mean : 


- File size of pure black image set in 4096x4096 & 32 Bit depth =
- File size of pure black set image in 2048x2048 & 32 Bit depth =
- File size of pure black set in 1024x1024 & 32 Bit depth =


Again, Try to use the same "standard rank" suits etc, as much as possible! Unless you "REALLY NEED" ranked suits, etc.
This can save alot of space & memory!


# **************************** HOW TO MAKE A HEAD/SUIT PACK ****************************


**  KEEP THE FILES SAFE > always open and "save as" a new name like "WorkingOnType.png", with type being suit or head etc. This will prevent you from accidently overwriting your "template" files (do the same when editing your suits or anything...its a good pratice!)

Now lets a male kerbal: 

1: You start by your 1st the Male version "Head",* ensure mouth, toung and teeth are coloured to your wishes and avoid placing unwanted items in this "bottom bar".

2: Select the desired "parts" for the head in order: (you already have a "base" skin tone head)

In order, as layers, on "base head": Eye sockets > Aging features (optional) > Hair > Facial hair 

You can find the guide for the zones of the different textures in the "old" ksp v.1.3 TRR_guide file, as heads have stayed the same.

3: Use Paint.net to combine the layers in above order and merge all (they have transparent backgrounds so its nice and easy). "Save the File as", set to "best quality settings", as "kerbalHead.PNG", in a folder on your desktop named "MaleHead01" for safe keeping and ease of editing, DO NOT CLOSE FILE IN Paint.net

Now: With the file still open in Paint.net, "mirror vertically" and "Save the File as", set to "best quality settings for DTX1 or DTX5", as "kerbalHead.DDS", in a folder on your desktop named "MaleHead01"


4 : You make the female version and have a kerbal of each gender. 

Using a female version "base head" (they are different, as they have a different "map", so MANDATORY, as with the male watch that the mouth & "hair band" are colored to your wishes and avoid placing unwanted items in these areas.

Select female "parts" as you did for male. This is  mandatory for all the parts exept these because the female version head mesh is different as you can see on the "map" 

In order, as layers, on "base head": Eye sockets > Aging features (optional) > Makeup (optional) > Hair
		
You can find the guide for the zones of the different textures in the "old" ksp v.1.3 TRR_guide file, as heads have stayed the same.

5: Use Paint.net to combine the layers in above order and merge all (they have transparent backgrounds so its nice and easy). "Save the File as", set to "best quality settings", as "kerbalGirl_06_BaseColor.PNG", in a folder on your desktop named "FemaleHead01" for safe keeping and ease of editing, DO NOT CLOSE FILE IN Paint.net

Now: With the file still open in Paint.net, "mirror vertically" and "Save the File as", set to "best quality settings for DTX1 or DTX5", as "kerbalGirl_06_BaseColor.DDS", in a folder on your desktop named "FemaleHead01"

============================================================

# Suits:

1 : You will find the "base labeled suit template" & "layers" for the of each elements you want to use. This will let you save "parts" of suits, sets of parts, or the ability to quickly "edit your suits"

Thess can be color variation on the base suit "parts", like:

 a set of boots, pants, helmet, patches, logos, name tags, medals etc. 

Your "basic parts", for EDITING NEW SUITS from needs to be "generic for your wanted look" and use "close color codes" on "single parts" as possible, so if you make "color pallette" change, its as easy as possible on you. Fine details, etc can be added during the "build". KEEP THE FILES SAFE > always open and "save as" a new name like "WorkingOnSuit.png", this will prevent you from accidently overwriting your "parts template" files.
  

I Will detail suit construction in a later revision of this document.
===========================================================================

# Working on NRM maps: !!! export in .png Uncompressed !!!  

1 : Generate all the normal Maps (NRM) you need from the ones in examples and save them also in .png uncompressed LOCALLY (on your computer) if you can, as backups. 

Put all these NRM in a different folder than the others, just like everything else, to avoid over writing your templates...Don't overwrite them !! you never know if you are going to need them again.   

I Will detail "NRM map" editing/construction in a later revision of this document
================================================================================

8 : PGN files must be mirrored vertically, all these files, when saved as DDS. Don't overwrite them !! you never know if you are going to need them again.   
	
I used XnConvert (see the usefull tools part)
	
9 : Batch convert in NRM all these files as this (I used XnConvert & Paint.net) : 
	
	- Use dxt1 with "Mipmaps" checked for the "backpacks" and suits
	
	- Use dxt5 with "Mipmaps" and "alpha" checked for the visors
	
	- Use dxt5NormalMap with "Mipmaps", "Normal" and "toNormalMap" checked for the NRM
	
	
	
****************************  Usefull tools :  ****************************

The files in guide are the working files I use to make all the original additions you can find in this pack. I use this software:

- Paint.net: 100% Free and, imho, the best program to make images. It can edit normal maps & can open .dds files in Paint.netp and you will also be able to see the image in .dds in your Windows explorer as thumbnails & XnView classic like it was a "normal image file" (png, jpeg, etc) VERY fast. 

- XnView classic: 100% Free like it was a "normal image file" (png, jpeg, etc) VERY fast. Can handle over 500 image formates

- XnConvert, 100% FREE, easily handles the files we will use. Like to "batch modify" your texture file , like the invert you need to do before converting .png to .dds or to "batch resize" a whole folder of files.

- [NormalMap-Online](http://cpetry.github.io/NormalMap-Online/)
Online tool for generating Normal, Displacement, Ambient Occlusion and Specular maps 
