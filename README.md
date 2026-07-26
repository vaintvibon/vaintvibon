```html
<!-- =========================
     GitHub Profile README
     ========================= -->

<!-- 상단 배너 -->
<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:6A5ACD,100:00BFFF&height=220&section=header&text=박망고&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Researcher%20%7C%20Developer&descAlignY=58&descSize=18"
/>

<h3>Efficient Vision Transformer & Dynamic Attention</h3>

<p>
  효율적인 Vision Transformer와 동적 Attention 구조를 연구하고 있습니다.
</p>

<p>
  <a href="https://github.com/깃허브아이디">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="mailto:이메일주소">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>

</div>

<br/>

<!-- 소개 -->
<h2>About Me</h2>

<ul>
  <li>Vision Transformer의 동적 Head 사용 구조를 연구하고 있습니다.</li>
  <li>저사양 환경에서도 효율적으로 작동하는 Attention 모델에 관심이 있습니다.</li>
  <li>PyTorch를 이용한 딥러닝 모델 구현과 실험을 진행합니다.</li>
  <li>생활 속 문제를 해결하는 웹·앱 서비스 개발에도 관심이 있습니다.</li>
</ul>

<br/>

<!-- 현재 연구 -->
<h2>Current Research</h2>

<table>
  <tr>
    <td width="180"><b>Research Topic</b></td>
    <td>Dynamic Attention Head for Vision Transformer</td>
  </tr>
  <tr>
    <td><b>Core Ideas</b></td>
    <td>Mini-Attention, Q-Seeding, GQA, Knowledge Distillation</td>
  </tr>
  <tr>
    <td><b>Baseline</b></td>
    <td>HydraViT, DeiT</td>
  </tr>
  <tr>
    <td><b>Framework</b></td>
    <td>PyTorch, timm</td>
  </tr>
  <tr>
    <td><b>Dataset</b></td>
    <td>CIFAR-10, ImageNet-100</td>
  </tr>
</table>

<br/>

<details>
  <summary><b>연구 구조 자세히 보기</b></summary>

  <br/>

  <p>
    저성능 환경에서는 Pooled Key/Value 기반의
    <b>Mini-Attention</b>을 사용하고,
    고성능 환경에서는 <b>Main-Attention</b>으로 확장하는 구조를 연구합니다.
  </p>

  <pre>
Low-resource device
        ↓
Mini-Attention
        ↓
Q-Seeding
        ↓
Main-Attention + GQA
        ↓
High-performance inference
  </pre>

  <ul>
    <li>Pooled Key/Value를 이용한 저비용 Attention</li>
    <li>Mini Query 정보를 Main Head에 전달하는 Q-Seeding</li>
    <li>Primary Head와 Supplementary Head의 역할 분리</li>
    <li>Head collapse 방지를 위한 Diversity Loss</li>
    <li>연산 자원에 따른 동적 Head 수 조절</li>
  </ul>

</details>

<br/>

<!-- 연구 관심 분야 -->
<h2>Research Interests</h2>

<p>
  <img src="https://img.shields.io/badge/Vision%20Transformer-5C4EE5?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dynamic%20Attention-007ACC?style=flat-square"/>
  <img src="https://img.shields.io/badge/Efficient%20AI-00A98F?style=flat-square"/>
  <img src="https://img.shields.io/badge/Grouped%20Query%20Attention-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/Knowledge%20Distillation-8A2BE2?style=flat-square"/>
  <img src="https://img.shields.io/badge/Model%20Compression-DC143C?style=flat-square"/>
</p>

<br/>

<!-- 기술 스택 -->
<h2>Tech Stack</h2>

<h3>AI & Data</h3>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
</p>

<h3>Web Development</h3>

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000000"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

<h3>Tools</h3>

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
</p>

<br/>

<!-- 프로젝트 -->
<h2>Projects</h2>

<table>
  <tr>
    <th>Project</th>
    <th>Description</th>
    <th>Tech</th>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/깃허브아이디/연구저장소">
        <b>Dynamic Attention ViT</b>
      </a>
    </td>
    <td>
      연산 환경에 따라 Attention Head 수를 동적으로 조절하는
      Vision Transformer 연구
    </td>
    <td>Python, PyTorch, timm</td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/깃허브아이디/상권프로젝트저장소">
        <b>Campus Commercial Platform</b>
      </a>
    </td>
    <td>
      대학 주변에 필요한 업종을 학생들이 추천하고 투표하는 웹 서비스
    </td>
    <td>Next.js, React, TypeScript</td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/깃허브아이디/프로젝트저장소">
        <b>AI Personality Analysis</b>
      </a>
    </td>
    <td>
      AI와의 대화를 기반으로 사용자의 성향을 분석하는 서비스
    </td>
    <td>Python, LLM, Web</td>
  </tr>
</table>

<br/>

<!-- GitHub 통계 -->
<h2>GitHub Stats</h2>

<div align="center">

<img
  height="165"
  src="https://github-readme-stats.vercel.app/api?username=깃허브아이디&show_icons=true&hide_border=true&count_private=true"
/>

<img
  height="165"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=깃허브아이디&layout=compact&hide_border=true"
/>

</div>

<br/>

<!-- 활동 그래프 -->
<h2>Contribution Graph</h2>

<div align="center">

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=깃허브아이디&theme=github-compact&hide_border=true"
/>

</div>

<br/>

<!-- 공부 중인 내용 -->
<h2>Currently Learning</h2>

<ul>
  <li>Transformer architecture</li>
  <li>Multi-Head Attention and Grouped Query Attention</li>
  <li>Efficient Vision Transformer</li>
  <li>Knowledge Distillation</li>
  <li>Model Compression and Dynamic Inference</li>
  <li>Next.js full-stack development</li>
</ul>

<br/>

<!-- 연락처 -->
<h2>Contact</h2>

<p>
  <a href="mailto:이메일주소">
    <img src="https://img.shields.io/badge/Email-이메일주소-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>

<br/>

<!-- 하단 -->
<div align="center">

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:6A5ACD,100:00BFFF&height=120&section=footer"
/>

</div>
```
