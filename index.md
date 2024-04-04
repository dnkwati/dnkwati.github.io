---
layout: page
---

<section class="homepage">
  <div class="article__content">
    <h1> {{ site.description }} </h1>
    <p>
      I am committed to empowering people <br />
      make their dreams and <br />
      imaginations a reality <br />
      by promoting persistence, <br />
      creativity and teamwork.
    </p>
    <p>
      <a
        class="button-fancy learn-more margin-1-0"
        href="{{ '/about' | relative_url }}">
        <!-- Learn more <span class="material-symbols-outlined font14"> chevron_right </span> -->
        <span class="circle" aria-hidden="true">
          <span class="icon arrow"></span>
        </span>
        <span class="button-text">Who I am?</span>
      </a>
    </p>
  </div>
  <p></p>
  <!-- <a
    href="mailto:drnkwati+web@gmail.com"
    title="Leave a message">
    <span class="material-symbols-outlined font48 fg-gray"> mail </span>
  </a> -->
  <div class="article__content">
    <p>
      Do you wish to find out what I am currently working on?
    </p>
    {% include links2social4git.md %}
  </div>
</section>
