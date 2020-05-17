<template>
  <div class="about" id="about">
    <div class="ttl mt-5 mb-4">about - Skills</div>
    <div class="d-flex flex-row w-75 mx-auto">
      <ul class="col text-left">
        <li>
          <div>
            <img src="../images/ai.svg" width="" height="">
          </div>
          <div class="skil_ttl">Illustrator</div>
        </li>
        <li>
          <div>
            <img src="../images/ps.svg" width="" height="">
          </div>
          <div class="skil_ttl">photoshop</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/html-5.svg" width="" height="">
          </div>
          <div class="skil_ttl">HTML</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/css-3.svg" width="" height="">
          </div>
          <div class="skil_ttl">CSS</div>
        </li>
      </ul>
      <ul class="col text-left">
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/sass.svg" width="" height="">
          </div>
          <div class="skil_ttl">Sass</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/bootstrap.svg" width="" height="">
          </div>
          <div class="skil_ttl">Bootstrap</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/javascript.svg" width="" height="">
          </div>
          <div class="skil_ttl">Javascript</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/jquery.svg" width="" height="">
          </div>
          <div class="skil_ttl">JQuery</div>
        </li>
      </ul>
      <ul class="col text-left">
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/vue.svg" width="" height="">
          </div>
          <div class="skil_ttl">Vue</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/wordpress-icon.svg" width="" height="">
          </div>
          <div class="skil_ttl">Wordpress</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/brackets.svg" width="" height="">
          </div>
          <div class="skil_ttl">Brackets</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/visual-studio-code.svg" width="" height="">
          </div>
          <div class="skil_ttl">VisualStudioCode</div>
        </li>

      </ul>
      <ul class="col text-left">
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/git.svg" width="" height="">
          </div>
          <div class="skil_ttl">Git</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/gitlab.svg" width="" height="">
          </div>
          <div class="skil_ttl">Gitlab</div>
        </li>
        <li>
          <div>
            <img src="../images/redmine.png" width="130px" height="">
          </div>
          <div class="skil_ttl">redmine</div>
        </li>
        <li>
          <div>
            <img src="https://cdn.svgporn.com/logos/google-analytics.svg" width="" height="">
          </div>
          <div class="skil_ttl">GoogleAnalytics</div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
  .about {
    height: 1000px;
    background-color: #ffffff;
  }

  ul {
    list-style: none;

  }

  ul li {
    height: 120px;
    position: relative;
    display: flex;

  }

  ul li img {
    position: absolute;
    top: 50%;
    left: 0;
    width: 70px;
  }

  .skil_ttl {
    position: absolute;
    top: 50%;
    left: 35%;
    font-size: 1.3rem;
  }

</style>
