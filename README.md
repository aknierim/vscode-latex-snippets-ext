# LaTeX Snippets EXT

LaTeX Snippets EXT is an extension for Visual Studio Code that provides a collection of simple snippets for .tex files.

## Features

LaTeX Snippets EXT features code snippets for the following keywords:
<details><summary>1. Preamble, Headers, Classes </summary>
    <ul>
    <li> <code>RequirePackage</code> </li>
    <li> <code>usepackage</code> </li>
    <li> <code>LoadClass</code> </li>
    <li> <code>documentclass</code> </li>
    <li> <code>input</code> </li>
    <li> <code>newcommand</code> </li>
    <li> <code>renewcommand</code> </li>
    <li> <code>NewDocumentCommand</code> </li>
    </ul>
</details>
<details><summary>2. Document structure: Parts, chapters, sections and paragraphs</summary>
    <ul>
    <li> <code>part</code> </li>
    <li> <code>chapter</code> </li>
    <li> <code>section</code> </li>
    <li> <code>subsection</code> </li>
    <li> <code>subsubsection</code> </li>
    <li> <code>paragraph</code> </li>
    <li> <code>subparagraph</code> </li>
    </ul>
</details>
<details><summary>3. Environments</summary>
    <ul>
    <li> <code>\begin{}...\end{}</code> </li>
    <li> <code>equation(*)</code> </li>
    <li> <code>align(*)</code> </li>
    <li> <code>gather(*)</code> </li>
    <li> <code>split(*)</code> </li>
    <li> <code>multiline(*)</code> </li>
    <li> <code>matrix</code> </li>
    <li> <code>matrix</code> (tabularray) </li>
    <li> <code>cases</code> </li>
    <li> <code>center</code> </li>
    <li> <code>flushleft</code> </li>
    <li> <code>flushright</code> </li>
    <li> <code>minipage</code> </li>
    </ul>
</details>
<details><summary>4. Lists</summary>
    <ul>
    <li> <code>itemize</code> </li>
    <li> <code>description</code> </li>
    <li> <code>enumerate</code> </li>
    </ul>
</details>
<details><summary>5. Figures & Tables</summary>
    <ul>
    <li> <code>figure</code> </li>
    <li> <code>tabular</code> </li>
    <li> <code>usepackage</code> </li>
	<li> <code>tblr</code> (tabularray) </li>
    <li> <code>usepackage</code> </li>
    </ul>
</details>
<details><summary>6. Math</summary>
    <ul>
    <li> Inline </li>
        <ul>
            <li> <code>Inline Math \(\)</code> </li>
            <li> <code>Display Math \[\]</code> </li>
        </ul>
    <li> Fonts </li>
        <ul>
            <li> <code>mathit</code> </li>
            <li> <code>mathbf</code> </li>
            <li> <code>mathbb</code> </li>
            <li> <code>mathrm</code> </li>
            <li> <code>mathsf</code> </li>
            <li> <code>mathtt</code> </li>
            <li> <code>mathcal</code> </li>
        </ul>
    <li> <code>sum</code> </li>
    <li> <code>prod</code> </li>
    <li> <code>int</code> </li>
    <li> <code>lim</code> </li>
    <li> <code>partial</code> </li>
    <li> <code>frac</code> </li>
    </ul>
</details>
<details><summary>7. TikZ</summary>
    <ul>
    <li> <code>tikzpicture</code> </li>
    <li> <code>scope</code> </li>
    <li> <code>coordinate</code> </li>
    <li> <code>draw</code> </li>
    <li> <code>node</code> </li>
    </ul>
</details>
<details><summary>8. Other</summary>
    <ul>
    <li> Beamer </li>
        <ul>
            <li> <code>frame</code> </li>
            <li> <code>columns</code> </li>
        </ul>
    <li> <code>label</code> </li>
    <li> <code>cite</code> </li>
    <li> <code>item</code> </li>
    <li> <code>item[description]</code> </li>
    <li> <code>autoref</code> </li>
    <li> <code>eqref</code> </li>
    <li> <code>ref</code> </li>
    <li> Colors </li>
        <ul>
            <li> <code>xdefinecolor</code> </li>
            <li> <code>colorlet</code> </li>
        </ul>
    <li> Glossaries </li>
        <ul>
            <li> <code>newacronym</code> </li>
            <li> <code>newglossaryentry</code> </li>
            <li> <code>gls</code> </li>
            <li> <code>glspl</code> </li>
            <li> <code>glsdesc</code> </li>
            <li> <code>makeglossaries</code> </li>
            <li> <code>printglossaries</code> </li>
        </ul>
    </ul>
</details>


## Usage

Open a .tex file in VS Code and either type in the name of a snippet or use Ctrl+Space to show a list of available snippets.


## Requirements

This extension does not require any additional extensions to be installed.


## Extension Settings

Although this extension does not have any settings, you may need to add the following setting to your `.vscode/settings.json` file to use the extension:

```json
"[latex]": {
    "editor.quickSuggestions": {
        "other": "on",
        "comments": "on"
    }
}
```
---

## Release Notes

### 1.0.0
Initial release of the LaTeX Snippets EXT extension.

##### Features
- Various LaTeX snippets


