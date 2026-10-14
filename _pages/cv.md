---
layout: academic
sitemap: true
description: "View and download the curriculum vitae of Xinran Liu, Economics Ph.D. candidate at the University of California, Riverside."
title: CV
permalink: /cv/
section: cv
---

<style>
.cv-toolbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 14px 24px;
  flex-wrap: wrap;
  margin: 0 0 20px;
}
.cv-updated { margin: 0; font-size: 14px; color: #697174; }
.cv-actions { display: flex; gap: 12px; flex-wrap: wrap; align-items: center; }
.cv-actions a {
  display: inline-block;
  padding: 8px 15px;
  border: 1px solid #b9c8ce;
  border-radius: 3px;
  font-size: 14px;
  font-weight: 600;
  line-height: 1.5;
}
.cv-actions a:hover { background: #f4f8fa; text-decoration: none; }
.cv-actions .cv-download { color: #fff; background: #345f70; border-color: #345f70; }
.cv-actions .cv-download:hover { background: #2b5060; }
.cv-pdf {
  display: block;
  width: 100%;
  height: 980px;
  border: 1px solid #e3e7e8;
  background: #f5f7f8;
}
.cv-fallback { margin: 12px 0 0; color: #697174; font-size: 13px; }
@media (max-width: 650px) {
  .cv-toolbar { align-items: flex-start; gap: 10px; }
  .cv-pdf { height: 70vh; min-height: 470px; }
}
</style>

<div class="cv-toolbar">
  <p class="cv-updated">Updated October 2026 · 2 pages</p>
  <div class="cv-actions">
    <a href="{{ '/assets/pdf/Xinran_Liu_CV.pdf' | relative_url }}" target="_blank" rel="noopener">Open PDF</a>
    <a class="cv-download" href="{{ '/assets/pdf/Xinran_Liu_CV.pdf' | relative_url }}" download="Xinran_Liu_CV.pdf">Download CV (PDF)</a>
  </div>
</div>

<iframe class="cv-pdf" src="{{ '/assets/pdf/Xinran_Liu_CV.pdf' | relative_url }}#view=FitH" title="Xinran Liu curriculum vitae, two-page PDF" loading="eager"></iframe>

<p class="cv-fallback">If the embedded preview does not appear on your device, use <a href="{{ '/assets/pdf/Xinran_Liu_CV.pdf' | relative_url }}" target="_blank" rel="noopener">Open PDF</a> above.</p>
