# Day7-31r-10000coders

multimedia tags
accordion
iframes

Multimedia tags
It is used embed the vidoe and audio to the html

First is video tag:
<video>
<source src="video link">
</video>

likewise audio tag
<audio>
<source src="audio link">
</audio>

But there are attributes to use to make the tags work!!
frist attribute is controls

<video controls>
<source src="video link">
</video>

This will display all the controls for the video(Playback controls, volume, pip, playback speed, full screen, download etc)

next attribute is loop: This will play the video again and again even after completely viewing once!!

next attribute is muted

<video controls muted>
<source src="video link">
</video>

This will directly make the video muted!! You should again unmute it to hear the audio from the source!!

next attribute is autoplay:
This will play the video once you open the website without actually clicking on play button!!

<video controls muted loop autoplay>
<source src="video link">
</video>

**Note: If you remove muted when you are using autoplay the autoplay feature won't work!! so if you want the video to autoplay don't forget to use muted attribute!!**

Next are width and height attributes: These are common just like in image tag!!
<video controls muted loop autoplay width="50%" height="100px">
<source src="video link">
</video>

Next one is fallback content: It is just like alt tag in image tag the text will be display if the video cannot be played. The text which is within the video tag will be shown <video>This will be displayed if the video doesn't work</video>


accordion(Details and summary tags):

details and summary tags are used to create interactive collapsible sections of content!!

First only summary tag is visible then when expanded by clicking on it, then all the content inside the tag is shown.
Example:
<details>
  <summary>Click to expand</summary>
  <p>Here's the expanded stuff that you wish to look after expanding the  summary tag!!</p>
</details>

Next concept is iframes:
Used to embed(link) the external content to the html page.
example:
<iframe src="link will be pasted here" frameborder="0" width="70%" height="500px"></iframe>

to make a dropdown kinda in same page, First we start with anchor tag in new page:
