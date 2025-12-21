---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- =========================
  Page-local styles (easy to tweak)
========================= -->
<style>
/* overall typography on this page */
.home-wrap{
  font-size: 0.85rem;          /* overall body text size */
  line-height: 1.65;
  color: #1f2937;
  font-family: -apple-system, BlinkMacSystemFont, "Inter", "Segoe UI", "Helvetica Neue", Arial,
               "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
}

/* links */
.home-wrap a{
  color: #0056b3;
  text-decoration: none;
}
.home-wrap a:hover{
  text-decoration: underline;
}

/* section title (Projects / Publications) */
.section-title{
  font-size: 1.45rem;          /* section header size */
  font-weight: 600;
  border-bottom: 2px solid #ccc;
  padding-bottom: 4px;
  margin-top: 40px;
  margin-bottom: 18px;
}

/* project block layout */
.project-block{
  display: flex;
  gap: 20px;
  margin-bottom: 30px;
  padding-bottom: 20px;
}
.project-media{
  width: 200px;
  border-radius: 10px;
  border: 1px solid #ccc;
  background: #fff;
}
.project-title{
  color: #0066cc;
  margin: 0;
  font-size: 1.15rem;          /* project title size */
  font-weight: 600;
}
.project-desc{
  font-style: italic;
  font-size: 0.8rem;          /* project description size */
  color: #4b5563;
  margin: 8px 0 0 0;
}

/* publications */
.pub-note{
  font-size: 0.8rem;
  color: #6b7280;
  margin: 0 0 8px 0;
}
.pub-list{
  font-size: 0.8rem;
  line-height: 1.55;
  padding-left: 1.2em;
  margin: 6px 0 0 0;
}
.pub-list li{
  margin: 0 0 10px 0;
}
.pub-meta{
  color: #6b7280;
}

/* book translation block */
.book-block{
  display: flex;
  align-items: flex-start;
  gap: 16px;
  margin-top: 30px;
}
.book-cover{
  width: 160px;
  height: auto;
  border: 1px solid #ccc;
}
.book-title{
  margin: 0;
  font-size: 1.12rem;
  font-weight: 600;
}
.book-desc{
  margin: 10px 0 0 0;
  color: #374151;
}
</style>

<div class="home-wrap">
  <p>
    Hi! I’m <strong>Shuowen Li (李硕文)</strong>, a third-year M.S. student in Optical Engineering at
    <strong>Tsinghua University</strong>, advised by Prof. Liangcai Cao. I also work as a research intern at the
    <strong>Academy of Arts &amp; Design</strong>, mentored by Prof. Haipeng Mi. Previously, I received my B.S. in Physics from
    Lanzhou University, where I studied nanomaterial design under Prof. Hao Jia.
  </p>

  <p>
    My research focuses on <strong>human–AI interaction</strong>, <strong>computational imaging</strong>, <strong>3D display</strong>, and
    <strong>creative robotics</strong>. I am particularly interested in how intelligent systems can support and extend human creativity,
    and I also hope to explore how optical technologies can enable novel forms of interaction and 3D experiences. By combining engineering
    and art, my goal is to develop interactive systems that empower people to create with AI across both digital and physical domains.
  </p>

  <p>
    Check out my <a href="../assets/CV_Shuowen_Li.pdf">CV</a> for more!
  </p>
</div>

  <h2 id="projects" class="section-title">🧪 Projects</h2>

  <!-- Project 1 -->
  <div class="project-block">
    <video src="/videos/semantic_life.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">🧬 Semantic-Guided Artificial Life System</h3>
      <p class="project-desc">
        Developed a real-time interactive system where users evolve digital lifeforms using <strong>natural language prompts</strong>.
        Integrated <strong>CLIP-based multimodal evaluation</strong> and <strong>CMA-ES optimization</strong>, supporting both semantic guidance and emergent swarm behaviors.
        Enables participatory generative design in the spirit of “evolving with intention”.
      </p>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-block">
    <video src="/videos/houxi.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">🐒 Houxi: Swarm Robotic Theater</h3>
      <p class="project-desc">
        Created a swarm-based storytelling system inspired by the Chinese fable <strong>“The Monkeys and the Moon”</strong>.
        Robots perform on a tabletop stage using <strong>path dynamics</strong> and <strong>spatial formations</strong> to convey plot and emotion.
        Dynamic projection enriches the narrative with vivid scenery and interactive visual cues.
      </p>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-block">
    <video src="/videos/toio.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">🤖 PuppetLine: Swarm Robotic Storytelling</h3>
      <p class="project-desc">
        Built a tangible storytelling system using <strong>Toio robots</strong> and <strong>large language models (LLMs)</strong>.
        Translates children’s narrative inputs into synchronized multi-robot actions and emotions.
        The system empowers <strong>co-creative expression</strong> through embodied interaction.
      </p>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-block">
    <video src="/videos/embo.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">✋ Embo: A Wearable Robot for Empathy Education</h3>
      <p class="project-desc">
        Designed a wearable puppet robot that transforms <strong>verbal aggression</strong> into <strong>tactile pressure feedback</strong>,
        addressing bullying scenarios in child–robot interaction.
        Combines <strong>natural language analysis</strong> and <strong>haptic feedback</strong> to build emotional awareness.
      </p>
    </div>
  </div>

  <!-- Project 5 -->
  <div class="project-block">
    <!-- If your filename contains a space, keep %20 (or rename the file to avoid spaces) -->
    <video src="/videos/holo%20interaction.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">🪞 Holographic Interaction System</h3>
      <p class="project-desc">
        Developed an interactive system that combines <strong>holographic 3D projection</strong> and <strong>hand-tracking sensors</strong>.
        Enables <strong>contactless, real-time interaction</strong> with floating 3D visuals through gesture recognition.
        Demonstrates the potential of holography in immersive and intuitive human–computer interfaces.
      </p>
    </div>
  </div>

  <!-- Project 6 -->
  <div class="project-block">
    <video src="/videos/机械臂.mp4" autoplay loop muted playsinline class="project-media"></video>
    <div>
      <h3 class="project-title">🖼️ 3D Display Quality Assessment</h3>
      <p class="project-desc">
        Proposed a hybrid evaluation framework for <strong>glasses-free 3D displays</strong>, integrating <strong>optical metrics</strong> and <strong>human visual comfort</strong> analysis.
        Contributed to drafting <strong>industry standards</strong> for autostereoscopic display technologies.
      </p>
    </div>
  </div>

  <!-- Project 7 -->
  <div class="project-block">
    <img src="/videos/CSST.gif" alt="Astronomical reconstruction" class="project-media">
    <div>
      <h3 class="project-title">🌌 Astronomical Image Reconstruction</h3>
      <p class="project-desc">
        Developed a GPU-accelerated pipeline for <strong>turbulence removal</strong> in single-frame astronomical images using <strong>blind deconvolution</strong>,
        <strong>deformable convolution</strong>, and <strong>diffusion models</strong>.
        Collaborated on hardware–software co-design with a <strong>four-aperture telescope array</strong>.
      </p>
    </div>
  </div>

  <h2 id="publications" class="section-title">📄 Publications</h2>
  <p class="pub-note">(* denotes equal contribution)</p>

  <ol class="pub-list">
    <li>
      <strong>Shuowen Li</strong><sup>*</sup>, Kexin Wang<sup>*</sup>, Minglu Fang, Danqi Huang, Ali Asadipour, Haipeng Mi, Yitong Sun.
      <em><a href="https://arxiv.org/pdf/2507.03839" target="_blank" rel="noopener">Participatory Evolution of Artificial Life Systems via Semantic Feedback</a></em>.
      In: <em>SIGGRAPH Asia 2025 Art Papers</em>.
    </li>

    <li>
      Ruhan Wang, <strong>Shuowen Li</strong>, Peiran Zhang, Danqi Huang, Yijie Guo, Haipeng Mi.
      <em>PuppetLine: An Interactive System for Embodied Storytelling with LLM-driven Swarm Robots</em>.
      In: <em>Adjunct Proceedings of the 38th Annual ACM Symposium on User Interface Software and Technology (UIST), 2025.</em>
    </li>

    <li>
      Shihan Qiu<sup>*</sup>, Yuhan Xie<sup>*</sup>, <strong>Shuowen Li</strong><sup>*</sup>, Wei Guo, Xiaoyue Gao, Yijie Guo.
      <em><a href="https://dl.acm.org/doi/abs/10.1145/3610978.3640616" target="_blank" rel="noopener">Embo: A Wearable Robot Transforming Child-Directed Verbal Aggression into Tactile Feedback</a></em>.
      In: <em>ACM/IEEE International Conference on Human-Robot Interaction (HRI '24) Companion</em>, 2024, pp. 857–861.
    </li>

    <li>
      <strong>Shuowen Li</strong>, Yunhui Gao, Jiachen Wu, Mingjie Wang, Zhangcheng Huang, Shumei Chen, Liangcai Cao.
      <em><a href="https://www.sciencedirect.com/science/article/pii/S2667325824001328" target="_blank" rel="noopener">Lensless Camera: Unraveling the Breakthroughs and Prospects</a></em>.
      <em>Fundamental Research</em>, 5(4), 2025, pp. 1725–1736, <span class="pub-meta">(JCR Q1, IF 6.3)</span>.
    </li>

    <li>
      <strong>Shuowen Li</strong>, Liangcai Cao.
      <em><a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-8-16911&id=570059" target="_blank" rel="noopener">Multidimensional Crosstalk Analysis in Autostereoscopic Displays: Integrating Subjective and Objective Evaluations for Image Quality Assessment</a></em>.
      <em>Optics Express</em>, 33(8), 2025, pp. 16911–16924, <span class="pub-meta">(JCR Q2, IF 3.3)</span>.
    </li>

    <li>
      <strong>Shuowen Li</strong>, Yunhui Gao, Jiachen Wu, Liangcai Cao.
      <em><a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-32-20-35579&id=559910" target="_blank" rel="noopener">Blind Deblurring of Astronomical Images Using SCGTV-Based Single-Frame Method</a></em>.
      <em>Optics Express</em>, 32(20), 2024, pp. 35579–35593, <span class="pub-meta">(JCR Q2, IF 3.3)</span>.
    </li>
  </ol>

  <div class="book-block">
    <img src="/images/matter_cover.jpg" alt="Matter book cover" class="book-cover">
    <div>
      <h3 class="book-title">📘 Book Translation</h3>
      <p class="book-desc">
        <em>Geoff Cottrell</em>.
        <strong><em>
          <a href="https://read.douban.com/ebook/479553544/" target="_blank" rel="noopener">Matter: A Very Short Introduction</a>
        </em></strong>.<br>
        Translated by Xiang Liu, <strong>Shuowen Li</strong>, Jiageng Li.<br>
        Yilin Press, 2024. ISBN: 9787575301671.
      </p>
      <p class="project-desc" style="font-style: italic; margin-top: 8px;">
        A concise yet wide-ranging introduction to matter, guiding readers through its forms from fundamental particles to cosmic structures—with clarity and accessibility.
      </p>
    </div>
  </div>

</div>


## Skills {#skills}

* **Programming**: Python, MATLAB, Java, C++
* **Softwares**: Blender, Unity, SolidWorks, Arduino, Adobe Illustrator, Lumerical FDTD, Zemax


## Research Interests {#interests}

* **Human–AI Co-Creation**: Designing interactive systems that fuse generative AI with human intention, language, and emotion.
* **Computational Design Tools**: Building tools for evolving, simulating, and editing digital forms—across visual, spatial, and behavioral dimensions.
* **Interactive 3D Technologies**: Creating spatial computing and fabrication methods that connect digital content with the physical world.
* **Creative Robotics & Embodied Interaction**: Leveraging swarm behavior, wearable tech, and storytelling to create expressive physical interactions.
* **Visual Perception & Evaluation**: Studying how humans perceive 3D content, depth, and image quality, and modeling this in computational terms.

