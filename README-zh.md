# Updated sd-webui-3d-open-pose-editor 

**Note**: I am not the creator of this plugin. I copied the repository and fixed a bug related to compatibility with the latest version of sd-webui-controlnet. All rights to the original plugin belong to its author.

You can find the original repository and description at the following link: [link to the original repository].

## Changes:
- Fixed an error in the `openpose_editor.py` file on line 70.
- Updated for compatibility with the latest version of `ControlNet v1.1.455`.
- Modified 3 files: `README.md`, `README-ja.md`, `README-zh.md`.

## Testing:
My fork version has been tested with `ControlNet v1.1.455` and is fully compatible.

## Installation:
1. Open the "Extension" tab of the WebUI.
2. Open the "Install from URL" tab.
3. Copy "https://github.com/jQQj/sd-webui-3d-open-pose-editor.git" into the "URL for extension's git repository" field.
4. Click the "Install" button.
5. Open the "Installed" tab and click the "Apply and restart UI" button

## Old Description:
> # 3D Openpose Editor (sd-webui-3d-open-pose-editor) [[English](README.md)] [[日本語版](README-ja.md)]
> 
> 这是一个用于在[stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)中使用[Online 3D Openpose Editor](https://github.com/ZhUyU1997/open-pose-editor)的扩展功能。
> 
> # 预览
> 
> ![Preview](https://user-images.githubusercontent.com/42905588/227674599-21610711-7276-413c-aa36-cc5108e74dc3.png)
> 
> # 安装
> 
> 1. 打开Web UI的 "Extension" 选项卡
> 2. 打开 "Available" 选项卡
> 3. 如果您的Web UI版本过旧，请将 "Extension index URL" 更改为 `https://raw.githubusercontent.com/AUTOMATIC1111/stable-diffusion-webui-extensions/master/index.json`
> 4. 点击 "Load from:" 按钮
> 5. 点击3D Openpose Editor的 "Install" 按钮
> 6. 打开 "Installed" 选项卡，点击 "Apply and restart UI" 按钮
> 
> # 特点
> 
> - **姿势编辑**: 通过选择关节并使用鼠标旋转编辑 3D 模型的姿势。
> 
> - **手部编辑**: 通过选择手部骨骼并使用彩色圆圈微调位置来精调手部位置。
> 
> - **深度 / 法线 / Canny 地图**: 生成和可视化深度、法线和 Canny 地图，以提高 AI 绘图的质量。
> 
> - **保存/加载/还原场景**: 使用内置的保存和加载功能保存进度并在以后恢复。
> 
> - **调整身体参数**: 调整各种身体参数，如身高、体重和肢体长度，创建自定义的 3D 模型。
> 
> # 用法
> ### 场景导航:
> - **旋转场景**: 单击空白处并按住鼠标左键拖动鼠标。
> - **移动场景**: 单击空白处并按住鼠标右键拖动鼠标。
> 
> ### 身体操纵:
> - **旋转身体**: 单击任何关节以选择它，然后按住彩色圆圈之一并移动鼠标以旋转所选关节。
> - **手部编辑**: 单击红点以选择手部骨骼，然后按住红色圆圈之一并移动鼠标以旋转它们。
> 
> ### 调整身体参数:
> - **选择身体**: 单击身体以选择它。
> - **打开身体参数**: 单击菜单中的“Body Parameters”以调整身体参数。
> 
> ### 调整输出分辨率:
> - **在菜单中调整输出分辨率**：更改菜单中的“宽度”或“高度”以控制输出分辨率。
> 
> ### 其他功能:
> - **切换到移动模式**: 按 X 键切换到移动模式，允许您移动整个身体。
> - **删除身体**: 按 D 键删除整个身体。
> 
> # 鸣谢
> 
> * [ZhUyU1997 - Online 3D Openpose Editor](https://github.com/ZhUyU1997/open-pose-editor): 原始版本
