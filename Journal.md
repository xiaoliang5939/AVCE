# Legent of Hanzi: Uniting the Past and Present

 Group work
 
 Video link：https://youtu.be/5GPBzBXBggk
 
 Outlines the design and development PDF：https://github.com/xiaoliang5939/AVCE/blob/main/Legend%20of%20hanzi%20%201.pdf
 
 Author: Xiao Liang

 Student ID: 22010608
 
 Yining Jiang(Jenny): Unity content integration, Arduino code integration, Arduino to Unity communication.

 Zhou Fang(Nora): Hardware code(Arduino), project planning, 3D modelling, Foley, physical device assembly.

 Xiao Liang(Luna): Audio assets, visual effects assets, 3D modelling, video shooting and editing, documentation.

 Han Hsun Shih(Amy): Art assets.

 Collaborative completion: Multiple testing, physical environment setup, and small-scale player experience exhibition.

 Inheritance from the previous term: Inspiration from the Tower of Babel, improving signal transmission efficiency between Arduino and   Unity, changes in code structure.
 
 
# Week 4

This week marks our first group discussion of the term.  Following our discussion, we aim to carry out iterative design based on the work we did last term, titled 'Tower of Babel,' a motion-sensory interactive game inspired by the Tower of Babel story, contributed by Yining.  Last term, we utilized four sensors to achieve the desired game interaction.  For this term, we have decided to continue with this interaction method and build upon it through iterative design.

<img width="349" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/5261d9b2-97f8-459b-876c-a7dcd4e2f821">

<img width="383" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/fa66a8d0-81d8-4ac7-8bc8-b5a331fbfa4c">

<img width="475" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/effe124a-9458-49e2-a8bd-56ae722766b5">

<img width="849" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/65c5065b-afeb-4321-828f-06acc344a01d">



During the brainstorming process, I suggested incorporating elements of ancient Chinese hieroglyphics to symbolize the idea of overcoming language barriers in the Tower of Babel.  In terms of interaction, I was influenced by the recent game 'Legend of Zelda' and proposed the inclusion of a bow and arrow mechanic.  After discussing this idea, we unanimously agreed to adopt it.

Building on these concepts, we further discussed the complete game flow, which involves dividing the game into two levels.  In the first level, users will need to select the correct image corresponding to the English words they hear, using our unique bow.  For the second level, players will observe the evolution of hieroglyphics into modern Chinese characters and aim to hit the bull's eye as accurately as possible using darts.

During the discussion, Zhou expressed her desire to incorporate new sensors in an iterative manner, ensuring they do not pose any health risks.  This consideration stems from our previous experience where, in the last exhibition of the previous term, we chose to forgo one sensor to prioritize health and safety.  Yining proposed a novel approach using Rubber Conductive Wire sensors attached to the bow and arrow.


# Week 5

RESEARCH

Hieroglyphics

Oracle bone inscriptions are the earliest mature Chinese characters we can see, and they are named for their engraving and writing on tortoise shells and animal bones. 

‘Know what it is, know why.’ The origin of Chinese characters reveals the original intention of modern Chinese characters, which is quite beneficial to learn.

<img width="314" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/f84f8e5e-d30a-41af-b563-e3d90fb98dd5">

Definition source：http://www.360doc.com/content/12/0121/07/15820106_1080831969.shtml

Chinese oracle bone script is the best preserved Chinese character font. The Chinese characters we use today originated from this hieroglyphic system.

<img width="360" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/e992348a-30ad-4322-aefb-42e84c542fbc">

Interactive mode

Darts are small, easy to operate, have a long range, are highly concealed, and have extremely sharp spikes. And very deadly, because the user would coat the darts with poison.

<img width="451" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/ba85c246-12f7-412c-902d-a5a510e11dcf">

Definition source：https://baijiahao.baidu.com/s?id=1740309703812868082&wfr=spider&for=pc

The bow and arrow is a rare remote weapon in ancient cold weapons, according to legend, the bow and arrow was invented by the ancestor of Zhang, so it was given the surname Zhang. Ancient bows and arrows are very dangerous long-range cold weapons.

<img width="390" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/9aea9952-d348-49eb-884b-48d25c802f79">

The spear was a favorite weapon of the ancient infantry, usually holding a shield in one hand and a spear in the other. The length of the spear is generally about five meters, and the red fringes on the spear can disturb the enemy's view.

<img width="626" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/180c6946-ee08-452c-9b1c-342933dac5bf">

Definition source：https://history.sohu.com/a/679839761_121166559

In this week's group discussion we worked together to select the hieroglyphs we wanted to use in the game

 
 <img width="1036" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/125271d5-e820-4d4c-8d9d-c5d754b1a533">

<img width="1033" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/2e2c3917-835a-4374-b048-f444c4938dad">

<img width="1029" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/77e6161d-d060-40c7-b354-2214d5be16ed">

<img width="319" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/d5de89f2-2590-411e-bb8b-d0c971f939c0">

<img width="323" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/79b99fc4-e5e4-4daa-8225-3dff3de3e0bb">

<img width="318" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/942653ed-297f-48f5-983f-4da0b41ef880">

From these four modeling styles, Zhou and I chose the second one. Reference link：https://www.bilibili.com/video/BV1PV4y1Z73e/?spm_id_from=333.788.recommend_more_video.11&vd_source=75160127f8394433f97c8d8727c85672
 

<img width="417" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/f0d7ebb2-713c-4fca-9eca-4bad85cf281e">

<img width="791" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/cdf722c6-4b99-43e9-976f-717a37ef5505">

<img width="568" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/70f155f3-5b43-404c-ae32-95a3e281404f">

<img width="605" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/86b072e0-cbb4-46b4-a7df-4978179bd52c">






# Week 6 

This week I finished modeling object text. I used blender to model the text in the same way I created brushes.


I chose to model the text as: moon, mouth, cloud, water, rain, wood.(月、口、云、水、雨、木)


<img width="1440" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/537d402e-b128-4383-b18c-5200fda22904">

<img width="1440" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/a3d43ee2-886a-4871-9d02-84ae0ee3a1a1">


During the process of making this 3d model, I learned how to create brushes in blender and became proficient in adjusting the pressure of the brushes.


<img width="1440" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/b9388da3-7818-4a18-962e-53ea2ccca7cb">


In this week's group discussion, I poured the modeled 3d text separately and gave it to Yining, who imported our modeled text into unity.

3D model：https://github.com/xiaoliang5939/AVCE/tree/main/Blender%203D%20model

# Week 7

On the basis of the Zhou's flow chart, a complete flow chart is added and prepared for the full pdf later.


<img width="621" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/b62e330d-7f6a-4c33-84ce-8cd0636b6f80">



Also, this week I need to make an in-game hint style.


During the design process, I wanted to make the prompts more specific to our game. For this purpose I refer to some styles of ancient Chinese calligraphy


<img width="447" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/d671d6e3-c6d2-4db2-ac45-b9cda7827b14">

<img width="572" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/ce45d09a-0227-46d8-b907-85f55ef2c8f1">


I want to try to use calligraphy to present the English style


<img width="973" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/90111f0e-ac00-40e7-ae93-485a1615a888">


However, because I have not learned calligraphy professionally, I have already learned the difference between English and Chinese writing, and I think the effect is not good. So I thought maybe I could use some elements of calligraphy as a background for the hint, so I referred to some elements of radicals in calligraphy.


<img width="614" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/4a2d7ffc-8de4-4a3d-85a0-6727f889ae91">

<img width="942" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/0f7a61fc-a609-42a9-a178-7e5225c76b40">

Based on this, I chose the radicals as the cue background and drew a different background for each cue.

<img width="1035" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/8f7d8007-c932-4953-aca6-2db61be6487e">

<img width="863" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/7680bb14-c97d-494f-bbea-b94bed961aae">

<img width="629" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/ec0527d7-be8a-4641-8b1e-8a6119dcac8f">

<img width="875" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/5e20604b-08df-4dd4-b0c1-9341a430893d">

<img width="888" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/77a61db1-60e6-4c43-8499-cd76fddd92df">



Conduct the first group test. The participants of this test are：Yining Jiang 、Zhou Fang、 Xiao Liang


We chose dark lab as the final filming location.And since our work requires darts at the screen, we need to make our own safe screens.After many attempts, we chose to use the school table as a projection screen after standing up.As for the occlude, we need to occlude the screen so that it doesn't reveal the magnetic board behind it, but it also needs to be able to attach the magnetic dart to it.I went to the market and finally chose white curtains.


<img width="537" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/01a74693-581e-4e51-9e7a-5a3b66585835">


For this test, we tested the feasibility of homemade screens, and together we tested the sensor part.


<img width="939" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/99a9adbe-2f18-4d9c-9789-88563c74c503">

<img width="948" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/3af64b83-7c63-42b2-b040-8af68a4cc287">

<img width="941" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/6e0213d3-aee7-46dd-8856-0b1d64e0cd60">

<img width="948" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/2b239e85-626d-40fe-8054-bb4a44e37907">

<img width="945" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/9a0dab23-89ad-4720-8bdf-d539880e1472">

<img width="947" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/542f0005-f628-4146-83be-f10994526d66">

Visual effects assets：https://github.com/xiaoliang5939/AVCE/tree/main/Visual%20effects%20assets


# Week 8

This week I studied the background music for our game.Since the theme of our game is about traditional Chinese characters, I hope to find suitable music with Chinese characteristics.While searching, I found that although they were all classical Chinese music, they sounded very different in terms of emotional content.Some music is too big for our game, and some music is too sad for our game.Out of a lot of music, I finally chose "Jiangshangqingfeng" and "Pingxuyufeng" as the background music for the game.

Audio element file：https://artslondon-my.sharepoint.com/:f:/g/personal/x_liang0220222_arts_ac_uk/EkJ2fd-4bvRAqbUxd_1b1ZEB3jcgYzQe7WsjWVPbS2EjfQ?e=bZIxkD

Access to music：[bilibili](https://www.bilibili.com)

Also this week, we learned how to create sound effects for our games ourselves. We need exactly three sound effects for our game, namely the bow sound, the bow sound, and the darts sound.I found it difficult to simulate the special effects of drawing and releasing the bow.Because he needed something very elastic and tough as a simulation, I used sticks and plastic bags to simulate, but the effect was not ideal.But Zhou used the collision of metal and wood to simulate the Foley of a dart hitting a darts sound.So we finally decided to use Zhou's Foley as the sound of a dart hitting a target.Then I found the right sound effects for bow drawing and archery on the Internet.

Audio element file：https://artslondon-my.sharepoint.com/:f:/g/personal/x_liang0220222_arts_ac_uk/EkJ2fd-4bvRAqbUxd_1b1ZEB3jcgYzQe7WsjWVPbS2EjfQ?e=bZIxkD

Access to music：[bilibili](https://www.bilibili.com)

I also wrote a video script this week. We figured out what our video should be about and how long it would last.

<img width="727" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/1454c780-1993-4776-afb6-afb6436314b3">




Conduct the second group test. The participants of this test are：Yining Jiang 、Zhou Fang、 Xiao Liang
Check out our test video here：
https://artslondon-my.sharepoint.com/:v:/g/personal/x_liang0220222_arts_ac_uk/Eeb1GuxUenRLrbYyqNfCGO4Bb4YcYcX5_JMpe8vkKhXuZg?e=KWm7eZ


Icon design

I wrote “汉字” by hand using elements of Chinese calligraphy. At the same time overlay the background elements to form our icon.



<img width="685" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/b124c1b3-0e5b-49f1-93e5-7a1d08ce4a9d">

Hanzi
（Chinese characters）

<img width="178" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/4e7c4804-459c-42ec-9d0f-e898de0a9c71">

We added and supplemented the design of buttons in the game. This time, we still used the side radicals of Chinese brush to design the button style of our own game.

<img width="1048" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/baee7061-f76c-4066-aefe-a011c2f667d8">

<img width="1049" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/f7b4988f-7a7c-461a-98b8-2fcd2d52561a">

<img width="695" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/6d1ddcc7-b613-4b27-9c6c-328a7bd8f6cf">




Visual effects assets：https://github.com/xiaoliang5939/AVCE/tree/main/Visual%20effects%20assets


This week I also finished editing the first two pages of the portfolio of this work.



# Week 9

Construction and arrangement
We finished the final test and set up the scene.

<img width="438" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/4cfa427d-56e3-4fe4-828c-6e31e4a43be4">

<img width="435" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/7c2564b8-c92e-4d73-936b-5f07a190e43d">

<img width="438" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/0b521b07-6cf5-4475-b09b-6af01b19caca">


Finally, we finished decorating our small exhibition together and invited friends to experience it. Players enjoy our game when they play it.

And I finished shooting all the video footage.

<img width="437" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/7f705191-63e9-4168-87d5-837f64b41f73">

<img width="385" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/36afc397-d87e-4bbb-807d-99f601c6dddd">

<img width="382" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/97f4bd13-0801-42fb-b1c4-c97a7ebf8bf4">

<img width="382" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/2facd235-d752-4a27-a97f-0885e50a294d">

<img width="383" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/3cf2468e-296a-4229-a550-dae1968ac1bc">

<img width="383" alt="image" src="https://github.com/xiaoliang5939/AVCE/assets/76156342/65a7a107-2b62-4727-ac62-98e1fa6c93fd">


I finished all the editing of the pdf document of our work in the last week, please see this link for details:
https://github.com/xiaoliang5939/AVCE/blob/main/Legend%20of%20hanzi%20%201.pdf

In addition, I completed the video clip of our work and the copy editing of the explanation in the video, please see this link for details:
https://youtu.be/5GPBzBXBggk

Video explanation dubbing is completed for each of our group.



 
