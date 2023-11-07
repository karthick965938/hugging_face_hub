# hugging_face_hub

### Hugging Face Models <a href="Hugging Face Models"/>

|                                                     Model Name                                                      |            Category            |                                                                                                  Description                                                                                                  |                          Framework                          |                                               License                                               |
| :-----------------------------------------------------------------------------------------------------------------: | :----------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: |
|                  [HuggingFaceH4/zephyr-7b-beta](https://github.com/huggingface/alignment-handbook)                  |        Text Generation         |                                              Zephyr-7B-β is a fine-tuned version of Mistral-7B-v0.1 that was trained using Direct Preference Optimization (DPO)                                               |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                        [mistralai/Mistral-7B-v0.1](https://github.com/mistralai/mistral-src)                        |        Text Generation         |                                                The Mistral-7B-v0.1 Large Language Model (LLM) is a pretrained generative text model with 7 billion parameters                                                 |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                   [distil-whisper/distil-large-v](https://github.com/huggingface/distil-whisper)                    |  Automatic Speech Recognition  |               Speech Recognition Model that is a distilled version of the Whisper model that is 6 times faster, 49% smaller, and performs within 1% WER on out-of-distribution evaluation sets.               |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|              [sentence-transformers/all-MiniLM-L6-v2](https://github.com/UKPLab/sentence-transformers)              |      Sentence Similarity       |                  This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search.                  |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|          [stabilityai/stable-diffusion-xl-refiner-1.0](https://github.com/Stability-AI/generative-models)           |         Image-to-Image         |                  This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search.                  |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                  [Phind/Phind-CodeLlama-34B-v2](https://github.com/Stability-AI/generative-models)                  |        Text Generation         |                               We've fine-tuned Phind-CodeLlama-34B-v1 on an additional 1.5B tokens high-quality programming-related data, achieving 73.8% pass@1 on HumanEval.                                |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                    [WizardLM/WizardCoder-Python-34B-V1.0](https://github.com/nlpxucan/WizardLM)                     |        Text Generation         |                                 WizardMath-70B-V1.0 model slightly outperforms some closed-source LLMs on the GSM8K, including ChatGPT 3.5, Claude Instant 1 and PaLM 2 540B.                                 |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                            [llama2](https://ai.meta.com/llama/license/)                             |
|                    [WizardLM/WizardCoder-Python-34B-V1.0](https://github.com/nlpxucan/WizardLM)                     |        Text Generation         |                                 WizardMath-70B-V1.0 model slightly outperforms some closed-source LLMs on the GSM8K, including ChatGPT 3.5, Claude Instant 1 and PaLM 2 540B.                                 |        Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118        |                            [llama2](https://ai.meta.com/llama/license/)                             |
|                            [h94/IP-Adapter](https://github.com/tencent-ailab/IP-Adapter)                            |        Text Generation         |                                    IP-Adapter, an effective and lightweight adapter to achieve image prompt capability for the pre-trained text-to-image diffusion models.                                    | Image Encoder,Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118 |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                    [bigscience/bloom](https://github.com/bigscience-workshop/Megatron-DeepSpeed)                    |        Text Generation         |                  BLOOM is an autoregressive Large Language Model (LLM), trained to continue text from a prompt on vast amounts of text data using industrial-scale computational resources.                   |  Megatron-DeepSpeed, DeepSpeed, pytorch-1.11 w/ CUDA-11.5   |   [bigscience-bloom-rail-1.0](https://bigscience.huggingface.co/blog/the-bigscience-rail-license)   |
|               [openai/clip-vit-large-patch14](https://github.com/openai/CLIP/blob/main/model-card.md)               | Zero Shot Image Classification |                                    The model was also developed to test the ability of models to generalize to arbitrary image classification tasks in a zero-shot manner.                                    |                  pytorch-1.11 w/ CUDA-11.5                  |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                    [suno/bark](https://github.com/suno-ai/bark)                                     |         Text-to-Speech         | Bark is a transformer-based text-to-audio model created by Suno. Bark can generate highly realistic, multilingual speech as well as other audio - including music, background noise and simple sound effects. |                  pytorch-1.11 w/ CUDA-11.5                  |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                  [coqui/XTTS-v1](https://github.com/coqui-ai/TTS)                                   |         Text-to-Speech         |                                        ⓍTTS is a Voice generation model that lets you clone voices into different languages by using just a quick 6-second audio clip.                                        |                  pytorch-1.11 w/ CUDA-11.5                  |                         [Coqui Public Model License](https://coqui.ai/cpml)                         |
|                    [CompVis/stable-diffusion-v1-4](https://github.com/CompVis/stable-diffusion)                     |         Text-to-Image          |                                         Stable Diffusion is a latent text-to-image diffusion model capable of generating photo-realistic images given any text input.                                         |                diffusers transformers scipy5                | [The CreativeML OpenRAIL M license](https://huggingface.co/spaces/CompVis/stable-diffusion-license) |
| [monster-labs/control_v1p_sd15_qrcode_monster](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster) |         Text-to-QRCode         |                                                                       This model is made to generate creative QR codes that still scan.                                                                       |                         ControlNet                          | [openrail++](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)  |
|     [databricks/dolly-v2-12b](https://github.com/databrickslabs/dolly#getting-started-with-response-generation)     |        Text Generation         |                       Databricks' dolly-v2-12b, an instruction-following large language model trained on the Databricks machine learning platform that is licensed for commercial use.                        |                  pytorch-1.11 w/ CUDA-11.                   |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                   [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B)                                           |         Text-to-Image          |   The Segmind Stable Diffusion Model (SSD-1B) is a distilled 50% smaller version of the Stable Diffusion XL (SDXL), offering a 60% speedup while maintaining high-quality text-to-image generation capabilities. It has been trained on diverse datasets, including Grit and Midjourney scrape data, to enhance its ability to create a wide range of visual content based on textual prompts.
                                           |                  PyTorch/Stable Diffusion                                |          [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)   |
| [stabilityai/stable-diffusion-xl-refiner-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0)   |     Image-to-Image             |
SDXL consists of an ensemble of experts pipeline for latent diffusion: In a first step, the base model  is used to generate (noisy) latents, which are then further processed with a refinement model specialized for the final denoising steps. Note that the base model can be used as a standalone module.       | PyTorch/Stable Diffusion                   |   [CreativeML Open RAIL++-M License](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/blob/main/LICENSE.md)      |
|  [CLIP](https://github.com/openai/CLIP/blob/main/model-card.md)      |     Zero-Shot Image Classification           |  Arbitrary image classification tasks in a zero-shot manner                     |    PyTorch                         |   [MIT](https://github.com/openai/CLIP/blob/main/LICENSE)       |
| [Wonder3D](https://github.com/xxlong0/Wonder3D/tree/main)         | 3d-generation                                   |  Wonder3D reconstructs highly-detailed textured meshes from a single-view image            |            PyTorch                                     | [GNU Affero General Public License v3.0](https://github.com/xxlong0/Wonder3D/blob/main/LICENSE)       |
