# Intro
Perhaps you've seen one of my animated voxel scenes ([my insta @timkimtimkim](https://www.instagram.com/timkimtimkim/)) 
and wondered _"How does one actually animate in MagicaVoxel?"_. This is an especially curious question given that 
the latest version of MagicaVoxel (v0.99.6.2) doesn't have any frame-by-frame or onion skinning ui. And since all of my
animations are stop motion (ie, I capture every frame in MagicaVoxel) how do I achieve this in a sane fashion?

The truth is that there is no short answer or *trick* to achieving animations in MV. Rather it all really comes down to
a lot of good "book keeping". And when I mean "book keeping", it's really about figuring out how to 
hide/show the right frame of your scene in an organised way. I'd say if you're thinking that you might need
about 30 frames of animation, then working this way is a decent way of achieving animations. Any more then 
you may as well start looking into blender or other options. The real downside to this method is that you have to sit 
for every frame to finish rendering to take a picture. So when your frames are rendering at about three-five or more minutes 
of a 30 frame animation...well, let's just say that the process is _slightly_ more fun than watching paint dry. 

But hey, if you're looking for a tight 8-30 frames of animation, then this method might work for you. I should mention that I do
use After Effects to stitch together my frames. There are other things available but I find After Effects the 
easiest way to manage my frames, the fps and other certain effects. 

# How does one animate in MagicaVoxel?
So the first difficulty is thinking about how to achieve "frames of animation". Hopefully you are an experienced user
of MagicaVoxel so it's not so outside your relm to be able to take *one* picture of your scene. But how to exactly sequence
a pictures of your scene to make an animation?

## First animations in MagicaVoxel using Turntable

The first real dip into animation with MagicaVoxel is actually using the `Render > Show Image Settings > Image > Turntable` 
mode. What this thing basically does is take your scene and just rotate the camera around it in a 360 fashion (or whatever
angle you put). Hopefully, if you placed the camera and your main object around the exact middle point to rotate around, 
and put in a decent number of frames you'll get a nice 360 camera rotation around it. 

After the tool finishes, it'll save a sequence of images for you to put into your favourite animation program. In this 
instance, we are essentially *animating* the camera's path around the object and creating the frames. This should give you 
an idea of how things *can be animated* in a voxel space. 

##  The first rule of MV Animation Club

Ok, now we're getting into the real meat here. And because of this I must mention the first rule of animating in 
MagicaVoxel. 

*ONCE YOU SAVE YOUR CAMERA'S POSITION, YOU DO NOT OVERWRITE YOUR CAMERA'S SAVED POSITION*

Let me repeat that again:

*ONCE YOU SAVE YOUR CAMERA'S POSITION, YOU DO NOT OVERWRITE YOUR CAMERA'S SAVED POSITION*

There is *nothing* worse when you are animating in MagicaVoxel to be halfway through your frames of animation
only to accidently push *7* (the hotkey to save the camera's current position) when it's not in the
correct animation position. Because what you have just done is moved the camera and so now
your precious frames up this point are all ruined because it is *extremely* unlikely you will
regain the camera's original position again unless you have written it down. This is especially
painful given that you *must* sit through every frame rendered so I cannot stress the point 
enough to not mess up you camera position once you are happy with it!

In fact, save the camera's position in multiple slots so incase you overwrite by accident,
then you can still recover it!

## 


Ok, so when it comes to animating objects in a scene, I would actually recommend using layers if


Pretty much the general workflow is to use the `Show Scene Outline` mode to organise your frames. 

When it comes to the traditional frame-by-frame feature in animation software, it's really just about showing/hiding 
things in a sequence. This is where the `Show Scene Outline` mode will help bridge the gap of this feature. 


It's kind of an awkward part of MV, I think for the average
user. When does one really need the granularity to name every object

I don't imagine many people have used the `Show Scene Outline` mode since the main feature it provides is some extra
organisation and the ability to name your objects in a scene


, really all it's about is hiding and showing the a particular object at the right time. 
Now, with this workaround what you lose is the sense of fps. 

The general workflow of when I'm thinking of animating a scene kinda goes:
- think of an idea/concept
- think about how long the animation in terms of how many frames it will be 
- the max number of frames I can do in a night's work is about 30 so I'll try to keep it under this number
- 6-15 is usually a good number of frames
- 

The first hard truth about this process is that I don't recommend it for anyone really trying to capture animations
more than 30ish frames of animation. 

The truth is that I forgo that sort of ui where you're able to cycle through your animations and go at it at a very
raw fashion. 

One of the first tings I do is think about all the frames that I need to make up a scene. 

It's a tough choice and
has definitely made animating a lot harder. It is incredibly difficult to conceive of an animation that takes up a 
certain amount of frames and have all the things that move 



I should mention that this article is really for the more experience and advanced users of MagicaVoxel.





For me, a lot of the actual work of animating is thinking about how a scene
unfolds and the actions involved and kinda making a guess about how much I n

# How to Animate in MagicaVoxel v.0.99.6.2 
