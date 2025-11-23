# Geometry Aware Imaging 12 Week Study

Public record of a 12 week independent research project focused on computational imaging for architectural visualisation.

Building a Geometry Aware Image Pipeline for Architectural Visualisation
I am starting a 12-week research series to learn how machine systems analyse and generate images. I am not aiming for a perfect result. I want to document the process openly so the ArchViz community can see the technical side of how images are understood and transformed.
Architectural visualisation has two sides. One side is artistic. It deals with mood, lighting, composition and atmosphere. The other side is technical. It involves software, rendering, image processing and, now, AI tools.  My use of AI is getting more often, and part of my role is to help develop workflows that combine traditional craft with these new computational methods. 
This study is separate from my company work. It is independent. I am not trying to create beautiful images. I want to understand how images work at a mechanical level. Pixels, gradients, depth cues and patterns all contain structure. I want to learn how neural networks read that structure and how those signals can be changed or controlled. Every AI model depends on geometry, statistics and learned patterns. Understanding these elements is essential as AI becomes a normal part of production.
The next twelve weeks follow a clear plan. Each week I will build one piece of a geometry-aware imaging pipeline using only 2D information. The goal is not to build a new render engine. The goal is to show how images behave when treated as numbers and structures, not just visual surfaces.
This work marks a step toward computational imaging within ArchViz. It is self-directed and done outside my job. It focuses on building technical understanding over artistic output.

Here is the road map

Week 1 . Images as numbers
 Turn a render into pure data. Look at pixel values and simple transforms to see how images behave as arrays.
Week 2 . Finding depth from one image
 Use a neural model to guess distance in the scene. Depth becomes the base signal for everything that follows.
Week 3 . Reading surface shape
 Create surface normals, gradients and edge maps from depth. Reveal how an image stores shape.
Week 4 . Where the light comes from
 Use surface shape to estimate the main lighting direction in the image.
Week 5 . Changing the light
 Use depth and normals to relight the image without running a render engine.
Week 6 . Reading materials
 Use simple rules to separate matte, glossy and bright surfaces.
Week 7 . Clean super resolution
 Increase resolution in a controlled way that keeps shapes consistent.
Week 8 . Smart stylisation
 Apply stylisation that follows object boundaries instead of blurring them.
Week 9 . Breaking the image into passes
 Estimate albedo, shadows, highlights and occlusion from a single image.
Week 10 . Rebuilding a basic render
 Combine all the passes to create a simple synthetic render using only two dimensional signals.
Week 11 . Testing the limits
 Check where the method works and where it breaks. Understand the weak points.
Week 12 . Full pipeline demo
 Run the entire workflow on one scene and publish the final results
