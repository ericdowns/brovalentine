---
# Page Title
title: Test Valentine Bro

# Hero Image - 1600px x 900px
# hero-image: /img/userstories/dear-angelica-hero.jpg

#Thumbnail Image - 800px x 450px
thumbnail-image: /img/userstories/dear-angelica-thumb.jpg

# Small description of post
excerpt: The Emmy-nominated Dear Angelica tells the story of Angelica and her daughter, with the vocal talent of Geena Davis and Mae Whitman.

# Position Order
order: 1

---

## The Emmy-nominated **Dear Angelica** tells the story of Angelica and her daughter, with the vocal talent of Geena Davis and Mae Whitman. 

It premiered at the [Sundance Film Festival](http://www.sundance.org/projects/dear-angelica) in 2017, was produced by the Oculus Story Studio entirely in Quill and Houdini, and played in the Unreal Engine in real-time VR. It can be watched for free today in the Oculus Store.

A narrative of grief, loss and love, Dear Angelica plays out in a series of painted memories &mdash; a visually stunning technique that increases our empathy for Angelica’s daughter as we’re fluidly pulled through her imagination to experience her adventures and poignant recollections. To execute such a magical piece, a team of technical artists, engineers and artists were put in place during a few months of production. Today Quill is more powerful, and the same can be achieved with fewer people, but much of the process and pipeline setup still applies.

Art Director Wesley Allsbrook painted every single scene in the film entirely by hand &mdash; each character, set and prop realized by a single artist. This is a significant moment for animation, whether based in VR or otherwise, as the field heavily relies on increasingly large teams of concept and production artists. Dear Angelica sheds light on an alternative, more accessible way to tell visual stories.

Visually speaking, the scenes construct themselves around the audience as individual strokes are rendered in real-time for an interactive viewing experience. That's where the team of technicians took over and choreographed the film in Houdini. Data from Quill flowed to Houdini in Alembic format as curves. Once in Houdini, procedural methods were used to time each element in the scene (the scripts the Story Studio used to do so are public and accessible in the Developers section of this website). From Houdini, data was exported as Alembic curves again to the Unreal Engine, where final distribution and playback happens. The best visual fidelity was achieved by setting the Unreal Engine in forward rendering mode and 8x antialiasing. Special shaders were written to implement curve to polygon conversion at render time for some extra performance.
