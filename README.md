# 2023: The best AI papers - A Review 🚀 [Work in progress ⏳]
## A curated list of the latest breakthroughs in AI by release date with a clear video explanation, link to a more in-depth article, and code.

With the creation of a whole new field called "Generative AI", whether you like the term or not, research hasn't slowed its frenetic pace, especially the industry, which has seen its biggest boom in implementation of AI technologies ever. Artificial intelligence and our understanding of the human brain and its link to AI are constantly evolving, showing promising applications improving our life's quality in the near future. Still, we ought to be careful with which technology we choose to apply.

>"Science cannot tell us what we ought to do, only what we can do."<br/>- Jean-Paul Sartre, Being and Nothingness

Here's curated list of the latest breakthroughs in AI and Data Science by release date with a clear video explanation, link to a more in-depth article, and code (if applicable). Enjoy the read!

**The complete reference to each paper is listed at the end of this repository.** *Star this repository to stay up to date and stay tuned for next year!* ⭐️

Maintainer: [louisfb01](https://github.com/louisfb01), also active on [YouTube](https://www.youtube.com/@whatsai) and as a [Podcaster](https://open.spotify.com/show/4rKRJXaXlClkDyInjHkxq3) if you want to see/hear more about AI!

[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40whats_ai)](https://twitter.com/Whats_AI)


Subscribe to my [newsletter](https://louisbouchard.substack.com/) - The latest updates in AI explained every week.


*Feel free to [message me](https://www.louisbouchard.ai/contact/) any interesting paper I may have missed to add to this repository.*

*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!* And come chat with us in our [Learn AI Together Discord community](https://www.louisbouchard.ai/learn-ai-together/)!

👀 **If you'd like to support my work**, you can check to [Sponsor](https://github.com/sponsors/louisfb01) this repository or support me on [Patreon](https://www.patreon.com/whatsai). You can also support me by following my favorite [daily AI newsletter](https://www.syntheticmind.io/subscribe?ref=EFowuebnlZ) to get frequent updates on new papers like those!


----

## The Full List
- [Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers [1]](#1)
- [InstructPix2Pix: Learning to Follow Image Editing Instructions [2]](#2)
- [MusicLM: Generating Music From Text [3]](#3)
- [Structure and Content-Guided Video Synthesis with Diffusion Models [4]](#4)
- [PaLM-E: An Embodied Multimodal Language Model [5]](#5)
- [Segment Anything [6]](#6)
- [Key-Locked Rank One Editing for Text-to-Image Personalization [7]](#7)
- [Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold [8]](#8)
- [Neuralangelo: High-Fidelity Neural Surface Reconstruction [9]](#9)
- [TryOnDiffusion: A Tale of Two UNets [10]](#10)
- [Paper references](#references)

---

## Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers [1]<a name="1"></a>
Last year we saw the uprising of generative AI for both images and text, most recently with ChatGPT. Now, within the first week of 2023, researchers have already created a new system for audio data called VALL-E.

VALL-E is able to imitate someone’s voice with only a 3-second recording with higher similarity and speech naturalness than ever before. ChatGPT is able to imitate a human writer; VALL-E does the same for voice.


* Short Video Explanation:<br/>
[<img src="https://imgur.com/aEvCsR0.png" width="512"/>](https://youtu.be/cZaZ-MQ3IBY)
* Short read: [VALL-E: An AI Generating Voice from Text!](https://www.louisbouchard.ai/vall-e/)
* Paper: [Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2301.02111)
* [Code](https://github.com/microsoft/unilm)


## InstructPix2Pix: Learning to Follow Image Editing Instructions [2]<a name="2"></a>
We know that AI can generate images; now, let’s edit them!

This new model called InstructPix2Pix does precisely that; it edits an image following a text-based instruction given by the user. Just look at those amazing results… and that is not from OpenAI or google with an infinite budget.

It is a recent publication from Tim Brooks and collaborators at the University of California, including prof. Alexei A. Efros, a well-known figure in the computer vision industry. As you can see, the results are just incredible.


* Short Video Explanation:<br/>
[<img src="https://imgur.com/1nUPDhb.png" width="512"/>](https://youtu.be/EJacROjI84s)
* Short read: [Image Editing from Text Instructions: InstructPix2Pix](https://www.louisbouchard.ai/instructpix2pix/)
* Paper: [InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/abs/2211.09800)
* [Code](https://github.com/timothybrooks/instruct-pix2pix)
* [Demo](https://huggingface.co/spaces/timbrooks/instruct-pix2pix)


## MusicLM: Generating Music From Text [3]<a name="3"></a>
We recently covered a model able to imitate someone’s voice called VALL-E. Let’s jump a step further in the creative direction with this new AI called MusicLM. MusicLM allows you to generate music from a text description.

Let's not wait any longer and dive right into the results... what you will hear will blow you away!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/7Y1QEJJ.png" width="512"/>](https://youtu.be/jTrYIGxOuKQ)
* Short read: [Generating music with AI!](https://www.louisbouchard.ai/musiclm/)
* Paper: [MusicLM: Generating Music From Text](https://arxiv.org/abs/2301.11325)
* [Listen to some results](https://google-research.github.io/seanet/musiclm/examples/)


## Structure and Content-Guided Video Synthesis with Diffusion Models [4]<a name="4"></a>
Runway have created a system called GEN-1 that can take a video, and apply a completely different style to it in seconds. The model is a work in progress and has flaws, but still does a pretty cool style transfer from an image or text prompt into a video, something that would've been impossible a few years or even months ago. Even cooler is how it works...


* Short Video Explanation:<br/>
[<img src="https://imgur.com/yBCKVaa.png" width="512"/>](https://youtu.be/FEHpinPZUqA)
* Short read: [Gen-1, the future of storytelling?](https://www.louisbouchard.ai/gen-1/)
* Paper: [Structure and Content-Guided Video Synthesis with Diffusion Models](https://arxiv.org/abs/2302.03011)
* [Try it](https://app.runwayml.com/login)


## PaLM-E: An Embodied Multimodal Language Model [5]<a name="5"></a>
PaLM-E, Google’s most recent publication, is what they call an embodied multimodal language model. What does this mean? It means that it is a model that can understand various types of data, such as text and images from the ViT and PaLM models we mentioned, and is able to turn these insights into actions from a robotics hand!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/YkDCiBE.png" width="512"/>](https://youtu.be/1RF06BL7VAc)
* Short read: [Google’s New AI Robot Can See and Understands Language! (PaLM-E)](https://www.louisbouchard.ai/palm-e/)
* Paper: [PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378)
* [More results!](https://palm-e.github.io/)


## Segment Anything [6]<a name="6"></a>
Segmentation - it's like the photo world's equivalent of playing detective. This superpower allows you to identify anything and everything in an image, from objects to people, with pixel-perfect precision. It's a game-changer for all kinds of applications, like autonomous vehicles that need to know what's going on around them, whether it's a car or a pedestrian.

You also definitely know about prompting by now. But have you heard of promptable segmentation? It's the newest kid on the block, and it’s really cool. With this new trick up your sleeve, you can prompt your AI model to segment anything you want - and I mean anything! Thanks to Meta's incredible new SAM (Segment Anything Model), there's no limit to what you can do.

If you're curious about how promptable segmentation and the SAM model work their magic, then you won't want to miss out on my video. In it, you'll learn all about how this amazing new technology is changing the game when it comes to image segmentation. So sit back, relax, and let me take you on a journey into the world of promptable segmentation with SAM. Trust me, you won't regret it!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/kHsMafX.png" width="512"/>](https://youtu.be/bx0He5eE8fE)
* Short read: [Meta's new Segment Anything Model Explained](https://www.louisbouchard.ai/meta-sam/)
* Paper: [Segment Anything](https://ai.facebook.com/research/publications/segment-anything/?ref=louisbouchard.ai)
* [Code](https://github.com/facebookresearch/segment-anything)


## Key-Locked Rank One Editing for Text-to-Image Personalization [7]<a name="7"></a>
Imagine creating stunning Instagram images without leaving home or snapping photos! NVIDIA's new AI model, Perfusion, advances text-to-image generation with enhanced control and fidelity for concept-based visuals.

Perfusion is a significant improvement over existing AI techniques, overcoming limitations in generating images that remain faithful to the original content. This model can accurately create these "concepts" in a variety of new scenarios.

Perfusion builds on Stable Diffusion with additional mechanisms for locking onto and generating multiple "concepts" in new images simultaneously. This results in unbeatable quantitative and qualitative performance, opening exciting possibilities across diverse industries.

🚧 While not perfect, Perfusion is a significant step forward for text-to-image models. Challenges include maintaining an object's identity and some overgeneralization, as well as requiring a bit of prompt engineering work.

NVIDIA's Perfusion sets the stage for an exciting future of AI-generated images tailored to our desires.


* Short Video Explanation:<br/>
[<img src="https://imgur.com/ecWaTs4.png" width="512"/>](https://youtu.be/WhFoEaB7CvY)
* Short read: [Perfusion: Stable Diffusion but more Controllable!](https://www.louisbouchard.ai/perfusion/)
* Paper: [Key-Locked Rank One Editing for Text-to-Image Personalization](https://arxiv.org/abs/2305.01644)
* [Code (coming soon as per the authors)](https://research.nvidia.com/labs/par/Perfusion)


## Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold [8]<a name="8"></a>
Drag Your Gan prioritizes precise object dragging over image generation or text manipulation. The AI realistically adapts the entire image, modifying the object's position, pose, shape, expressions, and other frame elements.

🐶🌄 Edit expressions of dogs, make them sit, adjust human poses, or even alter landscapes seamlessly. Drag Your Gan offers an innovative and interactive way to experiment with image editing.

How does it work? Drag Your Gan leverages StyleGAN2, a state-of-the-art GAN architecture by NVIDIA. By operating in the feature space (latent code), the AI learns how to edit images properly through a series of steps and loss calculations.

Even though the results are fantastic, as you will see below, it's essential to note that Drag Your Gan has some limitations, including only being able to edit generated images for now. Images are part of the distribution. Other limitations are that the selection of points is based on pixel colors and contrast, so you cannot really drag anything. If you take a part of a red car and move it staying on the red car, it might not understand that you move it at all.

Can't wait to try it out? The authors mention that the code should be available in June. Tune in to the video (or article) to learn more about this new image manipulation style with DragYourGan!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/QuULqbR.png" width="512"/>](https://youtu.be/r1mh-IqBEjg)
* Short read: [Image Manipulation with Your Mouse! Drag Your Gan Explained](https://www.louisbouchard.ai/draggan/)
* Paper: [Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold](https://arxiv.org/abs/2305.10973)
* [Code](https://github.com/XingangPan/DragGAN)


> Check out [the What's AI podcast](https://open.spotify.com/show/4rKRJXaXlClkDyInjHkxq3) for more AI content in the form of interviews with experts in the field! An invited AI expert and I will cover specific topics, sub-fields, and roles related to AI to teach and share knowledge from the people who worked hard to gather it.


## Neuralangelo: High-Fidelity Neural Surface Reconstruction [9]<a name="9"></a>
Neuralangelo is NVIDIA's latest breakthrough in image-to-3D AI. This new approach builds upon [Instant NeRF](https://www.louisbouchard.ai/nvidia-photos-into-3d-scenes/), enhancing surface quality and providing highly realistic 3D scenes from simple images in just seconds.

Neuralangelo aims to overcome the limitations of its predecessor, Instant NeRF, such as the lack of detailed structures and a somewhat cartoonish appearance of the AI-generated 3D models.

The secret behind Neuralangelo's improvements lies in two key differences: using numerical gradients for computing higher-order derivatives, and adopting a coarse-to-fine optimization on the hash grids controlling levels of detail, which we dive into in the video.

This optimization process results in a smoother input for the 3D model reconstruction, allows more information to be blended, and creates a perfect balance between consistency and fine-grain details for a realistic outcome.

The quality of Neuralangelo's 3D models is truly astounding, but the AI does face challenges with highly reflective scenes. Nonetheless, its potential real-world applications are vast and exciting!


* Short Video Explanation:<br/>
[<img src="https://imgur.com/1QD1QUK.png" width="512"/>](https://youtu.be/K_phjX9eYwY)
* Short read: [The Best Image-to-3D AI to date: Neuralangelo](https://www.louisbouchard.ai/neuralangelo/)
* Paper: [Neuralangelo: High-Fidelity Neural Surface Reconstruction](https://arxiv.org/abs/2306.03092)
* [More results!](https://research.nvidia.com/labs/dir/neuralangelo/)


## TryOnDiffusion: A Tale of Two UNets [10]<a name="10"></a>
In this week's episode I decided to explore a new research called TryOnDiffusion, presented at the CVPR 2023 conference. This innovative approach represents a significant leap forward in realistic virtual try-on experiences. By training AI models to understand input images, differentiate clothing from the person, and combine information intelligently, TryOnDiffusion produces impressive results that bring us closer to the ultimate goal of a perfect virtual try-on.

If you're intrigued by the intersection of AI and fashion, join us as we unravel the inner workings of TryOnDiffusion and its potential impact on the future of online shopping. Whether you're an AI enthusiast, a fashion lover, or simply curious about the latest technological advancements, the video offers valuable insights into the cutting-edge world of virtual clothing try-on.

We will dive into the world of diffusion models, UNets, and attention, where all those incredibly powerful mechanisms combine forces with helping the field of fashion and online retail. Of course, this work has limitations, but (as you will see) the results are just mind-blowing and very promising.


* Short Video Explanation:<br/>
[<img src="https://imgur.com/IkvpJDf.png" width="512"/>](https://youtu.be/2IJwaDbP3jI)
* Short read: [Revolutionizing Online Shopping: AI's Virtual Try-On Experience](https://www.louisbouchard.ai/tryondiffusion/)
* Paper: [TryOnDiffusion: A Tale of Two UNets](https://arxiv.org/abs/2306.08276)
* [More results!](https://tryondiffusion.github.io/)


---


>If you would like to read more papers and have a broader view, here is another great repository for you covering 2022:
[2022: A Year Full of Amazing AI papers- A Review](https://github.com/louisfb01/best_AI_papers_2022) and feel free to subscribe to my weekly [newsletter](https://louisbouchard.substack.com/) and stay up-to-date with new publications in AI for 2023!


*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!*

---

## Paper references<a name="references"></a>

[1] Wang, C., Chen, S., Wu, Y., Zhang, Z., Zhou, L., Liu, S., Chen, Z., Liu, Y., Wang, H., Li, J. and He, L., 2023. Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers, https://arxiv.org/abs/2301.02111

[2] Brooks et al., 2022: InstructPix2Pix, https://arxiv.org/abs/2211.09800

[3] Agostinelli et al., 2023: MusicLM, https://arxiv.org/abs/2301.11325

[4] Esser, P., Chiu, J., Atighehchian, P., Granskog, J. and Germanidis, A., 2023. Structure and content-guided video synthesis with diffusion models, https://arxiv.org/abs/2302.03011

[5] Driess, D., Xia, F., Sajjadi, M.S., Lynch, C., Chowdhery, A., Ichter, B., Wahid, A., Tompson, J., Vuong, Q., Yu, T. and Huang, W., 2023. Palm-e: An embodied multimodal language model, https://arxiv.org/abs/2303.03378

[6] Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., Xiao, T., Whitehead, S., Berg, A.C., Lo, W.Y. and Dollár, P., 2023. Segment anything, https://arxiv.org/abs/2304.02643

[7] Tewel, Y., Gal, R., Chechik, G. and Atzmon, Y., 2023. Key-locked rank one editing for text-to-image personalization, https://arxiv.org/abs/2305.01644

[8] Pan, X., Tewari, A., Leimkühler, T., Liu, L., Meka, A. and Theobalt, C., 2023. Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold, https://arxiv.org/abs/2305.10973

[9] Li, Z., Müller, T., Evans, A., Taylor, R.H., Unberath, M., Liu, M.Y. and Lin, C.H., 2023. Neuralangelo: High-Fidelity Neural Surface Reconstruction. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 8456-8465), https://arxiv.org/abs/2306.03092

[10] Zhu, L., Yang, D., Zhu, T., Reda, F., Chan, W., Saharia, C., Norouzi, M. and Kemelmacher-Shlizerman, I., 2023. TryOnDiffusion: A Tale of Two UNets. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 4606-4615), https://arxiv.org/abs/2306.08276

