<h1 align="center">AudioGen-Omni: A Generalist Multimodal Diffusion Transformer for Video-Synchronized Sound Effects, Speech, and Song Generation</h1>

<div align='center'>
  <span class="author-block">Le Wang<sup>1</sup><sup>*</sup>, Jun Wang<sup>*</sup>, Feng Deng<sup>*</sup>, Cheng Zhang<sup>*</sup>, Di Zhang<sup>*</sup></span>
</div>

<div align='center'>
  <span class="author-block"><strong><sup>1</sup>China University of Mining and Technology, </strong></span>
  <span class="author-block"><strong><sup>*</sup>Kuaishou Technology</strong></span>
</div>
<br>

<div align="center">

  <!-- 📄 Paper / project / GitHub stats -->
  <p>
    <a href="-" target="_blank"><img src="https://img.shields.io/badge/Paper-AudioGen-Omni-red" alt="arXiv link"></a>&nbsp;
    <a href="https://github.com/ciyou2/AudioGen-Omni/" target="_blank"><img src="https://img.shields.io/badge/Project-Homepage-green" alt="project homepage"></a>&nbsp;
    <img src="https://komarev.com/ghpvc/?username=ciyou2&color=5865f2" alt="Profile views" width="110.2" height="20">&nbsp;
    <a href="https://github.com/ciyou2/AudioGen-Omni" target="_blank"><img src="https://img.shields.io/github/stars/ciyou2/AudioGen-Omni?style=social" alt="GitHub stars"></a>
  </p>

  <!-- 🎬 Showcase -->
  <p><img src="./content/arch.jpg"></p>
  <p>🔥 For more results, visit our <a href="https://ciyou2.github.io/OmniGen/" target="_blank"><strong>homepage</strong></a> 🔥</p>

</div>

## Introduction 📖
We present AudioGen-Omni  — the first generalist multimodal diffusion transformer capable of generating high-fidelity sound effects, speech, and songs coherently synchronized with the input video. AudioGen-Omni  introduces a groundbreaking joint training paradigm that seamlessly integrates large-scale text-audio corpora, unlocking a model that can produce semantically rich, acoustically diverse audio spanning the entire spectrum of sound types. At its core, AudioGen-Omni  introduces a novel lyrics-transcription fusion module that maps raw graphemes or phonemes into dense, frame-level representations, enabling precise audio-visual alignment without relying on forced alignment or duration prediction. Trained under a powerful Flow Matching objective, AudioGen-Omni  redefines the state-of-the-art in Video-to-Audio, Video-to-Speech, and Video-to-Song synthesis—excelling in audio quality, semantic consistency, and lip-sync precision. With just 1.21 seconds of inference time for an 8-second audio clip, it outperforms prior models by a large margin in both speed and versatility.
Even more remarkably, AudioGen-Omni  also delivers competitive or superior results in Text-to-Audio/Speech/Song tasks—demonstrating that multimodal joint training not only preserves, but enhances unimodal capabilities. This positions AudioGen-Omni  as a truly generalist audio generator, opening new frontiers for synchronized multimodal content creation across speech, music, and sound design.
 
## Citation
```
@misc{AudioGen-Omni,
      title={AudioGen-Omni: A Generalist Multimodal Diffusion Transformer for Video-Synchronized Sound Effects, Speech, and Song Generation},
      author={Le Wang, Jun Wang, Feng Deng, Chen Zhang, Di Zhang, Kun Gai},
      journal={arXiv preprint arXiv:-},
      year={2025}
}
```
