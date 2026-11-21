## Hi, I'm Lernie Li 👋

I work on generative models: diffusion transformers, mixture-of-experts architectures, and image and video generation.

### 🔬 Research

**[DyLoMo-DiT: Dynamic Looped Mixture-of-Experts Diffusion Transformers](https://oneboxcream.github.io/DyLoMo-DiT/)**

DyLoMo-DiT reuses parameters instead of adding them. A weight-shared loop applies the middle layers several times, sparse experts decide which parameters each token uses, and the number of passes changes with the noise level. At the parameter and compute budget of DiT, it lowers FID on ImageNet 256×256 by 11–24%; scaled up for text-to-image generation, it scores higher on GenEval than FLUX.1 (0.714 vs. 0.673) with less than one tenth of its active parameters.

💻 [Code](https://github.com/OneBoxCream/DyLoMo-DiT) · 🌐 [Project page](https://oneboxcream.github.io/DyLoMo-DiT/) · 🤗 [Weights](https://huggingface.co/OneCreamBox)

### 📫 Contact

- Email: lernie.ai.lab@gmail.com
- Hugging Face: [OneCreamBox](https://huggingface.co/OneCreamBox)
