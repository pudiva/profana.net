---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Music
permalink: /music/

medias:
  - url: https://music.apple.com/us/artist/ventura-profana/1484569973
    name: Apple Music
  - url: https://open.spotify.com/artist/5OtKmdYx2SsAzr6RjrwAip
    name: Spotify
  - url: https://www.deezer.com/en/artist/76040832
    name: Deezer
  - url: https://tidal.com/browse/artist/17144167
    name: Tidal
  - url: https://www.youtube.com/c/VenturaProfanaypodeserdesligado
    name: YouTube
---

<div style="text-align: center">
  <img src="/assets/traquejos-capa-500.jpg" width="500" style="max-width: 100%"/>

  <br>

  <ul style="margin: 0; padding: 0">
    {%- for media in page.medias -%}
      <li style="display: inline; margin: 1em; padding: 0;">
        <a href="{{media.url}}">
          {{media.name}}
        </a>
      </li>
    {%- endfor -%}
  </ul>
</div>
