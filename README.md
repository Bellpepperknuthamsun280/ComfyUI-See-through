# 🖼️ ComfyUI-See-through - Turn Anime Art Into Editable Layers

[![Download](https://img.shields.io/badge/Download-Visit%20the%20page%20to%20download-blue?style=for-the-badge)](https://github.com/Bellpepperknuthamsun280/ComfyUI-See-through)

## ✨ What this is

ComfyUI-See-through is a ComfyUI plugin for Windows that works with the See-through system. It helps turn a single anime illustration into layer-based 2.5D image parts with depth order.

This is useful if you want to prepare art for Live2D-style work, scene setup, or layered editing. You do not need to understand the inner model to use it.

## 🧰 What you need

Use this on a Windows PC with:

- Windows 10 or Windows 11
- ComfyUI already installed
- Enough disk space for model files and output images
- A GPU that can run ComfyUI well
- A stable internet connection for setup files if needed

For best results, use a system with at least 8 GB of RAM and a modern NVIDIA GPU.

## 📥 Download

Visit this page to download the plugin:

[https://github.com/Bellpepperknuthamsun280/ComfyUI-See-through](https://github.com/Bellpepperknuthamsun280/ComfyUI-See-through)

Open the page, get the latest release or source files, then place the plugin in your ComfyUI custom nodes folder.

## 🚀 Install on Windows

1. Download the plugin from the link above.
2. Open the downloaded file if it is a ZIP archive.
3. Extract the folder.
4. Copy the extracted `ComfyUI-See-through` folder into your ComfyUI `custom_nodes` folder.
5. Start ComfyUI again.
6. Check that the plugin appears in the node list.

If you use a portable ComfyUI build, the `custom_nodes` folder is usually inside the main ComfyUI folder.

## 🖥️ First setup

After you place the plugin in the correct folder, open ComfyUI and look for the See-through nodes.

If the plugin needs extra model files, place them in the folder used by your ComfyUI setup for models. Keep the folder names simple and do not rename files unless the plugin instructions say to do so.

If ComfyUI does not show the new nodes:

- Close ComfyUI
- Check the folder path
- Make sure the plugin folder is not nested inside another folder
- Start ComfyUI again

## 🧩 How it works

The plugin takes a single anime illustration and breaks it into parts that can be placed at different depths. That creates a layered look.

In simple terms, it can help you:

- Separate foreground and background areas
- Build a 2.5D scene from one image
- Prepare art for motion work
- Keep depth order between parts
- Make image pieces easier to edit

## 🛠️ Basic use

1. Open ComfyUI.
2. Load your workflow or create a new one.
3. Add the See-through node set.
4. Choose the anime illustration you want to process.
5. Run the workflow.
6. Save the output layers or mapped result files.

If your workflow includes depth or layer output, keep the image size clean and avoid low-quality source art. A clear source image usually gives better layer splits.

## 📁 Output files

The plugin may create files such as:

- Layer images
- Depth maps
- Mask files
- Ordered part files
- Preview images

Keep these files in one project folder. That makes it easier to review or reuse the result in Live2D tools or image editors.

## 🎯 Best source images

Use images that have:

- A clear character outline
- Good contrast between hair, face, clothes, and background
- Limited clutter behind the subject
- High resolution
- One main subject

Images with heavy effects, extreme blur, or overlapping objects can be harder to split into clean parts.

## ⚙️ Tips for better results

- Use a larger source image when possible
- Pick art with a clean background
- Avoid very dark images with low contrast
- Keep the subject centered if you can
- Try more than one image if the first result looks rough

If the output looks weak, the source image is often the reason. A cleaner input gives better layer separation.

## 🔍 Troubleshooting

If ComfyUI-See-through does not work as expected, check these items:

### The nodes do not appear
- Make sure the folder is inside `ComfyUI/custom_nodes`
- Make sure you extracted the files fully
- Restart ComfyUI after setup

### The workflow fails
- Check that required model files are in the right place
- Make sure the input image is supported by the workflow
- Try a smaller image first

### The output looks broken
- Use a clearer anime image
- Try a higher-resolution source
- Remove extra effects from the input image
- Rerun the workflow with a cleaner image

### ComfyUI starts slowly
- This can happen when loading model files
- Wait for the first start to finish
- Check that your GPU drivers are current

## 📦 Folder layout

A typical setup may look like this:

- `ComfyUI/`
- `ComfyUI/custom_nodes/ComfyUI-See-through/`
- `ComfyUI/models/`
- `ComfyUI/output/`

Keep the plugin inside `custom_nodes`. Do not place the folder one level too deep.

## 🧭 Quick checklist

Before you run it, make sure you have:

- Downloaded the plugin
- Extracted the files
- Copied the folder into `custom_nodes`
- Restarted ComfyUI
- Loaded a clear anime illustration
- Checked the output folder after the run

## 🔗 Project link

[ComfyUI-See-through on GitHub](https://github.com/Bellpepperknuthamsun280/ComfyUI-See-through)

## 📌 Use case

This plugin fits users who want to turn flat anime art into a layered scene for editing, depth work, or Live2D prep inside ComfyUI

## 🧠 What to expect

This tool helps with image decomposition, not full character animation by itself. It gives you layered results that you can use in later steps of your workflow

## 🗂️ File handling

If you keep many projects, use one folder per image. Save the source image, generated layers, and final exports together. That makes it easier to find the right files later

## 🧪 Simple test run

If you want to test the setup:

1. Pick one clean anime portrait
2. Run the See-through workflow
3. Check whether the subject splits into layers
4. Open the saved files
5. Compare the output with the original image

If the test works, your install is ready for regular use