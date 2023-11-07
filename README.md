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
|                   [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B)                                           |         Text-to-Image          |                                                                    High-quality text-to-image generation                                                                                                         |                  PyTorch/Stable Diffusion                     |          [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                         |
| [stabilityai/stable-diffusion-xl-refiner-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0)   |     Image-to-Image             |          SDXL consists of an ensemble of experts pipeline for latent diffusion                                                                                                                              |                  PyTorch/Stable Diffusion                 | [CreativeML Open RAIL++-M License](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/blob/main/LICENSE.md) |
|                                [CLIP](https://github.com/openai/CLIP/blob/main/model-card.md)                       | Zero-Shot Image Classification |                                                              Arbitrary image classification tasks in a zero-shot manner                                                                                              |                              PyTorch                      |               [MIT](https://github.com/openai/CLIP/blob/main/LICENSE)                           |
|                  [Wonder3D](https://github.com/xxlong0/Wonder3D/tree/main)                                          |         3d-generation          |                  Wonder3D reconstructs highly-detailed textured meshes from a single-view image                                                                                                              |            PyTorch                                        | [GNU Affero General Public License v3.0](https://github.com/xxlong0/Wonder3D/blob/main/LICENSE)                      |
|                 [seamless_communication](https://github.com/facebookresearch/seamless_communication)                | Speech-to-speech translation   |                          Foundational Models for State-of-the-Art Speech and Text Translation                                                                                                                 |                               fairseq2 v0.1.1                    |         [ Attribution-NonCommercial 4.0 International](https://github.com/facebookresearch/seamless_communication/blob/main/LICENSE) |
|                  [ProPainter](https://github.com/sczhou/ProPainter)                                                 |    Video Inpainting            |           ProPainter involves enhanced ProPagation and an efficient Transformer to achieve video completion, object removal and video outpainting                                                            |            CUDA >= 9.2/PyTorch >= 1.7.1                   |        [S-Lab License 1.0](https://github.com/sczhou/ProPainter/blob/main/LICENSE)|
|          [MagicPrompt-Stable-Diffusion ](https://huggingface.co/Gustavosta/MagicPrompt-Stable-Diffusion/tree/main)  |         Text Generation        |           A model from the MagicPrompt series of models, which are GPT-2 models intended to generate prompt texts for imaging AIs                                                                            |                GPT2/PyTorch                               | [MIT](https://github.com/Gustavosta/MagicPrompt-Card/blob/main/LICENSE) |
|        [falcon-180B](https://huggingface.co/tiiuae/falcon-180B/tree/main)                                           |         Text Generation        |              Falcon 180B is a super-powerful language model with 180 billion parameters, trained on 3.5 trillion tokens.                                                                                     |                PyTorch/Transformers                       | [FALCON 180B TII LICENSE VERSION 1.0](https://huggingface.co/tiiuae/falcon-180B/blob/main/LICENSE.txt) |
|    [IllusionDiffusion](https://huggingface.co/spaces/AP123/IllusionDiffusion/tree/main)                             |         Text-to-Image          |                 Illusion Diffusion generates stunning high quality illusion artwork with Stable Diffusion                                                                                                    |                PyTorch/Transformers                       |                                   Unlicensed                                                            |    
|  [CLIP Interrogator](https://github.com/pharmapsychotic/clip-interrogator)                                          |         Image-to-Text          |                CLIP Interrogator is a prompt engineering tool that combines OpenAI's CLIP and Salesforce's BLIP to optimize text prompts to match a given image                                             |                 PyTorch(torch>=1.13.0)                              |          [MIT](https://github.com/pharmapsychotic/clip-interrogator/blob/main/LICENSE)    |
|   [MusicGen](https://huggingface.co/spaces/facebook/MusicGen/tree/main)                                             |        Audio Generation        |               MusicGen tackles the task of conditional music generation.  MusicGen can generate high-quality samples, while being conditioned on textual description or melodic features, allowing better controls over the generated output. |    PyTorch/CUDA      | [MIT](https://huggingface.co/spaces/facebook/MusicGen/blob/main/LICENSE)  |
|      [Image to Story](https://huggingface.co/spaces/fffiloni/Image-to-Story/tree/main)                              |         Text Generation        |                              Upload an image, get a story made by Llama2                                                                                                                                    |                 Llama2                                              |                  Unlicensed                                                                    |

