---
permalink: /test
---

|path|name|basename|extname|modified_time|permalink|test|
|:--:|:--:|:------:|:-----:|:-----------:|:-------:|:--:|
{% for file in site.static_files %}|{{file.path}}|{{file.name}}|{{file.basename}}|{{file.extname}}|{{file.modified_time}}|{{file.permalink}}|{{file.test}}|{% endfor %}
