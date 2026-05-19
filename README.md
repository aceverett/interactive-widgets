# Interactive HTML Widgets for LMS Use

A curated registry of uncompromised, lightweight, and self-contained interactive learning objects. This repository serves as a centralized hub for interactive activities built entirely with native, semantic HTML, CSS, and JavaScript. 

Every component is fully decoupled from heavy learning vendor tracking architecture and proprietary software. They are designed to run anywhere, load instantly, and remain highly stable inside modern Learning Management Systems (LMS).

---

## 🚀 Purpose & Philosophy

Traditional elearning interactive tools often require heavy external authoring software, expensive licensing, or bloated SCORM wrappers that introduce vendor lock-in, break mobile responsiveness, and fail basic accessibility standards. 

This repository advocates a "design studio" approach to instructional design:
* **Zero Dependencies:** Pure vanilla web languages mean these files will render correctly decades from now.
* **iframe-Ready Portability:** Optimized specifically for seamless embedding across Canvas LMS, Blackboard, Moodle, or Brightspace using native browser elements.
* **Universal Design for Learning (UDL):** Built intentionally using semantic HTML tags, explicit color-contrast ratios, and keyboard-friendly focus parameters.

---

## 🛠️ Repository Architecture

The repository separates the central showcase catalog page from the independent, embeddable widget engines. This directory structure ensures that you can fork individual tools without pulling unnecessary dependencies.

```text
interactive-lms-widgets/
│
├── index.html                  # Thariq-style main showcase gallery dashboard
├── README.md                   # Core project documentation and embedding guidelines
│
└── widgets/                    # Standalone, isolated active learning elements
    ├── flashcards/             # CSS Flip Flashcards with 3D transforms
    ├── matching-activity/      # Two-column dynamic matching matrix
    ├── sequencer-activity/     # Chronological timeline and process sorter
    ├── sorting-activity/       # Bin-classification sorting matrix
    └── this-or-that/           # Binary choice architecture with instant rationales
```

## 📥 How to Use & Embed These Widgets

You can deploy these activities into your courses in two primary ways:

### Method 1: Embed Directly via GitHub Pages (Recommended)
If you have forked this repository and enabled GitHub Pages, your activities are already securely hosted online. To embed an activity into an LMS page (such as a Canvas Page, Assignment, or Discussion block):

1. Navigate to your live showcase dashboard dashboard.
2. Click the **🌐 Copy iframe** button underneath the desired activity to instantly copy the custom responsive iframe string.
3. Switch your LMS text editor to the **HTML / Raw Code View**.
4. Paste the string and save.

*Example code format generated:*

```html
<iframe src="[https://your-username.github.io/interactive-lms-widgets/widgets/matching-activity/](https://your-username.github.io/interactive-lms-widgets/widgets/matching-activity/)" 
        width="100%" 
        height="620px" 
        style="border: 0; display: block;" 
        title="Interactive Matching Activity" 
        allow="clipboard-write"></iframe>

```
### Method 2: Copy Raw HTML or Upload Files Locally
If your institution’s security policy limits external iframes, or if you want to make deep modifications to terms, definitions, and styling:

* Click the **📋 Copy HTML** button on the dashboard to pull the entire self-contained text layout of that widget directly into your clipboard cache.
* Alternatively, open the specific widget folder (e.g., `widgets/matching-activity/index.html`), copy the code, and paste it directly into your LMS's advanced HTML editor.
* You can also upload the standalone `index.html` file directly into your LMS Course Files directory and link out to it internally.

## 📄 License & Attribution

The original interactive learning widgets contained within the `widgets/` directory are licensed under the **MIT License** and are free to use, modify, and redistribute.

The central showcase dashboard (`index.html`) and associated styling include modifications of layout design elements originally created by [Thariq S (HTML Effectiveness)](https://github.com/ThariqS/html-effectiveness), used under the **Apache License 2.0**. 

A copy of the Apache 2.0 License can be found at: http://www.apache.org/licenses/LICENSE-2.0
