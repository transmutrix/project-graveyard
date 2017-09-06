# project-graveyard
In memoriam of all the unfinished things that taught me something valuable.

*This is a list/timeline of past  gamedev projects. For most of them, source code has been lost to time and poor archival practices, or is simply too awful to share.*

*This list, naturally, is not comprehensive.*


## table of contents

Year | Project                               | Langs     | Libs/Tools
-----|---------------------------------------|-----------|-----------
2011 | [pong clone](## pong clone)           | C++       | SDL1.2, OpenGL
2012 | [untitled game 1](## untitled game 1) | C++       | SDL1.2, OpenGL
2013 | [untitled game 2](## untitled game 2) | C++, Angelscript | SDL1.2, OpenGL
2013 | [delta](## delta)                     | Haxe      | Stencyl Engine
2014 | [various h-games](## various h-games) | AS3       | Citrus Engine, Dragonbones
2015 | [lan party](## lan party)             | Java      | LWJGL, Slick2D
2016 | [all-90](## all-90)                   | C, Lua    | SDL2, OpenGL
2016 | [cave game](## cave game)             | C, Lua    | SDL2, OpenGL
2016 | [moony](## moony)                     | C, Lua    | SDL2, OpenGL
2016 | [point & click](## point & click)     | C, Lua    | SDL2, OpenGL
2017 | [trivia game](## trivia game)         | C#        | Unity Engine



## pong clone
![screenshot](2011/pong-clone/screen.png)

I made this when I was 17 and had just started learning programming more seriously. Before this, I had fiddled with Actionscript 2 and Actionscript 3, Ruby, RMXP, Unity, etc. in middle and high school, but hadn't really grasped any programming concepts well. Amazingly, my ex-husband still had the email I excitedly sent him with the exe.

[download (Win32)](2011/pong-clone/pong-clone.zip)



## untitled game 1
I learned about texture atlasing, pixel-perfect rendering, batch rendering, asset pipelines, and tools development. This project included the first level editor I wrote. I used borrowed art as placeholders. Most of the effort on this project was spent during my lunch breaks at the deli I worked at. Unfortunately, I can't find even a *screenshot* of this project. Oh well.




## untitled game 2
![](untitled-2/imgui.png)
![](untitled-2/particles.png)
![](untitled-2/softrend0.png)
![](untitled-2/softrend1.png)

I learned about embeddable scripting languages, Angelscript in this case. I also tried out Box2D. This project included both my first attempt at writing a substantial IMGUI framework, and my first attempt at software rendering.




## delta
![](delta/screen0.png)

This was going to be a Zeldalike RPG about battling mental illness. I actually don't remember why I stopped working on it. I had put a lot of work into it, both in artwork and scripts. I had recreated the kind of "pseudo z-axis" used in games like *Link to the Past*.



## various h-games
*(obviously not providing screenshots)*

After seeing lots of indie creators making a decent living with porny art and games, I thought about pursuing that as a way to pay my bills. Flash wasn't quite dead yet, and I already had several years of experience with it, both with AS3 and animation.

I spent some time developing small tools and a tolerable asset pipeline for this, but, once I actually started working on an h-game "for serious", I realized that I didn't have a passion for it and couldn't make myself do it for twelve hours a day. However, every time I see someone making bank on Patreon for porn, I think "I can draw a tiddy" and wonder if I should have continued.



## lan party
![](lan-party/login.png)
![](lan-party/pigs.png)
![](lan-party/dynamlight0.png)
![](lan-party/editor2.png)
![](lan-party/editor4.png)
![](lan-party/particles0.png)
![](lan-party/particles2.png)

I set out to make a small persistent world game to play with my friends. The goal was to have a Dragon Quest 2-ish overworld, populated with generated points of interest, and allowing players to establish little homes and towns. I knew almost nothing about network programming, and so did things very poorly.

The map editor had an Inspector, similar in concept to Unity's, using Java's Reflection library. Selected objects' classes were parsed, and editable members had UI elements generated for them. This made things a lot easier as one could just hand anything that needed to be editable to the Inspector without writing additional UI code by hand.

You could edit maps, entities and lights, test play the current map, etc. The engine had particle systems, dynamic lighting, simple physics.



## all-90
![](all-90/boot.png)
![](all-90/carousel.png)
![](all-90/gui.png)

Early in 2016 I was junk shopping and found a cool TV from the 70's. It is monochromatic, has a faux wood case with a carrying handle, and is in excellent condition. I immediately envisioned a completely ridiculous and absolutely fun project: Portable TV with a built-in Raspberry Pi running a fantasy console for old-school games. all-90 was my attempt at the fantasy console part.

I still have that TV, and I still plan to make it into an arcade box of some kind. Instead of a fantasy console, I will likely just make a few little monochromatic games for it, and set up some emulators for classic consoles.



## cave game
![](cave/gamejam0.png)
![](cave/gamejam1.png)
![](cave/gamejam2.png)
![](cave/gamejam3.png)

At the end of Summer 2016, I was leaving a really disappointing and stressful internship, and had signed up for a nice pile of CS classes at college. I lived with three people, was the only breadwinner for a long while, and really, *really* needed a vacation. So, being a moron, I decided I would do a solo "game jam" and give myself a week to make a game.

I learned a lot about prioritization, iteration times, autotiling algorithms, and duct-taping things under pressure. I also learned that an amateur Lua programmer should not try to write her physics code in Lua (shudder). The project used all soft rendering, and it is likely the worst software renderer that I have written.



## moony
This was my first attempt at an ultra minimal game framework. Two files, a few thousand LOC. I still didn't have a good grasp of C/Lua integration or interface design, resulting in a fugly mess.

After finishing the framework, I tossed it. The project gave me a little more software rendering experience, and I learned to throw away piles of code without guilt. Like figure sketches.



## point & click
<blockquote class="twitter-video" data-lang="en"><p lang="en" dir="ltr">Transitions are fun. <a href="https://twitter.com/hashtag/indiedev?src=hash">#indiedev</a> <a href="https://twitter.com/hashtag/gamedev?src=hash">#gamedev</a> <a href="https://t.co/yAqNqi8SVs">pic.twitter.com/yAqNqi8SVs</a></p>&mdash; TrashGirl (@transmutrix) <a href="https://twitter.com/transmutrix/status/806644420690976769">December 7, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Many students at my college struggle with early computer science classes. As one of *only two* CS tutors at the school, I attributed part of the problem to bad textbooks, bad example problems, and not enough course curricula focused on *making* things. One instructor seemed to be making efforts to fix this by trying out a project-based curriculum.

I wanted to supplement this by offering a free workshop on basic game development, which would cover a lot of programming basics not covered in classes, for extra credit or something, which would take the homework project from class and build it into a "real" game. I was told to make the finished product up front, so I made the guts of a point-and-click engine with an example project, and returned. **It had been a bluff to get me to go away. No workshop.**



## trivia game
![](trivia/start.png)
![](trivia/overworld.png)
![](trivia/sphinx.png)
![](trivia/question.png)
![](trivia/anubis.png)
![](trivia/win.png)

This game was a class project, and, in terms of the class, was "finished" (it was *not* finished). I did all the art, and made the SFX in [bfxr](http://www.bfxr.net/). The music is by [DST](https://dstech.bandcamp.com/).

We started with one of Unity's sample projects, and in a snowed-in and fluey weekend, I wrote a level generator, made most of the artwork, and created a trivia question based "battle system". One teammate drafted a nice pile of history questions, and the other helped with programming and testing the game.

I think we had a cool idea, and if done properly, it could have been pretty nice. Still, for an assignment done in a rush, we were happy with what we managed to do. It was beyond the scope of most projects done for courses at our school.

[download (Android)](trivia/Android.apk)
