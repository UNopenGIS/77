---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## UN Open GIS / DWG-7: Smart Maps / Objective 7: Core

---

### File Formats

{% for page in site.en_File_Formats %}

- [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
  {% endfor %}

---

### File Extensions

{% for page in site.en_File_Extensions %}

- [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
  {% endfor %}
