# graphics-resources

A few of my bookmarks related to game development and realtime graphics programming.

## Bulk Download

You can use [gh-readme-scrape](https://github.com/mattdesl/gh-readme-scrape) to bulk download some of the content here for offline reading. For example:

```sh
gh-readme-scrape mattdesl/graphics-resources resources/ -e pdf,pptx,ppt --rename
```

This will download all PDFs and power-point slides into a folder called `resources`.

## Topics

- [Physically Based Rendering](#physically-based-rendering)
- [Color Space](#color-space)
- [Light & Shadow](#light--shadow)
- [Environments](#environments)
- [Time](#time)
- [Post-Processing](#post-processing)
- [Ray Tracing & Distance Functions](#ray-tracing--distance-functions)
- [Text, Lines & Shapes](#text-lines--shapes)
- [Non-Photorealistic Rendering](#non-photorealistic-rendering)
- [Math](#math)
- [Misc Optimizations](#misc-optimizations)
- [Collections](#collections)
- [Bloggers](#bloggers)
- [Tools](#tools)

## Physically Based Rendering

- [Readings on Physically Based Rendering](https://interplayoflight.wordpress.com/2013/12/30/readings-on-physically-based-rendering/)
- [The State of Rendering (2013)](https://www.fxguide.com/featured/the-state-of-rendering/)
- [jMonkeyEngine's Physically Based Rendering (2014)](http://jmonkeyengine.org/299803/physically-based-rendering-part-one/)
- [CodingLabs: Physically Based Rendering I](http://www.codinglabs.net/article_physically_based_rendering.aspx)
- [CodingLabs: Physically Based Rendering II](http://www.codinglabs.net/article_physically_based_rendering_cook_torrance.aspx)
- SIGGRAPH Shading Courses: [2012](http://blog.selfshadow.com/publications/s2012-shading-course/), [2013](http://blog.selfshadow.com/publications/s2013-shading-course/) and [2014](http://blog.selfshadow.com/publications/s2014-shading-course/)
  - [Physically Based Shader Design in Arnold (2014)](http://blog.selfshadow.com/publications/s2014-shading-course/langlands/s2014_pbs_alshaders_notes.pdf)
  - [Moving Frostbite to Physically Based Rendering (2014)](http://www.frostbite.com/wp-content/uploads/2014/11/course_notes_moving_frostbite_to_pbr.pdf)
  - [Crafting a Next-Gen Material Pipeline for *The Order: 1886* (2013)](http://blog.selfshadow.com/publications/s2013-shading-course/rad/s2013_pbs_rad_notes.pdf)
  - [Real Shading in Unreal Engine 4 (2013)](http://blog.selfshadow.com/publications/s2013-shading-course/karis/s2013_pbs_epic_notes_v2.pdf)
  - [Physically Based Shading in Call of Duty: Black Ops (2013)](http://blog.selfshadow.com/publications/s2013-shading-course/lazarov/s2013_pbs_black_ops_2_notes.pdf)
- [Deferred Shading Tutorial (2005)](http://gamedevs.org/uploads/deferred-shading-tutorial.pdf)
- [Spherical Harmonic Lighting: The Gritty Details (2003)](http://www.research.scea.com/gdc2003/spherical-harmonic-lighting.pdf)
- [Spherical Harmonics for Beginners (2013)](https://dickyjim.wordpress.com/2013/09/04/spherical-harmonics-for-beginners/)
- [A Tiny Improvement of Oren-Nayar Reflectance Model (2012)](http://mimosa-pudica.net/improved-oren-nayar.html)
- [Plausible Environment Lighting in Two Lines of Code (2013)](http://casual-effects.blogspot.ca/2011/08/plausible-environment-lighting-in-two.html)
- [Microfacet Models for Refraction through Rough Surfaces (2007)](http://www.cs.cornell.edu/~srm/publications/egsr07-btdf.pdf)
- [Artist Friendly Metallic Fresnel (2014)](http://jcgt.org/published/0003/04/03/paper.pdf)
- [Realistic Rendering of Blue Ice (2009)](http://nccastaff.bournemouth.ac.uk/jmacey/MastersProjects/MSc09/Salas/Vanessa_Salas_Castillo.pdf)
- [Advanced WebGL - Irradiance Environment Map (2011)](http://codeflow.org/entries/2011/apr/18/advanced-webgl-part-3-irradiance-environment-map/)
- [Irradiance Volumes for Games (2012)](http://developer.amd.com/wordpress/media/2012/10/Tatarchuk_Irradiance_Volumes.pdf)
- [Wolfire Blog - Physically Based Rendering (2015)](http://blog.wolfire.com/2015/10/Physically-based-rendering)

## Color Space

- [CodingLabs: Gamms vs Linear](http://www.codinglabs.net/article_gamma_vs_linear.aspx)
- [Filmic Games: Linear-Space Lighting (i.e. Gamma) (2010)](http://filmicgames.com/archives/299)
- [GPU Gems 3: The Importance of Being Linear (2008)](http://http.developer.nvidia.com/GPUGems3/gpugems3_ch24.html)

## Light & Shadow

- [Shading Effects in Left 4 Dead 2 (2010)](http://www.valvesoftware.com/publications/2010/GDC10_ShaderTechniquesL4D2.pdf)
- [The Illustrative World of Team Fortress 2 (2008)](http://www.valvesoftware.com/publications/2008/GDC2008_StylizationWithAPurpose_TF2.pdf)
- [Hardware-Accelerated Global Illumination by Image Space Photon Mapping (2009)](http://graphics.cs.williams.edu/papers/PhotonHPG09/)
- [Ambient Occlusion Fields (2005)](https://mediatech.aalto.fi/~janne/aofields/)
- [Phong Illumination Model (2012)](http://www.cs.utexas.edu/~bajaj/graphics2012/cs354/lectures/lect14.pdf)

## Environments

- [Rendering Grass in Real Time with Dynamic Lighting (2005)](http://kevinboulanger.net/grass.html)
- [Water Flow in Portal 2 (2010)](http://www.valvesoftware.com/publications/2010/siggraph2010_vlachos_waterflow.pdf)
- [Manipulating UVs through Color Data in Portal 2 (2011)](http://www.valvesoftware.com/publications/2011/gdc_2011_grimes_nonstandard_textures.pdf)
- [WebGL Sky Rendering (2011)](http://codeflow.org/entries/2011/apr/13/advanced-webgl-part-2-sky-rendering/)
- [WebGL Terrain and Grass Rendering (2011)](http://codeflow.org/entries/2011/apr/11/advanced-webgl-part-1/)
- [Zephyros Anemos - WebGL Terrain Rendering](http://www.zephyrosanemos.com/)

## Time

- [Fix your Timestep! (2006)](http://gafferongames.com/game-physics/fix-your-timestep/)
- [deWiTTERS Game Loop (2009)](http://www.koonsolo.com/news/dewitters-gameloop/)
- [Fixed Timestep Implementation (2012)](http://lspiroengine.com/?p=378)

## Post-Processing

- [Post Processing in the Orange Box (2008)](http://www.valvesoftware.com/publications/2008/GDC2008_PostProcessingInTheOrangeBox.pdf)
- [Aggregate G-Buffer Anti-Aliasing (2015)](http://graphics.cs.williams.edu/papers/AggregateI3D15/)
- [Physically Based Real-Time Lens Flare Rendering (2011)](http://resources.mpi-inf.mpg.de/lensflareRendering/)
- [John Chapman - Pseudo Lens Flare (2013)](http://john-chapman-graphics.blogspot.ca/2013/02/pseudo-lens-flare.html)
- [Image Imperfections & Film Grain Post-Process FX (2013)](http://devlog-martinsh.blogspot.ca/2013/05/image-imperfections-and-film-grain-post.html)
- [GLSL Cubic Lens Distortion (2011)](http://devlog-martinsh.blogspot.ca/2011/10/glsl-cubic-lens-distortion.html)
- [Using Lookup Tables to Accelerate Color Transforms (2005)](http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter24.html)
- [The Skylanders SWAP Force Depth-of-Field Shader (2013)](http://casual-effects.blogspot.ca/2013/09/the-skylanders-swap-force-depth-of.html)
- [GPU Gems 3: Motion Blur as a Post-Processing Effect (2008)](http://http.developer.nvidia.com/GPUGems3/gpugems3_ch27.html)
- [GPU Gems 3: Practical Post-Process Depth of Field (2008)](http://http.developer.nvidia.com/GPUGems3/gpugems3_ch28.html)

## Ray Tracing & Distance Functions

- [Fast Soft-Shadowing on Dynamic Height Fields (2008)](http://www.iro.umontreal.ca/~derek/files/hfvisib.pdf)
- [Per-Pixel Displacement Mapping with Distance Functions (2005)](http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter08.html)
- [Raymarching Distance Fields (2013)](http://9bitscience.blogspot.ca/2013/07/raymarching-distance-fields_14.html)
- [Screen Space Glossy Reflections (2015)](http://roar11.com/2015/07/screen-space-glossy-reflections/)

## Text, Lines & Shapes

- [Higher Quality 2D Text Rendering (2013)](http://jcgt.org/published/0002/01/04/paper.pdf)
- [Improved Alpha-Tested Magnification for Vector Textures (2007)](http://www.valvesoftware.com/publications/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf)
- [Drawing Lines is Hard (2015)](http://mattdesl.svbtle.com/drawing-lines-is-hard)
- [Material Design on the GPU (2015)](http://mattdesl.svbtle.com/material-design-on-the-gpu)
- [Polygon Rendering in Ejecta (2012)](http://phoboslab.org/log/2012/09/ejecta)
- [Lecture: Polygon Triangulation (2014)](https://www.youtube.com/watch?v=qzX8zGMyl4Y&list=PLESnaHRvLM-72xIXf8dL2EOqN8UgAZMj7&index=16)
- [GPU Gems 3: Rendering Vector Art on the GPU](http://http.developer.nvidia.com/GPUGems3/gpugems3_ch25.html)
- [Drawing Text with Signed Distance Fields in Mapbox GL (2014)](https://www.mapbox.com/blog/text-signed-distance-fields/)
- [Multi-Channel SDF Text Rendering (2014)](https://lambdacube3d.wordpress.com/2014/11/12/playing-around-with-font-rendering/)
- [SDF Rendering of Color Bit Planes (2013)](https://gpuhacks.wordpress.com/2013/07/08/signed-distance-field-rendering-of-color-bit-planes/)

## Non-Photorealistic Rendering

- [Watercolor Inspired Non-Photorealistic Rendering for Augmented Reality (2008)](http://www.cc.gatech.edu/~turk/my_papers/npr_ar_2008.pdf)
- [Advanced Real-Time Cel Shading in OpenGL (2013)](http://www.cs.rpi.edu/~cutler/classes/advancedgraphics/S12/final_projects/hutchins_kim.pdf)
- [Stroke-Based Rendering (2002)](http://web.cs.ucdavis.edu/~ma/SIGGRAPH02/course23/notes/S02c23_3.pdf)
- [Hand Drawn Rendering (2012)](http://www.cs.rpi.edu/~cutler/classes/advancedgraphics/S12/final_projects/mcmullan_ooi.pdf)
- [Real-Time Ink Dispersion in Absorbent Paper (2005)](http://visgraph.cse.ust.hk/MoXi/moxi.pdf)
- ["Nijimi" Rendering Algorithm for Creating Quality Black Ink Paintings (2003)](http://cgm.cs.ntust.edu.tw/steve/www/paper/Abstract/941129/CG2003/01214460.pdf)
- [WYSIWYG NPR: Drawing Strokes Directly on 3D Models (2002)](http://gfx.cs.princeton.edu/pubs/Kalnins_2002_WND/wnpr-final.pdf)
- [Stylized Rendering Using Samples of a Painted Image (2007)](http://graphics.csie.ncku.edu.tw/Paper_Video/TVCG/NPR_2007/TVCG_NPR_2007.pdf)

## Math

- [Essential Mathematics for Games and Interactive Applications (2008)](http://www.amazon.ca/Essential-Mathematics-Games-Interactive-Applications/dp/0123742978)
- [3D Math Primer for Graphics and Game Development, 2nd Ed (2011)](http://www.amazon.ca/Math-Primer-Graphics-Development-Edition/dp/1568817231)
- [math-as-code (2015)](https://github.com/Jam3/math-as-code)
- [CodingLabs: World, View, Projection Matrices](http://www.codinglabs.net/article_world_view_projection_matrix.aspx)
- [Interactive Introduction to Noise Functions (2013)](http://www.redblobgames.com/articles/noise/introduction.html)

## Misc Optimizations

- [Fast, Branchless Ray/Bounding Box Intersections (2011)](http://tavianator.com/fast-branchless-raybounding-box-intersections/)
- [Combined Approximation of Fresnel Visibility (2015)](http://www.filmicworlds.com/2015/03/17/combined-approximation-of-fresnelvisibility/)
- [Compact Normal Storage for Small G-Buffers (2009)](http://aras-p.info/texts/CompactNormalStorage.html)
- [Normal Mapping without Precomputed Tangents (2013)](http://www.thetenthplanet.de/archives/1180)

## Collections

- [SIGGRAPH Real-Time Rendering Publications](http://kesen.realtimerendering.com/)
- [List of Realtime Global Illumination Techniques](https://extremeistan.wordpress.com/2014/05/11/realtime-global-illumination-techniques-collection/)
- [David Arcila's Game Development Resources](https://game-development.zeef.com/david.arcila)
- [awesome-opengl](https://github.com/eug/awesome-opengl)
- [Readings on Physically Based Rendering](https://interplayoflight.wordpress.com/2013/12/30/readings-on-physically-based-rendering/)

## Bloggers

- [Aras Pranckevičius](http://aras-p.info/blog/)
- [Stephen Hill](http://blog.selfshadow.com/)
- [Sébastien Lagarde](https://seblagarde.wordpress.com/)
- [Angelo Pesce](http://c0de517e.blogspot.ca/)
- [Yi-Wen Lin](http://blog.bongiovi.tw/)
- [Brian Karis](http://graphicrants.blogspot.ca/)
- [Christian Schüler](http://www.thetenthplanet.de/)
- [Tom Forsyth](http://home.comcast.net/~tom_forsyth/blog.wiki.html)
- [Michael Chang](http://mflux.tumblr.com/)
- [Timothy Lottes](http://timothylottes.blogspot.ca/)
- [John Chapman](http://john-chapman-graphics.blogspot.ca/)
- [John Hable](http://www.filmicworlds.com/) (and his [older blog](http://filmicgames.com/))
- [Philp Rideout](http://prideout.net/blog/)
- [Mikola Lysenko](http://0fps.net/)
- [Adrian Courrèges](http://www.adriancourreges.com/blog/)
- [Martins Upitis](http://devlog-martinsh.blogspot.ca/)
- [Colin Barré-Brisebois](http://colinbarrebrisebois.com/)
- [Rory Driscoll](http://www.rorydriscoll.com/)
- [Real-Time Rendering Blog](http://www.realtimerendering.com/blog/)
- [Mikael H Christensen](http://blog.hvidtfeldts.net/)
- [Fabian Giesen](https://fgiesen.wordpress.com/)
- [Iñigo Quilez](http://www.iquilezles.org/blog/)
- [Ignacio Castaño](http://www.ludicon.com/castano/blog/)
- [Jeremy Shopf](http://www.jshopf.net/)

## Tools

- [Disney BRDF Viewer](http://www.disneyanimation.com/technology/brdf.html)
- [cmft](https://github.com/dariomanesku/cmft) and [cmftStudio](https://github.com/dariomanesku/cmftStudio) - cubemap filtering tools
- [Modified AMD Cubemapgen](https://seblagarde.wordpress.com/2012/06/10/amd-cubemapgen-for-physically-based-rendering/) - cubemap filtering tool
- [preview-dds](https://github.com/Jam3/preview-dds) - minimal cross-platform DDS previewer
- [CrazyBump](http://www.crazybump.com/)

## License

MIT, see [LICENSE.md](http://github.com/mattdesl/graphics-resources/blob/master/LICENSE.md) for details.
