# Abstract
&emsp;&emsp;This is an immersive English cross-cultural communication scene roaming based on VR all-in-one machine. Through the VR simulation of the language environment of a foreign cafe, we create an immersive environment, and are committed to providing users with a platform to practice English in four aspects: listening, speaking, reading and writing, which is not boring and creative.  
<div align=center><img src=""/></div>  

# 1. Project Introduction
## 1.1 Design Ideas
&emsp;&emsp;This application chooses English learning as the theme. Meanwhile, a double-storey cafe was designed and modelled by the team members, plus information collection and discussion. We divided the application into two main parts, one is **scene roaming** and the other is **fun interactive learning**.  
&emsp;&emsp;In terms of **scene roaming**, we have created an original scene design and added a number of scene interaction points to create a real atmosphere, making players feel like they are in the real world.  
&emsp;&emsp;In terms of **fun interactive learning**, we start from the four aspects of **listening**, **speaking**, **reading** and **writing**, which are common in English learning, and design fun and interactive functions:  
- :speech_balloon:**Speaking practice**:Speaking exercises can be triggered with non-player characters in specific areas of the scene;
- :books:**Reading practice**:Look for items in the scene such as computer/ipad and click on them to see an English article (classic beauty/real-time news), which the player needs to finish reading;
- :ear:**Listening practice**:The scene is set up with a listen button that the player can click on to listen intently to the dialogue we have set up for the non-player character (the material is taken from the two-person dialogue in the listening test);
- :pencil2:**Spelling practice**：Daily Proverb boards at the entrance to the café; and crossword puzzles on the big screen in the screening room on the first floor.
## 1.2 Application Innovation Points
&emsp;&emsp;① **Thematic creativity** that focuses on language application for intercultural communication rather than limiting itself to learning and test scoring. Focus on the actual use of the language scene, pay attention to the details and authentic expression of the silent immersion, so as to promote the application of thematic innovation.  
&emsp;&emsp;② **Content creativity**, traditional classroom teaching lacks practical opportunities, and the strict grading system gives people a strong sense of pressure. This product breaks through the tradition and provides an immersive VR environment. Users can practice speaking, listening, reading and vocabulary in the virtual scene. Unlike theoretical learning, this product combines theory and practice. Users not only learn grammar, but more importantly, use English more in the virtual environment, master better expression ability, and learn to express themselves more authentically;  
&emsp;&emsp;③ **UI creativity**, purely original UI design, set up original logos, labels, slogans, patterns, etc., unified style and colour, systematic integrity is good, and strive to create a more close to the scene style and suitable for the VR scene of the UI design;  
&emsp;&emsp;④ **Technical creativity**, the use of PICO equipment development, clever use of handle buttons, so that the user has a more immersive feeling; another random and challenges, high playability, interesting, interactive experience.  
The overall framework flow of the application is as follows:
<div align=center><img src=""/></div>  

# 2. Technical Realisation
## 2.1 Scene Building
&emsp;&emsp;We realised the construction of the cafe scene in **Blender**. By studying the construction drawings of each cafe to learn about zoning and design, we designed our own original cafe with layers, functions and atmosphere.The setting is designed for a medium-sized urban cafe. It is divided into **two floors**：  
&emsp;&emsp;The ground floor is the largest activity area, with an open space. Different seating areas are set up at the entrance to facilitate the seating of different types of customers, and the rear is equipped with a long bar to provide quick service; a glass room is set up on the left to make full use of natural light and create an open space; and a washroom is set up under the staircase on the right to comply with the basic cafe structure.  
&emsp;&emsp;The first floor has an open view over the ground floor, linking the whole space together. A large LCD screen on one wall plays music and films on different themes.  
&emsp;&emsp;In summary, the design emphasises the social space on the ground floor and creates a diverse atmosphere by utilising the double height. The emphasis on natural lighting and open space is close to the design concept of a medium-sized urban cafe.  
<div align=center><img src=""/></div>  
<p align="center">(Diagram of the modelling process in blender)</p>
<div align=center><img src=""/></div>  
<p align="center">(Above is a sketch of the section/plan design)</p>
<div align=center><img src=""/></div>  
<p align="center">(Above is the final floor plan)</p>
<div align=center><img src=""/></div>  
<p align="center">(Above is the scene effect picture)</p>

## 2.2 UI Design
&emsp;&emsp;We designed the overall UI in Figma, using warm orange as the main colour in the design process, which is similar to the colour scheme of the café. The UI of the whole application is systematic and organized, with a clear catalogue, rich content, and detailed and logical jumping relationships.
<div align=center><img src=""/></div>  
<p align="center">(Overall UI design)</p>
<div align=center><img src=""/></div>  
<p align="center">(UI interface implementation effect demonstration)</p>

## 2.3 Functional Realisation
&emsp;&emsp;Most of our functions are realised through range detection, i.e. UI appears when you enter the interactable range, and you experience the function after interacting with it according to the prompts. Meanwhile, in order to better integrate the division of labour of each member, we adopt the way of demo for development, and the following functions are all demonstrated in the **demo scenarios**  
- Scene roaming：  
  We developed a controller for the player's character using the camera prefabs in Unity×Pico SDK.This includes basic movement and interaction with objects in the scene.
- Implementation of the read screen article Function：
  <div align=center><img src=""/></div>  
  
- Implementation of Dialogue Listening Function：
  <div align=center><img src=""/></div>  
  
- Implementation of Interactive Dialogue Functions for Cross-Cultural Characters：  
  <div align=center><img src=""/></div>  
  
- Implementation of ordering function：  
  <div align=center><img src=""/></div>  

- Implementation of a crossword game：
  <div align=center><img src=""/></div> 

## 3. Live demo screenshots
  <div align=center><img src=""/></div>  
  <div align=center><img src=""/></div>  
  <div align=center><img src=""/></div>  

