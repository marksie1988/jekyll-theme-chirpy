---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
{: .prompt-tip }


{% include elements/progress.html title="Programming Skills" source=site.data.progress.programming %} {% include elements/progress.html title="Other Skills" source=site.data.progress.other %}
{% include about/certifications.html title="Certifications" source=site.data.certifications %}
{% include about/timeline.html source=site.data.timeline.work %}
