# Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/SaschaWillems/Vulkan/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

A curated list of awesome Vulkan libraries, debuggers and resources. Inspired by [awesome-opengl ![GitHub Repo Stars](https://img.shields.io/github/stars/eug/awesome-opengl) ![GitHub last commit](https://img.shields.io/github/last-commit/eug/awesome-opengl)](https://github.com/eug/awesome-opengl) and other awesome-... stuff.

* **[Hardware Support](#hardware-support)**
* **[SDK](#sdk)**
* **[IHV Document](#document)**
* **[Tutorial](#tutorial)**
* **[Apps](#apps)**
* **[Samples](#samples)**
* **[Libraries](#libraries)**
* **[Bindings](#bindings)**
* **[Tools](#tools)**
* **[Books](#books)**
* **[Papers](#papers)**
* **[Khronos](#khronos)**
* **[Community](#community)**

## Hardware Support
*  [gpuinfo](http://vulkan.gpuinfo.org/) - Vulkan Hardware Database by Sascha Willems
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
    *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
    *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
    *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://www.amd.com/en-gb/innovations/software-technologies/technologies-gaming/vulkan)
    *  [Open-source Driver ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-Drivers/AMDVLK) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-Drivers/AMDVLK)](https://github.com/GPUOpen-Drivers/AMDVLK)
*  [Imagination](https://www.imgtec.com/developers/powervr-sdk-tools/)
*  Intel
    *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
    *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
*  Arm
    *  [Mali GPU Best Practices](https://developer.arm.com/solutions/graphics/developer-guides/mali-gpu-best-practices)

## SDK
*  [For Windows & Linux](https://vulkan.lunarg.com/signin)
*  [For Android](https://developer.android.com/ndk/guides/graphics/index.html)

## Document
*  [AMD](http://gpuopen.com/tag/vulkan/)
    *  [Vulkan barriers explained](http://gpuopen.com/vulkan-barriers-explained/)
    *  [Vulkan Fast Paths](https://gpuopen.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
    *  [Let Your Game Shine – Optimizing DirectX 12 and Vulkan Performance with AMD CodeXL	](https://gpuopen.com/wp-content/uploads/2016/03/Let_your_game_shine_optimizing_DirectX-12_and_Vulkan-performance_with_AMD_CodeXL.pdf)
    *  [D3D12 & Vulkan: Lessons Learned	 ](https://gpuopen.com/wp-content/uploads/2016/03/d3d12_vulkan_lessons_learned.pdf)
    *  [Say Hello to a New Rendering API in Town!](http://gpuopen.com/say-hello/)
    *  [Vulkan Renderpasses](http://gpuopen.com/vulkan-renderpasses/)
    *  [Performance tweets series: Barriers, fences, synchronization](http://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/)
    *  [Using the Vulkan™ Validation Layers](http://gpuopen.com/using-the-vulkan-validation-layers/)
    *  [Most common mistakes in Vulkan apps](https://gpuopen.com/wp-content/uploads/2016/05/Most-common-mistakes-in-Vulkan-apps.pdf)
	*  [Vulkan Device Memory](http://gpuopen.com/vulkan-device-memory/)
*  [NVIDIA](https://developer.nvidia.com/taxonomy/term/586)
    * [Vulkan Device-Generated Commands](https://developer.nvidia.com/device-generated-commands-vulkan)
    * [Getting Vulkan Ready For VR](https://developer.nvidia.com/getting-vulkan-ready-vr)
    * [GPU-Driven Rendering](http://on-demand.gputechconf.com/gtc/2016/presentation/s6138-christoph-kubisch-pierre-boudier-gpu-driven-rendering.pdf)
    * [GDC 16 - High-performance, Low-Overhead Rendering with OpenGL and Vulkan](http://developer.download.nvidia.com/gameworks/events/GDC2016/mschott_lbishop_gl_vulkan.pdf)
    * [GDC 16 - Vulkan and NVIDIA – The Essentials](http://developer.download.nvidia.com/gameworks/events/GDC2016/Vulkan_Essentials_GDC16_tlorach.pdf)
    * [Engaging the Voyage to Vulkan](https://developer.nvidia.com/engaging-voyage-vulkan)
    * [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
    * [Vulkan Memory Management](https://developer.nvidia.com/vulkan-memory-management)
    * [OpenGL like Vulkan](https://developer.nvidia.com/opengl-vulkan)
    * [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan)
    * [Siggraph 15 talk - Vulkan on NVIDIA GPUs](http://on-demand.gputechconf.com/siggraph/2015/presentation/SIG1501-Piers-Daniell.pdf)
*  [Arm](https://developer.arm.com/solutions/graphics/apis/vulkan)
    * [Vulkan Best Practice for Mobile Developers Tutorials ![GitHub Repo Stars](https://img.shields.io/github/stars/ARM-software/vulkan_best_practice_for_mobile_developers) ![GitHub last commit](https://img.shields.io/github/last-commit/ARM-software/vulkan_best_practice_for_mobile_developers)](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
    * [Vulkan's Key Features on Arm Architecture](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
    * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
    * [Get Your Engine Ready for Vulkan on Mobile](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
    * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
    * [Mali Vulkan SDK Tutorials](https://developer.arm.com/products/software/mali-sdks/vulkan) and [Slides](https://developer.arm.com/graphics/vulkan/vulkan-tutorials)
* Intel
    * [API without Secrets: Introduction to Vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/GameTechDev/IntroductionToVulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GameTechDev/IntroductionToVulkan)](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/GameTechDev/IntroductionToVulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GameTechDev/IntroductionToVulkan)](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
        * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
        * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
        * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
        * [Part 4: Vertex Attributes](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
    * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
    * [Migrating to Vulkan with the New PowerVR Graphics Framework](https://www.imgtec.com/webinar/migrating-to-vulkan-with-the-powervr-framework/)
    * [Migrating from OpenGLES to Vulkan](https://www.imgtec.com/downloads/download-info/migrating-from-opengl-es-to-vulkan/)
* Samsung
    * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/2_2D00_mmg_2D00_siggraph2016_2D00_best_2D00_practice_2D00_andrew.pdf)
    * [Vulkan Usage Recommencation](https://developer.samsung.com/game/usage) (for mobile)
* Epic
    * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/6_2D00_mmg_2D00_siggraph2016_2D00_vulkan_2D00_smedis.pdf)
* Khronos
   * [Vulkan Guide ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-Guide) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-Guide)](https://github.com/KhronosGroup/Vulkan-Guide)
* [LunarG](https://lunarg.com)
    * [Vulkan SDK](https://vulkan.lunarg.com/)
    * [Vulkan SDK Version Compatibility](https://www.lunarg.com/news-insights/white-papers/vulkan-sdk-version-compatibility/)
    * [Introducing the New Vulkan Configurator](https://www.lunarg.com/news-insights/white-papers/vulkan-validation-layers/)
    * [Unified Validation Layer for Vulkan](https://www.lunarg.com/news-insights/white-papers/unified-validation-layer-for-vulkan/)
    * [Vulkan Synchronization Validation Quick Start Guide](https://www.lunarg.com/news-insights/white-papers/vulkan-synchronization-validation-quick-start-guide/)
    * [Guide to Vulkan Synchronization Validation](https://www.lunarg.com/news-insights/white-papers/guide-to-vulkan-synchronization-validation/)
    * [Vulkan GPU-Assisted Validation](https://www.lunarg.com/news-insights/white-papers/vulkan-gpu-assisted-validation/)
    * [Automatic RelaxedPrecision Decoration and Conversion in Spirv-Opt](https://www.lunarg.com/news-insights/white-papers/automatic-relaxedprecision-decoration-and-conversion-in-spirv-opt/)
    * [SPIR-V Legalization and Size Reduction with spirv-opt](https://www.lunarg.com/news-insights/white-papers/spir-v-legalization-and-size-reduction-with-spirv-opt/)
    * [All White Papers](https://www.lunarg.com/vulkan-white-papers/)
* Community
    * [VulkanHub](https://vkdoc.net) 

## Tutorial
*  [How to Learn Vulkan](https://www.jeremyong.com/c++/vulkan/graphics/rendering/2018/03/26/how-to-learn-vulkan.html) - Meta post on how to learn Vulkan
*  [I Am Graphics And So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) - Blog post style tutorial for those new to graphics learning Vulkan.
*  [Vulkan Game Engine Tutorial](https://www.youtube.com/watch?v=Y9U9IE0gVHA) - Tutorial series on making a vulkan game engine by Brendan Galea on YouTube.
*  [Kohi Game Engine Series](https://www.youtube.com/watch?v=dHPuU-DJoBM&list=PLv8Ddw9K0JPg1BEO-RS-0MYs423cvLVtj) - "Vulkan Game Engine series, where we make a game engine from the ground up using C and Vulkan".
*  [Moving to Vulkan (Khronos UK May16)](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
*  [jhenriques's tutorial](http://jhenriques.net/development.html)
*  [Lunarg's tutorial](https://vulkan.lunarg.com/doc/sdk/1.0.26.0/windows/tutorial.html)
*  [Mike Bailey's Vulkan Page](http://web.engr.oregonstate.edu/~mjb/vulkan/) - Provides extensive Vulkan course slides. [CC BY-NC-ND 4.0]
*  [Qualcomm Video Tutorial Series](https://developer.qualcomm.com/software/adreno-gpu-sdk/tutorial-videos) - Leans more towards Vulkan for mobile devices.
*  [Raw Vulkan](https://alain.xyz/blog/raw-vulkan) - Overview on how to program a Vulkan application from the ground up.
* Siggraph
    * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - covers Vulkan, D3D12 etc.
*  [Tutorial by Overv](https://vulkan-tutorial.com/) and [its github repository ![GitHub Repo Stars](https://img.shields.io/github/stars/Overv/VulkanTutorial) ![GitHub last commit](https://img.shields.io/github/last-commit/Overv/VulkanTutorial)](https://github.com/Overv/VulkanTutorial). [CC BY-SA 4.0]
*  [vulkan-sxs ![GitHub Repo Stars](https://img.shields.io/github/stars/philiptaylor/vulkan-sxs) ![GitHub last commit](https://img.shields.io/github/last-commit/philiptaylor/vulkan-sxs)](https://github.com/philiptaylor/vulkan-sxs) - explain the Vulkan API step by step and [vulkan-sync ![GitHub Repo Stars](https://img.shields.io/github/stars/philiptaylor/vulkan-sync) ![GitHub last commit](https://img.shields.io/github/last-commit/philiptaylor/vulkan-sync)](https://github.com/philiptaylor/vulkan-sync) - rephrase Vulkan's requirements on execution dependencies in a more precise form. [MIT]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - by baldurk.
*  [Vulkan Demos and Tutorials ![GitHub Repo Stars](https://img.shields.io/github/stars/Z80Fan/VulkanDemos) ![GitHub last commit](https://img.shields.io/github/last-commit/Z80Fan/VulkanDemos)](https://github.com/Z80Fan/VulkanDemos). [MIT]
*  [Vulkan Guide](https://vkguide.dev). [MIT]
*  [Vulkan Lecture Series](https://www.youtube.com/playlist?list=PLmIqTlJ6KsE1Jx5HV4sd2jOe3V1KMHHgn) - University lectures by Johannes Unterguggenberger from the Research Unit of Computer Graphics, TU Wien. Covers basic and advanced topics like: Vulkan essentials, the swap chain, resources and descriptors, commands and command buffers, pipelines and stages, real-time ray tracing, and synchronization.

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - by Croteam.
*  [Dota2 ![GitHub Repo Stars](https://img.shields.io/github/stars/ValveSoftware/Dota-2-Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/ValveSoftware/Dota-2-Vulkan)](https://github.com/ValveSoftware/Dota-2-Vulkan/) - by Valve.
*  [Basemark](https://www.basemark.com/blog/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - by Basemark.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - by Kishonti.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - by Epic, built with Unreal Engine 4 technology.
*  [DDraceNetwork ![GitHub Repo Stars](https://img.shields.io/github/stars/ddnet/ddnet) ![GitHub last commit](https://img.shields.io/github/last-commit/ddnet/ddnet)](https://github.com/ddnet/ddnet/) - Cooperative 2D platformer with optional [Vulkan backend ![GitHub Repo Stars](https://img.shields.io/github/stars/ddnet/ddnet) ![GitHub last commit](https://img.shields.io/github/last-commit/ddnet/ddnet)](https://github.com/ddnet/ddnet/blob/master/src/engine/client/backend/vulkan/backend_vulkan.cpp). - [zlib ![GitHub Repo Stars](https://img.shields.io/github/stars/ddnet/ddnet) ![GitHub last commit](https://img.shields.io/github/last-commit/ddnet/ddnet)](https://github.com/ddnet/ddnet/blob/master/license.txt) [website](https://ddnet.tw/)
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)) - by id Software.
*  [vkQuake ![GitHub Repo Stars](https://img.shields.io/github/stars/Novum/vkQuake) ![GitHub last commit](https://img.shields.io/github/last-commit/Novum/vkQuake)](https://github.com/Novum/vkQuake) - Vulkan Quake port based on QuakeSpasm. [GPL]
*  [vkQuake2 ![GitHub Repo Stars](https://img.shields.io/github/stars/kondrak/vkQuake2) ![GitHub last commit](https://img.shields.io/github/last-commit/kondrak/vkQuake2)](https://github.com/kondrak/vkQuake2) - id Software's Quake 2 v3.21 with Vulkan support (Windows and Linux). [GPL]
*  [q2vkpt ![GitHub Repo Stars](https://img.shields.io/github/stars/cschied/q2vkpt) ![GitHub last commit](https://img.shields.io/github/last-commit/cschied/q2vkpt)](https://github.com/cschied/q2vkpt/) - Real-time path tracer VKPT integrated into q2pro Quake 2 client. [gpl]
*  [Linux port of SteamVR ![GitHub Repo Stars](https://img.shields.io/github/stars/ValveSoftware/SteamVR-for-Linux) ![GitHub last commit](https://img.shields.io/github/last-commit/ValveSoftware/SteamVR-for-Linux)](https://github.com/ValveSoftware/SteamVR-for-Linux) - SteamVR is built on top of the Vulkan API.
*  [3DMark](https://www.futuremark.com/pressreleases/compare-vulkan-and-directx-12-performance-with-3dmark) - 3DMark API Overhead test.
*  [Q2RTX ![GitHub Repo Stars](https://img.shields.io/github/stars/NVIDIA/Q2RTX) ![GitHub last commit](https://img.shields.io/github/last-commit/NVIDIA/Q2RTX)](https://github.com/NVIDIA/Q2RTX) - NVIDIA’s implementation of RTX ray-tracing in Quake II. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/NVIDIA/Q2RTX) ![GitHub last commit](https://img.shields.io/github/last-commit/NVIDIA/Q2RTX)](https://github.com/NVIDIA/Q2RTX/blob/master/license.txt)]

## Samples
*  Khronos [Vulkan samples ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-Samples) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-Samples)](https://github.com/KhronosGroup/Vulkan-Samples) [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-Samples) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-Samples)](https://github.com/KhronosGroup/Vulkan-Samples/blob/master/LICENSE)]
*  Sascha Willems's [samples ![GitHub Repo Stars](https://img.shields.io/github/stars/SaschaWillems/Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/SaschaWillems/Vulkan)](https://github.com/SaschaWillems/Vulkan) and [Deferred rendering of Sponza ![GitHub Repo Stars](https://img.shields.io/github/stars/SaschaWillems/VulkanSponza) ![GitHub last commit](https://img.shields.io/github/last-commit/SaschaWillems/VulkanSponza)](https://github.com/SaschaWillems/VulkanSponza) and his talk of [Khronos_meetup_munich](https://www.saschawillems.de/blog/2016/04/11/khronos-chapter-munich-vulkan-slides/).
*  (Incomplete) Sascha Willems's [samples port ![GitHub Repo Stars](https://img.shields.io/github/stars/jvm-graphics-labs/Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/jvm-graphics-labs/Vulkan)](https://github.com/jvm-graphics-labs/Vulkan) to Kotlin
*  Sascha Willems's [Vulkan-glTF-PBR ![GitHub Repo Stars](https://img.shields.io/github/stars/SaschaWillems/Vulkan-glTF-PBR) ![GitHub last commit](https://img.shields.io/github/last-commit/SaschaWillems/Vulkan-glTF-PBR)](https://github.com/SaschaWillems/Vulkan-glTF-PBR) - physical based rendering with Vulkan using glTF 2.0 models. [MIT]
*  [Vulkan Best Practice for Mobile Developers Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/ARM-software/vulkan_best_practice_for_mobile_developers) ![GitHub last commit](https://img.shields.io/github/last-commit/ARM-software/vulkan_best_practice_for_mobile_developers)](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
*  Google
    *  [Android port of LunarG samples ![GitHub Repo Stars](https://img.shields.io/github/stars/googlesamples/vulkan-basic-samples) ![GitHub last commit](https://img.shields.io/github/last-commit/googlesamples/vulkan-basic-samples)](https://github.com/googlesamples/vulkan-basic-samples).
    *  [android tutorials ![GitHub Repo Stars](https://img.shields.io/github/stars/googlesamples/android-vulkan-tutorials) ![GitHub last commit](https://img.shields.io/github/last-commit/googlesamples/android-vulkan-tutorials)](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) - NVIDIA DesignWorks Samples. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-samples/gl_vk_threaded_cadscene) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-samples/gl_vk_threaded_cadscene)](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
    *  [gl_vk_chopper ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-samples/gl_vk_chopper) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-samples/gl_vk_chopper)](https://github.com/nvpro-samples/gl_vk_chopper) - Simple vulkan rendering example.
    *  [gl_vk_threaded_cadscene ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-samples/gl_vk_threaded_cadscene) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-samples/gl_vk_threaded_cadscene)](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) - OpenGL and Vulkan comparison on rendering a CAD scene using various techniques and [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) about it.
    *  [gl_vk_bk3dthreaded ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-samples/gl_vk_bk3dthreaded) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-samples/gl_vk_bk3dthreaded)](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - Vulkan sample rendering 3D with 'worker-threads'.
    *  [gl_vk_supersampled ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-samples/gl_vk_supersampled) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-samples/gl_vk_supersampled)](https://github.com/nvpro-samples/gl_vk_supersampled) - Vulkan sample showing a high quality super-sampled rendering.
*  [NVIDIA GameWorks Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/NVIDIAGameWorks/GraphicsSamples) ![GitHub last commit](https://img.shields.io/github/last-commit/NVIDIAGameWorks/GraphicsSamples)](https://github.com/NVIDIAGameWorks/GraphicsSamples) - GameWorks cross-platform graphics API samples. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/NVIDIAGameWorks/GraphicsSamples) ![GitHub last commit](https://img.shields.io/github/last-commit/NVIDIAGameWorks/GraphicsSamples)](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/LunarG/VulkanSamples) ![GitHub last commit](https://img.shields.io/github/last-commit/LunarG/VulkanSamples)](https://github.com/LunarG/VulkanSamples)
*  [vkcube ![GitHub Repo Stars](https://img.shields.io/github/stars/krh/vkcube) ![GitHub last commit](https://img.shields.io/github/last-commit/krh/vkcube)](https://github.com/krh/vkcube) - 'vkcube' sample from krh, works under X, wayland and VT console with
drm/kms.
*  [Stardust from Intel ![GitHub Repo Stars](https://img.shields.io/github/stars/GameTechDev/stardust_vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GameTechDev/stardust_vulkan)](https://github.com/GameTechDev/stardust_vulkan) - The Stardust sample application uses the Vulkan graphics API to efficiently render a cloud of animated particles. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/GameTechDev/stardust_vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GameTechDev/stardust_vulkan)](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Vulkan Quake port based on QuakeSpasm ![GitHub Repo Stars](https://img.shields.io/github/stars/Novum/vkQuake) ![GitHub last commit](https://img.shields.io/github/last-commit/Novum/vkQuake)](https://github.com/Novum/vkQuake).
*  [C# Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/FacticiusVir/SharpVk-Samples) ![GitHub last commit](https://img.shields.io/github/last-commit/FacticiusVir/SharpVk-Samples)](https://github.com/FacticiusVir/SharpVk-Samples) - Port of Overv's tutorials to [SharpVk ![GitHub Repo Stars](https://img.shields.io/github/stars/FacticiusVir/SharpVk) ![GitHub last commit](https://img.shields.io/github/last-commit/FacticiusVir/SharpVk)](https://github.com/FacticiusVir/SharpVk) [MIT]
*  [Vulkan-Forward-Plus-Renderer ![GitHub Repo Stars](https://img.shields.io/github/stars/WindyDarian/Vulkan-Forward-Plus-Renderer) ![GitHub last commit](https://img.shields.io/github/last-commit/WindyDarian/Vulkan-Forward-Plus-Renderer)](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer) - VFPR - a Vulkan Forward Plus Renderer. [MIT]
*  [Laugh Engine ![GitHub Repo Stars](https://img.shields.io/github/stars/jian-ru/laugh_engine) ![GitHub last commit](https://img.shields.io/github/last-commit/jian-ru/laugh_engine)](https://github.com/jian-ru/laugh_engine) - Vulkan implementation of real-time PBR renderer.
*  [tinyrenderers ![GitHub Repo Stars](https://img.shields.io/github/stars/chaoticbob/tinyrenderers) ![GitHub last commit](https://img.shields.io/github/last-commit/chaoticbob/tinyrenderers)](https://github.com/chaoticbob/tinyrenderers) - Single header implemenations of Vulkan and D3D12 renderers.
*  [TLVulkanRenderer ![GitHub Repo Stars](https://img.shields.io/github/stars/trungtle/TLVulkanRenderer) ![GitHub last commit](https://img.shields.io/github/last-commit/trungtle/TLVulkanRenderer)](https://github.com/trungtle/TLVulkanRenderer) - Simple Vulkan-based renderer for my master thesis on real-time transparency. [CC BY-SA 4.0]
*  [Vulkan-Hpp Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/jherico/Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/jherico/Vulkan)](https://github.com/jherico/Vulkan) - Fork of Sascha Willems excellent Vulkan examples that uses Vulkan-Hpp.
*  [SDF Font Demo ![GitHub Repo Stars](https://img.shields.io/github/stars/kocsis1david/font-demo) ![GitHub last commit](https://img.shields.io/github/last-commit/kocsis1david/font-demo)](https://github.com/kocsis1david/font-demo) - Text rendering in Vulkan by estimating signed distance. [MIT]
*  [vulkantoy ![GitHub Repo Stars](https://img.shields.io/github/stars/jpystynen/vulkantoy) ![GitHub last commit](https://img.shields.io/github/last-commit/jpystynen/vulkantoy)](https://github.com/jpystynen/vulkantoy) - Shadertoy image shader test app with Vulkan. [MIT]
*  [GL_vs_VK ![GitHub Repo Stars](https://img.shields.io/github/stars/RippeR37/GL_vs_VK) ![GitHub last commit](https://img.shields.io/github/last-commit/RippeR37/GL_vs_VK)](https://github.com/RippeR37/GL_vs_VK) - Comparison of OpenGL and Vulkan API in terms of performance. [MIT]
*  [Vulkan Basic Graphics Samples ![GitHub Repo Stars](https://img.shields.io/github/stars/vcoda/basic-graphics-samples) ![GitHub last commit](https://img.shields.io/github/last-commit/vcoda/basic-graphics-samples)](https://github.com/vcoda/basic-graphics-samples) - Collection of simple graphics samples that are written using Magma library.
*  [Simple RTX Vulkan raytracing tutorials ![GitHub Repo Stars](https://img.shields.io/github/stars/iOrange/rtxON) ![GitHub last commit](https://img.shields.io/github/last-commit/iOrange/rtxON)](https://github.com/iOrange/rtxON). [MIT]
*  [Ray Tracing In One Weekend (Vulkan RTX) ![GitHub Repo Stars](https://img.shields.io/github/stars/GPSnoopy/RayTracingInVulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GPSnoopy/RayTracingInVulkan)](https://github.com/GPSnoopy/RayTracingInVulkan) - Implementation of Peter Shirley's Ray Tracing In One Weekend book using Vulkan and NVIDIA's RTX extension.
*  [Gears VK ![GitHub Repo Stars](https://img.shields.io/github/stars/jeffboody/gearsvk) ![GitHub last commit](https://img.shields.io/github/last-commit/jeffboody/gearsvk)](https://github.com/jeffboody/gearsvk) - Gears VK is a heavily modified port of the famous "gears" demo to Vulkan/Android/Linux. [MIT]
*  [Hello triangle, ![GitHub Repo Stars](https://img.shields.io/github/stars/maierfelix/VK_KHR_ray_tracing) ![GitHub last commit](https://img.shields.io/github/last-commit/maierfelix/VK_KHR_ray_tracing)](https://github.com/maierfelix/VK_KHR_ray_tracing) based on Vulkan Ray Tracing extensions. [MIT]
*  [Simple Animation Blender ![GitHub Repo Stars](https://img.shields.io/github/stars/Red1C3/Simple-Animation-Blender) ![GitHub last commit](https://img.shields.io/github/last-commit/Red1C3/Simple-Animation-Blender)](https://github.com/Red1C3/Simple-Animation-Blender) - A real-time 1D animation blender and player using Vulkan as graphical back end and ImGui for GUI. [MIT]

## Libraries
* 2D
   *  [imgui ![GitHub Repo Stars](https://img.shields.io/github/stars/ocornut/imgui) ![GitHub last commit](https://img.shields.io/github/last-commit/ocornut/imgui)](https://github.com/ocornut/imgui) - Immediate Mode Graphical User interface. [MIT]
   *  [Skia](https://skia.googlesource.com/skia) - Google's 2D graphics library has a [Vulkan](https://skia.org/user/special/vulkan) [backend ![GitHub Repo Stars](https://img.shields.io/github/stars/google/skia) ![GitHub last commit](https://img.shields.io/github/last-commit/google/skia)](https://github.com/google/skia/tree/master/src/gpu/vk), demonstrated in a cross-platform [sample application](https://skia.org/user/sample/viewer) with its own [window library ![GitHub Repo Stars](https://img.shields.io/github/stars/google/skia) ![GitHub last commit](https://img.shields.io/github/last-commit/google/skia)](https://github.com/google/skia/tree/master/tools/viewer). [BSD 3-clause] [website](https://skia.org)
   *  [VKVG ![GitHub Repo Stars](https://img.shields.io/github/stars/jpbruyere/vkvg) ![GitHub last commit](https://img.shields.io/github/last-commit/jpbruyere/vkvg)](https://github.com/jpbruyere/vkvg) - Vulkan 2D graphics library, API follows the same pattern as Cairo graphics lib, but with new functions.

* Compute
   *  [libvc ![GitHub Repo Stars](https://img.shields.io/github/stars/alexhultman/libvc) ![GitHub last commit](https://img.shields.io/github/last-commit/alexhultman/libvc)](https://github.com/alexhultman/libvc) - Vulkan Compute for C++.  [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/alexhultman/libvc) ![GitHub last commit](https://img.shields.io/github/last-commit/alexhultman/libvc)](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
   *  [Vulkan Kompute ![GitHub Repo Stars](https://img.shields.io/github/stars/axsaucedo/vulkan-kompute) ![GitHub last commit](https://img.shields.io/github/last-commit/axsaucedo/vulkan-kompute)](https://github.com/axsaucedo/vulkan-kompute) - Blazing fast and lightweight Vulkan Compute Framework optimized for advanced GPU processing usecases. [Apache License 2.0]
   *  [ncnn ![GitHub Repo Stars](https://img.shields.io/github/stars/Tencent/ncnn) ![GitHub last commit](https://img.shields.io/github/last-commit/Tencent/ncnn)](https://github.com/Tencent/ncnn) - High-performance neural network inference framework with Vulkan based GPU inference. [BSD 3-clause]
   *  [vuh ![GitHub Repo Stars](https://img.shields.io/github/stars/Glavnokoman/vuh) ![GitHub last commit](https://img.shields.io/github/last-commit/Glavnokoman/vuh)](https://github.com/Glavnokoman/vuh) - Vulkan-based C++ GPGPU computing framework. [MIT]
   *  [VkFFT ![GitHub Repo Stars](https://img.shields.io/github/stars/DTolm/VkFFT) ![GitHub last commit](https://img.shields.io/github/last-commit/DTolm/VkFFT)](https://github.com/DTolm/VkFFT) - Efficient Vulkan FFT library [MPL-2.0 License]

* Low Level
   *  [Vulkan Memory Allocator ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator)](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Easy to integrate Vulkan memory allocation library from AMD. [MIT]
      *  [VulkanMemoryAllocator-Hpp] (https://github.com/malte-v/VulkanMemoryAllocator-Hpp) - C++ Bindings for VMA, like Vulkan-HPP
   *  [Fossilize ![GitHub Repo Stars](https://img.shields.io/github/stars/Themaister/Fossilize) ![GitHub last commit](https://img.shields.io/github/last-commit/Themaister/Fossilize)](https://github.com/Themaister/Fossilize) - serialization format for various persistent Vulkan object types. [MIT]
   *  [vk-bootstrap ![GitHub Repo Stars](https://img.shields.io/github/stars/charles-lunarg/vk-bootstrap) ![GitHub last commit](https://img.shields.io/github/last-commit/charles-lunarg/vk-bootstrap)](https://github.com/charles-lunarg/vk-bootstrap) - C++ utility library to jump start Vulkan development by automating instance, physical device, device, and swapchain creation. [MIT]
   *  [Google's vulkan-cpp-library ![GitHub Repo Stars](https://img.shields.io/github/stars/google/vulkan-cpp-library) ![GitHub last commit](https://img.shields.io/github/last-commit/google/vulkan-cpp-library)](https://github.com/google/vulkan-cpp-library) - Vulkan abstraction library using C++11 for memory, resource management, type and thread safety as well as system independency. [Apache]
   *  [FrameGraph ![GitHub Repo Stars](https://img.shields.io/github/stars/azhirnov/FrameGraph) ![GitHub last commit](https://img.shields.io/github/last-commit/azhirnov/FrameGraph)](https://github.com/azhirnov/FrameGraph) - Vulkan abstraction layer that represent frame as a task graph. [BSD 2-clause]
   *  [V-EZ ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-LibrariesAndSDKs/V-EZ) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-LibrariesAndSDKs/V-EZ)](https://github.com/GPUOpen-LibrariesAndSDKs/V-EZ) - light-weight middleware layer for the Vulkan API targeting Professional Workstation ISVs. [MIT]
   *  [Vookoo ![GitHub Repo Stars](https://img.shields.io/github/stars/andy-thomason/Vookoo) ![GitHub last commit](https://img.shields.io/github/last-commit/andy-thomason/Vookoo)](https://github.com/andy-thomason/Vookoo) - Vookoo is a set of dependency-free utilities to assist in the construction and updating of Vulkan graphics data structres. [MIT]
   *  [vpp ![GitHub Repo Stars](https://img.shields.io/github/stars/nyorain/vpp) ![GitHub last commit](https://img.shields.io/github/last-commit/nyorain/vpp)](https://github.com/nyorain/vpp) - Modern C++ Vulkan Abstraction focused on performance and a straightforward interface. [MIT]
   *  [VulkanSceneGraph](https://github.com/vsg-dev) - Vulkan/C++17 scene graph project, successor to [OpenSceneGraph](http://www.openscenegraph.org).
   *  [Vulkan-WSIWindow ![GitHub Repo Stars](https://img.shields.io/github/stars/renelindsay/Vulkan-WSIWindow) ![GitHub last commit](https://img.shields.io/github/last-commit/renelindsay/Vulkan-WSIWindow)](https://github.com/renelindsay/Vulkan-WSIWindow) - Multi-platform library to create a Vulkan window, and handle input events. [Apache License 2.0]
   *  [Screen 13 ![GitHub Repo Stars](https://img.shields.io/github/stars/attackgoat/screen-13) ![GitHub last commit](https://img.shields.io/github/last-commit/attackgoat/screen-13)](https://github.com/attackgoat/screen-13) - An easy-to-use Vulkan render graph for Rust. [MIT]

* Frameworks, Engines, Higher Level Rendering
   *  [Acid ![GitHub Repo Stars](https://img.shields.io/github/stars/Equilibrium-Games/Acid) ![GitHub last commit](https://img.shields.io/github/last-commit/Equilibrium-Games/Acid)](https://github.com/Equilibrium-Games/Acid) - A high speed C++17 Vulkan game engine. [MIT]
   *  [AMD's Anvil ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-LibrariesAndSDKs/Anvil) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-LibrariesAndSDKs/Anvil)](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) - cross-platform framework for Vulkan. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-LibrariesAndSDKs/Anvil) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-LibrariesAndSDKs/Anvil)](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil/blob/master/LICENSE.txt)]
   *  [Auto-Vk ![GitHub Repo Stars](https://img.shields.io/github/stars/cg-tuwien/Auto-Vk) ![GitHub last commit](https://img.shields.io/github/last-commit/cg-tuwien/Auto-Vk)](https://github.com/cg-tuwien/Auto-Vk) - Vulkan convenience and productivity layer for modern C++, atop Vulkan-Hpp, by the Research Unit of Computer Graphics, TU Wien. [MIT]
   *  [Auto-Vk-Toolkit ![GitHub Repo Stars](https://img.shields.io/github/stars/cg-tuwien/Auto-Vk-Toolkit) ![GitHub last commit](https://img.shields.io/github/last-commit/cg-tuwien/Auto-Vk-Toolkit)](https://github.com/cg-tuwien/Auto-Vk-Toolkit) - C++ framework around [Auto-Vk ![GitHub Repo Stars](https://img.shields.io/github/stars/cg-tuwien/Auto-Vk) ![GitHub last commit](https://img.shields.io/github/last-commit/cg-tuwien/Auto-Vk)](https://github.com/cg-tuwien/Auto-Vk) for rapid prototyping, research, and teaching, by the Research Unit of Computer Graphics, TU Wien. [MIT for the framework's code]
   *  [bgfx ![GitHub Repo Stars](https://img.shields.io/github/stars/bkaradzic/bgfx) ![GitHub last commit](https://img.shields.io/github/last-commit/bkaradzic/bgfx)](https://github.com/bkaradzic/bgfx#bgfx---cross-platform-rendering-library) - Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library. [[BSD-2-clause ![GitHub Repo Stars](https://img.shields.io/github/stars/bkaradzic/bgfx) ![GitHub last commit](https://img.shields.io/github/last-commit/bkaradzic/bgfx)](https://github.com/bkaradzic/bgfx/blob/master/LICENSE)]
   *  [bsf ![GitHub Repo Stars](https://img.shields.io/github/stars/GameFoundry/bsf) ![GitHub last commit](https://img.shields.io/github/last-commit/GameFoundry/bsf)](https://github.com/GameFoundry/bsf) - Modern C++14 library for the development of real-time graphical applications. [MIT]
   *  [Cinder ![GitHub Repo Stars](https://img.shields.io/github/stars/cinder/Cinder) ![GitHub last commit](https://img.shields.io/github/last-commit/cinder/Cinder)](https://github.com/cinder/Cinder) and [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007). [BSD]
   *  [DemoFramework ![GitHub Repo Stars](https://img.shields.io/github/stars/NXPmicro/gtec-demo-framework) ![GitHub last commit](https://img.shields.io/github/last-commit/NXPmicro/gtec-demo-framework)](https://github.com/NXPmicro/gtec-demo-framework) - NXP GTEC C++11 cross-platform demo framework including lots of samples for Vulkan, OpenGL ES, OpenVX, OpenCL, OpenVG and OpenCV. [[BSD-3-clause ![GitHub Repo Stars](https://img.shields.io/github/stars/NXPmicro/gtec-demo-framework) ![GitHub last commit](https://img.shields.io/github/last-commit/NXPmicro/gtec-demo-framework)](https://github.com/NXPmicro/gtec-demo-framework/blob/master/License.md)]
   *  [Diligent Engine ![GitHub Repo Stars](https://img.shields.io/github/stars/DiligentGraphics/DiligentEngine) ![GitHub last commit](https://img.shields.io/github/last-commit/DiligentGraphics/DiligentEngine)](https://github.com/DiligentGraphics/DiligentEngine) - a modern cross-platform low-level graphics library that supports OpenGL/GLES, Direct3D11/12 and Vulkan. [Apache License 2.0]
   *  [Falcor ![GitHub Repo Stars](https://img.shields.io/github/stars/NVIDIAGameWorks/Falcor) ![GitHub last commit](https://img.shields.io/github/last-commit/NVIDIAGameWorks/Falcor)](https://github.com/NVIDIAGameWorks/Falcor) - Real-time rendering framework from NVIDIA, supporting mainly DX12, with experimental Vulkan support. [BSD 3-clause]
   *  [glfw ![GitHub Repo Stars](https://img.shields.io/github/stars/glfw/glfw) ![GitHub last commit](https://img.shields.io/github/last-commit/glfw/glfw)](https://github.com/glfw/glfw) and [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/glfw/glfw) ![GitHub last commit](https://img.shields.io/github/last-commit/glfw/glfw)](https://github.com/glfw/glfw/blob/master/LICENSE.md)]
   *  [Intrinsic Engine ![GitHub Repo Stars](https://img.shields.io/github/stars/begla/Intrinsic) ![GitHub last commit](https://img.shields.io/github/last-commit/begla/Intrinsic)](https://github.com/begla/Intrinsic) - Intrinsic is a Vulkan based cross-platform graphics and game engine. [Apache License 2.0]
   *  [Introductory Vulkan sample by GPUOpen ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-LibrariesAndSDKs/HelloVulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-LibrariesAndSDKs/HelloVulkan)](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan). [MIT]
   *  [liblava ![GitHub Repo Stars](https://img.shields.io/github/stars/liblava/liblava) ![GitHub last commit](https://img.shields.io/github/last-commit/liblava/liblava)](https://github.com/liblava/liblava) - A modern C++ and easy-to-use framework. [MIT]
   *  [Logi ![GitHub Repo Stars](https://img.shields.io/github/stars/UL-FRI-LGM/Logi) ![GitHub last commit](https://img.shields.io/github/last-commit/UL-FRI-LGM/Logi)](https://github.com/UL-FRI-LGM/Logi) - Light-weight object oriented Vulkan abstraction framework. [BSD 2-clause]
   *  [Lugdunum ![GitHub Repo Stars](https://img.shields.io/github/stars/Lugdunum3D/Lugdunum) ![GitHub last commit](https://img.shields.io/github/last-commit/Lugdunum3D/Lugdunum)](https://github.com/Lugdunum3D/Lugdunum) - Modern cross-platform 3D rendering engine built with Vulkan and modern C++14. [MIT]
   *  [openFrameworks ![GitHub Repo Stars](https://img.shields.io/github/stars/openframeworks-vk/openFrameworks) ![GitHub last commit](https://img.shields.io/github/last-commit/openframeworks-vk/openFrameworks)](https://github.com/openframeworks-vk/openFrameworks) - the most famouse C++ creative coding framework. [MIT]
   *  [PowerVR SDK ![GitHub Repo Stars](https://img.shields.io/github/stars/powervr-graphics/Native_SDK) ![GitHub last commit](https://img.shields.io/github/last-commit/powervr-graphics/Native_SDK)](https://github.com/powervr-graphics/Native_SDK) - C++ cross-platform 3D graphics SDK to speed up development of Vulkan and GLES. [[LICENSE ![GitHub Repo Stars](https://img.shields.io/github/stars/powervr-graphics/Native_SDK) ![GitHub last commit](https://img.shields.io/github/last-commit/powervr-graphics/Native_SDK)](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]
   *  [Pumex ![GitHub Repo Stars](https://img.shields.io/github/stars/pumexx/pumex) ![GitHub last commit](https://img.shields.io/github/last-commit/pumexx/pumex)](https://github.com/pumexx/pumex) - cross-platform Vulkan renderer implementing frame graph and simple scene graph. Able to render on many surfaces at once [MIT]
   *  [SDL](https://discourse.libsdl.org/t/sdl-2-0-6-released/23109) - added cross-platform Vulkan graphics support in SDL_vulkan.h. [zlib]
   *  [small3d](https://www.gamedev.net/projects/515-small3d/), Tiny Vulkan based C++ cross-platform game development framework [BSD 3-clause]
   *  [Spectrum ![GitHub Repo Stars](https://img.shields.io/github/stars/mwalczyk/spectrum_core) ![GitHub last commit](https://img.shields.io/github/last-commit/mwalczyk/spectrum_core)](https://github.com/mwalczyk/spectrum_core) - Work-in-progress framework and abstraction layer around Vulkan.
   *  [Tephra ![GitHub Repo Stars](https://img.shields.io/github/stars/Dolkar/Tephra) ![GitHub last commit](https://img.shields.io/github/last-commit/Dolkar/Tephra)](https://github.com/Dolkar/Tephra) - A modern C++17 graphics and compute library filling the gap between Vulkan and high-level APIs like OpenGL. [MIT]
   *  [The-Forge ![GitHub Repo Stars](https://img.shields.io/github/stars/ConfettiFX/The-Forge) ![GitHub last commit](https://img.shields.io/github/last-commit/ConfettiFX/The-Forge)](https://github.com/ConfettiFX/The-Forge) - DirectX 12, Vulkan, macOS Metal 2 rendering framework. [Apache License 2.0]
   *  [VKFS ![GitHub Repo Stars](https://img.shields.io/github/stars/MHDtA-dev/VKFS) ![GitHub last commit](https://img.shields.io/github/last-commit/MHDtA-dev/VKFS)](https://github.com/MHDtA-dev/VKFS) - Cross-platform easy-to-use C++ framework that allows you to quickly initialize Vulkan and get a ready-made environment. Provides high-level abstraction over basic Vulkan objects.
   *  [Vulkan Launchpad ![GitHub Repo Stars](https://img.shields.io/github/stars/cg-tuwien/VulkanLaunchpad) ![GitHub last commit](https://img.shields.io/github/last-commit/cg-tuwien/VulkanLaunchpad)](https://github.com/cg-tuwien/VulkanLaunchpad) - Vulkan framework for Windows, macOS, and Linux. Especially well-suited for Vulkan beginners, used in university education, by the Research Unit of Computer Graphics, TU Wien. [MIT]
       * [Vulkan Launchpad Starter ![GitHub Repo Stars](https://img.shields.io/github/stars/cg-tuwien/VulkanLaunchpadStarter) ![GitHub last commit](https://img.shields.io/github/last-commit/cg-tuwien/VulkanLaunchpadStarter)](https://github.com/cg-tuwien/VulkanLaunchpadStarter) - Starter template containing additional functionality and assets. [[LICENSE]](https://github.com/cg-tuwien/VulkanLaunchpadStarter/blob/main/LICENSE)

* Other API Interop and Implementations
   *  [visor ![GitHub Repo Stars](https://img.shields.io/github/stars/baldurk/visor) ![GitHub last commit](https://img.shields.io/github/last-commit/baldurk/visor)](https://github.com/baldurk/visor) - Vulkan Ignoble Software Rasterizer. [MIT]
   *  [VulkanOnD3D12 ![GitHub Repo Stars](https://img.shields.io/github/stars/Chabloom/VulkanOnD3D12) ![GitHub last commit](https://img.shields.io/github/last-commit/Chabloom/VulkanOnD3D12)](https://github.com/Chabloom/VulkanOnD3D12) - Vulkan API for D3D12. [Apache License 2.0]
   *  [rostkatze ![GitHub Repo Stars](https://img.shields.io/github/stars/msiglreith/rostkatze) ![GitHub last commit](https://img.shields.io/github/last-commit/msiglreith/rostkatze)](https://github.com/msiglreith/rostkatze) - C++ implementation of Vulkan sitting on D3D12 🐈[Apache License 2.0]
   *  [VK9 ![GitHub Repo Stars](https://img.shields.io/github/stars/disks86/VK9) ![GitHub last commit](https://img.shields.io/github/last-commit/disks86/VK9)](https://github.com/disks86/VK9) - Direct3D 9 compatibility layer using Vulkan
   *  [VUDA ![GitHub Repo Stars](https://img.shields.io/github/stars/jgbit/vuda) ![GitHub last commit](https://img.shields.io/github/last-commit/jgbit/vuda)](https://github.com/jgbit/vuda) - header-only lib that provides a CUDA Runtime API interface. [MIT]
   *  [clspv ![GitHub Repo Stars](https://img.shields.io/github/stars/google/clspv) ![GitHub last commit](https://img.shields.io/github/last-commit/google/clspv)](https://github.com/google/clspv) - prototype compiler for a subset of OpenCL C to Vulkan compute shaders. [Apache License 2.0]
   *  [MoltenVK ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/MoltenVK) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/MoltenVK)](https://github.com/KhronosGroup/MoltenVK/) - run Vulkan on iOS and macOS. [Apache-2.0]
   *  [Zink](https://gitlab.freedesktop.org/kusma/mesa/tree/zink) - OpenGL implementation on top of Vulkan, part of Mesa project. [MIT]
   *  [glo / OpenGL Overload ![GitHub Repo Stars](https://img.shields.io/github/stars/g-truc/glo) ![GitHub last commit](https://img.shields.io/github/last-commit/g-truc/glo)](https://github.com/g-truc/glo) - OpenGL implementation on top of Vulkan.
   *  [gfx-portability ![GitHub Repo Stars](https://img.shields.io/github/stars/gfx-rs/portability) ![GitHub last commit](https://img.shields.io/github/last-commit/gfx-rs/portability)](https://github.com/gfx-rs/portability) - Vulkan Portability implementation on Metal and D3D12, based on [gfx-rs ![GitHub Repo Stars](https://img.shields.io/github/stars/gfx-rs/gfx) ![GitHub last commit](https://img.shields.io/github/last-commit/gfx-rs/gfx)](https://github.com/gfx-rs/gfx/).

* Raytracing
   *  [Quartz ![GitHub Repo Stars](https://img.shields.io/github/stars/Nadrin/Quartz) ![GitHub last commit](https://img.shields.io/github/last-commit/Nadrin/Quartz)](https://github.com/Nadrin/Quartz) - Physically based Vulkan RTX path tracer with a declarative ES7-like scene description language. [LGPL-3.0]

* Scientific
   *  [datoviz ![GitHub Repo Stars](https://img.shields.io/github/stars/datoviz/datoviz) ![GitHub last commit](https://img.shields.io/github/last-commit/datoviz/datoviz)](https://github.com/datoviz/datoviz) - High-performance GPU interactive scientific data visualization with Vulkan. [MIT]
   *  [iMSTK](https://gitlab.kitware.com/iMSTK/iMSTK) - C++ toolkit for building surgical simulations with Vulkan and VTK backends. [Apache License 2.0]
  
* Shaders
   *  [glslang ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/glslang) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/glslang)](https://github.com/KhronosGroup/glslang) - Library for compiling glsl to spirv [BSD 3-Clause]
   *  [SPIRV-Cross ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/SPIRV-Cross) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/SPIRV-Cross)](https://github.com/KhronosGroup/SPIRV-Cross) - Library for reflection of spirv, simplify the creation of Vulkan pipeline layouts [ Apache-2.0 License]

* Outdated ⚠️
   *  [VkHLF ![GitHub Repo Stars](https://img.shields.io/github/stars/nvpro-pipeline/VkHLF) ![GitHub last commit](https://img.shields.io/github/last-commit/nvpro-pipeline/VkHLF)](https://github.com/nvpro-pipeline/VkHLF) - Vulkan High Level Framework. [[LICENSE]](https://github.com/nvpro-pipeline/VkHLF/blob/master/LICENSE.txt)

## Bindings
*  [ash ![GitHub Repo Stars](https://img.shields.io/github/stars/MaikKlein/ash) ![GitHub last commit](https://img.shields.io/github/last-commit/MaikKlein/ash)](https://github.com/MaikKlein/ash) - Vulkan bindings for Rust. [MIT]
*  [gfx-rs ![GitHub Repo Stars](https://img.shields.io/github/stars/gfx-rs/gfx) ![GitHub last commit](https://img.shields.io/github/last-commit/gfx-rs/gfx)](https://github.com/gfx-rs/gfx) - A low-overhead Vulkan-like GPU API for Rust. [Apache License 2.0]
*  [libvulkan.lua ![GitHub Repo Stars](https://img.shields.io/github/stars/CapsAdmin/ffibuild) ![GitHub last commit](https://img.shields.io/github/last-commit/CapsAdmin/ffibuild)](https://github.com/CapsAdmin/ffibuild/blob/master/vulkan/vulkan.lua) - Lua bindings for Vulkan.
*  [dvulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/ColonelThirtyTwo/dvulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/ColonelThirtyTwo/dvulkan)](https://github.com/ColonelThirtyTwo/dvulkan) - Auto-generated D bindings for Vulkan.
*  [ErupteD ![GitHub Repo Stars](https://img.shields.io/github/stars/ParticlePeter/ErupteD) ![GitHub last commit](https://img.shields.io/github/last-commit/ParticlePeter/ErupteD)](https://github.com/ParticlePeter/ErupteD) - Another Auto-generated D bindings for Vulkan.
*  [flextGL ![GitHub Repo Stars](https://img.shields.io/github/stars/mosra/flextgl) ![GitHub last commit](https://img.shields.io/github/last-commit/mosra/flextgl)](https://github.com/mosra/flextgl) - Minimal Vulkan header/loader generator and [the blog post](http://blog.magnum.graphics/hacking/simple-efficient-vulkan-loading-with-flextgl/) about it.
*  [Silk.NET ![GitHub Repo Stars](https://img.shields.io/github/stars/dotnet/Silk.NET) ![GitHub last commit](https://img.shields.io/github/last-commit/dotnet/Silk.NET)](https://github.com/dotnet/Silk.NET) - C# bindings for Vulkan and others. [MIT]
*  [vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/expipiplus1/vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/expipiplus1/vulkan)](https://github.com/expipiplus1/vulkan) - Haskell bindings for Vulkan and Vulkan Memory Allocator [BSD-3-Clause]
*  [nvk ![GitHub Repo Stars](https://img.shields.io/github/stars/maierfelix/nvk) ![GitHub last commit](https://img.shields.io/github/last-commit/maierfelix/nvk)](https://github.com/maierfelix/nvk) - JavaScript bindings for Vulkan. [MIT]
*  [racket-vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/zyrolasting/racket-vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/zyrolasting/racket-vulkan)](https://github.com/zyrolasting/racket-vulkan) - Racket bindings for Vulkan with [detailed implementation notes](https://sagegerard.com/racket-vulkan-notes-index.html). [MIT]
*  [Vulkan-hpp ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-Hpp) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-Hpp)](https://github.com/KhronosGroup/Vulkan-Hpp) Open-Source Vulkan C++ API originated from NVIDIA and [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) about it.
*  [VulkanSharp ![GitHub Repo Stars](https://img.shields.io/github/stars/mono/VulkanSharp) ![GitHub last commit](https://img.shields.io/github/last-commit/mono/VulkanSharp)](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano ![GitHub Repo Stars](https://img.shields.io/github/stars/vulkano-rs/vulkano) ![GitHub last commit](https://img.shields.io/github/last-commit/vulkano-rs/vulkano)](https://github.com/vulkano-rs/vulkano) - Safe and rich Rust wrapper around the Vulkan API. [MIT]
*  [LWJGL](https://www.lwjgl.org/) - Lightweight Java Game Library 3 has Vulkan bindings. [BSD]
*  [SharpVk ![GitHub Repo Stars](https://img.shields.io/github/stars/FacticiusVir/SharpVk) ![GitHub last commit](https://img.shields.io/github/last-commit/FacticiusVir/SharpVk)](https://github.com/FacticiusVir/SharpVk) - C# bindings for Vulkan with Linq-to-SPIR-V & [NuGet package](https://www.nuget.org/packages/SharpVk). [MIT]
*  [vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/realitix/vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/realitix/vulkan)](https://github.com/realitix/vulkan) - Ultimate Python bindings for Vulkan generated with CFFI. [Apache Licence 2.0]
*  [vulkan-go ![GitHub Repo Stars](https://img.shields.io/github/stars/vulkan-go/vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/vulkan-go/vulkan)](https://github.com/vulkan-go/vulkan) - Go bindings for Vulkan. [MIT]
*  [PasVulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/BeRo1985/pasvulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/BeRo1985/pasvulkan)](https://github.com/BeRo1985/pasvulkan) - Vulkan bindings plus high-level wrapper library for Object Pascal [Zlib]
*  [vulkan-zig ![GitHub Repo Stars](https://img.shields.io/github/stars/Snektron/vulkan-zig) ![GitHub last commit](https://img.shields.io/github/last-commit/Snektron/vulkan-zig)](https://github.com/Snektron/vulkan-zig) - Vulkan binding generator for Zig [MIT]
*  [VK² ![GitHub Repo Stars](https://img.shields.io/github/stars/kotlin-graphics/vkk) ![GitHub last commit](https://img.shields.io/github/last-commit/kotlin-graphics/vkk)](https://github.com/kotlin-graphics/vkk), Kotlin Wrapper for Vulkan: code expressiveness and safety meet graphic power [Apache License 2.0]
*  [Vortice.Vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/amerkoleci/Vortice.Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/amerkoleci/Vortice.Vulkan)](https://github.com/amerkoleci/Vortice.Vulkan) - .NET Standard 2.0 and .NET5 C# bindings [MIT]
*  [Raw Node.js Vulkan API ![GitHub Repo Stars](https://img.shields.io/github/stars/hydra2s/node-vulkan-api) ![GitHub last commit](https://img.shields.io/github/last-commit/hydra2s/node-vulkan-api)](https://github.com/hydra2s/node-vulkan-api) - A new Vulkan bindings for Node.JS, similar with LWJGL-3 or NVK.
*  [Deno Vulkan ![GitHub Repo Stars](https://img.shields.io/github/stars/deno-windowing/vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/deno-windowing/vulkan)](https://github.com/deno-windowing/vulkan) - Vulkan API bindings for Deno. [Apache Licence 2.0]

## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-LoaderAndValidationLayers) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-LoaderAndValidationLayers)](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers) - from KhronosGroup. [Apache Licence 2.0]
*  [renderdoc ![GitHub Repo Stars](https://img.shields.io/github/stars/baldurk/renderdoc) ![GitHub last commit](https://img.shields.io/github/last-commit/baldurk/renderdoc)](https://github.com/baldurk/renderdoc) - by baldurk, a stand-alone graphics debugging tool. [MIT]
    * [RDCtoVkCpp ![GitHub Repo Stars](https://img.shields.io/github/stars/azhirnov/RDCtoVkCpp) ![GitHub last commit](https://img.shields.io/github/last-commit/azhirnov/RDCtoVkCpp)](https://github.com/azhirnov/RDCtoVkCpp) - converts RenderDoc Vulkan capture to compilable and executable C++ code. [MIT]
*  [VulkanTools ![GitHub Repo Stars](https://img.shields.io/github/stars/LunarG/VulkanTools) ![GitHub last commit](https://img.shields.io/github/last-commit/LunarG/VulkanTools)](https://github.com/LunarG/VulkanTools) - LunarG's tools including layers and configurator. [Apache Licence 2.0]
*  [VKtracer](https://www.vktracer.com) - universal and easy-to-use profiler for Vulkan.
*  [CodeXL ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-Tools/CodeXL) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-Tools/CodeXL)](https://github.com/GPUOpen-Tools/CodeXL) - CodeXL goes open source. [MIT]
*  [Qualcomm Adreno GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools) - samples, Adreno recommendation layer, best practice docs for Adreno GPU.
*  [Qualcomm Snapdragon Profiler](https://developer.qualcomm.com/software/snapdragon-profiler) - includes Vulkan traces and frame captures for Adreno GPU.
*  [Arm Mobile Studio](https://www.arm.com/products/development-tools/graphics/arm-mobile-studio) - includes the Arm Graphics Analyzer to trace graphics performance issues easily, and Arm Streamline performance analyzer, for a whole-system view of performance to determine bottlenecks quickly across both the CPU and GPU.
*  [Open Capture and Analytics Tool (OCAT) ![GitHub Repo Stars](https://img.shields.io/github/stars/GPUOpen-Tools/OCAT) ![GitHub last commit](https://img.shields.io/github/last-commit/GPUOpen-Tools/OCAT)](https://github.com/GPUOpen-Tools/OCAT) - provides an FPS overlay and performance measurement for D3D11, D3D12, and Vulkan. [MIT]
*  [gapid ![GitHub Repo Stars](https://img.shields.io/github/stars/google/gapid) ![GitHub last commit](https://img.shields.io/github/last-commit/google/gapid)](https://github.com/google/gapid) - Graphics API Debugger, can trace and replay Android OpenGL ES and Vulkan applications. [Apache License 2.0]
*  [Arm - PerfDoc ![GitHub Repo Stars](https://img.shields.io/github/stars/ARM-software/perfdoc) ![GitHub last commit](https://img.shields.io/github/last-commit/ARM-software/perfdoc)](https://github.com/ARM-software/perfdoc) - a validation layer against the Mali Application Developer Best Practices document. [MIT]
*  [glsl_trace ![GitHub Repo Stars](https://img.shields.io/github/stars/azhirnov/glsl_trace) ![GitHub last commit](https://img.shields.io/github/last-commit/azhirnov/glsl_trace)](https://github.com/azhirnov/glsl_trace) - library for shader debugging and profiling for Vulkan and OpenGL. [MIT]
*  [MangoHud ![GitHub Repo Stars](https://img.shields.io/github/stars/flightlessmango/MangoHud) ![GitHub last commit](https://img.shields.io/github/last-commit/flightlessmango/MangoHud)](https://github.com/flightlessmango/MangoHud) - Vulkan and OpenGL overlay for monitoring FPS, temperatures, CPU/GPU load. [MIT]

## Books
* [Introduction to Computer Graphics and the Vulkan API](https://www.amazon.com/Introduction-Computer-Graphics-Vulkan-API/dp/1548616176) by **Kenwright** - Introduce the reader to the exciting topic of computer graphics from a grounds-up practical perspective with the Vulkan API.
* [Learning Vulkan](https://www.amazon.com/Learning-Vulkan-Parminder-Singh/dp/1786469804) - by **Parminder Singh** - Get started with the Vulkan API and its programming techniques using the easy-to-follow examples.
  * [Book's Examples ![GitHub Repo Stars](https://img.shields.io/github/stars/PacktPublishing/Learning-Vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/PacktPublishing/Learning-Vulkan)](https://github.com/PacktPublishing/Learning-Vulkan)
* [Vulkan Cookbook](https://www.amazon.com/Vulkan-Cookbook-Pawel-Lapinski/dp/1786468158)- by **Pawel Lapinski** - Explores a wide range of graphics programming and GPU compute methods to make the best use of the Vulkan API.
  * [Book's Examples ![GitHub Repo Stars](https://img.shields.io/github/stars/PacktPublishing/Vulkan-Cookbook) ![GitHub last commit](https://img.shields.io/github/last-commit/PacktPublishing/Vulkan-Cookbook)](https://github.com/PacktPublishing/Vulkan-Cookbook)
* [Vulkan Programming Guide](https://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - by **Graham Sellers** and **John Kessenich** - Introduces powerful 3D development techniques for many fields.
* [Mastering Graphics Programming with Vulkan](https://www.amazon.com/Mastering-Graphics-Programming-Vulkan-state/dp/1803244798/ref=sr_1_1?keywords=mastering+graphics+programming+with+vulkan&qid=1678290788&sprefix=mastering+graphics+%2Caps%2C255&sr=8-1) - Develop a modern rendering engine from first principles to state-of-the-art techniques, by **Marco Castorina** and **Gabriel Sassone**.

## Papers
*  [The Road to Vulkan: Teaching Modern Low-Level APIs in Introductory Graphics Courses](https://www.cg.tuwien.ac.at/research/publications/2022/unterguggenberger-2022-vulkan) by **Johannes Unterguggenberger**, **Bernhard Kerbl**, and **Michael Wimmer**, Eurographics 2022 - Education Papers
    *  Direct link to the [paper](https://www.cg.tuwien.ac.at/research/publications/2022/unterguggenberger-2022-vulkan/unterguggenberger-2022-vulkan-paper.pdf).
    *  Pre-recorded presentation on [YouTube](https://youtu.be/ZG0ct4V6c0k).

## Khronos
*  Specification
    *  Vulkan 1.0 Core API ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.0/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.0/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.0/html/vkspec.html))
    *  Vulkan 1.0 Core API + Khronos-defined Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.0-wsi_extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.0-wsi_extensions/html/vkspec.html))
    *  Vulkan 1.0 Core API + all registered Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.0-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.0-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.0-extensions/html/vkspec.html)) 
    *  Vulkan 1.1 Core API ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.1/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.1/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.1/html/vkspec.html))
    *  Vulkan 1.1 Core API + Khronos-defined Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.1-khr-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.1-khr-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.1-khr-extensions/html/vkspec.html))
    *  Vulkan 1.1 Core API + all registered Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.1-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.1-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.1-extensions/html/vkspec.html)) 
    *  Vulkan 1.2 Core API ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.2/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.2/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.2/html/vkspec.html))
    *  Vulkan 1.2 Core API + Khronos-defined Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.2-khr-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.2-khr-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.2-khr-extensions/html/vkspec.html))
    *  Vulkan 1.2 Core API + all registered Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.2-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.2-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.2-extensions/html/vkspec.html)) 
    *  Vulkan 1.3 Core API ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.3/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.3/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.3/html/vkspec.html))
    *  Vulkan 1.3 Core API + Khronos-defined Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.3-khr-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.3-khr-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.3-khr-extensions/html/vkspec.html))
    *  Vulkan 1.3 Core API + all registered Extensions ([Chunked HTML](https://registry.khronos.org/vulkan/specs/1.3-extensions/html/index.html)) ([PDF](https://registry.khronos.org/vulkan/specs/1.3-extensions/pdf/vkspec.pdf)) ([Single-file HTML](https://registry.khronos.org/vulkan/specs/1.3-extensions/html/vkspec.html)) 
*  Quick Reference Sheets
    *  [Vulkan 1.0 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
    *  [Vulkan 1.1 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.1/refguide/Vulkan-1.1-web.pdf)
*  [Conformance Tests (CTS) ![GitHub Repo Stars](https://img.shields.io/github/stars/KhronosGroup/Vulkan-CTS) ![GitHub last commit](https://img.shields.io/github/last-commit/KhronosGroup/Vulkan-CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
*  Conferences and Presentations
    *  [GDC 2016 Presentations](https://www.khronos.org/developers/library/2016-gdc)
    *  [2016 UK Chapter: Moving to Vulkan](https://www.khronos.org/developers/library/2016-uk-chapter-moving-to-vulkan)
    *  [SIGGRAPH 2016 BOF - Vulkan](https://www.youtube.com/watch?v=CsHMiEQgrLA)
    *  [SIGGRPAH 2016 Best Practices Roundtable](https://www.youtube.com/watch?v=owuJRPKIUAg)
    *  [2016 Vulkan DevDay UK](https://www.khronos.org/developers/library/2016-vulkan-devday-uk)
    *  [2016 Vulkan DevDay Seoul](https://www.khronos.org/developers/library/2016-Vulkan-DevU-Seoul)
    *  [2017 Vulkan DevU Vancouver](https://www.khronos.org/developers/library/2017-vulkan-devu-vancouver)
    *  [2017 Vulkan Loader Webinar](https://www.khronos.org/developers/library/2017-vulkan-loader-webinar)
    *  [SIGGRAPH 2017 BOF - Vulkan](https://www.youtube.com/watch?v=Nx0u-9ZwrmQ)
    *  [2018 Vulkan Montreal Dev Day](https://www.khronos.org/developers/library/2018-vulkan-montreal-dev-day)
    *  [2018 Vulkanised!](https://www.khronos.org/developers/library/2018-vulkanised)
    *  [SIGGRAPH 2018 BOF - Vulkan](https://www.youtube.com/watch?v=FCAM-3aAzXg&t=18350s)

## Community
*  [Freenode IRC](http://webchat.freenode.net/?channels=Vulkan)
*  [Google Plus](https://plus.google.com/communities/108983304183191634377)
*  [Khronos Forum](https://forums.khronos.org/forumdisplay.php/114-Vulkan)
*  [Reddit](https://www.reddit.com/r/vulkan/)
*  [Stack Overflow](http://stackoverflow.com/questions/tagged/vulkan)
*  [Discord](https://discord.com/invite/tFdvbEj)

## Related lists
*  [awesome ![GitHub Repo Stars](https://img.shields.io/github/stars/sindresorhus/awesome) ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/awesome)](https://github.com/sindresorhus/awesome) - Curated list of awesome lists.
*  [awesome-opengl ![GitHub Repo Stars](https://img.shields.io/github/stars/eug/awesome-opengl) ![GitHub last commit](https://img.shields.io/github/last-commit/eug/awesome-opengl)](https://github.com/eug/awesome-opengl) - Curated list of awesome OpenGL libraries, debuggers and resources.
*  [gamedev ![GitHub Repo Stars](https://img.shields.io/github/stars/ellisonleao/magictools) ![GitHub last commit](https://img.shields.io/github/last-commit/ellisonleao/magictools)](https://github.com/ellisonleao/magictools) - Awesome list about game development.
*  [graphics-resources ![GitHub Repo Stars](https://img.shields.io/github/stars/mattdesl/graphics-resources) ![GitHub last commit](https://img.shields.io/github/last-commit/mattdesl/graphics-resources)](https://github.com/mattdesl/graphics-resources) - List of graphic programming resources.
*  [awesome-d3d12 ![GitHub Repo Stars](https://img.shields.io/github/stars/vinjn/awesome-d3d12) ![GitHub last commit](https://img.shields.io/github/last-commit/vinjn/awesome-d3d12)](https://github.com/vinjn/awesome-d3d12) - Curated list of awesome D3D12 libraries, debuggers and resources.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
Please see [CONTRIBUTING ![GitHub Repo Stars](https://img.shields.io/github/stars/vinjn/awesome-vulkan) ![GitHub last commit](https://img.shields.io/github/last-commit/vinjn/awesome-vulkan)](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) for details.
