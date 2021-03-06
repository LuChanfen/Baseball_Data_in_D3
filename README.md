# Baseball_Data_in_D3
   This project explores a baseball dataset which is from https://s3.amazonaws.com and includes 1,157 baseball players.This project is to search some relationship among baseball players' height, weight and their batting average,full baseball scores.

## Abstract
   This project makes a visualization about baseball dataset which includes four types of information about baseball players,including height, weight, batting average and full baseball score. Starting the visualization, you first can see different batting average range in ascending order and then you can click the range to see the distribution of different baseball player' batting averages and full baseball score.According to the visualization, baseball players' height has positive proportional relationship with their weight in the distribution of their batting average and full baseball scores in defferent lever of batting average.

## Design
* first-design

     At the first time, I want to show the relationship among batting avgerage,full baseball scores and players' height and weight so I draw a coordinate system that the x-axis shows the scale of players' weight and y-axis stands for the scale of players' height. And then, I draw red circles to show each players' batting avgerage and the size of the circles stands for the value of batting avgerage. The blue rectangles shows players' full baseball scores and the size of rectangles stands for the value of full baseball score. What's more, I use opacity to see where have more players in the SVG. Besides, I use legends to note the meanging of circles and rectangles in the top left corner of SVG so that readers can notice the legends but legends do not become the mainly attraction place in SVG.
      
     According to the first-design visualization, It seems those baseball players' height has positive proportion relationship with their weight in the distribution of players' batting average and full baseball scores which shows that the baseball players in dataset have similar proportion of height to weight. Besides, there are more players distibutes around the middle of coordinate system which illustrates many player is in the height from 68 inch to 76 inch and weight from 150 pound to 220 pound. Also, in this region, the circles and rectangles are bigger than the others which means that in this dataset, the players with the height and weight in the region get better batting avgerages and full baseball scores.

* second-design

     At this time, I make some change in my visualization. Firstly, the most important change I make is to append animations in the first sign of visualization. When readers open the visualization, they can see some circles and rectangles exchange in the coordinate system and the circles are shown in ascending order according to the players'batting average. Also, in the bottom right of SVG, there are context to tell reader the range of batting avgerages. Finishing showing all points, it will show some buttom in the bottom right of SVG. Those buttons include different handedness players point and different level range of batting avgerages. When clicking one button of different level in batting avgerage, the button will highlight in the color of red, and circles and rectangles will be updated in the specific range of batting avgerage. Secondly, I append three buttons to show different handedness of players distribution. For example, when readers click in "Left Hand" button, this button will be highlight in red color and the data of left handedness players will be showed in the SVG so that readers can see different handedness players' situation and compare them together. Thirdly, I add notes to tell readers where the data from and the notes are shown in the bottom of HTML body which makes this visualization more truthful and credible.
     
     I append the animation of different level of batting averages so that readers can compare different level of batting averages. As observing the visualization, in high level of batting averages, many player'full baseball scores are bigger and the distirbution of players are more compact around the coordinate system. Besides, I append buttons according to different handedness. When observing different type of players who use different to play baseball, I get information that most of players in this dataset get used to using right hand and many players use left hand to play baseball and a small amount of players are used to both of two hand to play baseball. Further more, the "Left Hand" special sence has the least small circle than other two sences,"Right Hand" and "Both Hand", which means players who use left hand have high rate of getting large batting averages.

## Feedback
* first-design feedback

     I have an interview with several persons face to face and ask what they have noticed in the visualization and what information and problems they can get from the visualization. Besides, I share project link to my ten friends in WeChat and four of them give me some useful feedback.
     
     And then, I put their description and suggestion in order and sum up in three points that I can adopt. Firstly, although the opacity of color can show how many players in SVG, there are some regions that have so many players that we can not see the size of circles and rectangles clearly and we do not know their specific batting average and full baseball score. To improve this point, one person advise the visualization can show the circles and rectangles according to some level of batting averages. That's to mean that I can use animation to show one level of batting avgerages and full baseball scores one time and show another animation in next time. Secondly, there is not any animations that the readers can interact with the visualization and the readers can not get information they want to know. Also, with animations, the visualization can more attractive and vivid. Thirdly, there is not any notes to tell the readers what the size of circles and rectangles stand for which makes readers doubtful. To impove this point, I append some context to tell readers the values level of size of circles.

* second-design feedback

     This time, I have an interview with several persons who gave me feedback at first time face to face and ask their opinions about visualization. Besides, I ask three persons who see this visualization at first time for their views about this visualization. 
     
     Finishing the interviews, I sum up their opinions in two points. Fristly, the visualization are more attractive and vivid with some animations and readers can get some information from the visualization. For example, four persons know that in this dataset, baseball players'height have positive proportion relationship with players'weight in the distribution of players' batting average and full baseball scores. Also, five of interviewees say that they know most of players are distribution around the coordinate system and most of players'height is in the range of 68 inch to 76 inch and most of their weight is in the range of 150 pound to 210 pound. Besides, four of interviewees know the in the batting average range of [0.2424, 0.2783] and the range of [0.2784, 0.3500], baseball players'batting average are bigger and the full baseball scores are bigger,too. What's more, there are most players using right hand and least players using both of two hand. Also, in this three type of players, people using left hand have high rate of big batting average.In one word, the readers can get informations that I want to tell them from visualization. Secondly, lost of initereviewees notice that the contexts in the SVG make the visualization more clearly and those contexts include legends and the range of average values and data source.

## Reference
website
* https://www.w3.org/TR/SVG/text.html
* https://d3js.org/
* https://github.com/d3/d3-drag/blob/master/README.md#
* https://classroom.udacity.com/nanodegrees/nd002-cn-advanced/parts/7f46cd58-8041-4d9d-88a5-4b7c6f7be63e/modules/0a2b9337-2d60-4caf-8660-c9ffcff7dd3f/lessons/3184238632239847/concepts/31814787270923
* https://d3js.org/d3.v3.min.js

forum: 
* http://discussions.youdaxue.com/search?q=D3
