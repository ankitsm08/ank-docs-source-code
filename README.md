---
draft: true
---

# 📚 Ank Docs Content Source Files

Welcome! This is the public repository for our documentation site's content. Here, you'll can edit the notes found on the site. Feel free to jump in, make edits, and contribute to building a valuable resource for everyone studying these topics.

### How to Contribute

Want to make some edits or add new content? Great! Just follow these simple steps:

1. **Clone or Fork the Repository**  
   - **Clone the repo**: 
     ```bash
     git clone https://github.com/ankitsm08/ank-docs-source-code.git
     ```
   - Or **fork** the repo on GitHub to create your own copy and edit from there.  
   - After cloning, navigate to the `content` folder where you’ll find all the markdown files that make up the documentation.

2. **Edit the Markdown Files**  
   - Open any markdown (`.md`) file in **[VS Code](https://code.visualstudio.com/)** or any other markdown editor.
   - Alternatively, use this **[online Markdown & MathJax editor](https://kerzol.github.io/markdown-mathjax/editor.html)** if you prefer a browser-based tool.
   - Once in your editor, you can add new content, update existing entries, or tweak the formatting as needed.

3. **Push Your Changes**  
   - To save your changes to GitHub, **commit** and **push** your edits:
     ```bash
     git add .
     git commit -m "Your descriptive commit message"
     git push
     ```
   - If you forked the repo, submit a **pull request** from your forked version for review.

### Recommended Extensions for Easy Editing

To make editing smoother, we recommend these extensions for **[VS Code](https://code.visualstudio.com/)**:

- **Markdown All in One**: Offers several tools for working with Markdown.
- **Markdown Extended**: Provides extra syntax support.
- **Markdown Footnotes**: Handy for adding detailed references and notes.
- **Markdown Preview Mermaid Support**: Helps visualize diagrams in Markdown.
- **Markdown Table**: Makes working with tables easier.
- **Markdown YAML Preamble**: Assists with YAML front matter.
- **Markdown+Math**: Enables MathJax for easy mathematical notation.

### Repository Structure

The repository is organized into folders by subject, making it easy to navigate and find the information you need. Here’s how it’s structured:

- **content/**  
  This is the main folder where all the documentation lives.

  - **subjects/**  
    Inside this folder, you'll find subfolders for each subject:
    - **physics/**
    - **maths/**
    - **chemistry/**

#### Example directory structure
```
repo
│
├───maths
│   ├───algebra
│   │   ├───binomial-theorem
│   │   ├───complex-numbers
│   │   ├───matrices-&-determinants
│   │   ├───permutation-&-combination
│   │   ├───quadratic-equations
│   │   └───sequence-&-series
│   ├───calculus
│   │   ├───continuity-differentiability
│   │   ├───differentiation
│   │   ├───integration
│   │   └───limits
│   ├───constants-&-approximations
│   │   ├───approximations
│   │   └───constants
│   ├───coordinate-geometry
│   ├───trigonometry
│   │   ├───general-solutions
│   │   ├───identities
│   │   ├───inverse-trigo
│   │   ├───solution-of-triangles
│   │   └───values
│   ├───sets,-relation-&-function
│   └───statistics-&-probability
└───physics
    ├───constants-&-conversions
    │   ├───constants
    │   ├───conversions
    │   └───units
    ├───electromagnetism
    │   └───induction
    ├───mechanics
    ├───modern-physics
    ├───optics
    │    ...
    ├───thermodynamics
    │    ...
    └───waves
         ...
```

Each subject folder contains an `_index.md` file, which serves as an overview for that subject. The front matter in this file looks like this:

```yaml
---
menuPre: " <i class='fa-fw fas fa-atom'></i> "
title: 'Physics'
description: 'Physics'
weight: 200
---
```

- **menuPre**: This is an optional field that allows you to add an icon to the subject in the menu (using Font Awesome icons).
- **title**: This is the name of the subject that will be displayed on the site.
- **description**: A brief description of the subject, which can help users understand what content to expect.
- **weight**: This determines the order of subjects in the menu. A lower number means it will appear higher up in the list.

For subsections of a subject or sections of the subject itself, there will also be subfolders with their own `_index.md` files. For example, the **maths/** folder might contain a subfolder called **trigonometry/** with its own `_index.md` file that looks like this:

```yaml
---
menuPre: " "
title: 'Constants & Conversions'
description: 'Constants & Conversions'
weight: 100
---
```

In this case:

- menuPre: This is empty(with a space for padding), meaning no icon will be displayed for this subsection.
- title: This is the name of the subsection that will be shown on the site.
- description: A brief description specific to the subsection.
- weight: This controls the order of subsections within the subject, allowing you to organize them in a way that makes sense for users.

### Tips on Using the Site-Specific Syntax (Hugo)

This documentation site is built using **Hugo** and the **Relearn theme**. To ensure compatibility with the site, check out the Relearn theme's syntax guidelines: [**Relearn Hugo Theme Documentation**](https://mcshelby.github.io/hugo-theme-relearn/shortcodes/index.html).

### Contribution & Maintenance Rules

1. **Stay Organized**  
   - Keep entries clear and concise. If you’re adding a formula, a law, or a concept, ensure it has a title, description, and if possible, a worked example.

2. **Follow the Format**  
   - Use existing entries as a reference for formatting. Consistent formatting helps everyone understand and find information quickly.

3. **Test Your Changes**  
   - If possible, preview your markdown changes before committing. You can use **Markdown Preview** in VS Code or the [online editor](https://kerzol.github.io/markdown-mathjax/editor.html) to check your edits. 

4. **Be Respectful**  
   - Avoid unnecessary edits, and respect the existing content structure. This keeps the documentation coherent for everyone.

5. **Regular Updates**  
   - Feel free to improve on any entry, but avoid large-scale changes without discussion. Let’s keep it a friendly, collaborative space!

Happy contributing! 😊
