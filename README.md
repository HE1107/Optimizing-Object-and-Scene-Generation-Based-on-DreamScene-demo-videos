# Optimizing-Object-and-Scene-Generation-Based-on-DreamScene-demo-videos
Demo videos for paper: Optimizing Object and Scene Generation Based on DreamScene

# 🧠 Optimizing Object and Scene Generation Based on DreamScene

This project enhances the [DreamScene](https://github.com/DreamScene-Project/DreamScene) framework by integrating **3D Gaussian Splatting** with **NeRF supervision** to improve quality and consistency in text-to-3D object and scene generation. We use a PixelNeRF-based encoder for parameter initialization and employ NeRF-rendered RGB, depth, and weight for loss supervision.

---

## 📌 Key Features

- ✅ Combines **3D Gaussian Splatting** with **PixelNeRF-based NeRF supervision**
- ✅ Uses NeRF to generate RGB, depth, and opacity supervision signals
- ✅ Initializes Gaussian parameters from PixelNeRFNet encodings
- ✅ Maintains DreamScene’s real-time rendering while boosting visual quality
- ✅ YAML-based configuration for flexible object/scene generation


## 🧪 Demo Videos

Here are comparisons between the original DreamScene outputs and our enhanced results:

| Object         | DreamScene Baseline                                   | Ours (NeRF Supervised)                              |
|----------------|--------------------------------------------------------|-----------------------------------------------------|
| 🧴 Blue Bottle | [video_rgb_blue_bottle——dreamscene.mp4](./video_rgb_blue_bottle——dreamscene.mp4) | [video_rgb_blue_bottle——ours.mp4](./video_rgb_blue_bottle——ours.mp4) |
| 🐟 Fish        | [video_rgb_fish——dreamscene.mp4](./video_rgb_fish——dreamscene.mp4)             | [video_rgb_fish——ours.mp4](./video_rgb_fish——ours.mp4) |
| 🍇 Grapes      | [video_rgb_grapes——dreamscene.mp4](./video_rgb_grapes——dreamscene.mp4)         | [video_rgb_grapes——ours.mp4](./video_rgb_grapes——ours.mp4) |
| 💡 Lamp        | [video_rgb_lamp——dreamscene.mp4](./video_rgb_lamp——dreamscene.mp4)             | [video_rgb_lamp——ours.mp4](./video_rgb_lamp——ours.mp4) |
| 🪵 Wood House  | [video_rgb_wood house——dreamscene.mp4](./video_rgb_wooden_house——dreamscene.mp4) | [video_rgb_wood house——ours.mp4](./video_rgb_wooden_house——ours.mp4) |

> 📁 All video files are included in this repository root directory.


> 📁 You can find all videos in the [assets folder](https://github.com/HE1107/Optimizing-Object-and-Scene-Generation-Based-on-DreamScene-demo-videos/).

@project{dreamscene-enhanced,
  title={Optimizing Object and Scene Generation Based on DreamScene},
  author={Du Chunyang, Qian Yifan, He Yufei, Quan Yurou, Zhuo Shuming},
  year={2025}
}

