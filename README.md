
# $\LaTeX$ with GitHub, VS Code and Zotero for research teams

This small tutorial teaches you how to use LaTeX effectively with VS Code, Zotero and GitHub. Follow the steps below to set-up an environment to these tools to your LaTeX projects. The result will be a clean modern LaTeX environment with GitHub's version control capabilities and Zotero's power to manage bibliographies. The proposed set-up is well suited for collaborative projects in research & academic teams: you may use it for, e.g., efficient grant writing, grant proposals or preparing reports. The combination of these open-source tools offers a powerful alternative that supersedes commercial alternatives with locked premium features, such as Overleaf.

# Workflow & requirements

The workflow we will use requires the following setup of software tools:

1. A LaTeX distribution: We recommend TeX Live in Linux and MikTex in Windows. These are  widely used distributions that includes all of the necessary programs and files to typeset LaTeX documents.

2. A text editor: VS Code is a popular choice among LaTeX users, and it has a built-in extension that provides rich LaTeX support.

3. LaTeX Workshop Extension: An extension for VS Code that provides rich LaTeX support, such as autocompletion, linting, and building.

4. Git: A version control system that allows you to collaborate with others on the same LaTeX project.

5. GitHub Extension: An extension for VS Code that allows you to connect to GitHub and collaborate on LaTeX projects with others.

6. Zotero: A reference management software that allows you to store and organize your bibliographic references and citations, and can be integrated with LaTeX.

7. Zotero Connector: A browser extension that allows you to save references from webpages to your Zotero library.

8. LaTeX-Zotero-Integration package: A package that allows you to insert citations from your Zotero library into your LaTeX documents and automatically generate a bibliography. For VS Code: Citation Picker for Zotero. Other editors: https://retorque.re/zotero-better-bibtex/citing/cayw/

9. For Windows, install a full Perl distribution (such as Strawberry Perl) and put it in your PATH, because the VS Code LaTeX extension uses latexmk by default, which is a Perl script. Credit to: delta_p_delta_x & TUG. If you use Windows Chocolatey, you can directly install strawberryperl using Microsoft's PowerShell.

10. CTAN (Comprehensive TeX Archive Network) is a vast collection of TeX-related resources that includes a wide variety of LaTeX packages, styles, and fonts.

