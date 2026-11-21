# Awesome-Character-Animation-Motion-Optimization

## Top Character Animation & Motion Optimization Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on AI Motion Capture, Skeletal Rigging, Physics-Based Motion Optimization, Pose Estimation & 3D Character Animation*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Character Animation & Motion Optimization**. These tools capture, rig, retarget, clean, optimize, synthesize, and simulate 3D skeletal animations and human motion from monocular video, multi-camera setups, text prompts, and physics engines across game engines, VFX pipelines, and robotics/biomechanics workflows.



**Examples** include Mixamo, ActorCore, Plask, DeepMotion, Rokoko Studio, Kinetix, Move.ai, Cascadeur Cloud, Wonder Dynamics, Anyworld Cloud, and tejashmakwana/motionmaxxing (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for motion optimization & skeletal animation (`tejashmakwana/motionmaxxing`, `Blender`, `Rigify`, `Auto-Rig Pro alternatives`), markerless video-to-3D motion capture (`MediaPipe`, `OpenPose`, `MMPose`, `WHAM`, `4D-Humans`), text-to-motion synthesis (`MotionDiffuse`, `MDM`), and real-time character physics (`ozz-animation`, `OpenSim`) — ideal for 3D animators, game developers, technical artists, VFX pipelines, and AI motion researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Paid Price | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Mixamo (Adobe)](https://mixamo.com)** | **Valuation: ~$160B+** (Adobe Market Cap; TTM Revenue ~$25.97B) | Free utility ($0 / included with Adobe ecosystem) | **Free forever with Adobe ID**; unlimited auto-rigs and downloads; limited to humanoid bipedal meshes, stores only the single most recently uploaded asset, raw asset file redistribution prohibited. | Web-based automatic 3D humanoid character rigging service and extensive library of motion-captured animations exportable in FBX and Collada formats. |
| **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)** | **Valuation: ~$52B+** (Autodesk Market Cap; TTM Revenue ~$7.2B) | Lite: **$10/mo** (billed monthly) or **$7/mo** (billed annually) | **Free tier forever**; 300 credits/mo, 720p maximum export resolution, watermarked renders, 1 GB storage, 100 MB max video upload, 1-person MoCap, and up to 3 custom character uploads. | Cloud AI VFX and animation platform that automatically detects actors in live-action footage, captures motion/lighting, and replaces them with rigged CG characters. |
| **[Rokoko Studio & Rokoko Vision](https://rokoko.com)** | **Valuation: ~$80M** (Series A extension post-money; ~$50M–$100M est.) | Plus: **$24/mo** (billed annually) or **$29/mo** (billed monthly) | **Starter plan free forever**; 30 seconds/month of Rokoko Vision AI video processing (single-cam), unlimited text-to-motion generation prompts, 5 text-to-motion imports into Studio/month, unlimited `.FBX` export, 1-month cloud asset history; live-streaming excluded. | Motion capture software suite and cloud AI video-to-animation tool supporting smartsuit sensor fusion, live streaming to Blender/Unreal/Unity, and motion cleanup. |
| **[Kinetix](https://kinetix.tech)** | **Valuation: ~$50M–$75M** ($12.5M venture funding raised; acquired by Runway) | Custom developer SDK / Partner API pricing | **Developer sandbox & trial key access** (or partner integration via Mixamo/Unity Muse); free developer test allocations typically capped at 1 seat, small sandbox emote generation budgets / 3 test projects before custom commercial deployment. | AI-powered 3D animation and emote generation platform transforming user-uploaded videos into game-ready avatar animations via cloud APIs and SDKs. |
| **[Cascadeur](https://cascadeur.com)** | **Valuation: ~$30M–$50M est.** (Nekki gaming revenue; $1.5M+ standalone AI dev budget) | Indie: **$19/mo** (or **$8/mo** billed annually at $96/yr) | **Free tier forever**; full access to core animation, AutoPhysics, and rigging tools for 1 user, strictly non-commercial/personal/learning use, export limited to proprietary `.casc` format only (no FBX/USD/DAE export). | Keyframed 3D animation software utilizing AI-assisted secondary motion, center-of-mass trajectory optimization, and angular momentum physics. |
| **[ActorCore (Reallusion)](https://reallusion.com)** | **Valuation: ~$20M–$30M est.** (Reallusion TPEx: 6882; TTM Revenue ~NT$221M / ~$7M USD) | Motion Subscription: **$29/mo** (or $1.50–$12.00 per motion a la carte) | **Free forever account**; includes complimentary starter selection of 30+ free core 3D animations and starter rigged human models, plus free use of the AccuRIG auto-rigging utility; access to remainder of 5,000+ library requires paid downloads. | Cloud library of AAA 3D motion-captured animations and rigged digital humans with interactive browser preview and multi-engine retargeting. |
| **[Anything World](https://anyworld.ai)** | **Valuation: ~$15M–$25M est.** ($9M+ venture funding raised from Warner Music / Acrew) | Nano: **$30/mo** (or Micro: $60/mo) | **Individual tier free forever**; 15 credits/mo, 1 full model download/mo, 200 library API calls/mo; limited to personal/student use (revenue under $100k) with attribution required. | Cloud-based AI 3D character creation, animation, and interactive world-building platform streamlining rigged asset generation for games and virtual environments. |
| **[Move.ai](https://move.ai)** | **Valuation: ~$10M–$15M est.** ($17.4M raised; core assets acquired by Oxford Metrics for £525k–£725k) | Starter: **$18/mo** (or **$15/mo** billed annually) | **Free plan**; includes a one-time allocation of 30 non-expiring credits upon signup, max 30 seconds per video clip, Gen 1 processing; no monthly credit refresh on free plan without paid subscription. | Cloud markerless motion capture platform using computer vision and multi-camera or single-camera video to extract high-fidelity 3D skeletal animation. |
| **[DeepMotion (Animate 3D / SayMotion)](https://deepmotion.com)** | **Valuation: ~$8M–$12M est.** ($8.7M–$10M funding raised; estimated revenue <$2M) | Starter: **$15/mo** (or **$9/mo** billed annually) | **Freemium plan free forever**; 60 seconds/month (60 credits/mo for body tracking; hand/face cost +0.5 cred/sec each), maximum 10 seconds per clip, personal non-commercial use only. | Cloud AI markerless motion capture and text-to-3D animation platform featuring physics-based foot locking, hand/face tracking, and FBX/BVH/GLB export. |
| **[Plask](https://plask.ai)** | **Valuation: ~$5M–$8M est.** ($2.56M Pre-Series A/Seed funding raised from Smilegate / Naver) | Standard: **$18/mo** (billed annually) or **$50/mo** Pro | **Freemium plan free forever**; 15 seconds of AI motion capture processing per day, 1 GB storage, standard FBX/GLB/BVH export, personal non-commercial use only. | Browser-based AI motion capture and keyframe animation studio allowing creators to extract 3D skeletal poses from video and edit curves directly in the web. |





## Open-Source GitHub Projects



- **[tejashmakwana/motionmaxxing](https://github.com)**  

  Open-source character animation and motion optimization toolkit engineered to refine, smooth, and enhance skeletal motion data and animation workflows.



- **[Blender & Rigify (`blender/blender`)](https://github.com)**  

  Flagship cross-platform open-source 3D creation suite featuring non-linear animation (NLA), graph-editor curve optimization, Inverse Kinematics (IK), and modular `Rigify` auto-rigging.



- **[WHAM (`yohanshin/WHAM`)](https://github.com)**  

  State-of-the-art open-source World-grounded Human Motion recovery framework that reconstructs accurate 3D human pose and global trajectory from monocular video.



- **[4D-Humans (`shubham-goel/4D-Humans`)](https://github.com)**  

  Open-source transformer-based 3D human mesh recovery and tracking system (HMR 2.0) extracting SMPL body pose and shape directly from video frames.



- **[MMPose (`open-mmlab/mmpose`)](https://github.com)**  

  Comprehensive open-source PyTorch toolbox for 2D/3D human pose estimation, whole-body hand/face keypoint tracking, and multi-person motion capture pipelines.



- **[Google MediaPipe (`google-ai-edge/mediapipe`)](https://github.com)**  

  Fast, cross-platform open-source ML framework providing real-time 3D body pose, hand articulation, and facial blendshape tracking on CPU/GPU devices.



- **[OpenPose (`CMU-Perceptual-Computing-Lab/openpose`)](https://github.com)**  

  Pioneering open-source real-time multi-person 2D/3D body, foot, hand, and facial keypoint detection library for markerless motion capture.



- **[Motion Diffusion Model — MDM (`GuyTevet/motion-diffusion-model`)](https://github.com)**  

  Foundational open-source diffusion model for generating, editing, and in-betweening 3D human skeletal motion sequences from text prompts and keyframe constraints.



- **[ozz-animation (`guillaumeblanc/ozz-animation`)](https://github.com)**  

  High-performance open-source C++ runtime skeletal animation library and offline optimization toolset featuring cache-friendly compression, blending, and two-bone/aim IK.



- **[Rokoko Studio Live for Blender (`Rokoko/rokoko-studio-live-blender`)](https://github.com)**  

  Open-source Blender add-on for real-time motion capture streaming, one-click bone retargeting across arbitrary armatures, and animation cleanup.



- **[FreeMoCap (`freemocap/freemocap`)](https://github.com)**  

  Open-source, hardware-agnostic markerless motion capture system designed to record, triangulate, and export calibrated 3D skeletal animations directly to Blender.



### Additional Strong Open-Source Options



- **[Easymocap (`zju3dv/EasyMocap`)](https://github.com)** for open-source multi-view and monocular markerless human motion capture and SMPL parameter reconstruction.

- **[ProtoMotions / IsaacGymEnvs (`NVlabs/ProtoMotions`)](https://github.com)** for physics-based character animation and reinforcement-learning motion imitation controllers.

- **[MakeHuman (`makehumancommunity/makehuman`)](https://github.com)** and **[MPFB2](https://github.com)** for open-source parametric 3D humanoid generation with Mixamo- and Rigify-compatible skeletons.

- **[BVH / SMPL Retargeting Tools (`fairmotion` by Meta)](https://github.com)** for Python-based 3D motion data loading, quaternion smoothing, foot-contact optimization, and visualization.

- **[OpenSim (`opensim-org/opensim-core`)](https://github.com)** for open-source musculoskeletal modeling, inverse kinematics, and biomechanical motion optimization.



**Frameworks for building custom systems**: Combine **WHAM** or **FreeMoCap** for markerless video-to-3D motion capture, **fairmotion** or **tejashmakwana/motionmaxxing** for curve smoothing and foot-sliding cleanup, and **Blender (Rigify)** or **ozz-animation** for game-engine retargeting and runtime playback.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Many AI pose-estimation and motion-generation models (`WHAM`, `4D-Humans`, `MDM`) rely on SMPL body model weights, which require separate non-commercial academic or commercial licensing from the Max Planck Institute.

- Verify coordinate systems (Y-up vs. Z-up), bone roll conventions, and FPS sampling rates when retargeting BVH/FBX animations across Blender, Unreal Engine, Unity, and Godot.



---



**Made for 3D animators, game developers, technical artists, VFX pipelines, and AI motion researchers.**  

Let's make character animation and motion optimization more open, lifelike, and accessible.
