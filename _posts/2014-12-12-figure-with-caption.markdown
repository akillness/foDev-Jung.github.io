---
title: Figure With A Caption
layout: post
date: '2014-12-12'
---

<p class="intro"><span class="dropcap">L</span>Test</p>

아직 테스트단계입니다.

<figure>
	<img src="{{ '/assets/img/touring.jpg' | prepend: site.baseurl }}" alt=""> 
	<figcaption>Fig1. - This is an example figcaption</figcaption>
</figure>

{%- highlight html -%}
<figure>
	<img src="{{ '/assets/img/touring.jpg' | prepend: site.baseurl }}" alt=""> 
	<figcaption>Fig1. - This is an example figcaption</figcaption>
</figure>
{%- endhighlight -%}

내용을 어떻게 구성해야할까
