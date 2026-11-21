# Awesome-Character-Animation-Motion-Optimization

# Top Character Animation & Motion Optimization Ecosystem

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

- **[Mixamo (Adobe)](https://mixamo.com)**  
  Web-based automatic 3D humanoid character rigging service and extensive library of motion-captured animations exportable in FBX and Collada formats.

- **[DeepMotion (Animate 3D / SayMotion)](https://deepmotion.com)**  
  Cloud AI markerless motion capture and text-to-3D animation platform featuring physics-based foot locking, hand/face tracking, and FBX/BVH/GLB export.

- **[Move.ai](https://move.ai)**  
  Cloud markerless motion capture platform using computer vision and multi-camera or single-camera video to extract high-fidelity 3D skeletal animation.

- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  
  Cloud AI VFX and animation platform that automatically detects actors in live-action footage, captures motion/lighting, and replaces them with rigged CG characters.

- **[Plask](https://plask.ai)**  
  Browser-based AI motion capture and keyframe animation studio allowing creators to extract 3D skeletal poses from video and edit curves directly in the web.

- **[Rokoko Studio & Rokoko Vision](https://rokoko.com)**  
  Motion capture software suite and cloud AI video-to-animation tool supporting smartsuit sensor fusion, live streaming to Blender/Unreal/Unity, and motion cleanup.

- **[ActorCore (Reallusion)](https://reallusion.com)**  
  Cloud library of AAA 3D motion-captured animations and rigged digital humans with interactive browser preview and multi-engine retargeting.

- **[Kinetix](https://kinetix.tech)**  
  AI-powered 3D animation and emote generation platform transforming user-uploaded videos into game-ready avatar animations via cloud APIs and SDKs.

- **[Cascadeur (Physics-Assisted Animation & Cloud Tools)](https://cascadeur.com)**  
  Keyframed 3D animation software utilizing AI-assisted secondary motion, center-of-mass trajectory optimization, and angular momentum physics.

- **[Anyworld Cloud](https://anyworld.ai)**  
  Cloud-based AI 3D character creation, animation, and interactive world-building platform streamlining rigged asset generation for games and virtual environments.


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
