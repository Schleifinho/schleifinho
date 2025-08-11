<style>
  .container {
    display: flex;
    gap: 5px;
    align-items: stretch; /* make both divs the same height */
  }
  .stats {
    flex: 2;
  }
  .languages {
    flex: 1;
  }
  .grid {
    flex: 1;
  }
  picture, img {
    width: 100%;
    height: auto;
  }
</style>

<div class="container">
  <div class="stats">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api?username=schleifinho&show_icons=true&theme=dracula"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api?username=schleifinho&show_icons=true"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img src="https://github-readme-stats.vercel.app/api?username=schleifinho&show_icons=true" alt="GitHub Stats" />
    </picture>
  </div>
  <div class="languages">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=schleifinho&layout=donut&hide=Java&theme=dracula"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=schleifinho&layout=donut&hide=Java"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=schleifinho&layout=donut&hide=Java" alt="Top Languages" />
    </picture>
  </div>
</div>
<div class="container">
  <div class="grid">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=pubg-circle-analyzer&theme=dracula"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=pubg-circle-analyzer"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=pubg-circle-analyzer&layout=compact&langs_count=8&show_icons=true" alt="PUBG Circle Analyzer" />
    </picture>
  </div>
  <div class="grid">
    <picture>
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=wave-function-collapse-texture-generator&theme=dracula"
        media="(prefers-color-scheme: dark)"
      />
      <source
        srcset="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=wave-function-collapse-texture-generator"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
      />
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=schleifinho&repo=wave-function-collapse-texture-generator" alt="Wave Function Collapse" />
    </picture>
  </div>
</div>