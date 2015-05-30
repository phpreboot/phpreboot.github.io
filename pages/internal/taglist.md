---
layout: default
permalink: /internal/taglist/
---
<ul id="tags">
</ul>

<script language="javascript">
var tags = [{% for tag in site.tags %} "{{ tag[0] }}", {% endfor %} ];
tags.sort();

var ul = document.getElementById('tags');

var arrayLength = tags.length;
for (var i = 0; i < arrayLength; i++) {
  var li = document.createElement('li');
  li.innerHTML = tags[i];
  ul.appendChild(li);
}
</script>
