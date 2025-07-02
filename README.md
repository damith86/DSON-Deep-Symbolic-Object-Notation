# 🧬 DSON: Deep Symbolic Object Notation

*A next-generation visual data format for AI-native symbolic design, reasoning, and creation.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-1.0-blue.svg)]()
[![AI Native](https://img.shields.io/badge/AI-Native-green.svg)]()
[![GitHub Repo stars](https://img.shields.io/github/stars/damith86/DSON-Deep-Symbolic-Object-Notation?style=social)]()
[![GitHub forks](https://img.shields.io/github/forks/damith86/DSON-Deep-Symbolic-Object-Notation?style=social)]()

---

> 🔍 **What is DSON (Deep Symbolic Object Notation)?**
>
> DSON is a symbolic visual data format designed for AI-native design, pattern recognition, and cultural communication. It encodes not just structure — but **meaning, symmetry, evolution, and cultural context** — into a compact, LLM-parseable format.
>
> 🧠 Think of it as a visual language where:
> - AI can reason over symbols like visual DNA
> - Designers can compose culture-aware, animated forms
> - Tools can generate SVG, Canvas, 3D from symbolic intent

> ⚠️ **Note**: This project is not related to "Doge Serialized Object Notation". This DSON is an original initiative exploring symbolic geometry, mandala compression, and cross-cultural visual AI.

### The Problem DSON Solves

```
Traditional Pipeline:
Concept → JSON (data) → SVG (visual) → Human interpretation
❌ No semantic connection between data and meaning
❌ AI systems can't understand visual intention
❌ Cultural context lost in translation
```

```
DSON Pipeline:
Concept → DSON (symbolic) → Multiple outputs (SVG/Canvas/3D)
✅ Semantic meaning encoded in structure
✅ AI-interpretable visual logic
✅ Cultural intelligence built-in
✅ Temporal behavior as data
```

---

## 🧠 Key Capabilities

### 🎯 AI-Native Design

* **Symbolic Geometry**: Spatial relationships encoded as computable logic
* **Pattern Recognition**: AI can analyze, compare, and evolve visual structures
* **Cross-Modal Translation**: Convert text concepts directly to visual symbols

### 🌍 Cultural Intelligence

* **Contextual Rendering**: Same DSON renders as Celtic knot, Buddhist mandala, or Islamic pattern
* **Reading Order Awareness**: Supports different cultural interpretation patterns
* **Preservation Format**: Computational encoding of traditional visual languages

### ⏰ Temporal DNA

* **Living Symbols**: Encode animation, breathing, pulsing as intrinsic behavior
* **Keyframe Evolution**: Visual objects evolve over time with personality
* **Interactive States**: Symbols respond to user interaction through encoded logic

### 🔗 Modular Composition

* **Layer Architecture**: Visual functions that can be composed and referenced
* **Symbolic Inheritance**: Objects reference and build upon each other
* **Version Control**: Fork, merge, and evolve visual genetics like code

---

## 🏗️ DSON Architecture

```json
{
  "dson_version": "1.0",
  "type": "symbolic_structure",
  "meta": {
    "name": "TomatoCharacter",
    "creator": "Damith Welikala",
    "description": "Radial mandala of a tomato mascot"
  },
  "structure": {
    "resolution": [32, 32],
    "encoding_mode": "mandala_radial",
    "symmetry": "radial",
    "cultural_context": {
      "directionality": "clockwise",
      "reading_order": "inner_to_outer"
    },
    "layers": [
      {
        "name": "base_pixels",
        "type": "grid",
        "data": [{"x": 0, "y": 0, "rgba": [255,255,255,255]}]
      },
      {
        "name": "mandala_rings", 
        "type": "radial",
        "data": [
          {"angle": 45, "radius": 60, "color": "#DD3333", "shape": "circle"}
        ]
      }
    ]
  },
  "temporal": {
    "keyframes": [
      {"t": 0.0, "state": "closed"},
      {"t": 1.0, "state": "expanded"}
    ]
  },
  "semantics": {
    "tags": ["character", "mascot", "red"],
    "meaning": "Energetic tomato symbol representing vitality",
    "reversible": true
  }
}
```

---

## 🖼️ Symbol Gallery

Here are examples of DSON structures rendered visually:

| Tomato Character           | Peace Mandala             | Celtic Connector           |
| -------------------------- | ------------------------- | -------------------------- |
| ![](./examples/tomato.svg) | ![](./examples/peace.svg) | ![](./examples/celtic.svg) |

---

## 🚀 Quick Start

### Installation

```bash
npm install dson-renderer
# or
pip install dson-python
```

### Basic Usage

```javascript
import { DSONRenderer } from 'dson-renderer';

const renderer = new DSONRenderer();
const svg = await renderer.toSVG('path/to/symbol.dson');
const canvas = await renderer.toCanvas('path/to/symbol.dson');
```

### Creating DSON

```python
from dson import DSONBuilder

builder = DSONBuilder()
symbol = builder.mandala()
  .add_ring(radius=50, color="#FF0000")
  .add_temporal(duration=2.0, loop=True)
  .build()
```

---

## 📚 Documentation

* **📖 [Specification](./docs/specification.md)** – Complete DSON format reference
* **🎨 [Examples](./examples/)** – Gallery of DSON symbols and use cases
* **🔧 [API Reference](./docs/api.md)** – Renderer and builder documentation
* **🧠 [AI Integration](./docs/ai-integration.md)** – Using DSON with AI models
* **🌍 [Cultural Guide](./docs/cultural-contexts.md)** – Cultural interpretation patterns

---

## 🎯 Use Cases

### 🎨 Generative Design

```javascript
const brandSymbol = await ai.generateDSON("energetic tech startup logo");
const variations = brandSymbol.evolve({cultural_context: "minimalist"});
```

### 🧬 Visual DNA

```python
parent_a = load_dson("character_brave.dson")
parent_b = load_dson("character_wise.dson")
offspring = genetic_crossover(parent_a, parent_b)
```

### 🌐 Cross-Cultural Communication

```javascript
westernIcon.transform({
  cultural_context: {
    directionality: "counter_clockwise",
    reading_order: "outer_to_inner"
  }
});
```

### 🤖 AI-to-AI Communication

```python
concept = "peaceful morning"
dson_symbol = ai_model.conceptualize(concept)
shared_understanding = other_ai.interpret(dson_symbol)
```

---

## 🛠️ Tooling & Integrations

### Core Tools

* DSON Renderer – Convert DSON to SVG, Canvas, WebGL
* DSON Builder – Programmatic DSON creation
* DSON Validator – Schema validation and linting
* DSON Analyzer – Pattern recognition and similarity analysis

### Planned Integrations

* 🎨 Figma Plugin
* 🎮 Unreal Engine Integration
* 🧠 Hugging Face Symbolic Models
* 📱 React Native DSON Components

---

## 🤝 Contributing

DSON is designed for collaborative evolution. We welcome contributions from:

* 🎨 Artists
* 💻 Developers
* 🧠 AI Researchers
* 🌍 Cultural Experts
* 📚 Academics

### Getting Started

1. Read our [Contributing Guide](./CONTRIBUTING.md)
2. Check [Good First Issues](https://github.com/damith86/DSON-Deep-Symbolic-Object-Notation/labels/good%20first%20issue)
3. Join our [Discord Community](https://discord.gg/dson)

---

## 📊 Research & Academia

DSON is actively used in research on:

* Visual Intelligence
* Cultural Computing
* Human-AI Collaboration
* Generative Design

### Citations

```bibtex
@misc{welikala2025dson,
  title={DSON: A Symbolic Data Language for Visual Intelligence and Cultural Computation},
  author={Damith Welikala},
  year={2025},
  url={https://github.com/damith86/DSON-Deep-Symbolic-Object-Notation}
}
```

---

## 🗺️ Roadmap

### 2025 Q3

* ✅ Core specification release
* ✅ JavaScript/Python renderers
* ✅ Web-based DSON editor
* ✅ Cultural pattern library (100+ symbols)

### 2025 Q4

* 🔄 Figma plugin beta
* 🔄 AI model fine-tuning toolkit
* 🔄 Visual genetics marketplace
* 🔄 Academic paper submission

### 2026 Q1

* 🔄 3D renderer (Three.js/Babylon)
* 🔄 Mobile SDK (iOS/Android)
* 🔄 Blender integration
* 🔄 Cultural institution partnerships

---

## 💡 Vision

**DSON is the blueprint of visual thought.** It encodes not just what we see — but what we *mean*, how we *move*, and how we *remember*.

Our goal is to create a **universal visual language** that enables:

* 🤖 AI systems to truly understand visual content
* 🎨 Artists to preserve and evolve cultural symbols
* 🌍 Cultures to share visual heritage computationally
* 🧠 Humans and machines to collaborate visually

---

## 📄 License

MIT License – see [LICENSE](./LICENSE) for details.

---

## 🙏 Acknowledgments

DSON builds upon the rich traditions of:

* Mandala art (Buddhist, Hindu, Indigenous)
* Islamic geometric patterns
* Celtic knotwork
* Modern information design

We approach this work with deep respect for cultural heritage and commit to ethical development practices.

---

**Made with ❤️ for the future of human-AI visual collaboration**
