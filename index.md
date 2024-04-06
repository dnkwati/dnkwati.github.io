---
layout: page
---

<section class="homepage">
  <div class="article__content">
    <h1> Full Stack <br> {{ site.description }} <br> For Hire </h1>
    <p>
      I am committed to empowering people <br />
      make their dreams and imaginations <br />
      a reality by promoting <br />
      persistence, creativity and teamwork.
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
  <div class="article__content">
    <p>
      Do you wish to find out what I am currently working on?
    </p>
    {% include links2socialising4git.md %}
  </div>
</section>
