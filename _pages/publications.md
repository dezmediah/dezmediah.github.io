---
layout: page
permalink: /publications/
title: publications
description: Selected scholarly and creative publications
nav: true
---

### Peer-Reviewed Publications

<div class="publications">
{% bibliography --query @*[keywords~=peer-reviewed] %}
</div>

<div style="border-top:2px solid var(--global-text-color); margin:2rem 0;"></div>

### Creative Writing

<div class="publications">
{% bibliography --query @*[keywords~=creative writing] %}
</div>
