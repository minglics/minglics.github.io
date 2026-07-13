---
title: "Collaborative Research: NeTS: Small: A Privacy-Aware Human-Centered QoE Assessment Framework for Immersive Videos"
layout: research
categories:
    - research
papertitle: "Collaborative Research: NeTS: Small: A Privacy-Aware Human-Centered QoE Assessment Framework for Immersive Videos"
authors: ""
logo: "/images/nsf1.gif"
Sponsor: "Sponsored by the U.S. National Science Foundation"
Duration: ""
disclaimer: "Note: Any opinions, findings and conclusions or recommendations expressed on this website are those of the author(s) and do not necessarily reflect the views of the National Science Foundation (NSF)."
image: "/images/Bereimage.jpg"
---
<br>
<hr>
Welcome to the website of our research project: "Collaborative Research: NeTS: Small: A Privacy-Aware Human-Centered QoE Assessment Framework for Immersive Videos". This website is created and maintained to disseminate and share research results and other information related to the project.

Project Description
{: .research.headerStyle}

Immersive videos, also known as 360-degree videos, provide viewers with a complete visual perspective of their environment. With their growing popularity, network operators and service providers increasingly need accurate ways to understand users' Quality of Experience (QoE). However, conventional QoE models for two-dimensional videos cannot fully capture users' subjective perception in immersive environments.
This project develops a privacy-aware, human-centered QoE assessment framework for immersive videos. It leverages multi-modal sensory readings from VR onboard sensors to model users' perceptual experiences beyond traditional system-level metrics. The project includes three research thrusts: extracting salient features from multi-modal sensing data for QoE assessment, optimizing system and sensing resource utilization through shared edge-hosted models and adaptive sampling, and protecting user privacy under a differential privacy framework that accounts for cross-modality data correlation.
The research will be evaluated through measurement campaigns, simulations, and experimental studies. Its outcomes will advance human-centered sensing and networking research and support user-specific video streaming and network resource optimization for immersive applications.
{: .research.desc}

Personalized Video Recommendation for Virtual Reality Using Human Data
{: .research.headerStyle}

This work explores how to recommend videos more effectively in virtual reality. While video recommendation is already common on phones and computers, VR creates a different viewing experience because users can look around, move their heads, and interact with immersive content in more natural ways. These behaviors can reveal what users are interested in, but they have not been fully used in existing recommendation systems. The proposed system uses viewers' behavior while watching VR videos to better understand their preferences and suggest future videos they may enjoy. It also addresses practical challenges in VR, such as the limited amount of available training data and the need to reduce energy use on VR devices. Overall, the work aims to make VR video platforms more personalized, efficient, and user-friendly.
{: .research.desc}

<figure class="align-center">
  <img src="{{ site.baseurl }}/images/bere_architecture.png" alt="BeRE system architecture">
  <figcaption>Image: BeRE System Architecture</figcaption>
</figure>

Tile-Based Adaptive Bitrate Streaming for Bandwidth-Efficient VR Video Delivery
{: .research.headerStyle}

Another research direction in this project studies bandwidth-efficient VR streaming through tile-based adaptive bitrate delivery. Virtual reality video streaming requires extremely high bandwidth because a 360-degree scene must be delivered at high quality to preserve immersion. However, users only view a small portion of the full sphere at any given time. Delivering the entire frame at uniformly high quality therefore wastes significant bandwidth on unseen regions.
To address this problem, this work spatially divides each 360-degree frame into independent tiles and fetches only the tiles that are likely to fall inside the user's viewport at high quality. Tiles outside the viewport are either fetched at lower quality or skipped entirely. The system combines real-time viewport prediction, bandwidth estimation, and adaptive bitrate decision making to support efficient video delivery under bandwidth-constrained conditions.
Preliminary results show that tile-based streaming can substantially reduce bandwidth usage while maintaining visually acceptable quality in the visible viewport. This direction demonstrates how adaptive streaming decisions, guided by user viewport, can improve bandwidth efficiency for immersive VR applications.
{: .research.desc}

<div class="responsive-video-container">
  <video controls>
    <source src="{{ site.baseurl }}/videos/tile_based_vr_demo (2).mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <br>
  <em>Video: Demonstration of the tile-based adaptive bitrate streaming system for VR video delivery.</em>
</div>

<!-- <figure>
  <div class="responsive-video-container-half-center">
    <iframe 
      src="{{ site.baseurl }}/videos/tile_based_vr_demo (2).mp4" frameborder="0" sandbox  webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="">
    </iframe>
  </div>
  <figcaption style="margin-top: 10px;">
    <em>Video: Demonstration of the tile-based adaptive bitrate streaming system for VR video delivery.</em>
  </figcaption>
</figure> -->

<!-- <div class="responsive-video-container-half-center">
  <iframe src="{{ site.baseurl }}/videos/tile_based_vr_demo (2).mp4" frameborder="0" sandbox  webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="">
  <em>Video: Demonstration of the tile-based adaptive bitrate streaming system for VR video delivery.</em>
  </iframe>
  <br>

</div> -->

AI Smart-Glass Live Streaming Measurement Study
{: .research.headerStyle}

Another research direction in this project studies live streaming from AI smart glasses. Smart glasses are emerging as lightweight wearable platforms for real-time video capture, sensing, remote assistance, and AI-supported interaction. However, live streaming from smart glasses often suffers from high latency, unstable performance, CPU pressure, and energy limitations, all of which directly affect user experience.
In this project, we conduct a measurement study to understand the causes of latency, CPU usage, and energy consumption during live streaming from AI smart glasses. The study examines the end-to-end streaming pipeline, including the glasses, companion mobile application, media server, cloud relay, network path, and viewer-side playback path.
By analyzing the streaming pipeline stage by stage, we aim to identify where the main performance bottlenecks arise and how they affect real-time immersive video delivery. This effort supports the design of more efficient and research-friendly tools for future AI smart-glass streaming systems.
{: .research.desc}

<div class="responsive-video-container-as-horizontal">
  <video controls>
    <source src="{{ site.baseurl }}/videos/smartglass_streaming_demo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <br>
  <em>Video: Demonstration of the AI smart-glass live streaming study.</em>
</div>

Principal Investigator Team
{: .research.headerStyle}

| :--- | --- |
| ![logo]({{ site.baseurl }}/images/mingli.jpg){: width="150px" } | **Ming Li**<br>Principal Investigator<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Homepage: {{ site.baseurl }}/ |
| ![logo]({{ site.baseurl }}/images/miaoyin.jpg){: width="150px" } | **Miao Yin**<br>Co-Principal Investigator<br>The University of Texas at Arlington<br>Homepage: https://noodle-lab.github.io/ |
| ![logo]({{ site.baseurl }}/images/weili.jpg){: width="150px" } | **Wei Li**<br>Principal Investigator<br>Georgia State University<br>Homepage: https://tinman.cs.gsu.edu/~wli28/ |
| ![logo]({{ site.baseurl }}/images/yinshuli.jpg){: width="150px" } | **Yinshu Li**<br>Co-Principal Investigator<br>Georgia State University<br>Homepage: https://li.csgsu.org/ |
{: .research.table}

---

Students
{: .research.headerStyle}

| :--- | --- |
| ![logo]({{ site.baseurl }}/images/xuhao.jpg){: width="150px" } | **Xuhao Xie**<br>Ph.D. student (Aug 2024 - Present)<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Email: xxx9206@mavs.uta.edu |
| ![logo]({{ site.baseurl }}/images/raoa.png){: width="150px" } | **Raoa Faria Karim**<br>Ph.D. student (Aug 2024 - Present)<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Email: rxk2803@mavs.uta.edu |
| ![logo]({{ site.baseurl }}/images/siyi.jpg){: width="150px" } | **Siyi Wu**<br>Ph.D. student (Aug 2024 - Present)<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Email: sxw8121@mavs.uta.edu |
| ![logo]({{ site.baseurl }}/images/songling.jpg){: width="150px" } | **Songling Bai**<br>Ph.D. student (Spring 2025 - Present)<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Email: songling.bai@mavs.uta.edu |
| ![logo]({{ site.baseurl }}/images/youngtak.png){: width="150px" } | **Youngtak Cho**<br>Ph.D. student (Fall 2021 - Present)<br>Department of Computer Science and Engineering<br>The University of Texas at Arlington<br>Email: youngtak.cho@mavs.uta.edu |
{: .research.table}

Publications
{: .research.headerStyle}

<ol>
  <li>
    <div align="justify">OptiVibe: Keystroke Inference Attacks Through A New Optical-Vibration Side Channel,<br>
    Youngtak Cho, Sanket Suresh Badgujar, Srinivasan Murali, Xuhao Xie, and Ming Li,<br>
    <em>IEEE International Conference on Distributed Computing Systems</em> (ICDCS), June 2026.</div>
  </li>

  <li>
    <div align="justify">Resilient Percentile-Driven Spectrum Sharing for NTN-TN Coexistence,<br>
    Shaoying Wang, Beatriz Lorenzo, Ming Li, Linke Guo, and Xiaonan Zhang,<br>
    <em>IEEE INFOCOM WKSHPS: RI-NTNs 2026: Resilient and Intelligent Non-Terrestrial Networks</em>, May 2026.</div>
  </li>

  
  <li>
    <div align="justify"><a href="https://arxiv.org/pdf/2506.00799">Uni-LoRA: One Vector is All You Need</a>,<br>
    Kaiyang Li, Shaobo Han, Qing Su, Wei Li, Zhipeng Cai, and Shihao Ji,<br>
    <em>The Thirty-Ninth Annual Conference on Neural Information Processing Systems</em> (NeurIPS 2025), San Diego, CA, USA, December 2025.</div>
  </li>  

  <li>
    <div align="justify"><a href="https://arxiv.org/pdf/2509.18367">Multi-Worker Selection based Distributed Swarm Learning for Edge IoT with Non-iid Data</a>,<br>
    Zhuoyu Yao, Yue Wang, Songyang Zhang, Yingshu Li, Zhipeng Cai, and Zhi Tian,<br>
    <em>IEEE Global Communications Conference</em> (GLOBECOM 2025), Taipei, Taiwan, December 2025.</div>
  </li>

  <li>
    <div align="justify"><a href="https://arxiv.org/pdf/2510.18152">Efficient Multi-Worker Selection based Distributed Swarm Learning via Analog Aggregation</a>,<br>
    Zhuoyu Yao, Yue Wang, Songyang Zhang, Yingshu Li, Zhipeng Cai, and Zhi Tian,<br>
    <em>Asilomar Conference on Signals, Systems, and Computers</em> (Asilomar 2025), Pacific Grove, CA, USA, October 2025.</div>
  </li>

  <li>
    <div align="justify"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10884270">APOLLO: Differential Private Online Multi-Sensor Data Prediction with Certified Performance</a>,<br>
    Honghui Xu, Wei Li, Shaoen Wu, Liang Zhao, and Zhipeng Cai,<br>
    <em>IEEE International Conference on Data Mining</em> (ICDM), Abu Dhabi, UAE, Dec. 2024. (Regular Paper Acceptance Ratio: 10.9%)</div>
  </li>
  
  <li>
    <div align="justify"><a href="https://dl.acm.org/doi/pdf/10.1145/3636534.3690660">BeRE: A Novel Video Recommender System for Virtual Reality Using Human Behavioral Signals</a>,<br>
    Huadi Zhu, Chaowei Wang, Venkateshwar Reddy Darmanola, Hongbo Guo, Wenqiang Jin, and Ming Li,<br>
    <em>ACM Conference on Mobile Computing and Networking</em> (MobiCom'24).</div>
  </li>
</ol>
