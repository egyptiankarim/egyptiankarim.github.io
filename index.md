---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<div class="row justify-content-center">
  <div class="col-12 col-sm-10 col-md-8 col-lg-6 col-xl-5">

    <div class="card">
      <!-- <div class="card-header"></div> -->

      <div class="card-picture">
        <img id="avi" alt="{{ site.author }}" title="{{ site.author }}" src="{{ site.gravatar_url }}" />
      </div>

      <div class="card-body text-center">
        <h1 class="card-title">{{ site.author }}</h1>
        <p class="card-text text-muted">Computer Nerd</p>
        <p><strong><em>Washington, DC</em></strong></p>
      </div>

      <div class="card-space">
      </div>

      <div class="card-footer text-center">
        <p>
          <a href="{{ site.linkedin_url }}" class="text-dark">
            <i class="fa fa-linkedin" aria-hidden="true"></i>
          </a>
          <a href="{{ site.github_url }}" class="text-dark">
            <i class="fa fa-github-alt" aria-hidden="true"></i>
          </a>
          <a href="{{ site.medium_url }}" class="text-dark">
            <i class="fa fa-medium" aria-hidden="true"></i>
          </a>
          <a href="{{ site.twitter_url }}" class="text-dark">
            <i class="fa fa-twitter" aria-hidden="true"></i>
          </a>
        </p>
      </div>
    </div>

  </div>
</div>
