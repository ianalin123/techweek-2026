# Spatial Creation in 2026: A Comprehensive Tooling Landscape for the MOLTEN Hackathon

**Key Points**
*   **The Paradigm Shift**: Spatial consumption has matured via Apple Vision Pro and Meta Quest 3, yet spatial creation remains constrained by legacy 2D interfaces.
*   **Hackathon Feasibility**: Several tier-one companies, notably World Labs and Luma AI, have recently launched robust, low-latency APIs uniquely suited for 24-hour student prototyping.
*   **Critical Industry Exits**: Former avatar leader Ready Player Me was acquired by Netflix in late 2025 and has ceased public API access, removing them from partner consideration.
*   **The a16z Ecosystem**: Andreessen Horowitz, particularly through its Speedrun accelerator, dominates the funding landscape for generative 3D and spatial intelligence startups.

**Contextual Overview**
The transition from two-dimensional screen interfaces to spatial computing requires a fundamental rethinking of digital authoring. Current industry-standard tools—such as Blender, Unity, and Unreal Engine—rely heavily on keyboard and mouse inputs, creating a cognitive and physiological disconnect for spatial output. The MOLTEN hackathon posits that the next generation of authoring tools will leverage multimodal, whole-body inputs to natively construct three-dimensional environments.

**Strategic Alignment for MOLTEN**
This report maps the current 3D generative landscape as of late 2026 to identify optimal targets for sponsorship, speaking engagements, and API partnerships. The ecosystem is bifurcated into closed-platform applications and API-first infrastructures. For a 24-hour hackathon, API accessibility, clear documentation, and free or student-tier pricing are paramount. The following analysis systematically categorizes these technologies to equip the MOLTEN organizing team with actionable recruitment intelligence.

## 1. Executive Summary: The 12 Best Targets Ranked

The following twelve organizations and individuals represent the highest-value targets for the MOLTEN hackathon, categorized by their optimal mode of engagement. These targets have been selected based on their technological relevance, geographical presence, hackathon support history, and alignment with the event's core thesis of multimodal spatial creation.

### Top Speaker Asks
1.  **Amit Jain (Luma AI)**: As CEO of a company that has pioneered both NeRF/Gaussian Splatting and generative video (Dream Machine), Jain is an ideal keynote speaker. Luma AI is deeply integrated into the a16z portfolio [cite: 1, 2] and Jain frequently speaks on multimodal foundation models at major academic and industry conferences [cite: 2, 3]. 
2.  **Dr. Fei-Fei Li (World Labs)**: As a pioneer in spatial intelligence and founder of World Labs, Dr. Li's vision perfectly aligns with MOLTEN's thesis. World Labs recently launched the Marble API, making her an authoritative voice on transitioning from 2D pixels to navigable 3D worlds [cite: 4, 5].
3.  **Marguerite deCourcelle (Blockade Labs)**: CEO of Blockade Labs, deCourcelle (also known as Coin Artist) is a proven speaker on the intersection of AI, virtual environments, and interactive storytelling [cite: 6, 7]. Her insights into Skybox AI's generation capabilities would resonate with students building immersive environments.
4.  **Mandeep Waraich (Yellow)**: Backed by a16z, Waraich leads Yellow in revolutionizing 3D character creation through generative AI. His focus on empowering human creativity rather than replacing it makes him an excellent theoretical and technical speaker for a student audience [cite: 8, 9].

### Top Sponsor Asks
5.  **a16z Speedrun**: The Andreessen Horowitz Speedrun accelerator is the most prolific investor in the spatial and AI gaming ecosystem [cite: 10, 11]. Securing Speedrun as a marquee sponsor would provide MOLTEN with significant capital, prestige, and direct access to their portfolio companies for mentorship.
6.  **Meshy**: Having recently raised a $400M Series B [cite: 12, 13], Meshy possesses significant capital to deploy for developer relations. Their focus on AI-assisted 3D modeling makes them a prime candidate for financial sponsorship and tiered prizes [cite: 14, 15].
7.  **Arcturus**: With $11M in Series A funding backed by a16z and Epic Games, Arcturus is the leader in volumetric video editing [cite: 16, 17]. Their technology is crucial for bridging real-world human performance with spatial computing, making them a highly relevant financial and technical sponsor [cite: 17, 18].
8.  **Polycam**: A dominant force in mobile 3D capture and Gaussian splatting, Polycam has raised $22M [cite: 19, 20]. Given their strong integration with the Apple Vision Pro and iOS ecosystems [cite: 20, 21], they are an ideal sponsor for the device-specific tracks of the hackathon.

### Top API Partners
9.  **World Labs**: The recently launched World API allows developers to generate explorable 3D worlds from text, images, and video [cite: 5, 22]. This is the most powerful public API currently available for rapid spatial environment generation in a 24-hour timeframe.
10. **Inworld AI**: For the AI character and avatar track, Inworld AI offers an unmatched, ultra-low latency Realtime API for dynamic NPC interactions [cite: 23, 24]. Their established history of supporting Speedrun startups (e.g., Playroom) proves their viability for rapid hackathon deployment [cite: 23].
11. **Luma AI**: Luma's Ray 2 API and new Model Context Protocol (MCP) servers allow students to rapidly integrate 3D and video generation into spatial applications [cite: 25, 26]. Their documented history of sponsoring AI hackathons makes them a reliable technical partner [cite: 25, 27].
12. **Kinetix**: Offering a $1M AI-UGC fund and a robust API for AI-driven user-generated emotes and 3D animations [cite: 28, 29], Kinetix provides the necessary infrastructure for students building body-input animation tools.

## 2. Text-to-3D and Image-to-3D Asset Generation

The transformation of textual prompts and two-dimensional images into fully realized, topologically sound 3D meshes is a foundational requirement for next-generation spatial authoring. The companies in this sector utilize various generative diffusion models and neural radiance field translations to output standard 3D formats (OBJ, GLTF, USDZ) suitable for real-time spatial engines.

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Meshy** | Sunnyvale, CA [cite: 30] | Unverified | IDG Capital, Matrix Partners China, Monolith [cite: 12] | No | Yes [cite: 13, 31] | Yes (Free-tier signups) [cite: 13] | Unverified | Yes (148+ employees) [cite: 14, 30] |
| **Common Sense Machines (CSM)** | Cambridge, MA [cite: 32, 33] | Unverified | Angel/VC ($5M-$7M) [cite: 33, 34] | No | Yes (CSM Developer Tools) [cite: 35] | Unverified | Unverified | Unverified |
| **Luma AI** | San Francisco, CA [cite: 36, 37] | Unverified (Bay Area lab) [cite: 36, 37] | NVIDIA, Amazon, AMD, a16z [cite: 1, 37] | Yes [cite: 1] | Yes (Ray 2 API, MCP) [cite: 25, 27] | Yes (Developer grants/credits) [cite: 27, 36] | Yes (Sponsored AI Tech Sandbox) [cite: 27] | Yes [cite: 36] |

### Academic & Technical Analysis
**Meshy** represents a significant leap in capital concentration within the 3D generative space, having secured a massive $400M Series B valuation at $1.5B [cite: 12, 13]. Their primary value proposition is enterprise-scale API workflows for game studios and 3D pipelines [cite: 14, 31]. For MOLTEN students, Meshy's API is highly attractive as it directly addresses the asset-creation bottleneck. Students could theoretically use spatial hand-tracking on a Quest 3 to "mold" a primitive shape, pass the coordinates and a vocal text prompt to the Meshy API, and instantly retrieve a textured GLB file to drop into their WebXR scene.

**Common Sense Machines (CSM)** focuses heavily on providing AI technologies for generating 3D assets from multi-modal inputs, explicitly positioning themselves to simplify immersive experience creation [cite: 32, 38]. They offer dedicated developer tools and APIs [cite: 35], making them a strong secondary option if Meshy proves cost-prohibitive, though their capital backing is significantly smaller [cite: 34].

**Luma AI** crosses multiple categories, but its foundation in 3D capture and generation makes it a critical player. Their recent rollout of Model Context Protocol (MCP) servers and the Ray 2 API [cite: 25, 26] means students can bypass traditional REST architecture complexities and directly integrate Luma's generation capabilities into local AI agents during the 24-hour sprint. Luma's active participation in hackathons [cite: 27] indicates a strong developer relations apparatus ready to support student builders.

## 3. Generative 3D Scene and World Models

Moving beyond individual asset generation, the frontier of spatial computing lies in "spatial intelligence"—the ability of AI models to understand, generate, and simulate entire 3D worlds. These persistent, explorable environments are crucial for moving spatial creation away from placing individual assets in Unity toward generating holistic environments via whole-body prompts.

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **World Labs** | San Francisco, CA [cite: 39] | Unverified | a16z [cite: 4, 40] | Yes [cite: 40] | Yes (World API) [cite: 5, 22] | Yes (Credit minimum $5) [cite: 22] | Unverified | Yes [cite: 39] |
| **Blockade Labs** | Indianapolis, IN [cite: 41] | Unverified | Polyient [cite: 41] | No | Yes (API Access) [cite: 42, 43] | Unverified | Unverified | Unverified |
| **Nilo Technologies** | Dover, DE (Reg) [cite: 44] | Unverified | a16z Speedrun, Flex Capital [cite: 10, 44] | Yes [cite: 10] | No (Closed App/Platform) [cite: 45] | N/A | Won SF Demo Day [cite: 10, 44] | Yes [cite: 44, 45] |

### Academic & Technical Analysis
**World Labs**, founded by AI luminary Dr. Fei-Fei Li, recently unveiled "Marble," a multimodal world model, followed by the public launch of the World API in January 2026 [cite: 5, 39]. This API is a monumental asset for a hackathon. It accepts text, single images, panoramas, and video, returning fully navigable 3D spatial environments (often via Gaussian splats) [cite: 5, 46]. At a cost of roughly $1.00 per 1,250 credits (with a generated world costing a fraction of that depending on input), it is highly affordable for rapid prototyping [cite: 22]. A student team could build an Apple Vision Pro app where a user physically dances, the spatial video of the dance is passed to the World API, and a persistent 3D world matching the emotional tone of the movement is returned in minutes.

**Blockade Labs** focuses on 360-degree skybox generation (Skybox AI), which is a lightweight alternative to full volumetric world generation [cite: 42, 47]. Their API is robust and includes terms of service specifically outlining API use and ownership [cite: 42, 43]. For WebXR projects on mobile AR, rendering a massive 3D mesh might crash the browser, making Blockade Labs' high-fidelity 360-degree equirectangular outputs a highly viable solution for 24-hour WebXR projects [cite: 42]. 

**Nilo Technologies** represents a common paradigm in the a16z Speedrun portfolio: a highly capable, AI-native platform that operates as a closed ecosystem. Nilo allows users to create 3D worlds in seconds directly in the browser via text and AI assistance [cite: 10, 45]. However, the research indicates this is a self-contained application rather than a headless API that developers can hook into [cite: 45]. Therefore, while Nilo is an excellent example of the *goal* of spatial creation, they are not a viable API partner for students who need to build their own custom physical interfaces.

## 4. Gaussian Splatting, NeRF, Capture, and Reconstruction

Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting (3DGS) represent the most significant breakthroughs in reality capture. Unlike traditional photogrammetry, which struggles with reflective surfaces and complex geometries, these AI-driven techniques synthesize novel views from standard 2D video or image sets, creating highly realistic spatial representations.

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Polycam** | San Francisco, CA [cite: 19] | Unverified | Left Lane, Adjacent, Adobe, a16z, Sequoia [cite: 21, 48] | Yes [cite: 48] | Unverified (Mostly Closed App) [cite: 21, 48] | Free basic tier [cite: 21] | Unverified | Yes [cite: 20] |
| **Luma AI** | San Francisco, CA [cite: 36, 37] | Unverified | NVIDIA, Amazon, a16z [cite: 1, 37] | Yes [cite: 1] | Yes (Ray 2 API) [cite: 25, 26] | Yes [cite: 27, 36] | Yes [cite: 27] | Yes [cite: 36] |

### Academic & Technical Analysis
**Polycam** has established itself as the dominant consumer and prosumer application for mobile 3D capture, leveraging smartphone LiDAR and cloud photogrammetry [cite: 20, 48]. They recently raised an $18M Series A [cite: 20, 48] and have launched a dedicated Apple Vision Pro app [cite: 20, 21]. However, from a hackathon infrastructure perspective, Polycam functions primarily as a closed application (SaaS product) that allows users to export standard 3D files [cite: 21, 48]. While students could use the Polycam app to capture a physical room and export it to Unity, they cannot programmatically trigger Polycam's reconstruction algorithms via an open API within a custom 24-hour application. Thus, Polycam is best approached as a financial sponsor rather than a core API partner.

**Luma AI** remains the superior choice for programmatic capture and reconstruction. Their foundational technology relies heavily on advanced Gaussian Splatting techniques. Because Luma exposes its backend via APIs and CLI tools [cite: 27], a student team could write a script that takes a continuous video feed from a Meta Quest 3's passthrough cameras, chunks the video, uploads it to Luma's API, and dynamically loads the resulting Gaussian splat back into the headset, effectively creating an asynchronous real-time spatial memory tool.

## 5. Volumetric and Spatial Video

While Gaussian Splatting excels at capturing static environments, volumetric video is required to capture human performance and dynamic motion over time. This technology is critical for the "whole body" input modality central to the MOLTEN hackathon.

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Arcturus** | San Francisco, CA [cite: 49, 50] | Unverified | Cloudtree, Autodesk, Epic Games, a16z [cite: 16, 17] | Yes [cite: 16] | Yes (SDKs/Plugins for Engines) [cite: 17, 18] | Unverified | Unverified | Yes [cite: 51] |

### Academic & Technical Analysis
**Arcturus** is the premier software provider for volumetric video editing and streaming. Their flagship product, HoloSuite (comprising HoloEdit, HoloCompute, and HoloStream), solves the massive data storage and playback challenges associated with fully three-dimensional video [cite: 17, 51]. Backed by an $11M Series A that includes strategic investments from Epic Games and a16z [cite: 16, 17], Arcturus is deeply embedded in the spatial creation ecosystem. 

For the MOLTEN hackathon, Arcturus is highly relevant. They provide robust plugins for Unity and Unreal Engine [cite: 17, 18]. A student team tasked with creating a "whole body" authoring tool could utilize a volumetric capture setup (even a simplified multi-camera array), process the performance via Arcturus' tools, and stream the volumetric video directly into a WebXR or Vision Pro environment. Because volumetric video contains "nuanced human performance" [cite: 18], it aligns perfectly with the event's thesis that spatial creation should move away from keyboard and mouse inputs toward genuine physical presence.

## 6. AI Character Animation, Motion, Rigging, Avatars

A persistent spatial world is lifeless without dynamic, interactive entities. The authoring of non-player characters (NPCs) and player avatars has traditionally required arduous 2D keyframing and manual rigging. The new generation of AI tools automates these processes, allowing creators to drive characters using natural language, voice, and physical motion.

**CRITICAL ADVISORY:** Previous industry leader **Ready Player Me** must be excluded from hackathon integration. As of late 2025, Netflix acquired the company and has explicitly shut down public developer API services effective January 31, 2026 [cite: 52, 53]. 

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Inworld AI** | San Francisco, CA [cite: 54] | Unverified | a16z (implied portfolio ties) [cite: 23, 55] | Yes [cite: 55] | Yes (Realtime API, Router) [cite: 24] | Yes (Free start, growth plan) [cite: 24] | Yes (Supports Speedrun startups) [cite: 23] | Yes [cite: 54] |
| **Yellow** | Unverified | Unverified | a16z ($5M Seed) [cite: 8] | Yes [cite: 8] | Unverified | Unverified | Unverified | Unverified |
| **Kinetix** | EU/France (implied) [cite: 56, 57] | Unverified | Unverified | Unverified (noted by a16z) [cite: 57, 58] | Yes (Emote SDK/API) [cite: 28, 29] | Yes ($1M UGC Fund) [cite: 28] | Unverified | Unverified |

### Academic & Technical Analysis
**Inworld AI** is the strongest partner for the character interaction track. They provide a comprehensive API suite optimized for gaming, offering a Realtime API that handles orchestration between speech-to-text, large language models, and their proprietary, ultra-low latency TTS-2 (Text-to-Speech) model [cite: 23, 54]. Their infrastructure can process emotional intent and conversational context in real time [cite: 24]. For a hackathon, students could utilize the Meta Quest 3's microphone and hand tracking: the user physically points at an NPC, speaks a command, and the Inworld API processes the audio, generates an in-character response, and returns the audio to the headset in under 250 milliseconds [cite: 24, 54]. 

**Yellow**, led by CEO Mandeep Waraich and backed by a $5M seed round from a16z, focuses on 3D character creation through generative AI, tackling the notoriously difficult problem of maintaining clean topology during generation [cite: 8]. While highly relevant to the hackathon's thesis, comprehensive documentation regarding a public API is unverified, making them a better target for speaking engagements than API deployment.

**Kinetix** specializes in AI-driven 3D animation and user-generated emotes [cite: 28, 57]. They have actively launched a $1M AI-UGC fund to help developers integrate their emote technology via APIs into live games [cite: 28, 29]. For a "whole body" authoring tool, a student could capture real-world user movement, utilize the Kinetix SDK to translate that video/motion data directly into a rigged 3D animation [cite: 57, 58], and instantly apply it to an avatar within a Unity-based Vision Pro application.

## 7. AI Tooling inside Blender, Unity, Unreal, Houdini, and WebXR

To facilitate rapid prototyping in 24 hours, students need frameworks that bridge generative AI with established rendering engines and browser-based spatial computing (WebXR). The goal is to move the authoring process *into* the spatial device itself, rather than operating these engines solely on 2D desktop monitors.

| Company Name | Headquarters | LA Presence | Investors | a16z Backed? | Public API Usable in 24h? | Free/Student Tier | Hackathon History | Hiring? |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Spline** | San Francisco, CA [cite: 59, 60] | Unverified | Unverified | Unverified | Yes (Real-time API, Webhooks) [cite: 59, 60] | Yes (Free basic tier, $29/mo Pro) [cite: 60] | Unverified | Yes [cite: 59] |
| **Space** | San Francisco, CA [cite: 11] | Unverified | a16z Speedrun ($2.4M) [cite: 11] | Yes [cite: 11] | Yes (Filesystem streaming) [cite: 11] | Private Beta [cite: 11] | Built out of Founders Inc. [cite: 11] | Unverified |

### Academic & Technical Analysis
**Spline** has positioned itself as the accessible, collaborative alternative to heavy desktop engines like Unity and Blender [cite: 59, 61]. Crucially for the MOLTEN hackathon, Spline recently added comprehensive support for the Apple Vision Pro and Android spatial devices [cite: 59, 60]. They also introduced the "Omma" AI canvas, which allows users to generate interactive 3D motion designs via text prompts [cite: 60]. Because Spline offers a Real-time API and Webhooks, students can bridge Spline scenes with external data [cite: 59]. For example, a student could build an interface where body gestures (captured via device sensors) trigger Webhooks that dynamically alter variables within a live Spline 3D scene rendered in WebXR.

**Space**, an a16z Speedrun-backed startup ($2.4M pre-seed), addresses a critical infrastructure bottleneck in spatial creation: file size [cite: 11]. Spatial assets (meshes, high-res textures, volumetric videos) are notoriously large. Space provides a cloud filesystem that streams only the exact byte ranges requested by an application or AI agent, meaning terabytes of 3D data can be manipulated without local downloads [cite: 11]. If a hackathon team is building a spatial WebXR authoring tool that requires loading massive generative outputs from World Labs or Luma, integrating Space's filesystem would allow instant, zero-latency viewing inside the headset. 

## 8. Hackathon-Ready APIs: What Students Can Actually Ship Against in 24 Hours

The distinction between a closed SaaS platform (like Polycam or Nilo) and an open API is the determining factor for hackathon viability. The following platforms offer well-documented, low-latency APIs with accessible pricing structures that students can integrate within a 24-hour sprint.

### 1. World Labs (Marble World API)
*   **Documentation & Capabilities**: The World API transforms text, single images, panoramas, and video into fully navigable 3D environments (Gaussian splats and meshes) [cite: 5, 46]. 
*   **Hackathon Utility**: Students can programmatically send an image captured by the headset's camera and receive an explorable 3D world back. The API runs asynchronously and requires no proprietary tooling [cite: 5].
*   **Pricing**: Credit-based system. $1.00 USD yields 1,250 credits. Generating a world costs roughly $1.28 to $1.71, making it highly affordable for a few dozen test generations during a hackathon [cite: 22].

### 2. Inworld AI (Realtime API & Router)
*   **Documentation & Capabilities**: Inworld provides a unified API for NPC orchestration, featuring top-ranked TTS-2 (text-to-speech) with sub-250ms latency [cite: 23, 54]. Their system is explicitly optimized for gaming environments and handles conversational context and emotional steering natively [cite: 23, 24].
*   **Hackathon Utility**: Essential for adding interactive intelligence to the spatial creations. Students can bypass stringing together OpenAI and ElevenLabs by using Inworld's unified Router, reducing integration time [cite: 23, 24].
*   **Pricing**: A generous free start tier is available, with enterprise scaling driving costs down significantly. The Router itself is provided at no extra cost [cite: 24]. 

### 3. Luma AI (Ray 2 API & MCP)
*   **Documentation & Capabilities**: Luma offers APIs for 3D capture reconstruction and generative video. Their recent integration of the Model Context Protocol (MCP) server allows AI agents to interface directly with Luma's systems [cite: 26, 27].
*   **Hackathon Utility**: Students building "AI-assisted tools" could use Luma's MCP to create a local voice agent in Unity that automatically generates 3D models and inserts them into the scene based on verbal commands and spatial pointing [cite: 26, 27].
*   **Pricing**: They possess a strong history of supporting developers via API credits and licensing models [cite: 25, 36]. 

### 4. Spline (Real-Time API & Webhooks)
*   **Documentation & Capabilities**: Spline allows variables and triggers within its 3D canvas to be controlled externally via standard REST/Webhook protocols [cite: 59].
*   **Hackathon Utility**: Because Spline exports natively to Vision Pro and WebXR, students can use Spline as their rendering frontend. They can write custom Python or Node.js backends that process body-tracking data and push updates via the API to manipulate the 3D scene in real-time [cite: 15, 59]. 
*   **Pricing**: Free basic tier available; Pro starts at $29/month [cite: 60]. 

## 9. Realistic Speaker Asks with Proven Public Speaking History

To recruit high-level judges and speakers for MOLTEN, the organizing team should target individuals who have demonstrated a willingness to speak publicly about the intersection of AI, spatial computing, and human creativity.

1.  **Amit Jain (CEO, Luma AI)**
    *   **Background**: Jain led the integration of LiDAR into the iPhone and worked on Vision Pro passthrough at Apple before founding Luma AI [cite: 2, 62].
    *   **Evidence of Public Speaking**: Jain is a highly active public speaker. He has guest-lectured at Stanford University (CS153) [cite: 2], presented at the Web Summit Qatar [cite: 37], Advertising Week NY 2025 [cite: 1], and The AI Conference [cite: 3].
    *   **Ask Angle**: "The Evolution of Spatial Capture to Unified World Models."

2.  **Marguerite deCourcelle (CEO, Blockade Labs)**
    *   **Background**: Known as "Coin Artist," she bridges the worlds of fine art, generative AI, and virtual environments through Blockade Labs' Skybox AI [cite: 6].
    *   **Evidence of Public Speaking**: deCourcelle was a featured speaker at the GamesBeat Summit 2024 (panel: "AI and Games") [cite: 7, 63] and the VSMSummit23 [cite: 64]. She frequently appears on technical podcasts [cite: 6, 65].
    *   **Ask Angle**: "Building a Text-to-World Future in Spatial Environments."

3.  **Dr. Fei-Fei Li (Founder, World Labs)**
    *   **Background**: Former director of the Stanford AI Lab, pioneer of ImageNet, and now leader in "Spatial Intelligence" [cite: 4, 66].
    *   **Evidence of Public Speaking**: Dr. Li is a globally recognized speaker, frequently appearing on a16z podcasts [cite: 4, 67] and publishing thought leadership on spatial intelligence as AI's next frontier [cite: 66, 67]. 
    *   **Ask Angle**: "Spatial Intelligence: From Pixels to Navigable Worlds."

4.  **Mandeep Waraich (CEO, Yellow)**
    *   **Background**: Leads an a16z-backed team focusing on generative 3D characters, emphasizing clean topology and artist empowerment [cite: 8].
    *   **Evidence of Public Speaking**: While a newer founder, his deep academic partnerships (MIT, Oxford, Stanford) and a16z backing make him a prime candidate for technical, academic-leaning talks on 3D generation constraints [cite: 8].

## 10. Unverified Information and Strategic Caveats

While this report synthesizes the most current data up to late 2026, the following points remain unverified or require direct communication with the respective organizations:

*   **Los Angeles Physical Presence**: The vast majority of the top-tier 3D generative AI startups (Luma, World Labs, Polycam, Inworld, Arcturus) are headquartered in the San Francisco Bay Area [cite: 19, 23, 36, 39, 49]. Explicit, permanent physical offices in Los Angeles for these specific startups could not be definitively verified in the current data. However, given the proximity and the heavy media/entertainment footprint of spatial video, a16z partners and executives from these companies frequently travel to LA.
*   **Yellow's API & Headquarters**: While Yellow is prominently backed by a16z for 3D character generation [cite: 8], specific documentation regarding a public-facing developer API or their exact physical headquarters could not be verified. 
*   **Nilo Technologies' Extensibility**: Nilo is confirmed as an a16z Speedrun portfolio company building a browser-based 3D sandbox [cite: 10, 44]. However, it remains unverified if they expose a headless API that hackathon students could hook into to build custom body-input authoring tools [cite: 45]. They appear to be a closed consumer platform.
*   **Polycam's Programmatic API**: While Polycam offers robust capture tools, evidence of a public-facing API that allows developers to programmatically upload raw sensor data and retrieve Gaussian splats seamlessly via code (as opposed to using their proprietary app UI) remains unverified [cite: 21, 48]. 

**Conclusion**
The MOLTEN hackathon is perfectly timed. By October 2026, the infrastructure to support programmatic spatial creation will have moved from theoretical research into accessible, low-cost APIs. By securing a16z Speedrun as a primary sponsor and providing students with API credits for World Labs, Luma AI, and Inworld AI, MOLTEN will successfully demonstrate that the era of authoring 3D content with a 2D mouse is coming to an end.

**Sources:**
1. [advertisingweek.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG1HiGBlkcZJPqsCSgbKPiTZijpn-MXjlK2sOlTqZGKaYksiUtTV5yvIchk9IBbD2OlTHOnov_q16YjaNvcM2wnI9mwD3VKOikibbNDI944tl5gc0bCjwOQ8EeytIDDwKeVkiVDtn5AWpO0CY4hTSCJTRSjZtx2GWw=)
2. [youtube.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHlu6od8BXFgahSAgyh4eeSMyjsl6LfU9klIwGDmqS3bZghhKlOuKWwMK-gWUI_ilFkmM94I5sMwn9jzBCE2B2VZn26dVg5Jnvorkcb6CCjPmUf4jIEjNkqRqY7wTE1qj82)
3. [aiconference.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHn29rz9hEs3WYByl5rOiu9Hx5-AfVRR21Fhus6qGaJCmi-bpJTHK52D2-kwvdJqmZeM-qsr1h9-nXGjMrNLubcs-zd6fw0JvmT36dSs3y0lmn6qmr4HtCXb5CoQfEEp0pFjw==)
4. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFqXKgthtLTy77ZNlPule5qVYMhC0M1vVgI8rqHDTBV-q0GNYUcWpHgUBhQA28GqQC59V6SHyj8hkrwfBQgD1pQppCYLsdYtDBfejlf9yJ19NQFTFCkUG_MjegXgUV01B9D4bKXY0GRQPzUEcn5naGFwb0UeiPCIAo9u_QnBbYTdnNENT4MdQ==)
5. [worldlabs.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEelHdlyP-hgmhM4AwHzUtm0XiP7b5GmJbHfuMJ8FWkSHaVV278hQ1hzhhnzuk7dfdLYDy71LIG2PvC8M3bWcnczzw1mr5U0VI5Z3cGj9mp5TcCkyu_XhefsTbhsvhChsxP85Nm8qcb8-CPpVY=)
6. [youtube.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHGYvbutjz1WPyBepOWVVa7ZBuyTxdK56IkY6fbKUx1-jFPi4wESQ8SPRvOy9LBxlKvY8j3f3otQOgjUN8dfbB4_0XWadIomjFK3woXkqCGnYZhapfIL54pvbUcXDIcQLoI)
7. [gamesbeat.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG0Nei76anEpRv-py2v86v2806Yq-VNjJ2Kho9b7xvuEYkzFP5ObXiOlYuzZJfaZP6xYRKuyHVgSN54Rcq279TcGaMfgTXWOmNHIiUD7Tp6pq1Tu5r99B1d8OwRRkbSgrqmj0iuf8GBBcTwu0QbJDzW8rOtPJXOoUBxsE15Rx6bHBJMwEfvecKe8Jl5KLZ_y5Re1FGXtW4lTzg6-2PCmAs=)
8. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHslLRrLV-hm1klG5jehZIUco0XU9FHmYwKj43R5rUSAHQC3pBkvNwwyiR4_-08PK7czas_SLgORz1ecWjrx_IJfyb75lvb9s_uexHGmmn_8KqihQirZkSNMk4T4xhVT1Yg6ptMGOHMww==)
9. [facebook.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHUAebAKhXDBvuHSIIZgafz3UT9WtGkD_I1W1Z8KgdeCLKf4CedcHyjf_mwuRbrEru6tnQgPdzIxeoQhvrQI-gBbRSiB4fC-rjg50pwwWwHwPo_h8A7Kl8GCBmfwvu4ySrAAejNj0rdRMIKRvz0n4f5sPxIBXsSjo-wffMoni8OSvhksxMcNqqQCPtgaQajDuoj15UKOe9vLdudRRm2HHhqANM7Jo7Nr0ld2auv5l6XIVJWw9qb14lR7bdOJ83azGch)
10. [artificialintelligencemadesimple.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHAA816yDNZlXnssua8II6DAYJMzzVECvd_JQKSzPRi1qgQgdH85nnVBlc0ujAfNxMwJCs65arTkt3DerosKEAaGLf6FO1b7jYu9R3CC9z-KhnGUqd3j_x-jCqnnQgQs5RQZ9e1nXPLwwrYEOOLDop0bidEGWgT0PmoGpg_TkxO4ir2zdYC9fuTkQ==)
11. [sovereignmagazine.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQG65ZVfMNRiGR397_-lSuKaGYkEA02oMa-EHVb0p-W_jaEQy3nH0N-JcxCt3eWkmb5lMpgJhegiY2U4C3tuloYfoxbDn9R9q4noxFm5_4IPGIFpP2mkK2SizTB97fBhwPsQXR4NBakWMVUlNXSuFqUZsCf3IEfXg9saMgeSY9fDQdmanlv19ryi)
12. [dealroom.co](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGoxlMP3aaCfIVM-gKmlWq378lmn9n5a4MP9qXQFbwMPRFaa85tNm4LsZlgBdZeEOaZmkIxHyfo644juomfcL6iMD7ADaqSArUcctTOytXwtDtDL3_K11TG9UVNEwyeG5SLYNROm3DuVBnVtpaQKjskkrEJNMJ7bTwh7Hqc3UknOYY8qBwHzg4R_CUYINQ=)
13. [technologies.org](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFUsgGxEexCxP5Jz8bqIp5T67ROk-vbb8e0oReltgKqgNmk4XaEcj3JQhRWYCQlsdGO5NvBZIMt_e4HC2JsL6a5-c4eJbFnCaRsPASuZRig9GbTfO9JnV6_SgYGfDuNjnUNRxbSuRHVCG_XC9lKKLOQfQGaeJExxQkwt1VcOQKVgejtLIhxRCqrz8wv4NJkAixNoYEpRPyrcjqiJxbVwzAKtOkdsEwDeA==)
14. [caplight.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFXF8mCTNzwg2DJ7HwyBMwBVRhCpJ5dJ2qzk_pkyH7BSIZmcFZpq50LyA263So3MbRFxzBYR3qjTcv56tMLPCrm7iH5woXIxiDg-K8TvcHfU4d-AGwkolkAhmHaMg==)
15. [aicentralresources.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHIKh1NLrOSXtSrUJfmAHwUaNSXKZdZ1Z53jN58tr2DjoISyN7sbghnpZiLPWQ61-GGrGRqUFxXGmHqWenI-B4_LH2XRQZGNXe67RywhtUU5aaVcUOyFkwLnCMJaIN6PdA_PEsvRxUM048gsdaIETXx)
16. [dot.la](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEJDUrOLpgzoCjpmXtqjy7rvBNwFPMZkrDHUSoQvTmBV1y-tFz_wkkn0nTwbZ27CTN40F3edZTXH_CmPKhqlIPRUvex-mxGzUeSQELfUPpGXHQhy4kSKCTptv595aNuqFwPN3rJ2BUdZaC1k5I=)
17. [arcturus.studio](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFmGwpLIRs9fZtC1butSUGgQmyud1HphC_TnxNXt9brvBllwPvRUbHIWABG38ub85Zc_NuZ5xyXrUdq07R8vmpcNpB54QfclMAdho9kPDFGUrcc-W77yIh__wacnbCpPq5MK40khYclz-qIDTAuHWjzDc3EQMvhy-C16O74gmHmvXrxT--jXjTZeJixTQJY8wMv3v8m9H9iJNwx46EnmPb1uvbn0vs=)
18. [autodesk.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFXHak1plYPrUZHwcE0gqD7KXZ9Hs-j1uqYlZKV_rWRbP8ctEJMj3Fgm_frpeHY-OdlM00PLJcpRMyd2LdXdamXv2ixHzSUz6T-qON50ZFKprppWupkMNz1CN9HClpxKKAOvZRDxPbRLppbrPvtP6PLp4Hs3XlBMILks_LQM-k=)
19. [tracxn.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEUdeh0TDWjle6Ng0Eug22e9IbQm2ZAUppKFsn7f1aso7kojh9tLgmBXWxNke7NwKfMffIK4Mq1XF8kBgkxy0laQ9jD8oUvHAvIkqHhpQC8umX3KLoXkcCA0jBPCbqgWgtLt49QtOJnPv1eC1vmyVb-f35MaWIOXobsJq2XvSyj5Z-LpL6xJmT9oLA=)
20. [pulse2.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF7rWzW8fQ5xQr4DxDTkj7GKzozfFO3BZ_5Gcsvbwp9JORAtO9D1BsvY20s0CAWgArpvnkmXbna91eSR7tImk3qWlGaC8gZd_wJyyTNsC-yaTnGvduqmqMCaE6envDUE8hQqmNFJpc12-1aGiq-do_iq7206HcgysEGG4R6zFunUHlS)
21. [preqin.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEgMtxzxzJ32C6yjXjBt6xHQg1Pk09LOc4Nxhnm_ftw1hr5nQpAGT7QRk9a1QxekmJjHAlhJzWRq9MgKpWVL-NPIUOdRWxQZ3w6PN1DXplsu85LoCh0SuaKcwvk2Fc54DdsdwUwpAg7IjwEjaVaiQ==)
22. [worldlabs.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGxdlp_yWme2cjkKdRFs6aR33BxC0KHDfULlgzmZdgwpCJZg2AuvjizwcA-ADJg7_g83N45C8nK_5jnYdz6LRADY0Q2C0yteD8f4C_Wbf23r5lHF_5mnbikt_X4)
23. [inworld.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHGXOvFtTPtXaskL4gv0yyOAxSBwNPQIfSTfPD0AJ4gjJZmSdPrSKn2-QrdByuX7mrD0yEyp_Eex9zMLFVz_dpNhPwWxgjQRCJkjLLZgVbWu7pEZ1HaUj7XReIWVLC3)
24. [inworld.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHF7u1NVOg1E92JDsXBE-Pw6DyzbAJQ9aA9YCbpWTJZ5URTSAn8z7EsSZwvViP2_MD96hqmMtE5t-YoPVzDP4yIjcBDhj-mHDmBpaagwyYIXrEzqKGhEq0VnRF037ijfwph767GpnY=)
25. [ababnews.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGGpL1TZ6up8eJoPh8ncI9DsrGgjdV7LaeW6kPgSsmOebeY4zqkJXhcEIkCoo9byzl832neRj5Ryylf4yGKYn4ztS7kVKeAB3xzcDW71QW57wyp2v9COMGKx3AH1eLKEC3p8X_sm5bLxvW5MXpUnwlZSkABRg==)
26. [facebook.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHHgjFKVVpgG9NfZgIMvbQiQDTCj7Ck6muxxG8Myzfk-qS1Au8XYCrO4u3tTKs5SLsYY1BKV39JxJm5zkKE2TvaMcyM27RRSG51ZjwJc5PLJmpzLJlwX6FrnfiDghN-OpuI3yWr5ccsSgpwG7Ll5e4qDWFUsQjt0sji81iwCp_okMRyLe8L71ZTq2uc363_iuMocFoSUvTCQ1BMoasOTqzPOKYzxlla5ZKth2f0EIQQ6jsS0tDpNeHJWZuxZdQjhWqxv-FtGDcutWY=)
27. [techdogs.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE57XCn_lSx42ix3dH1lpEq4BXBPoZLH1cpTKvjgjZvmt6M8LcQ22sixhFHV7ZORE3p5DOzJBY5Ea3nylKaSWNtOMyKJFSp68ciPmSa4QkkvvtVe110QayeTX7Qo5lNaygg2bExIrGQA8vixSbENJu93kB9V0Df6qxidNLn4Bpx-Vfhri3L-0PI70-zjM31k9LPbcZdJ0iChwtYhH94sf0iX04RwR5HZxngXzr-jDWn5GulknhprWaoK60TddLeMzZ2BiIXG7hwfNpWaa9nA_uy)
28. [facebook.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGCW0C-aojXpqNVPAqJ2LamCwHF5bI6eU4HrBQEqnPqVChOSWU_l9ntJg6awvu_DTK0QT8yrKOrsT3MkBvbvg6Z-jJXFaAiuirEjRzwRZ0Nq1n1n_9AinUrpcAaEmHPmEzXZwC8JKj8CXmxRxjGXVofE4CD0Y8T88-RvkVLw_6hk2hVWm-z_dlaGNFHBcyTH4m7GTRhke-JRvM2jo1I9MpDHZu3pa8bSVzSL9WN1jQW_KUMERRgxf-aHbsdz_B_2hoVWRA=)
29. [pocketgamer.biz](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFlYv7DY5iXhBeIKUZoAHptRg4UqmtvkjtBVZfg7mM3y3DyeYQY4FqZC-nziosE5aN5ghomUoAqxXdlvD1Mtyebs9A_ZkkJMnJmHrYltTuKklrbxcOlT8VhMxwj3d5e8e8=)
30. [pitchbook.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEXave9onhSJY9h_FYSKRPcbxm8NWxELPp-qmZ6QmPvQFbkKCyJo1Ow-WUNy6qgRSjuOFTAxiDh-aseR1Sv5ARy7m4C3sSWF9pe-QQs94h4RyqubIDAgT5W4d-U4-rOg3C2hjs2Vyg=)
31. [substack.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE5ABe8EkptFeu5uWCb2FU44rHRxZ8oaBAQc6ZiUFcOiQ23x6RSA0W4JdaKJh81XBKyshBMNTCKyJUSEM4LFKUJypTr1rkE7idnKrglsTkw7BGtm6DswB61XupTGYXiPmnXD49KduHZhp617Ft5B3w_7Iz0D0hqopr5bw==)
32. [analyticsinsight.net](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEJhTUP4Hjd5yR6LFiFb123wd4S9ufq310EKczEbYp5w1nsfdX4zkxuUGTw0qPV341BV0XVTYcf7ZIgcvsSP3XPu7TX916eLlOLkSICWidGiy5L9mAI6HAA6zzX4nKHVpfLLoa-I8QNUWjYj3_AVmUWn6G8Vm5GSC12b3CBTq4YdXGtH0-R)
33. [employbl.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHHBUgZBgqXv5F4ZOOe-dBkQXJ9_r0Qxyl6msNKkGACgDG1bzg2fYcwAIRRiUCTFOTDBib3soPG_zG9p6GrSZqza08Tk7stRp084yKBGy1kgL5zn2wMJEclfworKSyncitA5XS7IwcX3FIbAZ696apkCIc=)
34. [dealroom.co](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEzD_Jeu4Td_IkWi1uKQktmnnJiHj4Hn0V4UB-8qXTunnrKv9HnKcPJZxtJ6tBvo4R8ubKwFnmxnMFNwRdXizP5csk6tGI4J73m5ZoVsHEa2Anb0uERorg3UOoX84B_MNGhm2ZQcbbPDFKskc7MjaaqCHPrWlys)
35. [scribd.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQERJvrfjc8jBGpkKkvSt0xXnoout5AVuxWtZqa99Ysr4N8-ouFCc0wVCn5SCqRAhgD275rzAroBWvLnoe2J6sUHNPr-0BUJ-41i61Y26UpdGrirq3QH4Co5GGGgT5eiT2rb5UOJ1UKHg58aYqWz9gH-pVc=)
36. [startupfortune.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHznul-EaSI44NPJiE_RLy9QvNmFAf2JKKgo-iC8B19eZcmnFdkY98APKdnUvUDryDbM_PXBdqLj7lxbIvsMUScuQcHfKGFXfleIuhhyUG6y1KPMEby9C8JiQ==)
37. [websummit.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGJxxafHNCdKbnj3tbswW_2pBiDPOghVbydBUDZLUz_pE-3VvHeaBdoEXwtGdUANBJim78mH0MPW6gbj9tOYoPImoAdmtaS44raO6sCxWItKO_ek4XlF55T_lHpe8OX6jKAuc6ia37n46ZLJd6Wmx9XGMTlvcLBL9Sj1guQyyD30FbTY68-UayGpCDW50ObzMXN)
38. [gdconf.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF53RWbHnanFR4iW3XD3NSxXIZH_vxq26bQ8noLqihvaKI2LTuIAlWu5FHl_62ywFHmMM0rms0duFLrgFJXK0zjJ02yEJzJDNrl4nhbGOQeee7840T1iM8=)
39. [worldlabs.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHsMqqhdJtfFttEHcWPbpF51qLeuYVDnRsXUkffsLOwaXBN0yoWKHGU-iUiJWTKYvqTREu-iHo_1fy-LeeGfR3rSy41-h48RPbcQynbS3Hy)
40. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFBPH9_VVtjapnXVFKjwRaFYc1DSYiibzhtxkdq-O4it1du0DkiXBK1IppiqQ9Cz85nnQzRJvWL_nHgN14RY7pH4GsGazlHGKx6IvMxQ7s3vw9j6MOXxGevXtTNDCWI_sZqmGoVihw9DUyJ4Qg=)
41. [tracxn.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH_JTptIy9fkSXgHj5I-iPhQJTTjLVcwGT9MOwGVoeoWlPV1Juu-u56KpIDZuxifZbreXSmr2NYkbepKvhBymxXRUrjqpGOApWMf75puApOb743UZROmn8ACQEJyJZ4cijJdq04Xw-jiwPRFGNPnFow8BHPfLc8g9TvVjmU2enYGyuKWihvpObocuVn9_EGysw=)
42. [slashdot.org](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFq2UNAsoWJ6wtcq5fp1puKdan3uLxwoe4H3Wt4RoxQCOcsJzR6-6_gxL1pdr8wX2n5s1NbO9PJ1K5BkK0kzSfHqB8ZsvrvjKASJrztEmkBwXnPKiI88g-MPq4bz8yhqL9cCXO3bdt2CoMVyCqmoYK02fA=)
43. [blendbox.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEgK2Tsra_9w09AgcxsSEO9r7oKTFpQKhvIyRbJd3vU0v0uHF-vJQgxLhVGTAxpoRZAWDIuLDD20nhs8Gd3-y9gQEe2_Pf_-azTBEEF1sz5Z3UnLoWeaYgMn_MY8lj7)
44. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEYwiTLyLVhnpeGVfTww2rFtQwFNgQfKpd1M1ysFavVa1xgxt-rTFqA8FSRgTM4ln329oOI5I0F0e3zHWcfocTFwP51Pks83RuIYuH9M4YIj1lKGCzDyhPmmaTklBnP8qKPibkqP88mMV3ijQ==)
45. [startupintros.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQH-vB1nSrjYm-WAs26UwMaXLyt96OfakI7DYrwtlRROMIzaQny7C8RKgASE0emb7AUv5_qKG16TVdIT19menifd2OGCCi1wYQIJqLS9BYSkaiT1C_NOy242ug==)
46. [worldlabs.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFUNaFt62WMmmgNqytVlAdow5VOySJKiP0TQVAzLXN0ym8t5Pcv9KXvECbXXvLKSjbjILEHAWoG8tcclW6oNMzBllVGBYyEGsxDDJrxn1OWcyoJEfXKXpvRrb7nJlTTddqw8Q==)
47. [ascendion.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHrKlFNA0YP1RqbF9UCE2MraqTpHpprRkC3hy8EpoqfJdDfXbUJ2246XarRhzyltndSnyvOkXCexig_dxzGQQPDLu7-FdrBWVQBZjTY_4tNHz3MRjrakQiKWoQOtx-A0DT9otklPQQnGy59ScSyBw-dMekx_XT-iFOkPaHtYMMOPlVANJ23lga0m1rNpKOPqfW3-ZzbJLFZ)
48. [startupintros.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHRIFM7qLwIkjbNu_FrycXol2uEbZxzeDhwqKW9fpn72aUSRu1WwIsZa2lvDM9el-Qf2-u-7OSwzXNoYyDTzlC_gbwJh8y6ianmRXfTW1r_GWXvwIBBPAXEKD-5OQ==)
49. [ldv.co](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEt3kUhY6HTe3J-HId7xr_9LxRm24YpJBFcRbzWZb4FrmZnzSm_2ezW2PIX8N2C0U0beY2bihoXB7FwU-RhdGNp2RzMO-2b6o6bQU4LStb2Pg==)
50. [finsmes.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFHr89NhKfnmQ1j3q4qj4O6WMRiqyoE2XUzXSFGcoZ3Ph8cp8wm5v64T2uHb8Ha0C34zk98arcnG-eX9rf56ft9eAadxJ5T96htawOAIaWQptIJBC1wt3icdGigrhsxh8mF9NklFzpSxm-nNt6hhRqxvTAeHom3Jix7alUcbCPI)
51. [roadtovr.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHZvyz_ORf4-ME1fyq23aOBjk2qXi8zYru1RjFe2rhI9Xaf-HhAoGbIDrIObfcoXd1Vy9nSpPse76Z4LZOrNDDQ8wwEVTHSsOAvCz1CtU7dQwBpPYro1ha5-XNC7DXtrw03PH2k0WIoXbCrx5bYxduWrKdh9W2D0ft1ddBnnA3O)
52. [rootdata.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFfV5ZjIxfOZIfi2Nxnnl4al2n7QVzF68U9jfoxFC-W4u-dWizGrmpFQME4SATB2xnIvFUflsnA1i4HEsAI2rkgpHVnV99TzkTaSJFZ5_dgXRtUFjIH45VsFe8=)
53. [wikipedia.org](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGh2Wlq1Veo6pWfo42Q9QGxpAxY4DmgSE_5WHMwFPvsZLn0Y17XY5hck31SyP7fzS8UK8w_-6XA-bjli6MtYwZRZjP9a7dzI-IuZcevXGjNj2OohY8xcwJ0qdpoCOziqCX2tpE=)
54. [substack.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEeb3BmVliA2xUroCp9aRdDUQkyRh_Jp4O4NDYgoKRxQJiYAR9GC-5AJtQlHbC1tO-FSQ_HMGsUjhOgkAtRBFCeQPwqjdTA6Nw6hHCg4XQK5G1JpaY0vbgV2azFe1qUqQFL_WYNQjLh)
55. [substack.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFukUZgncDLQfBUCiIY1ddSpgen04zi2Mur7_0hnYhpc6CHffE-F1u1KJb6gJc7FgDCMtVmocwknOKT2NyvltFmsk6jHDNPpWEXpUfP6WAoQP-JQmYxut9e5FC-hNAcUVhaGJnRFxVkxzhKIj9KrL03tEo=)
56. [engr-sng.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHKimYWOLcF4UE6CoPtd5T1xSFcBFC-1FEqtaCCc6sQHl3Fduf5ZLaM3f3uJqyBeu2evYq0fxEomk_MdQpohMfeF2tZVOmvw7VzedNOJF87Vm8eAubdDrbJpvd3YKgQE62EwKt7)
57. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGHi5_WUMlgDLu7zRIzAtETfjP-EA1O_CpxLxjHHVbR7O9-JYo7PIjh4Pcsw1fcmHAAzDouyVH7qDzaJxpGmBZSskgA452AtP3QF3UdDv0xgzQM5VrAZAIFPLi1FvXHd9R77hnKJ6bDsF-mKEGwPw4tV8Dh0n-9IsVgPdCRJv8l0KGVFTK2jBenwQ==)
58. [a16z.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHU_Y-8JwKXRgxnHs9AaQIrnxjf98C_hBd4pvaUc5-N9VyXzMU6K77PX59vdeQUNsVmVUd2moWP5mCCmsErLTuTDslAPyAXmLkZeYGeaV4Q2VBsvmesFSVS5EetjFuV4XeoWc1Zl9Lk-pHXJJms)
59. [businesswire.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFvVXNPZXGvt9znLlgAD5HXCNOFqUt8XhUPVcam609Ue5bpiL_UG-vtb6sURfvZPbQK-5kAcpFhqVBD2DlofE3cfgFm4Ku5zkl71WiJLX2AxIIZvxDc-SUKUYPzIMnbvelisoTMr9kR50ZIhL3kuLOadibYeSce2R-MwgyYLa5Mjq9s8ykGfiv-CkaQf9uSnUAQuPHt-ioDPaU-jcmRbsfq2aqdZGm8kSm67FxqjEAho35sI-qFoRT1nMQCBWfUhvcgb0HTxKB0Tkavw-Ml0RmWGuv0FYxQVpK-2A==)
60. [businesswire.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFwb38iPHdCErD8fmJkdcLLtyT24CzDNLbH9AtWeH6ARH56lKWW81I4SB7l_PmZDKTZYkZSnppSu3aIHEBXy9zcv-h7WlVlKEzQ2AH4NcaftD3ihL8bKrgSlKdqEzPD_Mwjp9cS5cCiOISBwBuiJJwQ5zE_bvHLTm5aHkMm8jALKSHRuJwzW0MNbn4H4-J5faVKMMoS93L_Ttbao9GXRBJN9mZzQicgLbekXK0PXcJY)
61. [unity.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEPzNFqTFHFDQrgUqARufkGG_cp6Ac50FCV98e0bcDEeFcFZoqB5h1u-aNz1k4isJ8ilnzLWobUDG933QrjV3Y5VVzrHNHem4cS_2m385yN_GFvw_-70Hx3hclWXCVNY9Dyckt427eQeGsjUg==)
62. [montgomerysummit.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF_ii80tUDgBzbVl1SxQVWcoit5s29kTlhIWLgB5FxMFY_vCzlWgh834DMH8GamIzeuzjUr5N_IVQO5FjLgeKSpi3ASb5vfQ-vXDXT3WN2uZO8ZyfqT2HE5gQD9NoYDMMDVo_mHccQ=)
63. [kowatek.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEMl8bV1WHEVtnYREHFLA_my8LGhDeZf4znZjsiqd3iep2DD_nTpZ2LbHqGjyNYHD9YaLEtkJc8CtDgqPPa0j-GjJ2qVFvD6Awb6BHwYXqxJQQ9Dm8r0_QK9PQq6jf57yyx9ERIrCcRD_khUKR9C6EWt4kcKIRf0qj04sTS2kCh34H29YEf5d-Vc4U5MNg9uX2tK6JQzXxrJjw1vGuaZhuhsTwhP9UpkIznMROb8rBg3x_Bos0k68LNHP-N5LYlXQekYCteVFneqZkkgtiN-mpleg==)
64. [hci.social](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFnh1BSJPOktJac5u7RwFbDCqsSWbDlvlCKpfzOwXXXsPWKA-Efpj6JqsnMANlb1FeaQeiXrExXryc9SAGzF1vt9TJAKaIViaTiw1ZkQkK1h-I=)
65. [goodpods.com](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFu93BdRZ5aCSeu0XYeSJfDzrR1S98L45V5LLbS7ZjZJM9rYxOr6Q8dwAfaDDzu-EFDPnJASqTiFmxcmOfehyZXOAtZEyNDj_y6f92MTyMXr2mp6hZN04UgKHj22VbOOG2Q7n1FbItZ1wfamIAV-9C2Jka81K_M9-5cE5EIie34RSD6l27mWNP4-hzb4SCO_tw0qLCSEpQZhOSr7GR6R5gjkdl2dSpxGE22W_FtQAimNFqYIgexrNXwEevtV34w3x0=)
66. [gigazine.net](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFuCfl5odhDr9ySF-9Hh3Cow-n1BTp7CO80io0N7jYK8ub0F-Za3oyHEHgJay2nysh4-BgSUfpuym5zZ3WxfU5Y6jz-mzVKSqsIAiD9pl3uSV9DLw3-ZbIApWLqk2PHrllONbTAZRPgKpIv4hGBdTkT7ulpzzY5lq8nT1S-v9g=)
67. [worldlabs.ai](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHD0O1lbI_N53HER5pKGtvw4afpRUmXx8ZRRBtMRNGScDMZX6lZG1huUMlBwnpO0t1cGnEQHNJWEoc-Biu8O4s568WTwtL8LooEdr7LpWHxAYkV4w==)
