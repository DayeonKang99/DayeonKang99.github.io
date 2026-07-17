---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  html { scroll-behavior: smooth; }

  h1[id], h2[id] { scroll-margin-top: 40px; }

  .section-divider {
    border: none;
    border-top: 1px solid #e5e7eb;
    margin: 3em 0 2em 0;
  }

  /* ---------- Publications ---------- */
  .pub-grid {
    display: flex;
    flex-direction: column;
    gap: 1.1em;
    margin-top: 1.5em;
  }

  .pub-card {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-left: 4px solid #2b6cb0;
    border-radius: 10px;
    padding: 1.1em 1.4em;
    box-shadow: 0 1px 2px rgba(0,0,0,0.04);
    transition: box-shadow 0.2s ease, transform 0.2s ease;
  }

  .pub-card:hover {
    box-shadow: 0 6px 16px rgba(0,0,0,0.08);
    transform: translateY(-2px);
  }

  .pub-venue {
    display: inline-block;
    background: #ebf4ff;
    color: #2b6cb0;
    font-size: 0.75em;
    font-weight: 700;
    letter-spacing: 0.02em;
    padding: 0.2em 0.7em;
    border-radius: 999px;
    margin-bottom: 0.5em;
  }

  .pub-title {
    font-size: 1.08em;
    font-weight: 700;
    margin: 0.1em 0 0.35em 0;
    color: #1a202c;
  }

  .pub-authors {
    font-size: 0.92em;
    color: #4a5568;
    margin: 0 0 0.6em 0;
  }

  .pub-authors b { color: #1a202c; }

  .pub-links a.pub-btn {
    display: inline-block;
    font-size: 0.85em;
    font-weight: 600;
    color: #2b6cb0;
    border: 1px solid #2b6cb0;
    border-radius: 6px;
    padding: 0.25em 0.8em;
    margin-right: 0.4em;
    text-decoration: none;
    transition: background 0.15s ease, color 0.15s ease;
  }

  .pub-links a.pub-btn:hover {
    background: #2b6cb0;
    color: #fff;
  }

  .pub-pending {
    font-size: 0.85em;
    color: #a0aec0;
    font-style: italic;
  }

  /* ---------- Academic Services ---------- */
  .tt-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.5em;
    margin-top: 1.5em;
  }

  .tt-card {
    background: #fafafa;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    padding: 1.2em 1.4em;
  }

  .tt-card h3 {
    margin-top: 0;
    font-size: 1em;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    color: #2b6cb0;
  }

  .tt-card ul {
    padding-left: 1.1em;
    margin: 0;
  }

  .tt-card li {
    margin-bottom: 0.6em;
    font-size: 0.93em;
    line-height: 1.45;
  }

  .tt-card li .tt-sub {
    display: block;
    color: #718096;
    font-size: 0.92em;
  }
  
    .author__avatar img {
    border-radius: 12px;
  }
</style>

I am a PhD student in Computer Sciences at University of Massachusetts Amherst, advised by [Prof. Amir Houmansadr](https://people.cs.umass.edu/~amir/) and co-advised by [Prof. Pubali Datta](https://people.cs.umass.edu/~pdatta/).

I am interested in the intersection of **computer networking**, **cloud systems**, and **security and privacy**, with a particular focus on **autonomous AI agents**. This is related to the following areas: 1) Analyzing security risks that emerges as cloud systems scale, and how AI agents can be fingerprinted and attributed through network-layer signals. 2) Designing privacy-preserving AI agents that leverage cloud and network infrastructure.

Prior to starting my PhD studies, I received my bachelor’s degree from Ewha Womans University in South Korea, advised by [Prof. HyungJune Lee](https://inslab-ewha.weebly.com/).

## News

- **February 2026**: My first first-author paper "CensorLess: Cost-Efficient Censorship Circumvention Through Serverless Cloud Functions" is accepted at PETS'26
- **June 2025**: Our paper "I'll Shake Your Hand: What Happens After DNS Poisoning" is accepted at FOCI'25
- **December 2024**: Our paper "CollageMap: Tailoring Generative Fingerprint Map via Obstacle-Aware Adaptation for Site-Survey-Free Indoor Localization" is accepted at IEEE PerCom'25
- **December 2024**: Our paper "CAMPUSRSSI: Real-World Wi-Fi RSSI Measurements for Indoor Localization" is accepted at IEEE PerCom Workshops'25
- **October 2024**: Our paper "GAN-Loc: Empowering Indoor Localization for Unknown Areas via Generative Fingerprint Map" is accepted at IEEE SECON'24

<hr class="section-divider">

# Publications

<div class="pub-grid">

  <div class="pub-card">
    <span class="pub-venue">preprint</span>
    <p class="pub-title">Whose Agent Are You? Multi-Layer Fingerprinting and Attribution of Autonomous Web Agents</p>
    <p class="pub-authors"><b>Dayeon Kang</b>, J.Jeong, J. Sheffey, P. Datta, and A. Houmansadr</p>
    <div class="pub-links"><a class="pub-btn" href="https://arxiv.org/pdf/2606.20910" target="_blank">Paper</a></div>
  </div> 

  <div class="pub-card">
    <span class="pub-venue">PETS 2026</span>
    <p class="pub-title">CensorLess: Cost-Efficient Censorship Circumvention Through Serverless Cloud Functions</p>
    <p class="pub-authors"><b>Dayeon Kang</b>, J. Sheffey, M. Wu, P. Datta, and A. Houmansadr</p>
    <div class="pub-links"><a class="pub-btn" href="https://petsymposium.org/popets/2026/popets-2026-0096.pdf" target="_blank">Paper</a></div>
  </div> 

  <div class="pub-card">
    <span class="pub-venue">FOCI 2025</span>
    <p class="pub-title">I'll Shake Your Hand: What Happens After DNS Poisoning</p>
    <p class="pub-authors">J. Sheffey, A. Johaib, <b>Dayeon Kang</b>, Z. Durumeric, A. Houmansadr, and Q. Wu</p>
    <div class="pub-links"><a class="pub-btn" href="https://petsymposium.org/foci/2025/foci-2025-0015.php" target="_blank">Paper</a></div>
  </div>

  <div class="pub-card">
    <span class="pub-venue">IEEE PerCom Workshops 2025</span>
    <p class="pub-title">CAMPUSRSSI: Real-World Wi-Fi RSSI Measurements for Indoor Localization</p>
    <p class="pub-authors">J. Yoon, Y. You, <b>Dayeon Kang</b>, J. Kim, and H. Lee</p>
    <div class="pub-links"><a class="pub-btn" href="https://www.computer.org/csdl/proceedings-article/percom-workshops/2025/355300a697/27FQKMuSkco" target="_blank">Paper</a></div>
  </div>

  <div class="pub-card">
    <span class="pub-venue">IEEE PerCom 2025</span>
    <p class="pub-title">CollageMap: Tailoring Generative Fingerprint Map via Obstacle-Aware Adaptation for Site-Survey-Free Indoor Localization</p>
    <p class="pub-authors">Y. You, J. Yoon, <b>Dayeon Kang</b>, J. Kim, and H. Lee</p>
    <div class="pub-links"><a class="pub-btn" href="https://ieeexplore.ieee.org/abstract/document/11018726" target="_blank">Paper</a></div>
  </div>

  <div class="pub-card">
    <span class="pub-venue">IEEE SECON 2024</span>
    <p class="pub-title">GAN-Loc: Empowering Indoor Localization for Unknown Areas via Generative Fingerprint Map</p>
    <p class="pub-authors">J. Yoon, Y. You, <b>Dayeon Kang</b>, J. Kim, and H. Lee</p>
    <div class="pub-links"><a class="pub-btn" href="https://ieeexplore.ieee.org/abstract/document/10934883" target="_blank">Paper</a></div>
  </div>

  <div class="pub-card">
    <span class="pub-venue">Korea Computer Congress 2022</span>
    <p class="pub-title">Grape Grade Discrimination System using Step-by-step Deep Learning Model and Drone Path Planning Algorithm</p>
    <p class="pub-authors"><b>Dayeon Kang</b>, J. Kim, D. Kim, H. Kim, and K. Chae</p>
    <div class="pub-links"><a class="pub-btn" href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11123682" target="_blank">Paper</a></div>
  </div>

</div>

<hr class="section-divider">

# Academic Services

<div class="tt-grid">

  <div class="tt-card">
    <h3>Talks</h3>
    <ul>
      <li><b>Guest Talk:</b> Women in Cybersecurity (WiCyS) at UMass, Mar. 2025
        <span class="tt-sub">Journey to Security Researcher</span>
      </li>
      <li><b>Guest Lecture:</b> UMass COMPSCI 560 Introduction to Computer and Network Security, Dec. 2024
        <span class="tt-sub">Break the anonymity of Tor network: What is traffic analysis?</span>
      </li>
    </ul>
  </div>

  <div class="tt-card">
    <h3>Mentorship</h3>
    <ul>
      <li><b>Undergraduate Research Volunteers (URV)</b> at UMass Amherst
        <span class="tt-sub">Summer 2024, Winter 2025</span>
      </li>
      <li><b>Samsung Junior SW Creation Contest</b> at Samsung SDS
        <span class="tt-sub">Jul. 2022 – Aug. 2022</span>
      </li>
    </ul>
  </div>

  <div class="tt-card">
    <h3>Reviews</h3>
    <ul>
      <li>PETS 2027 Tadpole Reviewer</li>
      <li>External Reviewer of USENIX Security 2026</li>
    </ul>
  </div>

</div>