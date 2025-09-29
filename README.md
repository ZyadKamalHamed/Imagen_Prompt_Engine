
Professional AI prompt engineering templates for creating perfect prompts across different platforms and use cases.
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Features

- **🎬 Midjourney Storyboard Template**: Professional cinematography workflow with 19+ specialized categories
- **🍌 Nano Banana AI Template**: Multi-platform image generation and editing prompts
- **🔗 Direct Platform Integration**: One-click access to AI platforms (Gemini, Leonardo AI, Stability AI, DALL-E)
- **🛠️ Image Conversion Tools**: Built-in links to professional image editing and conversion tools
- **📱 Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **⚡ Live Prompt Building**: Real-time prompt generation as you type
- **📄 Export Options**: Copy, download, or refine prompts with AI assistance

##  Templates

### Midjourney Storyboard Template
Perfect for creating cinematic storyboards and visual storytelling:
- Story foundation (subject, action, mood)
- Camera setup (style, angle, lens, aspect ratio)
- Composition (rule of thirds, depth of field, background)
- Lighting & atmosphere (direction, weather, color grading)
- Details & styling (materials, wardrobe, artistic references)
- Technical finishing (rendering, negatives, seeds)

### Nano Banana AI Template
Ideal for general AI image generation and editing:
- Subject & main focus
- Visual style & approach
- Environment & setting
- Colors & mood
- Technical specifications
- Style references & special requirements

##  Platform Integrations

- **Canva Resize** - Professional image resizing
- **TinyPNG** - Image compression
- **Convertio** - Format conversion
- **Remove.bg** - Background removal
- **Photopea** - Advanced online editing
- **Squoosh** - Quick optimization

## 🛠️ Installation & Usage

### Option 1: Use Online (Recommended)
Visit the [live demo](https://huggingface.co/spaces/yourusername/the-general-store) - no installation required!

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/the-general-store-ai-prompts.git
   cd the-general-store-ai-prompts
   ```

2. Open `index.html` in your web browser

3. Start creating professional AI prompts!

## 📁 File Structure

```
the-general-store-ai-prompts/
├── index.html              # Homepage with template selection
├── midjourney.html          # Midjourney storyboard template
├── nano-banana.html         # Nano Banana AI template
├── README.md               # This file
└── LICENSE                 # MIT License
```

## How to Use

1. **Choose Your Template**: Start at the homepage and select either Midjourney or Nano Banana
2. **Fill in the Fields**: Complete the form sections relevant to your project
3. **Watch the Magic**: Your prompt builds automatically as you type
4. **Export Your Prompt**: Copy, download, or refine with AI assistance
5. **Generate Images**: Use the integrated platform buttons to create your images

## 🔧 Customization

The templates are built with vanilla HTML, CSS, and JavaScript for easy customization:

- **Colors**: Modify the CSS gradient variables in each file
- **Fields**: Add or remove form fields by editing the HTML structure
- **Platforms**: Update the platform URLs in the JavaScript functions
- **Styling**: Customize the CSS for your brand

##  Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Ideas
- Add new AI platform integrations
- Create additional prompt templates
- Improve mobile responsiveness
- Add new image tools
- Enhance accessibility features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## Syncing to GitHub and Hugging Face

This repository is configured so that running `git push` (or `git push origin`) updates both GitHub (`origin`) and the Hugging Face Space. Git manages two push URLs under the `origin` remote and sends the same commit to each in sequence.

- To reuse the setup after cloning on a new machine, run:
  ```bash
  git remote set-url --push origin https://github.com/ZyadKamalHamed/Imagen_Prompt_Engine.git
  git remote set-url --add --push origin https://huggingface.co/spaces/24Zyad/Image_Gen_Prompt_Engine
  ```
- When prompted for credentials, use your GitHub Personal Access Token and your Hugging Face token. A credential helper will cache them if configured.
- Use `git push` as usual. GitHub updates first; Hugging Face follows automatically. If one push fails, Git aborts before reaching the other and prints the error so you can retry.
- You can still push directly to Hugging Face with `git push space main` if you need to test the Space without touching GitHub.

Before pushing large image assets, keep Git LFS installed so that `.png` files tracked in `.gitattributes` continue to flow through LFS on both remotes.
