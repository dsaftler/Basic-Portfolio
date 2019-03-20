POST-POST Submit Notes:
I was in a panic tonight because https://dsaftler.github.io/Basic-Portfolio didn't render on correctly on my laptop.
I had completed the project on my desktop since I have dual 1920x1080 monitors, a regular keyboard and trackball mouse.
Everything looked fine when I submitted it on Saturday, but on the laptop, the "center-panel" rose up over the top of the background div "bg-pattern".
I thought that the version in github wasn't the current one, as I had seen (and fixed) that problem before.
 
When I came home and saw both renderings side by side, I saw that the "center-panel" only rendered correctly on a full size monitor.
Then I saw that my desktop scaling is also set to 125%, so there was a huge difference between my laptop and the oversized desktop.
When I reset my desktop monitor to 100%, "center-panel" rendered too low.  
I found I had set the position to absolute in the CSS.  I removed that and it now renders OK on both monitors.  
Wow! It's been a challenge wrapping my head around CSS.
I will address these issues in the Responsive-Portfolio homework.




Post Submit Notes:
I noticed that I did not set the width of the content to 960px.  
My 'whole page' is set to 1200px, with the center panel at 900px.  
I also missed some attributes borders on the header and footer.
It looked OK to my eye, but I realize that following specs is important.

circles-light.png:  downloaded from www.toptal.com/designers/subtlepatterns/
