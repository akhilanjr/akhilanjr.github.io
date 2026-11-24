---
title: "CV"
permalink: /cv/
---

{% assign cv = "/assets/files/Akhilan_J_R_CV.pdf" | relative_url %}
{% assign v = site.time | date: "%s" %}

[Download PDF]({{ cv }}?v={{ v }}){: .btn .btn--primary}
<small>Last updated {{ site.time | date: "%-d %B %Y" }}</small>

<object data="{{ cv }}?v={{ v }}#view=FitH" type="application/pdf" width="100%" style="height: 85vh; border: 1px solid #ddd;">
  <p>Your browser can't show the PDF here. <a href="{{ cv }}">Download it instead.</a></p>
</object>
