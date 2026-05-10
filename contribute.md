---
layout: default
title: Contribute
permalink: /contribute/
---

<div class="contribute-page-wrapper">
  <div class="contribute-hero">
    <h1 class="hero-title">Contribute to Arabic Pathway</h1>
    <p class="hero-subtitle">Help us make learning Quranic Arabic accessible and engaging for everyone.</p>
  </div>

  <div class="contribute-sections">
    <div class="contribute-card">
      <div class="card-header">
        <div class="icon-wrapper">💻</div>
        <h2>Contribute Code</h2>
      </div>
      <div class="card-body">
        <p>Are you a web developer? You can contribute by fixing bugs, adding new features, or improving the UI.</p>
        <p>The code is Open Source and available on GitHub. You are more than welcome to create a PR for your contribution, Inshallah.</p>
        <a href="https://github.com/Huzaifa-code/ArabicPathwayBlogs" class="btn-primary mt-3" target="_blank">View on GitHub</a>
      </div>
    </div>

    <div class="contribute-card">
      <div class="card-header">
        <div class="icon-wrapper">✍️</div>
        <h2>Contribute Content</h2>
      </div>
      <div class="card-body">
        <p>Thank you for your interest in contributing! Writing blog posts helps other students immensely.</p>
        <p>To write an article, simply create a Markdown (<code>.md</code>) file following our formatting guidelines.</p>
        <a href="mailto:developerhuzaifa@gmail.com" class="btn-secondary mt-3">Submit Article via Email</a>
      </div>
    </div>
  </div>

  <div class="markdown-guide-section">
    <h2>Markdown Formatting Guide</h2>
    <p class="guide-intro">Here's how to style your content using Markdown and our custom classes.</p>

    <div class="guide-grid">
      <div class="guide-item">
        <h3>Headings</h3>
        <div class="code-preview">
          <code># Heading 1</code>
          <code>## Heading 2</code>
        </div>
        <p class="note-small">Arabic text with # or ## will get underline highlight automatically.</p>
      </div>

      <div class="guide-item">
        <h3>Lists</h3>
        <div class="code-preview">
          <code>- Item 1</code>
          <code>- Item 2</code>
          <code>  - Subitem</code>
        </div>
      </div>

      <div class="guide-item">
        <h3>Custom Highlighting</h3>
        <div class="code-preview">
          <code>&lt;span class="hl"&gt;Highlighted text&lt;/span&gt;</code>
        </div>
        <div class="preview-box">
          <span class="hl">Highlighted text</span>
        </div>
      </div>

      <div class="guide-item">
        <h3>Urdu Font</h3>
        <div class="code-preview">
          <code>&lt;p class="ur" dir="rtl"&gt;تعریف اللہ کے لیے ہے&lt;/p&gt;</code>
        </div>
        <div class="preview-box">
          <p class="ur" dir="rtl">تعریف اللہ کے لیے ہے</p>
        </div>
      </div>
    </div>

    <div class="frontmatter-guide">
      <h3>Required Frontmatter</h3>
      <p>Make sure to add this at the top of your file:</p>
      <div class="code-block">
        <pre><code>---
layout: post
title:  "Your Blog Title"
date:   YYYY-MM-DD HH:MM:SS +0530
categories: category_name
author: Your Name
img: image_url
---</code></pre>
      </div>
      <p class="file-name-instruction">Save the text file as <strong>yyyy-mm-dd-blog-title.md</strong> (e.g., 2024-09-24-How-To-Contribute.md)</p>
    </div>
  </div>
</div>