# System design template: excalidraw - `emoji edition`

> Rough shapes to do rapid system design in front-end, full-stack, back-end, distributed, and product settings.

<details open><summary>Preview</summary>
  <p><img src="https://user-images.githubusercontent.com/4022631/126106256-a60fc6c8-1924-4fe2-9a02-78c38254f060.png" alt="System design template preview (emoji, aretecode)"></p>
</details>

<details><summary>Goals</summary>
  <ol>
    <li>Make it easy to do common system designs.</li>
    <li>Make system design faster.</li>
  </ol>
</details>

## Usage

### [1. Download]
[1. Download]: #-download--clone

```bash
gh repo clone aretecode/system-design-templates-excalidraw && cd system-design-templates-excalidraw/src && ((open .) || (open `pwd`))
```


<details><summary><strong>See in action</strong></summary>

![system-design-template-aretecode--how-to-download](https://user-images.githubusercontent.com/4022631/126106274-4e416beb-9bd9-4c76-92e4-d0c33a145245.gif)
_clones repo, cd to cloned dir, and opens in finder/explorer._

</details>

### [2. Use in excalidraw]
[2. Use in excalidraw]: #-use-in-excalidraw

<details><summary><strong>See how to</strong></summary>

![system-design-template-aretecode--how-to-import-to-excalidraw](https://user-images.githubusercontent.com/4022631/126106181-d37baa44-105f-4253-8fea-3d5b88fa22c4.gif)

</details>

## More

<details>
  <summary><u><i>How to customize?</i></u> <a href="#-tips-faq--customization">🔗<a></summary>
  <p><img src="https://user-images.githubusercontent.com/4022631/126106291-eb966e66-6ee2-4abb-9f8c-e7649d9e03da.gif" alt="system-design-template-aretecode-excalidraw--how-to-customize-and-use-tips" /></p>
</details>
<details>
  <summary><u><i>There are so many icons, how do you use this in a real world setting?</i></u> <a href="#-tips-faq--too-big">🔗<a></summary>
  <p>Open 2 tabs, 1 you can drop in all the icons, then copy into the other tab, delete the unused, then re-arrange as-needed.</p>
  <p><img src="https://user-images.githubusercontent.com/4022631/126108386-952c197f-46c0-4dee-b7ca-bb10d71122af.gif" alt="system-design-template-aretecode--how-to-use-across-tabs-quickly" /></p>
</details>
<details>
  <summary><u><i>Why are the shapes not each in their own library component?</i></u> <a href="#-tips-faq--why-shapes-in-1">🔗<a></summary>
  <p>When I used other libraries on excalidraw, it was difficult to see the shape from the thumbnail/preview. Without a search feature, I found myself dragging and dropping each shape 1-by-1 to find the one I was looking for. The shapes here are loosely-grouped. This (ideally) makes the icons easier to find and copy in to any system design.</p>
</details>
<details><summary><i>How to use in excalidraw without a gif?! TLDR</i></summary>
  <ul>
    <li>Open <a href="https://excalidraw.com">excalidraw</a>.</li>
    <li>Open library (<em>at the top right</em>).</li>
    <li>Click import (<em>folder icon</em>).</li>
    <li>Select the <code>.excalidrawlib</code> from your computer.</li>
  </ul>
</details>
<details><summary><i>I want to download some other way, how?</i> <a href="#-tips-faq--why-shapes-in-1">🔗<a></summary>
  <h5>wget</h5>
  <pre><code class="lang-bash">wget -O "system-design-template-emoji.excalidrawlib" "https://raw.githubusercontent.com/aretecode/system-design-templates-excalidraw/main/src/system-design-template-emoji.excalidrawlib"
  </code></pre>
  <h5>Save file</h5>
  <ol>
    <li>Open the <a href="https://github.com/aretecode/system-design-templates-excalidraw/raw/main/src/system-design-template-emoji.excalidrawlib">raw library file</a></li>
    <li>Press <a href="https://support.google.com/chrome/answer/95759?hl=en&amp;co=GENIE.Platform%3DDesktop"><code>Command-S</code> (<em><code>[Cmd ⌘]</code> + <code>[s]</code> on osx, <code>Ctrl+S</code> on windows</em>) to save the file</a>.</li>
    <li>Append <code>.excalidrawlib</code> extension to the file name <strong>and</strong> change format from <code>txt</code> to <code>all files</code>.</li>
    <li>Click save in the save-as modal.</li>
  </ol>
  <hr />
</details>
<details>
  <summary><u><i>What tools did you use?</i></u><a href="#-tips-faq--tools used">🔗<a></summary>
  <section>
  <ul>
    <li><a href="https://excalidraw.com">excalidraw</a> to create and use the library</li>
    <li><a href="https://imageoptim.com/">imageoptim</a> to reduce size of images exported by excalidraw</li>
    <li><a href="https://github.com/excalidraw/excalidraw-libraries">excalidraw libraries</a> for naming, formatting, library standards and instructions</li>
    <li><a href="https://emoji.muan.co/">emoji.muan</a> to search for emoji</li>
    <li><a href="https://github.com/sindresorhus/Gifski">Gifski</a> to convert mov recordings to gif</li>
    <li><a href="https://github.com/keycastr/keycastr">keycastr</a> to show key strokes</li>
    <li><a href="https://docs.github.com/en/github/writing-on-github">github md docs for reference</a> <a href="https://github.github.com/gfm/">gfm</a></li>
  </ul>
  </section>
</details>
