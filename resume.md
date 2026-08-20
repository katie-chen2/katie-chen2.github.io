---
title: Resume
feature_text: |
  View my resume below or open the PDF directly if your browser does not support inline previews.
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "Resume page with an embedded PDF preview."
aside: true
---

<div class="resume-embed">
  <object data="{{ '/assets/resume.pdf' | relative_url }}" type="application/pdf">
    <p>
      Your browser cannot display PDFs inline.
      <a href="{{ '/assets/resume.pdf' | relative_url }}">Download the resume PDF</a>.
    </p>
  </object>
</div>

<p class="resume-actions">
  <a href="{{ '/assets/resume.pdf' | relative_url }}">Download the PDF version</a>
</p>

<p class="resume-actions">
  Put the exported resume PDF at <code>/assets/resume.pdf</code> so the embed and download links work.
</p>