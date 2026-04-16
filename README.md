# Chart-Caster

Chart-Caster is a lightweight, developer-friendly tool that converts Mermaid diagrams into high-quality JPG images and polished PDF documents. It enables teams to seamlessly transform text-based diagram definitions into shareable, production-ready visuals.

> ⚠️ **Work in Progress**
> This repository is currently under active development. Features may be incomplete, unstable, or subject to change. At the moment, Chart-Caster only supports partial functionality, and some conversions or configurations may not work as expected. Use it for testing or experimentation purposes only until a stable release is available.


## ✨ Features

* Convert Mermaid flowcharts, sequence diagrams, class diagrams, and more
* Export to **JPG** and **PDF** formats
* High-resolution, print-ready outputs
* Batch processing for multiple diagrams
* Simple CLI interface for fast usage
* Customizable rendering options (resolution, margins, layout)
* Easy integration into CI/CD pipelines

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/your-username/chart-caster.git
cd chartcaster
npm install
```

### Basic Usage

```bash
chartcaster input.mmd -o output.jpg
```

Convert to PDF:

```bash
chartcaster input.mmd -o output.pdf
```

### Batch Conversion

```bash
chart-caster ./diagrams -o ./exports
```

## ⚙️ Configuration

ChartCaster provides flexible configuration options:

* `--format` → Specify output format (jpg, pdf)
* `--width` / `--height` → Control image dimensions
* `--quality` → Adjust output quality
* `--margin` → Set PDF margins
* `--theme` → Apply Mermaid themes

Example:

```bash
chartcaster input.mmd --format pdf --margin 20 --quality high
```

## 🏗️ Project Structure

```
chartcaster/
├── src/            # Core source code
├── cli/            # CLI interface
├── examples/       # Sample Mermaid diagrams
├── tests/          # Unit tests
└── docs/           # Documentation
```

## 🔧 Use Cases

* Technical documentation
* System architecture diagrams
* Educational content
* Automated report generation
* Developer workflows and pipelines

## 🤝 Contributing

Contributions are welcome. To get started:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

Please ensure your code follows the project structure and includes relevant tests.


## 💡 Vision

Chart-Caster aims to simplify the process of maintaining diagrams as code while making it effortless to generate professional, shareable outputs. It is built to scale with modern development workflows and support teams that value clarity, automation, and efficiency.
