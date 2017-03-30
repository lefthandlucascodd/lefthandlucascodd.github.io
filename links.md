---
layout: page
title: Links
permalink: /links/
---

Follow us on Social Media:

<ul class="social-media-list">
          {% if site.facebook_username %}
          <li>
            <a href="https://www.facebook.com/{{ site.facebook_username }}">
                 <i class="fa fa-facebook"></i> Facebook
            </a>
          </li>
          {% endif %}

          {% if site.twitter_username %}
          <li>
            <a href="https://twitter.com/{{ site.twitter_username }}">
              <i class="fa fa-twitter"></i> Twitter
            </a>
          </li>
          {% endif %}

          {% if site.instagram_username %}
          <li>
            <a href="https://instagram.com/{{ site.instagram_username }}">
              <i class="fa fa-instagram" aria-hidden="true"></i> Instagram
            </a>
          </li>
          {% endif %}
        </ul>