---
permalink: /test
---
|path|name|basename|extname|modified_time|output_ext|permalink|test|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|{% for file in site.static_files %}
|{{file.path}}|{{file.name}}|{{file.basename}}|{{file.extname}}|{{file.modified_time}}|{{file.output_ext}}|{{file.permalink}}|{{file.test}}|{% endfor %}
