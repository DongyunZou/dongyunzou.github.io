<div class="research-list">

<article class="research-card research-card-featured" aria-labelledby="project-humanize">
  <div class="research-head">
    <span class="research-venue">arXiv 2026</span>
    <span class="research-tag">Featured · Open source</span>
    <h3 class="research-title" id="project-humanize">Humanize: Judgement Engineering for Agentic Coding</h3>
    <p class="research-authors">Sihao Liu, Ligeng Zhu, Zijian Zhang, <strong>Dongyun Zou</strong>, Zhengyang Zhang, Changye Li, Song Bian, Song Han and Tony Nowatzki.</p>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://arxiv.org/abs/2610.08900" target="_blank" rel="noopener noreferrer" aria-label="Explore Humanize: Judgement Engineering for Agentic Coding"><img src="static/assets/img/projects/humanize.svg" alt="Humanize workflow: human-approved planning, iterative implementation, independent review, and learning" width="548" height="301" loading="lazy"></a>
    <div class="research-description">
      <p>Making coding agents reliable through <strong>judgement engineering</strong>. Humanize coordinates planning, implementation, independent review, and learning, with explicit decisions and mechanical gates at each boundary.</p>
      <p>Its applications span CUDA kernel optimization, large-scale software migration, and olympiad problem solving. The open-source workflow brings independent review into everyday agentic coding.</p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://arxiv.org/abs/2610.08900" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/humanfia/humanize" target="_blank" rel="noopener noreferrer">Code <span aria-hidden="true">↗</span></a>
    <a class="research-stars" href="https://github.com/humanfia/humanize/stargazers" target="_blank" rel="noopener noreferrer" aria-label="Humanize GitHub stars"><img src="https://img.shields.io/github/stars/humanfia/humanize?style=flat&amp;label=GitHub%20stars&amp;color=701e5e" alt="Humanize GitHub stars" height="20" loading="lazy"></a>
  </div>
</article>

<article class="research-card" aria-labelledby="project-vc-attention">
  <div class="research-head">
    <span class="research-venue">arXiv 2026</span>
    <span class="research-tag">Co-first author</span>
    <h3 class="research-title" id="project-vc-attention">VC-Attention: Value Smoothing and Softmax Casting for Low-bit Attention</h3>
    <p class="research-authors">Xingyang Li<sup>&#42;</sup>, <strong>Dongyun Zou</strong><sup>&#42;</sup>, Shining Zhang, Jiacheng Chen, Haocheng Xi, Lvmin Zhang, Jun-Yan Zhu, Song Han, Zhekai Zhang, Yujun Lin and Muyang Li.</p>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://arxiv.org/html/2609.15810v1" target="_blank" rel="noopener noreferrer" aria-label="Explore VC-Attention: Value Smoothing and Softmax Casting for Low-bit Attention"><img src="static/assets/img/projects/vc-attention-figure5.png" alt="VC-Attention Figure 5: ExpCast-FP8 replaces exponentiation and casting with a linear map; the plots show the encoded byte and approximation error" width="1666" height="670" loading="lazy"></a>
    <div class="research-description">
      <p>Training-free low-bit attention for faster video generation. <strong>V-Smooth</strong> groups and smooths value tokens to reduce quantization error; <strong>ExpCast-FP8</strong> directly encodes attention probabilities to remove the softmax bottleneck.</p>
      <p>Evaluated across four video diffusion models, with attention speedups of <strong>1.46–1.59×</strong> on datacenter GPUs and <strong>2.3–3.6×</strong> on workstation GPUs over BF16 FlashAttention-4.</p>
      <p><span class="research-note">Equal contribution. Code is not publicly available.</span></p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://arxiv.org/html/2609.15810v1" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">↗</span></a>
    <a href="https://www.nunchux.ai/blog/attention-is-the-video-bottleneck" target="_blank" rel="noopener noreferrer">Blog <span aria-hidden="true">↗</span></a>
  </div>
</article>

<article class="research-card" aria-labelledby="project-kda">
  <div class="research-head">
    <span class="research-venue">MLSys 2026 · FlashInfer Contest</span>
    <h3 class="research-title" id="project-kda">Kernel Design Agents (KDA)</h3>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://github.com/mit-han-lab/kernel-design-agents" target="_blank" rel="noopener noreferrer" aria-label="Explore Kernel Design Agents (KDA)"><img src="static/assets/img/projects/kda.svg" alt="Kernel Design Agents workflow: implement, verify, profile, and optimize CUDA kernels with a shared knowledge base" width="640" height="360" loading="lazy"></a>
    <div class="research-description">
      <p>An agentic CUDA kernel optimization workflow that combines implementation, correctness checks, profiling feedback, and a kernel knowledge base.</p>
      <p>As part of <strong>HAN Lab Kernel Mafia</strong>, we ranked <strong>1st in Fused MoE</strong>, <strong>2nd in Sparse Attention (DSA)</strong>, and <strong>3rd in Gated Delta Net (GDN)</strong> in the Full-Agent track of the MLSys 2026 FlashInfer AI Kernel Generation Contest.</p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://github.com/mit-han-lab/kernel-design-agents" target="_blank" rel="noopener noreferrer">Code <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/mit-han-lab/mlsys2026-flashinfer-contest" target="_blank" rel="noopener noreferrer">Contest Release <span aria-hidden="true">↗</span></a>
    <a href="https://mlsys26.flashinfer.ai/" target="_blank" rel="noopener noreferrer">Competition <span aria-hidden="true">↗</span></a>
  </div>
</article>

<article class="research-card" aria-labelledby="project-jetvit">
  <div class="research-head">
    <span class="research-venue">CVPR 2026 Findings</span>
    <span class="research-tag">First author</span>
    <h3 class="research-title" id="project-jetvit">JetViT: Efficient High-Resolution Vision Transformer with Post-Training Attention Search</h3>
    <p class="research-authors"><strong>Dongyun Zou</strong>, Zhuoyang Zhang, Junyu Chen, Wenkun He, Qinhe Peng, Hanrong Ye, Yao Lu, Hongxu Yin, Yu Wang, Song Han and Han Cai.</p>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://arxiv.org/abs/2605.26636" target="_blank" rel="noopener noreferrer" aria-label="Explore JetViT: Efficient High-Resolution Vision Transformer with Post-Training Attention Search"><img src="static/assets/img/projects/jetvit.png" alt="JetViT teaser comparing efficient hybrid attention with full-attention vision transformers" width="2039" height="529" loading="lazy"></a>
    <div class="research-description">
      <p><strong>Post-Training Attention Search</strong> converts pre-trained vision transformers into efficient hybrid architectures by replacing redundant full-attention blocks with linear or window attention.</p>
      <p>On DINOv3 and DepthAnythingV2, JetViT preserves accuracy while achieving up to <strong>1.79× higher throughput</strong> and <strong>44.81% lower latency</strong> on an NVIDIA H100.</p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://arxiv.org/abs/2605.26636" target="_blank" rel="noopener noreferrer">arXiv <span aria-hidden="true">↗</span></a>
    <a href="https://openaccess.thecvf.com/content/CVPR2026F/papers/Zou_JetViT_Efficient_High-Resolution_Vision_Transformer_with_Post-Training_Attention_Search_CVPRF_2026_paper.pdf" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">↗</span></a>
  </div>
</article>

<article class="research-card" aria-labelledby="project-usf">
  <div class="research-head">
    <span class="research-venue">IEEE TPAMI</span>
    <span class="research-tag">Co-first author</span>
    <h3 class="research-title" id="project-usf">USF++: A Unified Sampling Framework for Solver Searching of Diffusion Probabilistic Models</h3>
    <p class="research-authors"><strong>Dongyun Zou</strong><sup>&#42;</sup>, Enshu Liu<sup>&#42;</sup>, Xuefei Ning, Huazhong Yang and Yu Wang.</p>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://ieeexplore.ieee.org/document/11275964" target="_blank" rel="noopener noreferrer" aria-label="Explore USF++: A Unified Sampling Framework for Solver Searching of Diffusion Probabilistic Models"><img src="static/assets/img/projects/usf.png" alt="Unified Sampling Framework diagram showing the diffusion solver search space" width="7987" height="3657" loading="lazy"></a>
    <div class="research-description">
      <p>A unified framework for exploring diffusion sampling solvers and searching for efficient sampling schedules. USF++ studies solver design to accelerate diffusion generation under limited sampling budgets.</p>
      <p><span class="research-note">Equal contribution with Enshu Liu.</span></p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://ieeexplore.ieee.org/document/11275964" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/thu-nics/USF" target="_blank" rel="noopener noreferrer">Code <span aria-hidden="true">↗</span></a>
  </div>
</article>

<article class="research-card" aria-labelledby="project-dcae">
  <div class="research-head">
    <span class="research-venue">ICCV 2025</span>
    <h3 class="research-title" id="project-dcae">DC-AE 1.5: Accelerating Diffusion Model Convergence with Structured Latent Space</h3>
    <p class="research-authors">Junyu Chen, <strong>Dongyun Zou</strong>, Wenkun He, Junsong Chen, Enze Xie, Song Han and Han Cai.</p>
  </div>
  <div class="research-body">
    <a class="research-cover" href="https://openaccess.thecvf.com/content/ICCV2025/html/Chen_DC-AE_1.5_Accelerating_Diffusion_Model_Convergence_with_Structured_Latent_Space_ICCV_2025_paper.html" target="_blank" rel="noopener noreferrer" aria-label="Explore DC-AE 1.5: Accelerating Diffusion Model Convergence with Structured Latent Space"><img src="static/assets/img/projects/dc-ae.png" alt="DC-AE 1.5 structured latent channels separate object structure from image details" width="1040" height="522" loading="lazy"></a>
    <div class="research-description">
      <p>Deep compression autoencoders with a <strong>structured latent space</strong>: early channels capture object structure, while later channels encode image details. Augmented diffusion training accelerates convergence in this compressed space.</p>
      <p>On ImageNet 512×512, DC-AE-1.5-f64c128 improves generation quality over DC-AE-f32c32 while being <strong>4× faster</strong>.</p>
    </div>
  </div>
  <div class="research-links">
    <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Chen_DC-AE_1.5_Accelerating_Diffusion_Model_Convergence_with_Structured_Latent_Space_ICCV_2025_paper.html" target="_blank" rel="noopener noreferrer">Paper <span aria-hidden="true">↗</span></a>
    <a href="https://github.com/dc-ai-projects/DC-Gen" target="_blank" rel="noopener noreferrer">Code <span aria-hidden="true">↗</span></a>
  </div>
</article>

</div>
