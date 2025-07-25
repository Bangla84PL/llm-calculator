# 🚀 LLM Hardware Calculator

> Find the perfect hardware configuration for your language model

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://[YOUR-USERNAME].github.io/llm-calculator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A beautiful, modern web calculator that helps you determine the optimal hardware requirements for running Large Language Models (LLMs). Built with vanilla HTML, CSS, and JavaScript featuring a stunning dark glassmorphism design.

## ✨ Features

### 🌍 **Multi-language Support**
- 🇵🇱 Polish (Polski)
- 🇺🇸 English  
- 🇨🇳 Chinese (中文)

### 🎯 **Smart Calculations**
- **Model sizes**: 7B to 70B parameters
- **Quantization options**: FP16, INT8, Q4, Q3
- **Context length**: 2K to 32K tokens
- **Target speed**: Customizable tokens/second
- **Budget constraints**: Cost-effective recommendations

### 💻 **Hardware Recommendations**
- **Local builds**: Budget, medium, and high-end configurations
- **VPS options**: Cloud providers comparison
- **Performance estimates**: Expected speeds and costs

### 🎨 **Modern Design**
- **Dark theme**: Eye-friendly interface
- **Glassmorphism**: Beautiful backdrop blur effects
- **Responsive**: Works on all devices
- **Animations**: Smooth transitions and floating particles

## 🛠️ Supported Models

| Model | Parameters | Base RAM |
|-------|------------|----------|
| Llama 2 7B | 7B | 14 GB |
| Llama 3.1 8B | 8B | 16 GB |
| Llama 2 13B | 13B | 26 GB |
| Qwen2.5 24B | 24B | 48 GB |
| Code Llama 30B | 30B | 60 GB |
| Llama 2 70B | 70B | 140 GB |

## 🚀 Quick Start

### Online Version
Visit the live demo: [https://[YOUR-USERNAME].github.io/llm-calculator/](https://[YOUR-USERNAME].github.io/llm-calculator/)

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/[YOUR-USERNAME]/llm-calculator.git
cd llm-calculator
```

2. Open in your browser:
```bash
open index.html
# or
python -m http.server 8000  # Then visit http://localhost:8000
```

## 📱 Screenshots

### Desktop View
![Desktop View](screenshots/desktop.png)

### Mobile View
![Mobile View](screenshots/mobile.png)

## 🧮 How It Works

The calculator uses advanced algorithms to determine:

1. **Memory Requirements**: Based on model size and quantization
2. **GPU VRAM**: Minimum requirements for efficient inference
3. **Bandwidth Needs**: Memory bandwidth for target performance
4. **Cost Analysis**: Budget-friendly hardware suggestions

### Calculation Formula
```
Total RAM = (Model Size × Quantization Factor) + Context Memory + System Overhead
Min VRAM = max(8GB, Total RAM × 0.8)
Bandwidth = Target Speed × Model Size × Quantization Bits / 8000
```

## 🛡️ VPS Providers

| Provider | GPU | VRAM | Price/Month | Performance |
|----------|-----|------|-------------|-------------|
| Hetzner Cloud | RTX 4060 | 16GB | €25 | 85% |
| OVH Public Cloud | RTX 3080 | 12GB | €28 | 80% |
| Scaleway | RTX 4070 | 12GB | €22 | 82% |
| DigitalOcean | RTX A4000 | 16GB | €35 | 75% |
| Vultr | RTX 3070 | 8GB | €18 | 70% |

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with glassmorphism effects
- **Vanilla JavaScript**: No dependencies, lightweight
- **SVG**: Scalable vector graphics for logos

### Browser Support
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Adding New Models
To add new models, update the `modelDatabase` object in `index.html`:

```javascript
const modelDatabase = {
    // Add new model
    80: { name: "New Model 80B", baseRAM: 160 }
};
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 Powered By

[![Smart Camp AI](https://img.shields.io/badge/Powered%20by-Smart%20Camp%20AI-blue)](https://smartcamp.ai/)

Advanced AI tools for your business. Visit [smartcamp.ai](https://smartcamp.ai/) to discover more solutions.

## 🐛 Bug Reports

Found a bug? Please create an issue with:
- Browser and version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## 📊 Roadmap

- [ ] Add more LLM models (Mistral, Claude, etc.)
- [ ] GPU performance benchmarks
- [ ] Power consumption calculator
- [ ] Docker deployment options
- [ ] API for programmatic access
- [ ] Model comparison features

## ⭐ Star History

If you found this project helpful, please give it a star!

---

Made with ❤️ by [Your Name] | Powered by [Smart Camp AI](https://smartcamp.ai/) 