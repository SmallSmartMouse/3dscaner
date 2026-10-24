# 苹果 API 实测清单

AI 和开发者使用系统 API 前，先查这里。状态为"已验证"的才能直接用；其他的先按技术验证卡验证，把结论和证据补进来。新的 iOS 大版本发布后，全部重新验证一遍。

状态：✅ 已验证 · ⚠️ 有条件可用（见备注） · ❌ 不可用 · ❓ 待验证

| 能力 | 状态 | 结论 | 证据 | 设备 / 系统 | 日期 |
|---|---|---|---|---|---|
| iOS 端 `PhotogrammetrySession` 可用的细节级别、照片上限、耗时、发热 | ❓ | | | | |
| iOS 端 `.poses` 请求可用，位姿与模型同一坐标系 | ❓ | | | | |
| Object Capture 拍摄的 HEIC 带相机内参 | ❓ | | | | |
| 物件模式重建是否裁掉标定板区域 | ❓ | | | | |
| `RoomCaptureSession(arSession:)` 能同时开 `sceneReconstruction = .mesh` | ❓ | | | | |
| `StructureBuilder` 对斜墙、弧形墙、错层的表现 | ❓ | | | | |
| Xcode ARKit 会话录制回放能驱动 RoomPlan | ❓ | | | | |
| `ARWorldMap` 跨天重定位后 RoomPlan 坐标一致 | ❓ | | | | |

> 前 6 项来自技术方案 §9.3，在 Phase 0 第一周完成。
