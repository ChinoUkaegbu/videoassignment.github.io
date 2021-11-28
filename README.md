# Video Assignment - *Insert Name*

## Maaz Ahmed, Thais Alvarenga, Riley Ha, Chinonyerem Ukaegbu

### **Description**

It has been a really bad day for John Doe(dummy name). All manner of troubles have come their way from the moment they woke up and the day seems to be getting worse and worse as it progresses. From missed appointments to stomach aches to even running head first into a glass door, folllow John throughout the day and determine the sequence in which each of these events happened.

This video project leads the users to determining the sequence in which the unfortunate events take place. The users take on the role of a professor whose student came late for an important class and thr users get to decide which videos they want to see as many times as they'd like in order to determine what happened and when. Clues are scattered throughout the videos and users would have to pay attention to these clues to determine the order.

### **Implementation**

+ **Index/Loading Page**
  
  Will you help us find the missing cat?? Help or Ignore. In the loading page, we decided to let the reader decide if he or she wants to help us find the missing cat or not. We did this by making two buttons. Clicking the help button will lead to the first pannel of the comic, while clicking the ignore button will.. make us cry. The gif file was made through photoshop.
  

+ **Panel 1**
  
  The first panel sets an introduction to the whole comic. It introduces how a cat has gone missing and the whole journey is about finding it! Photoshop was used to crop the image of the wanted cat. After that, a black and white filter (done through grayscale) was used to deliver a serious mood.
  

+ **Panel 2**
  
  The second panel shows the cats and the cat mom being interviewed. This panel provides clues and hints as to where the missing cat might be which influences the decisions the reader makes in the next panel. The images were placed in a grid and the grid-template-areas properties was used to position the images. Then the speech bubbles were downloaded as PNGs with transparent backgrounds. And then, the opacity of the speech bubbles was set to 0 and would only be displayed when the reader hovers over the image.
  
  
+ **Panel 3 and 5**

  The third panel was the world map panel and the fifth panel was the airport page. For these parts, it was mostly about hovering over images and interact with them. What was  difficult was that you can not interact with the image if it’s embedded with the background image, and two solutions were found were that: first using svg to trace all the border needed, and interact through different layers’ id and this was applied to the world map panel. We found a traced world map on internet, and then called the ID of different layers in CSS to change the color of the continent chosen. And the second solution is to place different layers of images, then one can directly interact with the image. However, this solution has the issue of positioning the image precisely. So to solve this, the grid display was used to posiiton the image.
  

+ **Panel 4**
  
  Photoshop was used to edit the image and illustrator to trace the image and buttons to allow for interactivity. The class name was called from the svg file to start the ringtone when hovered on the top, make colors darken when buttons are hovered, and to trigger sound when clicked on the green button. Then logic was applied to distort the audio and make it sound spooky.
  

+ **Panel 6**
  
  Finally!! This panel shows you who the criminal was. Speech balloons were used to make it seem like there were actual dialogues. The location was set by giving specific location through percentages.
  

+ **Ending Page**
  
  The ending page wraps up the comic by granting you a huge amount of money! A cute image with the message "Congratulations You Won!" and an image of a happy cat is displayed! The adventure is over but if the reader would like to play again, they can either click the 'Go Back to Home' button on the navigation bar which will take them to the index page, or click the 'Missing Cat' button which will take them to the first panel.



### **Reflection**

We found this project to be very fun! It was rather interesting to work on the different parts of the website together and to make some certain changes, discuss how we could make it better, discuss implementations etc. Overall, I believe our expectations for the project were met. We just really wanted the readers to have fun exploring the story and to have a very wholesome experience in total. We also believed the implementation was way less stressful than the first website, now that we've played around with website making so it was a really interesting experience. We hope the readers have as much fun experiencing the comic as we did making it!


### **Interesting Notes**

For some reason, one of the fonts that was in .ttf wasn't loading until we converted it to .otf even though the other fonts were in .ttf! Also, Github takes some time to show the changes you've effected so you have to consider that as well.

