---
title: Blog
permalink: /blog/
layout: page
---
{%- if site.posts.size > 0 -%}
  <div style="text-align:center">  
  <h2 class="post-list-heading">{{ page.list_title | default: "Tout | Everything" }}</h2>
  </div>
  <br><br>
    <table style="width:100%;border:none;">
      {%- for post in site.posts -%}
      <tr>
        <td style="width:15%;border:none;">
        {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        <span>{{ post.date | date: date_format }}</span>
        </td>
        <td style="border:none;">
          <a href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </td>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </tr>
      {%- endfor -%}
    </table>
<br><br>
    <div style="text-align:center"><p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p></div>
  {%- endif -%}