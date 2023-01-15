---
permalink: /test
---
|path|name|basename|extname|modified_time|
|-|-|-|-|-|
{% for file in site.static_files %}
|{{file.path}}|{{file.name}}|{{file.basename}}|{{file.extname}}|{{file.modified_time | date:"%H:%m"}}|
{% endfor %}
