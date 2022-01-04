
## Hi there

<ul>
    
      {%- for post in site.posts -%}
      <li>
        
        <h3>
          <a href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>
