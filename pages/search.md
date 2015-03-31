---
layout: page
show_meta: false
title: "Busqueda"
header: no
permalink: "/busqueda/"
---

{% include google_search.html %}

<form style="padding-bottom: 200px;" onsubmit="google_search()" >
<input type="text" id="google-search" placeholder="...">
<input type="submit" value="Buscar">
</form>
