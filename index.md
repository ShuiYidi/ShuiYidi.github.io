---
layout: page
title: "Home"
class: home
---

<!-- <h1 id="typewriter">Hi, I'm  Yan Luo</h1>
<style>
  #typewriter {
    font-size: 2em;
    font-weight: bold;
    font-family: monospace;
    white-space: nowrap;
    overflow: hidden;
    display: inline-block; /* 确保光标跟随文字 */
    position: relative; /* 为伪元素定位 */
    letter-spacing: 0.1em; /* 调整字符间距 */
  }
  #typewriter::after {
    content: '';
    position: absolute;
    right: 0;
    width: 0.15em;
    background-color: orange;
    animation: blink-caret 0.75s step-end infinite;
  }
  @keyframes blink-caret {
    from, to { border-color: transparent; }
    50% { border-color: orange; }
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const element = document.getElementById("typewriter");
    const text = element.innerText;
    element.innerText = ""; // 清空初始文本
    let i = 0;
    const speed = 300; // 打字速度，单位为毫秒

    function typeWriter() {
      if (i < text.length) {
        if (text.charAt(i) === ' ') {
          element.innerHTML += '&nbsp;'; // 添加空格字符
        } else {
          element.innerHTML += text.charAt(i);
        }
        i++;
        setTimeout(typeWriter, speed);
      }
    }

    typeWriter();
  });
</script> -->

<div class="columns" markdown="1">

<div class="intro" markdown="1">
I'm a Mphil student in the School of Ocean & Civil Engineering at Shanghai Jiao Tong University. Before that, I received my Bachelor’s Degree from Huazhong University of Science and Technology in Wuhan.

<!-- My interest lies in [Data Visualization](https://yanluo0913.github.io) and [Human-Computer Interaction(HCI)](https://yanluo0913.github.io). I have experience in developing Visual Analytics System. Now, I'm seeking opporunity for [Data Storytelling]((https://yanluo0913.github.io)). -->

In my spare time, I enjoy citywalk, taking photos, and playing open-world rpg games. If you're interested in these things, feel free to chat with me:)
</div>

<div class="me" markdown="1">
<picture>
  <source srcset='/images/Shui.webp' type='image/webp' />
  <img
    src='/images/Shui.jpg'
    alt='Yan Luo'>
</picture>

{:.no-list}
* <a href="mailto:{{ site.email }}">{{ site.email }}</a>
</div>

</div>

<!-- During my first year at UW, I received support from the [Fulbright program](https://en.wikipedia.org/wiki/Fulbright_Program). In 2013, I received my B.S. from [Hasso Plattner Institute](https://hpi.de/). I am a scholar of the [German National Academic Foundation](http://www.studienstiftung.de/). I have worked with the [Open Knowledge Foundation](http://www.okfn.org), [Google Research](https://ai.google/research/), [Microsoft Research](https://www.microsoft.com/en-us/research/group/vibe/), and others. Details are in my [CV]({{ "/cv/" | relative_url }}). -->

<!-- ## <a href="">News</a>

<div class="news">
  {% assign news_all = site.data.news %}
  {% for news in news_all %}
      {% include news.html news=news %}
  {% endfor %}
</div> -->
<!-- 如何做成折叠卡片式 -->

<!-- ## <a href="">Publications</a>

<div class="featured-projects">
  {% assign sorted_projects = site.data.projects %}
  {% for project in sorted_projects %}
    {% if project.highlight %}
      {% include project.html project=project %}
    {% endif %}
  {% endfor %}
</div>

## <a href="">Memories</a>

<div class="featured-memories">
  <!-- {% assign sorted_memories = site.data.memories %} -->
  {% assign sorted_memories = site.data.memories | sort: 'highlight' %}
  {% for memories in sorted_memories %}
    {% if memories.highlight == 1 or memories.highlight == 2 or memories.highlight == 3 %}
      {% include memories.html memories=memories %}
    {% endif %}
  {% endfor %}

</div>

<div class="featured-memories">
  {% assign sorted_memories = site.data.memories | sort: 'highlight' %}
  {% for memories in sorted_memories %}
    {% if memories.highlight == 4 or memories.highlight == 5 or memories.highlight == 6 %}
      {% include memories.html memories=memories %}
    {% endif %}
  {% endfor %}
</div> -->


<!-- <a href="{{ "/projects/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show More Projects
</a> -->

<!-- ## <a href="{{ "/publications/" | relative_url }}">Memories</a>

<div class="featured-publications">
  {% assign sorted_publications = site.publications | sort: 'year' | reverse %}
  {% for pub in sorted_publications %}
    {% if pub.highlight %}
      <a href="{{ pub.pdf }}" class="publication">
        <strong>{{ pub.title }}</strong>
        <span class="authors">{% for author in pub.authors %}{{ author }}{% unless forloop.last %}, {% endunless %}{% endfor %}</span>.
        <i>{% if pub.venue %}{{ pub.venue }}, {% endif %}{{ pub.year }}</i>.
        {% for award in pub.awards %}<br/><span class="award"><i class="fas fa-{% if award == "Best Paper Award" %}trophy{% else %}award{% endif %}" aria-hidden="true"></i> {{ award }}</span>{% endfor %}
      </a>
    {% endif %}
  {% endfor %}
</div> -->

<!-- <a href="{{ "/publications/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show All Publications
</a> -->

