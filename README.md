<p align="center">
  <img src="assets/readme/app-icon.png" width="112" alt="CharaNest 裂纹蛋壳 App 图标">
</p>

<h1 align="center">CharaNest</h1>

<p align="center"><strong>让你的角色住进电脑。</strong></p>

<p align="center">
  导入属于自己的角色，让 TA 出现在桌面、与你聊天、陪伴专注，<br>
  也拥有可以回去的 Room 与 Garden。
</p>

<p align="center">
  <code>0.4.0-beta.5</code> · macOS Apple Silicon · Windows support is currently in validation
</p>

![PAPAlu 在 CharaNest 中陪伴专注，旁边是真实运行的 Garden](assets/readme/hero.png)

## 你的角色，从素材包来到桌面

选择角色素材文件夹，填写角色名称与陪伴提示词，就能把自己的角色带进 CharaNest。角色管理页可以继续切换、编辑和整理多个角色。

<table>
  <tr>
    <td width="42%"><img src="assets/readme/custom-character-import.png" alt="CharaNest 完整角色包导入界面"></td>
    <td width="58%"><img src="assets/readme/character-management.png" alt="CharaNest 角色管理界面，当前角色为 PAPAlu"></td>
  </tr>
</table>

- 支持角色资料、人格 Prompt、用户称呼与日常作息
- 支持多个动作状态；缺少动作时回退到当前角色自己的 `idle`
- 可以添加、切换、编辑或删除角色，并保护最后一个角色不被删除

## 角色真的会留在桌面上

PAPAlu 会在桌面上待机和眨眼。角色可以被拖动，也会根据状态切换动作；靠近桌面边缘时，可以进入探头状态。

<p align="center">
  <img src="assets/readme/desktop-companion.gif" width="720" alt="PAPAlu 在 CharaNest 桌面上真实待机与眨眼">
</p>

## 聊天，也陪你专注

Chat 使用当前角色自己的 Prompt 与人格。要获得真实回复，需要填写你自己的 DeepSeek API Key。需要安静做事时，可以直接让角色陪你开始一段 Focus。

<table>
  <tr>
    <td width="56%"><img src="assets/readme/chat.png" alt="PAPAlu 的 CharaNest Chat 界面"></td>
    <td width="44%"><img src="assets/readme/focus.png" alt="PAPAlu 陪伴 15 分钟专注的运行状态"></td>
  </tr>
</table>

## 回房间，也去花园

CharaNest 有独立的中性 Room / Garden 主题。你可以回到房间，也可以进入花园种下粉色玫瑰。

![CharaNest 真实运行的 Room 与 Garden](assets/readme/room-garden.png)

当前角色、角色资料与本地状态会被保存，重新启动后仍可恢复。

## 下载与安装

Beta 下载即将开放。发布后请前往 [GitHub Releases](https://github.com/chaoyan-spec/CharaNest/releases)：

1. 优先下载 macOS Apple Silicon 的 `DMG`
2. 将 CharaNest 拖入 `Applications`
3. 首次打开时，如被 macOS 拦截，请右键 CharaNest 并选择“打开”
4. `ZIP` 将作为备用下载方式提供

> 当前 Beta 使用 ad-hoc signing，尚未经过 Apple notarization。请只从本仓库的 Releases 下载。

## Current Beta Status

| 项目 | 当前状态 |
| --- | --- |
| Version | `0.4.0-beta.5` |
| macOS | Apple Silicon |
| Windows | Support is currently in validation |
| Signing | ad-hoc |
| Apple notarization | 尚未完成 |
| Chat | 需要用户自己的 DeepSeek API Key |

### 当前限制

- Windows 版本仍在真机验收中，暂未作为正式下载提供
- 不同角色可用的动作取决于其素材包；缺失动作会回退到该角色自己的 `idle`
- Two-image Idle Generator 的底层能力已存在，但尚未作为正式用户入口开放

## Feedback

遇到问题，或有角色素材与体验建议，欢迎在 [GitHub Issues](https://github.com/chaoyan-spec/CharaNest/issues) 中反馈。

## Repository Status

本仓库用于 CharaNest 产品介绍、文档、用户反馈和 Release 分发，不包含 CharaNest 应用源代码。
