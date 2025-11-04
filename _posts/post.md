---
title: Your Post Title
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [Category1, Category2]
tags: [tag1, tag2]
math: true
include_scripts:
  - "https://cdn.jsdelivr.net/npm/katex@0.16.0/dist/katex.min.js"
  - "/assets/js/latex-renderer.js"
---
Your content goes here...

<div id="math-container"></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const mathContainer = document.getElementById('math-container');
  
  // Example: Render LaTeX equation
  katex.render("E = mc^2", mathContainer, {
    throwOnError: false
  });
});
</script>
