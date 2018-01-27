---
title: "4 Theoretical Ways to Change Dynamic Range - YouTube"
category: motion
image: /media/youtube_title.jpg
caption: "Thinking Inside the Box on YouTube."
tags:
  - video
  - youtube
  - dynamic-range
---

<div class="embed-responsive embed-responsive-16by9">
	<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/wRevuU-grf4" allowfullscreen></iframe>
</div>

_Dynamic Range Tips on YouTube._
{: .text-center .text-muted}

Hi, welcome to an episode of “Thinking Inside the Box” on Noah’s Ark. In the video, I’m going to show you 4 different ways to change the dynamic range of a signal, in other words alter the dynamics of an audio source.

The content of this episode was inspired by the amazing book by mastering engineer Bob Katz called “Mastering Audio: the Art and the Science” that I highly suggest to check out.

Katz sees dynamic alteration as one of four possibilities, and it made perfect sense to me. Either you decrease the loudest part of a performance, increase the quietest part, decrease the quietest part, or increase the loudest part. He calls these respectively Downward Compression, Upward Compression, Downward Expansion and Upward Expansion.

 * * *

# __1. Downward Compression (Standard Compression)__

Downward Compression is what is commonly referred to as regular standard compression and is the most common method used to reduce dynamic range. It simply brings the loudest parts of a signal down and can be performed by applying a compressor as an insert to a track.

Simple enough and doesn’t need further explanation as you’ve probably seen this in other videos many many times.

I just want to note that using the make-up gain feature of a compressor doesn’t make this upward compression by raising the quietest bits. It simply raises everything and as a consequence raises quietest peaks but does not change the microdynamics of the signal.

 * * *

# __2. Upward Compression (Parallel Compression)__

Many people like to refer this technique as Parallel Compression or New York Style Compression. Upward Compression simply reduces dynamic range by bringing the quietest parts of a signal up and can be performed by applying a compressor as a send to a duplicate track along with the dry signal.

You may have seen a lot of tutorials on parallel compression so I won’t dive into it but I would like to explain why it brings the quietest parts up in a theoretical context.

Consider a loud part that is being compressed and reduced. When added to the original dry signal, the sum will not have an apparent increase in level and will be virtually unaltered. Now consider a quiet part that is being unaltered by the compressor. When added to the original dry signal, the sum will have an apparent increase in level, thus bringing the quiet part up by the additive signal flow.

Therefore, `Upward Compression = Dry Signal + Downward Compression`

Also, I would like to note that using the mix knob of a compressor will not result in the same because the overall volume is compensated automatically and the result will not be additive as in the parallel method.

 * * *

# __3. Downward Expansion (Standard Expansion)__

Downward Expansion is what is commonly referred to as regular standard expansion and is the most common method used to increase dynamic range. It simply brings the quietest parts of a signal down and can be performed by applying an expander as an insert to a track.

A form of dynamic modification that is fairly common on many channel strips and can also be disguised as a gate. The only difference is that an expander is basically a gate with a 2:1 fixed ratio.

 * * *

# __4. Upward Expansion (Parallel Expansion)__

The most obscure form of dynamic modification by far. Upward Expansion simply increases dynamic range by bringing the loudest parts of a signal up and can be performed by applying an expander as a send to a duplicate track along with the dry signal.

There aren’t a lot of tutorials out there on it but how does parallel expansion bring loudest parts up? The process is similar to our previous parallel compression.

Consider a quiet part that is being expanded and reduced. When added to the original dry signal, the sum will not have an apparent increase in level and will be virtually unaltered. Now consider a loud part that is being unaltered by the expander. When added to the original dry signal, the sum will have an apparent increase in level, thus bringing the loudest part up by the additive signal flow.

Therefore, `Upward Expansion = Dry Signal + Downward Expansion`

 * * *

# __5. Theoretical Experiments__

So now that we know different ways to wire our signal flow to create different dynamic content, you may be thinking about other combinations and possibilities. So here are two other theoretical signal flows that could work to achieve the same result with a different flavor.

Consider a quiet part that is being expanded and reduced. When added to the polarity-flipped dry signal, the difference will not have an apparent decrease in level and will be virtually unaltered. Now consider a loud part that is being unaltered by the expander. When added to the polarity-flipped dry signal, the difference will have an apparent decrease in level, thus bringing the loud part down by the subtractive signal flow.

Thus, `Downward Compression = Dry Polarity-Flipped Signal + Downward Expansion`
Or, `Downward Compression = Dry Signal - Downward Expansion`

Consider a loud part that is being compressed and reduced. When added to the polarity-flipped dry signal, the difference will not have an apparent decrease in level and will be virtually unaltered. Now consider a quiet part that is being unaltered by the compressor. When added to the polarity-flipped dry signal, the difference will have an apparent decrease in level, thus bringing the quiet part down by the subtractive signal flow.

Thus, `Downward Expansion = Dry Polarity-Flipped Signal + Downward Compression`
Or, `Downward Expansion = Dry Signal - Downward Compression`

As a recap, here are the formulas for all four combinations of additive and subtractive signal flows.

```
Downward Compression = Dry Signal - Downward Expansion
Upward Compression = Dry Signal + Downward Compression
Downward Expansion = Dry Signal - Downward Compression
Upward Expansion = Dry Signal + Downward Expansion
```

So that’s it, I hope you learned how to look at compression and expansion in a different light and opened up the possibilities for experimentation.

To find out more about dynamic range alteration, you can watch the video above or on YouTube [here](https://youtu.be/wRevuU-grf4).
