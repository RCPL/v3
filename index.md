---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
titleAfter: Ebooks, movies, music, and events free for Richland Library cardholders.
---

<section>
  <h2>The Catalog</h2>
  <form>
  <input type="text" placeholder="e.g. 'nikola tesla' or 'ghost towns'">
  <button>Search</button>
  </form>

  <h3>Top Authors</h3>
  <ul>
    <li>Martel, Yann</li>
    <li>Rowling, J.K.</li>
    <li>Vonegut, Kurt</li>
  </ul>
</section>

<h3>Events</h3>
<ul>
{% for event in site.events %}
  <li>
    <a href="{{event.url}}">{{event.title}}</a>
    {{event.excerpt}}
  </li>
{% endfor %}
</ul>

<section class="newsletter cushion">
  <form>
  <p>Subscribe to the Richland Library Newsletter and enjoy written wonders delivered straight to your inbox.</p>
  <input type="email" placeholder="Your Email">
  <button>Subscribe</button>
  </form>
</section>
