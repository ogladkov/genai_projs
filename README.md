## Cars cutout with generated shadows and reflections

#### Project description
The project considers unification of a set of car photos getting consistent look at the website.
#### Workflow
* Cut the car from an image
* Place the car to a background image
* Generate reflection and shadows maps
* Merge all

#### Input data: photos of car, background images

*Background:*
![](imgs/bg002.png)

*Cars:*
![](imgs/IMG_4089.jpg)

![](imgs/IMG_4088.jpg)

![](imgs/IMG_9427.jpg)

#### Result
The main point of the project is to get organic view which is unreachable without shadows and reflections

![](imgs/ComfyUI_temp_drdft_00001_.png)

![](imgs/ComfyUI_temp_drdft_00009_.png)

![](imgs/ComfyUI_temp_drdft_00014_.png)


## Painting panoramas to photos (Vilnius City 18th century)

#### Project description
A project for a TV historical series. The task was to recreate paintings of ancient Vilnius panoramas as photos. 
 
*Input 1:*
![](imgs/i12.jpg)

*Output 1:*
![](imgs/o12.png)

*Input 2: *
![](imgs/i11.jpg)

*Output 2:*
![](imgs/o11.png)

*Input 3:*
![](imgs/i13.jpg)

*Output 3:*
![](imgs/o13.png)


## HeadShot App - Photo Enhancer

#### Project description
A workflow for the headshot app which considers utilization of InstantID and IPAdapter for SDXL aiming to nhance users photographs.
#### Workflow
* Take users photo
* Extract facial embedding with InstantID
* Extract haircut embedding with IPAdapter
* Properly masking
* Generate a person with the background regarding textual prompts 
 
*Input:*
![](imgs/input1.png)

*Workfl (prototyping in ComfyUI):*
![](imgs/wf1.png)

Output:
![](imgs/output1.png)


## Game components generation with depth maps
#### Project description
The goal of the project is to setup the workflow which allows to generate images and masks for the images for a game where it is necessary to keep one style and fit cells using depth maps of objects. 
*For example: we have a depth map of a cell for factory (the image below): 

![](imgs/factory_depth_1.png)

#### Workflow
I used ComfyUI to arrange all the nodes and eventually get proper generation of the images and its mask. ![[Upwork/_pics/wf_1.png]]

#### Result
Finally I got the workflow which can generate infinite number of stylized masked images for a cell map of the game in high resolution.

![](imgs/result.png)


## Consistent character 

### Project description
The most usable case for generative AI is characters generation. I worked much with the case and made some consistent characters known as "AI influencers" which is a huge trend in 2023/2024.
This projects considers:
* Train LORA model for a character
* Add pose control for the person
* Perform different facial expressions
* Utilize outfit application for the person basing on outfit image

### Input data

*Pose reference image: **pose_1***
![](imgs/pose1.png)

*Pose reference image: **pose_2***
![](imgs/pose2.png)

*Face reference image: **face_1***
![](imgs/face1.png)

*Outfit reference image: **outfit_1***
![](imgs/outfit1.png)

*Outfit reference image: **outfit_2***
![](imgs/outfit2.png)

#### Result

*pose_1 + face_1 + outfit_1*:
![](imgs/pose1_face1_outfit1.png)

*pose_1 + face_1 + outfit_2 + smiling:*
![](imgs/pose1_face1_outfit2_smiling.png)

*pose_2 + face_1 + outfit_1*:
![](imgs/pose2_face1_outfit1.png)


## Outdoor photo generation basing on a sketch and applying styles

#### Project description
Imagine, you have only a sketch of an outdoor location. You need to generate a photo of the building according the sketch and apply different style (e.g. spanish, contemporary, tropical, etc.).

*The sample of sketch:
![](imgs/arch_sketch_1.png)

#### Result

*Christmas style*
![](imgs/christmas_01.png)

*Spanish style*
![](imgs/spanish_01.png)

*Tropical style*
![](imgs/tropical_01.png)

*Contemporary style*
![](imgs/contemporary_01.png)


## Interior style change generation by one one photo

####  Project description
This is the work regarding interior style generation. Imagine, you have a photo (or a render) of an interior and it is necessary to change a style of the interior leaving fundamental parts. 

*The image of the base interior*
![](imgs/init_2.jpg)

*Balinese style*
![](imgs/bali_2.png)

*Contemporary style*
![](imgs/contemporary_2.png)

*Christmas style*
![](imgs/christmas_2.png)

*Victorian style*
![](imgs/victorian_2.png)

*Space style*
![](imgs/space_2.png)