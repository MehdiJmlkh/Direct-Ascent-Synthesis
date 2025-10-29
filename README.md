# Direct Ascent Synthesis: Revealing Hidden Generative Capabilities in Discriminative Models
A demo for the Direct Ascent Synthesis: Revealing Hidden Generative Capabilities in Discriminative Models paper (https://arxiv.org/abs/2502.07753)

[This Colab](https://github.com/stanislavfort/Direct_Ascent_Synthesis/blob/main/Direct_Ascent_Synthesis_generation_demo.ipynb) demonstrates
1. Text to image generation
2. "Style" transfer
3. Image reconstruction from its CLIP embedding

What you can expect:
1. Text to image generation for `a photo of swiss mountain valley` looking like this:

   ![DAS generated meteor](figures/das-demo-generation.png "Text to image generation")

2. Its individual resolutions looking like this after generation:

   ![DAS generated meteor](figures/das-demo-resolutions.png "resolutions")

3. To showcase generation diversity, 4 generations of the `a beautiful photo of  Mount Pinatubo eruption., detailed`:

   ![DAS generated meteor](figures/das-demo-many-generations.png "generation diversity")

4. Combining a source image of an SF skyline at night with a medieval fortress:

   ![DAS generated meteor](figures/das-demo-style.png "style transfer")

5. And finally reconstructing an image from its CLIP embedding:

   ![DAS generated meteor](das-demo-reconstructed.png "reconstruction")

6. Get a spectrum of a generated image:

   ![DAS generated meteor](das-demo-spectrum.png "a title")

