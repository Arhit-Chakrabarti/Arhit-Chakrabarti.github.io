```html
<!-- Navigation -->
<nav style="text-align:center; font-size:18px; margin-bottom:20px;">
  <a href="/index.html">Home</a> |
  <a href="/background.html">Background</a> |
  <a href="/research.html">Research</a> |
  <a href="/teaching.html">Teaching</a> |
  <a href="/awards.html">Awards</a> |
  <a href="/cv.html">CV</a>
</nav>

<style>
.home-intro {
  display: flex;
  align-items: flex-start;
  gap: 24px;
}

.home-photo {
  width: 250px;
  max-width: 40%;
  height: auto;
  border-radius: 6px;
}

.home-text {
  flex: 1;
}

@media (max-width: 700px) {
  .home-intro {
    display: block;
  }

  .home-photo {
    width: 100%;
    max-width: 260px;
    display: block;
    margin: 0 auto 20px auto;
  }
}
</style>

<div class="home-intro">
  <img src="assets/images/Pic.jpg" alt="Arhit Chakrabarti" class="home-photo" />

  <div class="home-text">
    <p>
      I am currently a <strong>Postdoctoral Fellow</strong> in the Department of
      Statistics and Data Sciences at <strong>The University of Texas at Austin</strong>.
      My research is conducted in collaboration with <strong>Peter M&uuml;ller</strong>
      and <strong>Yang Ni</strong> at UT Austin, as well as <strong>Yanxun Xu</strong>
      from the Department of Applied Mathematics and Statistics at
      <strong>Johns Hopkins University</strong>.
    </p>

    <p>
      My primary research focuses on <strong>Bayesian nonparametrics</strong>,
      <strong>machine learning</strong>, and <strong>artificial intelligence</strong>.
      In particular, my research deals with <strong>Bayesian nonparametric clustering</strong>
      and <strong>feature allocation</strong> for complex data with additional information,
      with applications spanning <strong>genetics, multi-omics, spatial transcriptomics,
      health outcomes</strong>, and beyond.
    </p>

    <p>
      Prior to joining UT Austin, I completed my <strong>Ph.D.</strong> in
      <strong>Statistics</strong> in the Department of Statistics at
      <strong>Texas A&amp;M University</strong>. I previously earned a
      <strong>Bachelor of Science</strong> (<strong>B.Sc.</strong>) in
      <strong>Statistics</strong> from <strong>Presidency University</strong>,
      followed by a <strong>Master of Science</strong> (<strong>M.Sc.</strong>) in
      <strong>Statistics</strong> from the <strong>University of Calcutta</strong>.
      Subsequently, I worked at <strong>Novartis India Ltd.</strong> as a
      biostatistician for several years.
    </p>
  </div>
</div>
```

