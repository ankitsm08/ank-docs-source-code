---
draft: true
---

# 📚 Ank Docs Content Source Files

Welcome! This is the public repository for our documentation site's content. Here, you'll can edit the notes found on the site. Feel free to jump in, make edits, and contribute to building a valuable resource for everyone studying these topics.

---

## How to Contribute

Ready to make some edits or add new content? Awesome! Just follow these simple steps:

1. **Fork the Repository**

   A **fork** is a copy of this repository under your GitHub account. This allows you to freely make changes without affecting the original repository. Here’s how:

   - Go to the repository page: [ank-docs-source-code](https://github.com/ankitsm08/ank-docs-source-code).
   - Click the **Fork** button at the top right corner of the page. This will create a copy of the repository under your GitHub profile.

2. **Clone Your Forked Repository**

   Once you’ve forked the repository, clone it to your local machine to start making edits:

   ```bash
   git clone https://github.com/<your-username>/ank-docs-source-code.git
   ```

   Replace `<your-username>` with your GitHub username. This will download your forked copy to your local system.

   Navigate into the cloned directory:

   ```bash
   cd ank-docs-source-code
   ```

3. **Create a New Branch for Your Edits**

   It’s best to make your changes in a separate branch so that your work stays organized. To create a new branch, run:

   ```bash
   git checkout -b your-branch-name
   ```
   Replace `your-branch-name` with a descriptive name for your branch, such as `update-physics-notes` or `add-math-concepts`.

4. **Edit the Markdown Files**

   - Open the content folder where all the markdown files are stored.

   - Open any markdown (`.md`) file in **[VS Code](https://code.visualstudio.com/)** or any other markdown editor.
  
     - You can view the preview of your edits by clicking the **Markdown Preview** button at the top right of the editor (VS Code).
  
   - Alternatively, use this **[online Markdown & MathJax editor](https://kerzol.github.io/markdown-mathjax/editor.html)** if you prefer a browser-based tool.

   - Feel free to add new files, update existing content, or improve formatting as needed.

5. **Stage, Commit, and Push Your Changes**

   After making your changes, use these commands to save and upload them to GitHub:

   1. Stage your changes:
      ```bash
      git add .
      ```

   2. Commit your changes with a message describing what you did:
      ```bash
      git commit -m "Added new content to physics notes"
      ```

   3. Push your changes to your forked repository on GitHub:
      ```bash
      git push origin your-branch-name
      ```

6. **Stay up-to-date with the Main Repository**
   
   To stay up-to-date with the main repository, follow these steps:
   
   1. Add the Main Repository as an Upstream Remote

      First, we need to link your local clone to the main repository (the one you forked from), so you can pull updates from it.

      ```bash
      git remote add upstream https://github.com/ankitsm08/ank-docs-source-code.git
      ```
      Here, `upstream` is a label pointing to the main repository. Now your local clone has two remotes:

      - `origin`: your fork on GitHub
      - `upstream`: the main repository
   
   2. Fetch Updates from the Main Repository

      Get the latest changes from the `upstream` repository:

      ```bash
      git fetch upstream
      ```

      This fetches any new commits from the main repository without merging them yet.

   3. Merge Changes from Upstream into Your Local Branch

      To update your fork’s `main` branch, switch to it and merge the `upstream` changes:

      ```bash
      git checkout main
      git merge upstream/main
      ```
      This merges the changes from the main repository’s `main` branch into your fork’s `main` branch on your local machine.

   4. Push the Updated Main Branch to Your Fork

      Finally, push the updated local `main` branch to your GitHub fork to bring it up-to-date:

      ```bash
      git push origin main
      ```

7. **Create a Pull Request**

   Now that your changes are pushed to GitHub, it’s time to submit a Pull Request (PR) to merge your edits into the main repository.

   1. Go to your forked repository on GitHub.
   2. You should see a message offering to create a Pull Request for your recently pushed branch. Click on Compare & pull request.
   3. Add a title and description for your PR explaining your changes.
   4. Click Create pull request to submit it.
   
   Your PR will be reviewed, and once approved, it will be merged into the main repository. 🎉

### Recommended Extensions for Easy Editing

To make editing smoother, we recommend these extensions for **[VS Code](https://code.visualstudio.com/)**:

- **Markdown All in One**: Offers several tools for working with Markdown.
- **Markdown Extended**: Provides extra syntax support.
- **Markdown Footnotes**: Handy for adding detailed references and notes.
- **Markdown Preview Mermaid Support**: Helps visualize diagrams in Markdown.
- **Markdown Table**: Makes working with tables easier.
- **Markdown YAML Preamble**: Assists with YAML front matter.
- **Markdown+Math**: Enables MathJax for easy mathematical notation.

## Repository Structure

The repository is organized into folders by subject, making it easy to navigate and find the information you need. Here’s how it’s structured:

- **repo/**  
  This is the main base repository where all the documentation lives.  
  Inside this repo, you'll find subfolders for each subject:

  - **(subjects)**  
     -  **physics/**
     - **maths/**
     - **chemistry/**

  - Inside each subject folder, we have sections(topics) and subsections(subtopics).
  - Each directory has its own `_index.md` file to serve as a page.  
    The `_index.md` file is a Markdown file that contains the content for the directory (page in the site).

### Example directory structure
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

Each subject folder contains an `_index.md` file, which creates a page in the site which lists the sections of the subject. The front matter in this file looks like this:

```yaml
---
menuPre: " <i class='fa-fw fas fa-atom'></i> "
title: 'Physics'
description: 'Physics'
weight: 200
---

{{% children containerstyle="div" style="h2" %}}
```

- **menuPre**: This is an optional field that allows you to add an icon to the subject in the menu (using Font Awesome icons).
- **title**: This is the name of the subject that will be displayed on the site.
- **description**: A brief description of the subject, which can help users understand what content to expect.
- **weight**: This determines the order of subjects in the menu. A lower number means it will appear higher up in the list.
- **children shortcode**: This lists the subsections of the subject.


For subsections of a subject or sections of the subject itself, there will also be subfolders with their own `_index.md` files. For example, the **maths/** folder might contain a subfolder called **trigonometry/** with its own `_index.md` file that looks like this:

```yaml
---
menuPre: " "
title: 'Constants & Conversions'
description: 'Constants & Conversions'
weight: 100
---

{{% children containerstyle="div" style="h3" %}}
```

In this case:

- **menuPre**: This is empty(with a space for padding), meaning no icon will be displayed for this subsection.
- **title**: This is the name of the subsection that will be shown on the site.
- **description**: A brief description specific to the subsection.
- **weight**: This controls the order of subsections within the subject, allowing you to organize them in a way that makes sense for users.
- **children shortcode**: This lists the subsections of the section.

### Tips on Using the Site-Specific Syntax (Hugo)

This documentation site is built using **Hugo** and the **Relearn theme**. To ensure compatibility with the site, check out the Relearn theme's syntax guidelines: [**Relearn Hugo Theme Documentation**](https://mcshelby.github.io/hugo-theme-relearn/shortcodes/index.html) if you want to add advanced features.

## FAQ for New Contributors

### Why Create a New Branch in Your Fork?

- Creating a branch for your changes is important for organization and version control. Instead of making all changes on the main main branch of your fork, each new feature or edit is created in its own branch, such as update-physics-notes.
- This keeps your work separated, so if you decide not to pursue a change or make a mistake, you can abandon that branch without affecting anything else.
- It’s especially useful if you’re making multiple contributions to the same repo; you can work on several things at once without merging unfinished work.

### Why Push to Your Forked Repository First?
- Pushing to your fork allows you to review your changes on GitHub and make sure they appear as expected. It’s like a final checkpoint before you formally suggest merging them into the main project.
- This also avoids overwhelming the main repository with multiple incomplete changes and commits.

### Why Not Directly Update the Main Repository?
- Only trusted maintainers have direct write access to the main repository. This prevents unwanted edits and ensures a high standard for contributions.
- It also maintains consistency. Multiple people making direct edits without review could lead to errors, conflicts, and confusion in the main project’s content.

## Contribution & Maintenance Rules

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

## Contact

If you have questions or concerns about this Code of Conduct, please reach out via one of the following methods:

- GitHub Issues: Please open an issue in the repository.
- Discussions: Feel free to post in the Discussions section of the repository for any concerns or suggestions.