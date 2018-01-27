---
title: "5 Digital Workflow Tips for the Modern DAW User - YouTube"
category: motion
image: /media/youtube_title.jpg
caption: "Thinking Inside the Box on YouTube."
tags:
  - video
  - youtube
  - digital
  - workflow
  - tips
---

<div class="embed-responsive embed-responsive-16by9">
	<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/ogGTRiToepw" allowfullscreen></iframe>
</div>

_Digital Workflow Tips on YouTube._
{: .text-center .text-muted}

Hi, welcome to an episode of "Thinking Inside the Box" on Noah's Ark. In the video, I'm going to share 5 tips on when not to think analog in the DAW and how we can take advantage of the technology we have at our finger tips.

 * * *

# __1. The Bob Katz Bounce Trick__

During a brief conversation over email with renowned mastering engineer Bob Katz, inventor of the K-metering system and author of Mastering Audio: The Art and the Science, he taught me an invaluable trick about bouncing wordlengths.

In the days of analog tape, clipping was less of an issue than in the digital world because tape saturation could sound musical and even desirable in certain cases. In the case of digital clipping not so much the case. There aren't many cases when digital clipping is desirable, in fact there are none.

So when mixing in the box, gain staging and headroom on the master bus is very important. Now with most of the DAW internal architectures running on floating points, we rarely need to worry about clipping on auxiliaries or sub mixes. But the final output can still clip in 16-bit or 24-bit and most mastering engineers won't master your tracks if they don't receive tracks with acceptable headroom to work with.

Now this is where 32-bit float bit depth comes into place. Since all the internal plugins perform calculations and summing in 32-bit or 64-bit floating point precision, we can still capture that information with minimal truncation on the master bus if bounced at a bit depth of 32-bit float.

On top of the fact that the mastering engineer can work with virtually all the information from your mixes in this bit depth, it also eradicates the need for headroom since floating point precision allows for virtually infinite headroom before clipping.

So two ways to do that in your DAW: if you like to bounce internally on a track in your DAW, make sure you switch the bit depth of your session to 32-bit float before bouncing the track otherwise you will lose the precision during this internal summing stage. Most DAW can playback files with different bit depths in a single session but not different sample rates. The second method would be to bounce all the tracks directly externally at 32-bit float.

Thanks to Bob Katz and the advance of floating point computations for this trick.

 * * *

# __2. Dither to 16-bit__

Most of you out there probably record at 24-bit to allow for plenty of dynamic range. But when it's time to send a mix to a client or prepare for CD, then we usually lower the bit depth to 16-bit. During that process some of the dynamic range is therefore lost and some low level noise can be introduced at the quietest parts of the song.

This is where dithering is useful and what it does is that it introduces random bits of information in order to cover up this noise that is introduced when reducing bit depth.

There is also something called noise-shaping that allows to EQ this dithering noise by cutting and boosting certain frequencies that human ears are more or less sensitive to and masks even further the dithering noise. Generally, we find three different types of noise shaping EQs and they are suitable for different types of music. Type 1 is recommended for solo instruments, type 2 is good for rock and pop music, and finally type 3 is suitable for orchestral performances.

So now you know how and when to use dithering.

 * * *

# __3. Limit with a Ceiling of -0.5dBFS__

Again, when sending a mix to a client you want to have your tracks at an appropriate level so that they can have a fair comparison of loudness to commercial tracks they reference to. So we usually limit our master bus with a maximiser plugin but how do you set the ceiling?

The problem with keeping the ceiling at 0dBFS is that even though theoretically they are no sample points in the digital waveform that can exceed this value, there are a number of problems that could arise later.

First of all, if ever there is a format conversion that follows, such as when uploading to SoundCloud or sending to iTunes, the processes that involve in creating an mp3 codec or a streamable version may end up boosting the track by a couple tenth of a dB in which case the song will be clipped.

Additionally, if your limiter does not detect inter-sample peaks you can potentially have clipping in the analog domain notably when your speakers are trying to reproduce the waveforms. What it means is that even though your limiter was set to a ceiling of 0dBFS for all the samples to be controlled at that level, you may have waveforms that go beyond when reconstructed as a smooth curve in the analog domain.

So in general, it is good practice to have a ceiling of -0.5dBFS in order to avoid these problems later on. Nowadays, with more and more loudness normalisation on digital stores, half a dB won't be noticeable but a clipped song may be.

 * * *

# __4. Mixing with Headphones__

I often find myself mixing in an environment where I do not have access to proper monitors or I don't have access to the gear I am used to monitoring through so I end up mixing with headphones. This is when the Reference 3 plugin by Sonarworks comes in handy and I have to say I have been using this for quite a while with great success.

Reference 3 allows you to apply a correction EQ curve on the output master bus that compensates the frequency response of your set of headphones and balances the frquency to a target frequency spectrum of your choice. For instance, I can load the Beyerdynamic DT770 80ohms impulse response of my headphones and choose a flat target response to flatten out the response. You can also load different target profiles of popular headphones and speakers for referencing such as Yamah NS10s and B&W to name a few.

So that has been a real game changer for me so far and an essential plugin in the arsenal.

 * * *

# __5. Record in 48kHz__

The human ear's theoretical range of perceived frequencies ranges from 20Hz to 20kHz at its best and most of you know that the Nyquist theorem states that we need a sample rate of at least double the highest frequency we want to sample in order to avoid aliasing problems.

So many people wonder why record higher than 44.1kHz since it can technically capture any frequencies up to 22.05kHz? Well the problem lies in the quality of the filters in our converters. An analog to digital converter has to apply a low pass filter before sampling the waveforms in order to remove aliasing and the steeper the filter the more difficult and expensive it gets to manufacture.

So when you think about 44.1kHz sampling rate, the frequency range for the filter slope to operate is only 2050Hz whereas a 48kHz smapling rate has a range of 4000Hz to operate. As the sampling rate gets higher than 48kHz the gain in higher frequency content is virtually inaudible.

Therefore, I recommend recording at 48kHz to safeguard against poor converters and additionally, the standard in video audio is at 48kHz so you won't need to upsample if ever the music is used along with video.

So there you go, 5 digital tips to take advantage of technology in modern music productions.

To find out more about digital workflow tips, you can watch the video above or on YouTube [here](https://youtu.be/ogGTRiToepw).
