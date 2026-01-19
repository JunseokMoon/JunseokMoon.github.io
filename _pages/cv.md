---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 3
description: 
---

{% assign cv_filename = 'CV_Jan19_2026_JSM.pdf' %}

{% capture cv_path %}assets/pdf/{{ cv_filename }}{% endcapture %}

<div class="row" style="margin-bottom: 30px; justify-content: center;">
  <a href="{{ cv_path | relative_url }}" target="_blank" class="btn btn-sm z-depth-1" style="font-size: 1.1rem; padding: 10px 20px;">
    <i class="fas fa-file-pdf"></i> Download PDF
  </a>
</div>

<div class="row">
  <div class="col-sm-12" style="height: 100vh;">
    <object data="{{ cv_path | relative_url }}" type="application/pdf" width="100%" height="100%">
      <p>
        Your web browser doesn't have a PDF plugin.
        Instead you can <a href="{{ cv_path | relative_url }}">click here to download the PDF file.</a>
      </p>
    </object>
  </div>
</div>
