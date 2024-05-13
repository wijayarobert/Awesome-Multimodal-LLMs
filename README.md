# Awesome-Multimodal-LLMs
This repository aims to summarize the current state of research on Multimodal Large Language Models (LLMs). The focus is on exploring the applications, and potential improvements of LLMs in various tasks. The following are some potential topics in Multimodal LLM for further research.

**1. Evaluating LLMs on Specific Tasks**
Evaluating the performance of Multimodal LLMs on specific tasks such as data analysis and sign language translation can provide valuable insights into their capabilities and limitations. For instance, LLMs have been shown to be effective in data analysis tasks, but what can be learned from this to upgrade their performance? Similarly, representing signs as language can enable sign language translation from videos, but what ideas can be explored to improve this?

- Cheng, L., Li, X., & Bing, L. (2023). Is GPT-4 a Good Data Analyst? arXiv preprint arXiv:2305.15038v2 [cs.CL].
- Gong, J., Foo, L. G., He, Y., Rahmani, H., & Liu, J. (2024). Representing Signs as Language: A New Method for Sign Language Translation from Videos. CVPR 2024.
  
**2. Multimodal LLMs on Perceiving Tasks**
Despite recent advances, Multimodal LLMs still perform poorly on perceiving tasks such as IQ Test questions, Visual similarity, Counting, Relative Depth, Jigsaw, and Object localization.

- Fu, X. et al. (2024) 'BLINK: Multimodal Large Language Models Can See but Not Perceive', arXiv preprint arXiv:2404.12390v2 [cs.CV].
- Jain, J., Yang, J. and Shi, H. (2024) 'VCoder: Versatile Vision Encoders for Multimodal Large Language Models', CVPR 2024.
  
**3. Generative Pretraining Multimodal Models**
Generative pretraining has been shown to be effective in multimodal models, utilizing generative models which employ Stable diffusion for the decoder.

- Sun, Q. et al. (2024) 'Generative Multimodal Models are In-Context Learners', CVPR 2024.
- Sun, Q. et al. (2024) 'Generative Pretraining in Multimodality', ICLR 2024.
  
**4. Decoder Only Multimodal Model**
Decoder-only multimodal models have shown promise, utilizing a pretrained decoder-only LLM and freezing the encoder and decoder of LLM, except the vision encoder. Examples include LLaVa. However, there is still room for improvement, such as using higher image resolution, text labels, data mixture, and scaling LLM.

- Liu, H., Li, C., Wu, Q. and Lee, Y. J. (2023) 'Visual Instruction Tuning', NeurIPS 2023.
- Li, Z. et al. (2023) 'Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models', arXiv preprint arXiv:2311.06607v3 [cs.CV].
  
**5. Region Understanding Task with Visual Prompts**
Region understanding tasks require interacting with the model using natural cues like "red bounding box" or "pointed arrow" to mark images. Research is needed to develop models that can effectively understand these cues.

- Cai, M. et al. (2024) 'ViP-LLaVA: Making Large Multimodal Models Understand Arbitrary Visual Prompts', CVPR 2024.
- Lin, W. et al. (2024) 'Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want', arXiv preprint arXiv:2403.20271v2 [cs.CV].

**6. Identifying the Speaking Person**
Identifying the speaking person in an image is a challenging task that requires integrating information from multiple modalities. Research is needed to develop effective models that can accurately identify the speaking person.

- Lee, S. et al. (2024) 'Modeling Multimodal Social Interactions: New Challenges and Baselines with Densely Aligned Representations', CVPR 2024.
  
**7. Enhancing the Reading Ability of the Multimodal LLM**
Enhancing the reading ability of Multimodal LLMs is crucial for tasks such as reading rich-text images like posters and book covers. Research is needed to develop models that can effectively read and understand these images.

- Zhang, R. et al. (2024) 'TRINS: Towards Multimodal Language Models That Can Read', CVPR 2024.

**8. Segmentation Task with Multimodal LLM**
Segmentation tasks with LLMs require utilizing segmentation encoders and Multimodal LLMs to output segmentation masks along with text responses.

- Xia, Z. et al. (2024) 'GSVA: Generalized Segmentation via Multimodal Large Language Models', CVPR 2024.
  
**9. Exploring the Transferability of Visual Prompting**
Visual prompting has been shown to be effective in guiding the generation of multimodal models, but its transferability remains largely unexplored.

- Zhang, Y. et al. (2024) 'Exploring the Transferability of Visual Prompting for Multimodal Large Language Models', CVPR 2024.
  
**10. Visual Representation Learning in Multimodal LLM**
Visual representation learning is critical in Multimodal LLMs, but more research is needed to develop effective and efficient visual representation learning strategies. This includes comparing CLIP with vision-only self-supervised learning methods like DINO, and building specific encoders for specific tasks.

- Tong, S. et al. (2024) 'Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs', CVPR 2024.
- Jain, J., Yang, J. and Shi, H. (2024) 'VCoder: Versatile Vision Encoders for Multimodal Large Language Models', CVPR 2024.
  
**11. Projector Part of Multimodal LLM**
The projector part of Multimodal LLMs plays a crucial role in bridging pre-trained vision encoders with LLMs, but remains less explored. Research is needed to develop effective projector architectures that can improve the performance of Multimodal LLMs.

- Cha, J. et al. (2024) 'Honeybee: Locality-enhanced Projector for Multimodal LLM', CVPR 2024.
  
**12. LLMs for Classification Task**
- Berrios, W. et al. (2023) 'Towards Language Models That Can See: Computer Vision Through the LENS of Natural Language', arXiv preprint.
- Toubal, I. et al. (2024) Modeling Collaborator: Enabling Subjective Vision Classification With Minimal Human Effort via LLM Tool-Use, arXiv preprint.
