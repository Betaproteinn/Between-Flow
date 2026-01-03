![Version](https://img.shields.io/badge/version-1.955-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-experimental-lightgrey)




# Between Flow（English version)

<img src="screenshots/main.png" width="800" />
<img src="screenshots/main2.png" width="800" />
<img src="screenshots/main3.png" width="800" />

Between Flow is a personal thinking tool for recording, breaking down, and continuing thought processes.  
It is closer to a continuously unfolding stream of thinking than an editor designed to produce final results.

**It is not meant to produce content for me, but to give me a way to keep thinking.**

---

## Core Idea

Between Flow does not try to tell you how you should think.  
Instead, it provides a stable, low-friction space where thinking can naturally unfold, be seen, and revisited.

Here:

- Every input is part of the thinking process  
- Order can be adjusted, rather than locked in time  
- Thoughts can be replied to, referenced, and rearranged  

It feels more like a workbench for thinking than a tool for producing conclusions.

---

## Usage Overview

- The left panel contains Streams, each representing an independent line of thought  
- The center area displays thoughts expanded in sequence  
- The input box at the bottom is used to continue the current thinking  
- Each piece of content is an independent thought node, and its order can be moved up or down later  
- Thought nodes can reference, reply to, or be rearranged relative to each other  
- The tool intentionally stays low-interference, keeping attention on thinking itself  

---

## PC Keyboard Shortcuts

Below are the PC keyboard shortcuts implemented in the current version (v1.954).

### Input and Sending

- **Enter**  
  Send the current input and create a new thought node  

- **Shift + Enter**  
  Insert a new line in the input box without sending  

### Reordering Thought Nodes (Non-input State)

When the input box is not focused and a thought node is selected:

- **Alt + ↑ (Arrow Up)**  
  Move the selected thought node up by one position  

- **Alt + ↓ (Arrow Down)**  
  Move the selected thought node down by one position  

This operation preserves reference relationships to avoid semantic confusion after reordering.

### Selection and References

- Click on a thought node  
  Select the node for further actions such as reordering or replying  

- Click on a reference like `>>#number`  
  Jump to the corresponding thought node and highlight it  

### Editing and Actions (UI-based)

The following actions are currently triggered via mouse or touch, not keyboard shortcuts:

- Reply to a thought node  
- Edit existing content  
- Copy node content  
- Delete a node  
- Add or remove reactions  
- Open the full emoji panel  

These actions are available through the floating toolbar or context menu of each node.

---

## Data and Storage

- All data is stored locally in the browser (localStorage)  
- No backend dependency and no data upload  
- Supports exporting a single Stream as a Markdown file  
- Supports importing Markdown files as new Streams  

Between Flow behaves more like a local thinking environment than a cloud service.

---

## Status and Scope

This is an ongoing personal project.  
It does not aim to be feature-complete, nor does it try to cover every use case.

Its value lies in:

- Whether it is genuinely used  
- Whether it reduces friction in thinking at certain moments  
- Whether it allows complex thoughts to move one step further  

If it is helpful to you, that is already enough.

---

## License

MIT License





# Between Flow（中文版本)

Between Flow 是一个用于记录、拆解和推进思考过程的个人思维工具。  
它更接近一条持续展开的思考流，而不是一个用于产出结果的编辑器。

**它不是帮我产出内容，而是给我一个继续思考的方式。**

---

## 核心理念

Between Flow 并不试图告诉你“应该怎么想”，  
而是提供一个足够稳定、低干扰的空间，让思考自然展开、被看见、被回溯。

在这里：

- 每一条输入都是思考过程的一部分  
- 顺序可以被调整，而不是被锁死  
- 思考可以被回应、引用、重排  

它更像是一个思考的工作台，而不是一个结论制造器。

---

## 使用方式概览

- 左侧是 Stream（思考流）列表，每个 Stream 是一条独立的思考路径  
- 中间区域是按顺序展开的思考内容  
- 底部输入框用于继续推进当前思考  
- 每一条内容都是一个独立的思考节点，其顺序可以在之后上下调整  
- 思考节点之间可以相互引用、回复或重排  
- 工具本身尽量保持低干扰，让注意力停留在思考本身  

---

## PC 端快捷键说明

以下为 **当前版本（v1.954）已实现的 PC 端快捷键**。

### 输入与发送

- **Enter**  
  发送当前输入内容，生成一条新的思考节点  

- **Shift + Enter**  
  在输入框中换行，不发送  

### 思考节点重排（非输入状态）

在 **未聚焦输入框**、且已选中某一条思考节点时：

- **Alt + ↑（方向键上）**  
  将当前选中的思考节点向上移动一位  

- **Alt + ↓（方向键下）**  
  将当前选中的思考节点向下移动一位  

该操作会同时维护节点引用关系，避免顺序调整后语义错乱。

### 选择与引用

- 鼠标点击某一条思考节点  
  选中该节点，用于后续操作（重排、回复等）  

- 点击形如 `>>#编号` 的引用  
  跳转到对应编号的思考节点，并高亮显示  

### 编辑与操作（通过界面触发）

以下操作目前通过鼠标或触控触发，而非快捷键：

- 回复某条思考节点  
- 编辑已有内容  
- 复制节点内容  
- 删除节点  
- 添加或移除 reaction  
- 打开完整 emoji 面板  

这些操作集中在每条节点的悬浮工具栏或右键菜单中。

---

## 关于数据与存储

- 所有数据默认存储在本地浏览器（localStorage）  
- 不依赖后端，不上传数据  
- 支持将单个 Stream 导出为 Markdown 文件  
- 支持从 Markdown 文件导入为新的 Stream  

Between Flow 更像是一个本地思考环境，而不是一个云服务。

---

## 状态与定位

这是一个持续迭代中的个人项目。  
它并不追求功能完整，也不试图覆盖所有使用场景。

它的存在价值在于：

- 是否真的被使用  
- 是否在某些时刻，降低了思考的摩擦  
- 是否让复杂问题“多走了一步”  

如果它对你有帮助，那就已经足够。

---

## License

MIT License

