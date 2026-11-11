---
title: "Zotero Literature Connection for Obsidian"
excerpt: "Keep papers and notes connected. Find your Obsidian notes from Zotero, or return to the paper’s Zotero entry with one click."
collection: portfolio
area: "Research workflow tools"
group: "Small tools"
period: "2026"
order: 6
preview_image: "/images/zotero-literature-note.png"
preview_alt: "An Obsidian literature note with a link to its Zotero source"
github: "https://github.com/fab1s/zotero-literature-link"
---

If you keep references and PDFs in Zotero and write literature notes in Obsidian, you often want to open your notes while looking at a paper. A link in the Obsidian note can take you back to the source. From the Zotero item, finding the matching note meant searching in Obsidian or adding and maintaining a link by hand.

When you create a literature note from a Zotero link, the plugin creates links in both directions. It puts a link to the source in the note and adds an **Obsidian attachment** alongside the PDF in Zotero. You can also add that attachment for an existing note that already links to the Zotero item. After Zotero syncs, the attachment opens the matching note directly. The plugin can update the attachment link when you move or rename the note.

<div class="paper-figure-pair">
  <figure class="paper-figure">
    <a href="{{ page.preview_image | relative_url }}">
      <img src="{{ page.preview_image | relative_url }}" alt="{{ page.preview_alt | escape }}" width="991" height="412" loading="lazy">
    </a>
    <figcaption><span class="paper-figure__label">Figure 1.</span> A literature note in Obsidian with a link back to its Zotero entry.</figcaption>
  </figure>
  <figure class="paper-figure">
    <a href="{{ '/images/zotero-attachment.png' | relative_url }}">
      <img src="{{ '/images/zotero-attachment.png' | relative_url }}" alt="The Zotero attachments list showing a PDF and an Obsidian link" width="330" height="122" loading="lazy">
    </a>
    <figcaption><span class="paper-figure__label">Figure 2.</span> The Zotero entry with an attachment that opens the Obsidian note.</figcaption>
  </figure>
</div>

[Code and installation instructions on GitHub](https://github.com/fab1s/zotero-literature-link).

Agentically engineered with OpenAI Codex under human direction.

[← All projects](/projects/)
