# Extended Reality (XR)

**Last verified: 12 September 2026** — Resources and documentation links; sample projects were not build-tested.

**Versions checked:** Engine: not verified; SDK/packages: not verified; device OS/runtime: not verified. No headset or mobile-device compatibility testing was performed.

[Home](README.md) · [Unity](Unity.md) · [Other engines](GameDev.md)

**Start:** Unity basics, C#, transforms, physics. Choose VR, AR, or MR based on available hardware.

## 1. Unity VR

| Order | Topics | Resources |
| --- | --- | --- |
| 1 | OpenXR, tracking, input | [Khronos OpenXR](https://www.khronos.org/openxr/) · [Unity OpenXR Plugin](https://docs.unity3d.com/Packages/com.unity.xr.openxr@latest/) |
| 2 | XR Origin, grab, ray, socket, locomotion | [XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@latest/) |
| 3 | Guided first project | [Valem — Unity 6 VR beginner course](https://www.youtube.com/watch?v=H8dWVlZKQu4) |
| 4 | Hand tracking | [Unity XR Hands](https://docs.unity3d.com/Packages/com.unity.xr.hands@latest/) |
| 5 | Rendering and profiling | [Meta — Unity OpenXR settings](https://developers.meta.com/horizon/documentation/unity/unity-openxr-settings/) · [Unity Profiler](https://docs.unity3d.com/Manual/Profiler.html) |

**Build:** Grab-and-place task → small VR puzzle. Test comfort, reset, and performance on a headset.

## 2. Mobile AR

| Order | Topics | Resources |
| --- | --- | --- |
| 1 | Setup, planes, raycasts, anchors | [AR Foundation docs](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@latest/) |
| 2 | Placement, tracking, occlusion | [Unity AR Foundation samples](https://github.com/Unity-Technologies/arfoundation-samples) |
| 3 | Device support and platform features | [Google ARCore](https://developers.google.com/ar) · [Apple ARKit](https://developer.apple.com/augmented-reality/arkit/) |
| 4 | Video walkthroughs | [Dilmer Valecillos / Learn XR — YouTube](https://www.youtube.com/@dilmerv) |

**Build:** Place, rotate, and reset an object on a surface. Test on a supported phone.

## 3. Mixed reality

| Topic | Resources |
| --- | --- |
| Room data and placement | [Meta MRUK — scene data](https://developers.meta.com/horizon/documentation/unity/unity-mr-utility-kit-manage-scene-data/) |
| Unity MR walkthroughs | [Dilmer Valecillos — YouTube](https://www.youtube.com/@dilmerv) |
| visionOS, SwiftUI, RealityKit | [Apple visionOS](https://developer.apple.com/visionos/) |

**Build:** A tabletop activity. Handle missing room data and tracking loss.

## 4. Other XR routes — optional

| Route | Resources |
| --- | --- |
| Godot XR | [Official XR guide and XR Tools](https://docs.godotengine.org/en/stable/tutorials/xr/index.html) |
| WebXR | [MDN WebXR](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API) · [Three.js XR examples](https://threejs.org/examples/?q=webxr) |

**Build:** One interaction on a named device/browser; provide a desktop fallback for WebXR.

## Demo checklist

- [ ] Engine, package, device, and runtime versions recorded.
- [ ] Supported input, readable UI, reset, and permission handling tested.
- [ ] Comfort and performance checked on the target device.
- [ ] Build, video, source, and credits ready for an NTL review or portfolio.

Simulation supports development; it does not replace device testing. Package docs and tutorials must match your installed versions.
