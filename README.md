
# 📊 Gabor-Granger Code Generator (gabrV2)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-green)](https://santoshhh000.github.io/gabrV2/)
[![Pure HTML/CSS/JS](https://img.shields.io/badge/Stack-Pure%20Frontend-orange)](https://github.com/santoshhh000/gabrV2)

## 📖 About

**gabrV2** is a powerful, client-side web application that generates XML survey code for **Gabor-Granger price sensitivity analysis**. This tool helps market researchers and survey designers quickly create complex pricing survey logic without manual coding.

The Gabor-Granger technique is a classic pricing research method used to determine the optimal price point for a product by measuring purchase intent at different price levels.

## ✨ Features

### 🎨 **Modern UI/UX**
- **7 Beautiful Themes**: Midnight, Ocean, Forest, Sunset, Rose, Slate, and Light
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Glassmorphism Effects**: Modern frosted glass UI with backdrop filters
- **Smooth Animations**: Hover effects, transitions, and micro-interactions

### ⚡ **Core Functionality**
- **Dynamic Code Generation**: Real-time XML generation as you type
- **Multi-Question Support**: Configure 1 to 20+ price questions
- **Customizable Scales**: Define your own rating scales (e.g., 5-point Likert)
- **Smart Routing**: Automatic skip logic for price sensitivity testing
- **Positive/Negative Mapping**: Map scale responses to Yes/No purchase intent

### 🛠️ **Developer Tools**
- **One-Click Copy**: Copy generated XML to clipboard instantly
- **XML Download**: Download survey code as `.xml` file
- **Shareable Links**: Generate URLs that preserve your configuration
- **Local Persistence**: Auto-saves inputs to browser localStorage
- **Validation System**: Real-time input validation with warnings and errors

### ⌨️ **Keyboard Shortcuts**
- `Ctrl/Cmd + Enter`: Generate code
- `Ctrl/Cmd + Shift + C`: Copy code to clipboard

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Visit the live demo: **[https://santoshhh000.github.io/gabrV2/](https://santoshhh000.github.io/gabrV2/)**

### Option 2: Run Locally

# Clone the repository
git clone https://github.com/santoshhh000/gabrV2.git

# Navigate to directory
cd gabrV2

# Open index.html in any modern browser
# No build step or dependencies required!


## 📋 Configuration Guide

### Input Fields

| Field | Description | Example |
|-------|-------------|---------|
| **Question ID** | Prefix for question labels | `Q10x` |
| **Questions** | Number of price points to test | `4` |
| **Question Text** | Text displayed with each price | `Agree to buy at ...` |
| **Price Labels** | Price points (high to low, one per line) | `$100\n$80\n$60\n$40` |
| **Scale Options** | Response scale labels | `1. Would not consider\n2\n3\n4\n5. Would strongly consider` |
| **Positive Scale** | Codes that map to "Yes" | `r4\nr5` |
| **Negative Scale** | Codes that map to "No" | `r1\nr2\nr3` |

### Generated Output

The tool generates **XML code** compatible with survey platforms like:
- **Sawtooth Software** (Lighthouse Studio)
- **Qualtrics** (with XML import)
- **SurveyGizmo/Alchemer**
- Other XML-based survey engines

The generated code includes:
- Random price assignment logic
- Conditional routing (skip logic)
- Purchase intent recording
- Price sensitivity calculations

## 🎯 How It Works

1. **Setup**: Enter your question parameters and price points
2. **Configure**: Define your rating scale and response mappings
3. **Generate**: Click "Generate Code" or use keyboard shortcut
4. **Validate**: Check the validation panel for any warnings
5. **Export**: Copy XML or download as file
6. **Implement**: Import the XML into your survey platform

## 🧪 Example Use Case

**Scenario**: Testing price sensitivity for a new software subscription

**Inputs**:
- Question ID: `SW_SUB`
- Questions: `4`
- Prices: `$29\n$49\n$79\n$99`
- Scale: `1. Definitely not\n2\n3\n4\n5. Definitely yes`

**Output**: Generates XML that randomly shows one price, asks purchase intent, and routes respondents through different price points based on their answers.

## 🛡️ Technical Details

### Architecture
- **Pure Frontend**: No backend required, runs entirely in the browser
- **Zero Dependencies**: No external libraries or frameworks
- **Vanilla JavaScript**: ES6+ with modern browser APIs
- **CSS Variables**: Theme system using CSS custom properties

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### Privacy & Security
- **Client-Side Only**: No data sent to servers
- **Local Storage**: Configuration saved locally in your browser
- **No Tracking**: No analytics or third-party scripts

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Areas for Contribution
- 🌍 Internationalization (i18n) support
- 📱 Mobile UI improvements
- 🎨 Additional themes
- 🧪 More validation rules
- 📚 Documentation improvements

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**santoshhh000**
- GitHub: [@santoshhh000](https://github.com/santoshhh000)

## 🙏 Acknowledgments

- Inspired by the classic Gabor-Granger pricing methodology
- Built with modern CSS features (Grid, Flexbox, Custom Properties)
- Designed for market researchers and survey professionals

---

## 📞 Support

If you encounter any issues or have feature requests:
- 🐛 Open an [Issue](https://github.com/santoshhh000/gabrV2/issues)
- 💬 Start a [Discussion](https://github.com/santoshhh000/gabrV2/discussions)

---

*Built with ❤️ for the market research community*


## 📝 Key Highlights of this ABOUT file:

1. **Clear Purpose**: Explains what Gabor-Granger is and why the tool exists
2. **Feature-Rich**: Highlights all the advanced features (themes, validation, shortcuts)
3. **Practical Examples**: Includes a table of configuration options and a use case
4. **Technical Details**: Explains the architecture (pure frontend, no dependencies)
5. **Professional Structure**: Uses badges, tables, and clear sections
6. **Action-Oriented**: Clear installation and usage instructions
