# CSS-to-the-rescue-2024
This is a project from school

##Control panel
This is an interactive application  made in html and Css.

## Week 1
### Concept
In week 1 i came up with a concept.By looking for inspirations of modular designs i can remake. I finally came up with a concept of a camera.

### Sketches
<img src="./imgs/WhatsApp%20Image%202024-03-15%20at%2011.11.50%20(1).jpeg" alt="Image Alt Text" width="500" height="500">

<img src="./imgs/WhatsApp%20Image%202024-03-15%20at%2011.11.50.jpeg" alt="Image Alt Text" width="500" height="500">



## Workshop - color hsl , rgb , oklch , display_p3
During this workshop i got to understand the difference between the various *color models* I did an exercise on it making it more clear to me what each color model does.
### Notes ( Color panels)*

- HSL (Hue, Saturation, Lightness):

   - Hue: Represents the color itself, ranging from 0 to 360 degrees (red to red).
   - Saturation: Describes the intensity or purity of the color, ranging from 0% (grayscale) to 100% (fully saturated).
   - Lightness: Indicates the brightness of the color, with 0% being black and 100% being white.


- RGB (Red, Green, Blue):
   - Red, Green, and Blue are additive primary colors, with each ranging from 0 to 255 (or 0 to 1 in some contexts).

- OKLCH (LCh, Lightness, Chroma, Hue):
   - Lightness: Similar to HSL, represents brightness from 0 (black) to 100 (white).
   - Chroma: Describes the colorfulness or saturation of the color.
   - Hue: Represents the type of color, similar to HSL.

Link to codepen: https://codepen.io/Whitneyas/pen/vYMXBZa


## Ideas and inspirations?
- Piano
- Printer
- Desktop
- Washing machine
- Camera (Preferred)

### Experimenting with gradients 
***

### Experimenting with with textshadows

I was experimenting with how text shadow works and how i can animate letters one by one. I started experimenting in codepen. I also made notes on things i found about textshadows. 

https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/e9b83d14-4f18-448a-a9ce-153eea122ae6


## WEEK 2 

In week 2 i got an idea to add curtains that opens to my comcept. So the idea is that when the curtain opens then the title appears. Both curtains and texts would be animated.I followed a typography workshop and during this workshop i learnt how to animate text.

### Experimenting in codepen- Curtains 
I had to first experiment in codepen to see if it works before transferring to vscode. I was experimenting with gradients, and animation. How i can animate it to open and close. The knowledge i got forom the typography workshop i applied it to my concept. But first i tried it in codepen
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/b343240e-439b-4267-b182-e1d25dc76c88)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/eff69b4f-1dbb-4b15-a380-926981f4a3d5)

### Final results for the curtains and title 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/2222ada5-92b1-4388-9ac1-9c8e2379cf8a)


What i have now? 

In codepen : https://codepen.io/Whitneyas/pen/mdgroxd

### What i learnt ?
- How to animate text separately using span for each letter
- Use of vw to make components responsive (was new for me)
- Use of filter

### Deciding on the structure of my camera 
Before deciding on the sturcture of my camera i first drew out my camera and how i want it to be and the components it will contain. With this in mind the structure will become like this: 

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/ffdea408-dc56-4723-9aaf-bc2087a625e0")
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/789059d4-6021-4029-8395-41f06ed3cf43)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/494e353f-f22a-4c77-be6e-47bc2e99e723)
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/9f5c9949-06e5-4c51-b026-8a66d67ea7e4)


### Code structure
I was skeptical about how my the structure of my code for the camera is. Before having to start i wanted to get the structure so that it will be easier for me when deciding on which properties i want to use and which component i have to create or work on first.
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/e666dcf9-2e39-41ec-aed8-e302c1500057)


## Week 3 
In week 3 i decided to work on the different parts of my camera. 

### Printer
I wanted the printer to look more realistic not just a rectangle with a border but a more realistic 3d looking printer. I didn't know which css property i should use. I then thought of box shadow using inset property for the box shadow which helps me to draw the shadow inside the element making it look more realistic. I had a little difficult with making it more realistic so i was just add serverals insets to and trying out different ways to finally be like what i want it to me. 

### First try 

With this one i tried giving th bottom inner part een shadow which made it look like 2 double bars inside the element.

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/04d9836b-d1fe-4a00-b5aa-f490549c3bd4)

### Second try 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/48eea535-b408-43f8-af7e-ecc9ebba1a83)

 ### Code for second try
 After analysing what the problem was i decided to get rid of the shadow i added at the bottim inner part of the element to make it look more realistic🥰

 ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/52f23586-20a0-48ad-a4cd-99943ae0a86e)


 ### Turning label/input into clickable buttons



  ### Home screen with button icons
  ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/ebcd3577-d66b-4bed-80a4-97abd2cd81bc)
  This is the homescreen i have in mind to make. 




  ### Photo screen.

  I wanted to add an activate button that activates the camera. For this to happen i have to use js. Which is not allowed in this course but i still tried to see how it will turn out. I used js to make this happen but i couldn't position the camera in the container like i wanted to. It was taking too much of time so i decided to rather create a camera effect rather with just css. 


### First try to activate a camera. 
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/0d3e5575-722d-461b-be2f-bae2356a7d8a)

### code used
![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/0f40615c-cdaa-4f01-816a-932aa24ae23b)

![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/d4027166-536f-4358-8071-19e86c35bb0f)


  ### Gallery screen

  In the gallery screen i wanted to make gallery album using scroll animation so that i can scroll smoothly . I also made the gallery in a way that when you click an image you will get a bigger size of the image on the left. 

  Difficulty: The only difficulty i have is getting read of the vertical scrollbar on the left and the horizontal scrollbar on the right. I tried using overflow hidden but then it hides the scrollbar without me being able to scroll and that is not how i want it. I came to find out that using overlay will hide it the scrollbar but the scrtollbar wont lose its functionnality. 

  ![image](https://github.com/Whtneyas/CSS-to-the-rescue-2024/assets/90154152/39ccfa1b-5985-4f41-914d-40c37d1ce7b4)



  







### Resources
Images
- https://stock.adobe.com/nl/search/images?k=simple+cartoon+landscape&asset_id=79905462
  
Text shadows
- https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow

3d transoforms
- https://3dtransforms.desandro.com/3d-transform-functions
- https://3dtransforms.desandro.com/perspective
  

