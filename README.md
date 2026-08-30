### Hi there 👋

I'm **Ruize Xia**, a student researcher at **Nanjing Foreign Language School**.

My work is in **generative models** and **vision–language adaptation**: training video diffusion under a single-GPU budget, measuring how CLIP’s attention and representations drift during fine-tuning, and turning quantization methods into kernels that actually run faster on hardware.

---

### Research

#### [Text2Sign](https://github.com/xiaruize0911/text2sign) · [IEEE Access](https://doi.org/10.1109/ACCESS.2026.3686260)

A single-GPU diffusion baseline for **text-to-sign-language video**. Frozen CLIP text conditioning, a 3D encoder–decoder, and factorized spatial/temporal attention, trained and evaluated on How2Sign with a signer-disjoint split.

- Paper: *Text2Sign: A Single-GPU Diffusion Baseline for Text-to-Sign Language Video Generation*
- Code: [text2sign](https://github.com/xiaruize0911/text2sign) · manuscript: [text2sign_paper](https://github.com/xiaruize0911/text2sign_paper)

#### [Attention heatmap drift in CLIP](https://github.com/xiaruize0911/Attention_Collapse_in_CLIP_Fine-tuning_repo) · [preprint](https://doi.org/10.20944/preprints202604.0317.v1)

A controlled study of how CLIP ViT attention and representations change under **full fine-tuning vs LoRA**, with matched learning rates. Attention entropy tracks *how much* the encoder adapts; early representation drift (CKA) is the more stable flag of **zero-shot forgetting**.

- Preprint DOI: [10.20944/preprints202604.0317.v1](https://doi.org/10.20944/preprints202604.0317.v1)
- Code and ICDM manuscript: [Attention_Collapse_in_CLIP_Fine-tuning_repo](https://github.com/xiaruize0911/Attention_Collapse_in_CLIP_Fine-tuning_repo)

#### [On-device diffusion / MoDiff](https://github.com/xiaruize0911/MoDiff)

Systems work on **Modulated Diffusion**: fused low-bit CUDA/Triton kernels and cache-update fusion, measured on real GPUs rather than op-count estimates. Follows the ICML 2025 MoDiff framework (quantizing activations down to 3 bits) with hardware-level ablations on LDM / attention.

- Manuscript: *Real-Time On-Device Diffusion: Practical Acceleration via Fused Low-Bit Kernels*
- Fork + kernel work: [MoDiff](https://github.com/xiaruize0911/MoDiff)

#### Earlier / supporting

- [diffusion-model-mnist](https://github.com/xiaruize0911/diffusion-model-mnist) — from-scratch DDPM on MNIST (U-Net FID 34.4), used as a small-scale testbed before the video models

---

### Selected writing

| | |
| --- | --- |
| [Text2Sign](https://doi.org/10.1109/ACCESS.2026.3686260) | IEEE Access, 2026 |
| [Attention heatmap drift in CLIP](https://doi.org/10.20944/preprints202604.0317.v1) | Preprint, 2026 |
| [ORCID](https://orcid.org/0009-0000-0501-0943) | `0009-0000-0501-0943` |

---

### Interests

Diffusion models · video generation · CLIP / VLM adaptation · quantization & inference systems · accessibility (sign language)

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,linux,git,cpp" alt="Python, PyTorch, Linux, Git, C++" />
</p>

---

### Competitive programming

I came up through olympiad programming before shifting toward ML research.

[![Codeforces Master](https://img.shields.io/badge/Codeforces-Master_2239-blueviolet?style=flat-square&logo=codeforces)](https://codeforces.com/profile/xiaruize)
[![AtCoder 1 Dan](https://img.shields.io/badge/AtCoder-1_Dan-1f6feb?style=flat-square)](https://atcoder.jp/users/xiaruize)

---

### GitHub stats

<p>
  <img src="https://github-readme-stats.shion.dev/api?username=xiaruize0911&theme=vue&show_icons=true&hide_border=false&count_private=true" alt="xiaruize0911 GitHub stats" />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=xiaruize0911&theme=vue&show_icons=true&hide_border=false&layout=compact" alt="xiaruize0911 top languages" />
</p>

<p>
  <img src="https://streak-stats.demolab.com?user=xiaruize0911&theme=vue&hide_border=false" alt="xiaruize0911 GitHub streak" />
</p>

<p>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=xiaruize0911&theme=vue" alt="GitHub profile details" />
</p>

---

### Contact

- **Email**: [xiaruize0911@gmail.com](mailto:xiaruize0911@gmail.com)
- **ORCID**: [0009-0000-0501-0943](https://orcid.org/0009-0000-0501-0943)
- **Blog**: [xiaruize.org](https://xiaruize.org)
- **QQ**: 2188298460
- **WeChat**: xiaruize0911
