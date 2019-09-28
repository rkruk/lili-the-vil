<p align="center">
  <img src="https://raw.githubusercontent.com/rkruk/lili-the-vil/master/img/header.png">
</p>
<br><br>
<p align="center"><b> LILI THE VIL </b></p>
<p>Lili The Vil is a mini Voice Recognition project I'm working on when I have a spare time (which means RARELY).<br>
It is mostly based on Google Voice Recognition Addon to Raspberry Pi https://aiyprojects.withgoogle.com/voice/.</p>
<br>
<br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/000.jpg">
</p>
<br>
<br>
<p><b>At this moment this project is stale</b> as I'm trying to figure it out how to randomise and anonymise requests which are send to and from google servers and this little device.</p><br>
<br>
<p>At first the 'Personal Assistant on my desk' seamed like a nice idea... BUT... when I started to think about it sending all voice commands outside. Or even letting to manage my microphone by Google/Amazon/etc... Uh well.. It started to creeps me out. If you think about it from security standpoint, you began to wonder what kind of creep wants to collect that sort of data, and what they are planning to use it for.<br> 
That is why this little project exist on the paper so far. As there is no viable SECURE open source options with good voice recognition patterns, databases, security models, local data retention, etc..<br><br>
There a few things here to work with:<br>
- If to go with awailable software (the commercial one): I would like to work around the problem with key binding of the single Google/Amazon account to randomize output send to external servers. Is it even possible? Will it get banned? Is it against licences?<br>
- Research and review Open Source available projects.<br> 
  -- Review their security model and data retention;<br>
  -- Where the data is stored (locally preferable);<br>
  -- On exactly what Voice Patern Recognition software and data are based those projects?<br>
- To work on a 'Press Button to Voice Command' only solution. I don't like the idea of microphone turn on 24h/7days a week, no matter if it's sending data out or not.<br>
<br><br>
  
<p align="center"><b>UPDATES:</b></p><br>
<b>UPDATE 1.</b> AYI board has been assembled with Raspberry board.<br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/14.png">
</p>
<br>
<br>
<b>UPDATE 2.</b> After last Halloween I had some leftovers (not food though). And it ooccurred me that I can use it as a chasis for this project.<br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/1.png">
</p>
<br>
Yeah, voice recognition inside a halloween skull - neat. Isn't it?<br>
<br>
<b>UPDATE 3.</b>
With Google AIY board I bought, there were also parts like: little speaker, button, mic, kables... which simplified things a little. I don't want to put much money into this Halloween project - that is why I decided to restrict myself to use only spare parts I had already at my disposal. There will be a lot of glue and cardboards in use... CHEAP is a keyword here.<br><br>
With that in mind I started to think how to fit together AYI board elements into the skull.<br> 
The button should fit nicely into eye socket:<br><br>   
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/3.png">
</p>
<br>
<br>
The only one place I could fit the speaker was on top of the skull. None of other sides of skull had enough of room inside to fit it.
<br>
<br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/5.png">
</p>
<br>
<br>
With a little help of dremmel tool I opened the skull and started to cut holes needed for speaker, activation button and mic.
<br><br>
The activation button from inside:
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/4.png">
</p>
<br><br>
<b>UPDATE 4.</b>
The speaker mesh on the top of the skull:
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/7.png">
</p>
<br><br>
<b>UPDATE 5.</b>
With a mic placement I was forced to look for a compromise. Initially I wanted it to be at the bootom but there was not place for it. Actually the voice bonnet board have built in a stereo mic, hence the size is surprisingly long. It make sense in only one place - forehead of the skull. At first I wasn't convinced to that but afyer drilling holes, and putting it into place it looks rather neat.<br>
<br>
Here is a look of mic holes with the activation button installed in the eye socket<br>
<br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/9.png">
</p>
<br><br>
The look of voice bonnet fixed inside with the help of a cardboards and glue. Yep... it doesn't look good... but let me remind you of "CHEAP is a keyword" rule. ;-)
<br><br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/8.png">
</p>
<br><br>
With the mic already inside, the speaker was next to put in:
<br><br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/6.png">
</p>
<br><br>
The excesive amount of glue used here had an explanation: unfortunatelly the skull inside is rather peculiarly shaped and not easy to work with.
<br><br>
<b>UPDATE 6.</b>
Would you look at that! :D<br>
Raspberry Pi have some indication lights on LAN output and on the board. I wanted to see them outside of the skull somehow and strugled for a bit how to do that. And then BAM! I had some spare fibre optic cable and it looks promising:<br><br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/16.gif">
</p>
<br><br>
How?<br> With a glue of course :) (do you remember THE CHEAP Rule? :) ).
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/13.png">
</p>
<br><br>
<b>UPDATE 7.</b>
This is how it finally looks from the inside. Everything installed and in place. There were some minor issues with fibre optic cables as the glue didn't work very well with them and I had to use not corrosive one.. hopefully it will work as I want it.
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/10.png">
</p>
<br><br>
<b>UPDATE 8.</b>
Skull is almost ready but it looks dull somehow. With cyber-punk aesthetic in mind I put few bits here and there. I'm not 100% convinced about the final look yet.<br><br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/11.png">
</p>
<br><br>
And The final look:<br><br>
<p align="center">
  <img width="50%" height="50%" src="https://github.com/rkruk/lili-the-vil/blob/master/img/12.png">
</p>
<br><br>






