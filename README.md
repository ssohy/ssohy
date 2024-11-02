<style>
  /* 기본 스타일 */
  .container {
    text-align: center;
  }

  .capsule-image {
    width: 100%;
    max-width: 800px;
  }

  .stats-container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  /* 화면 너비가 768px 이하일 때 */
  @media (max-width: 768px) {
    .capsule-image {
      width: 90%;
      height: auto;
    }

    .stats-container h3 {
      font-size: 1.2em;
    }
  }

  /* 화면 너비가 480px 이하일 때 */
  @media (max-width: 480px) {
    .capsule-image {
      width: 100%;
      height: auto;
    }

    .stats-container h3 {
      font-size: 1em;
    }
  }
</style>

<div class="container">
  <img class="capsule-image" src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=SSOHY!&fontSize=90&fontAlign=75" />
  <br>
  <h3>🌵GitHub🌵</h3>

  <div class="stats-container">
    <a href="https://github.com/ssohy/ssohy">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ssohy&langs_count=10&layout=compact&theme=dark" />
    </a>
    <br>
    <h3>🔥Baekjoon🔥&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🎆SSOHY's GitHub stats🎆</h3>
    <a href="https://solved.ac/jshpqpw/">
      <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=jshpqpw" />
    </a>
    <img src="https://github-readme-stats.vercel.app/api?username=ssohy&show_icons=true&theme=tokyonight" />
  </div>
  <br>
</div>

