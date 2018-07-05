# Introduction
This is no standard README.md. I'm writing it with a heavy heart as I do this. This is a mirror of Symon's website who passed away on 2 July 2018. The reason for this mirror is for permanency; let old friends know what kind of things he enjoyed and perhaps be a reference to the young ones(when they grow up) what kind of dude Symon was. My goal for creating this mirror is to remind us all what kind of cool dude Symon was, celebrate his life through words he wrote. For us in the "technical" fields, this should always encourage us to never be afraid to "get technical".

This document alos describes how the site was mirrored. At the end, I'll share some things about him.

Thanks, Symo, it's been chill. Let's get technical...

## Mirror
I used [HTTrack](www.httrack.com) to mirror the website. It allows you to download WWW sites from the internet to a local directory, building recursively all directories, getting HTML, images, and other files from the server to your computer[0]. This mirror was taken on 2018-07-05.

The goal of mirroring his website was to retain all the content that Symon blogged about as is before the domain expires.

This command was ran from the terminal:

```
httrack http://symonmk.com/ -O symonmk 
```

In github, I created an "organisation": symonmuthemba as a necessary hack to acquire the domain name symonmuthemba.github.io(This is more appropriate for going through his stuff). The pages are static.

## A bit about Symon
Well, Symon was a cool dude. We first met in Primary School eons ago. In our grown up years, We talked about alot of things. He was one of the few dudes I enjoyed to talk about the state of engineering and software; and building a career around it. For me, "let's get technical", was one of my favourites things about him- he could get "technical" and make you enjoy it. His love for technology led him to become a broadcast engineer. He would talk about wireless technology and some really cool things about radio technology. We were supposed to meet up and talk about some really cool recent developments around codecs(where it is now possible to barely sample speech audio at 720bps[1]). I wanted to convince him to give a talk about his work at the NAILUG[2]. Unfortunately, this could not happen.

Outside, technology, he was a fun dude to hang around with. The one time we went out, he did some really crazy things(like jump on some tank) which got him into trouble, and gave us some hearty laughs. I'm sure that stories about him from friends and family are endless. I hope that in this repo, friends and family, can remember, through his own words, what he loved doing.

# References:
[0] http://www.httrack.com/  
[1] https://auphonic.com/blog/2018/06/01/codec2-podcast-on-floppy-disk/  
[2] https://nairobilug.or.ke/  
