# hugging_face_hub

### Hugging Face Models <a href="Hugging Face Models"/>

|                                                                               Model Name                                                                               |            Category            |                                                                                                  Description                                                                                                  |                                 Framework                                  |                                               License                                               |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: |
|                                           [HuggingFaceH4/zephyr-7b-beta](https://github.com/huggingface/alignment-handbook)                                            |        Text Generation         |                                              Zephyr-7B-β is a fine-tuned version of Mistral-7B-v0.1 that was trained using Direct Preference Optimization (DPO)                                               |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                                 [mistralai/Mistral-7B-v0.1](https://github.com/mistralai/mistral-src)                                                  |        Text Generation         |                                                The Mistral-7B-v0.1 Large Language Model (LLM) is a pretrained generative text model with 7 billion parameters                                                 |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                             [distil-whisper/distil-large-v](https://github.com/huggingface/distil-whisper)                                             |  Automatic Speech Recognition  |               Speech Recognition Model that is a distilled version of the Whisper model that is 6 times faster, 49% smaller, and performs within 1% WER on out-of-distribution evaluation sets.               |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                       [sentence-transformers/all-MiniLM-L6-v2](https://github.com/UKPLab/sentence-transformers)                                        |      Sentence Similarity       |                  This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search.                  |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                    [stabilityai/stable-diffusion-xl-refiner-1.0](https://github.com/Stability-AI/generative-models)                                    |         Image-to-Image         |                  This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search.                  |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                           [Phind/Phind-CodeLlama-34B-v2](https://github.com/Stability-AI/generative-models)                                            |        Text Generation         |                               We've fine-tuned Phind-CodeLlama-34B-v1 on an additional 1.5B tokens high-quality programming-related data, achieving 73.8% pass@1 on HumanEval.                                |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                              [WizardLM/WizardCoder-Python-34B-V1.0](https://github.com/nlpxucan/WizardLM)                                              |        Text Generation         |                                 WizardMath-70B-V1.0 model slightly outperforms some closed-source LLMs on the GSM8K, including ChatGPT 3.5, Claude Instant 1 and PaLM 2 540B.                                 |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                            [llama2](https://ai.meta.com/llama/license/)                             |
|                                              [WizardLM/WizardCoder-Python-34B-V1.0](https://github.com/nlpxucan/WizardLM)                                              |        Text Generation         |                                 WizardMath-70B-V1.0 model slightly outperforms some closed-source LLMs on the GSM8K, including ChatGPT 3.5, Claude Instant 1 and PaLM 2 540B.                                 |               Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118                |                            [llama2](https://ai.meta.com/llama/license/)                             |
|                                                     [h94/IP-Adapter](https://github.com/tencent-ailab/IP-Adapter)                                                      |        Text Generation         |                                    IP-Adapter, an effective and lightweight adapter to achieve image prompt capability for the pre-trained text-to-image diffusion models.                                    |        Image Encoder,Transformers 4.35.0.dev0, Pytorch 2.0.1+cu118         |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                             [bigscience/bloom](https://github.com/bigscience-workshop/Megatron-DeepSpeed)                                              |        Text Generation         |                  BLOOM is an autoregressive Large Language Model (LLM), trained to continue text from a prompt on vast amounts of text data using industrial-scale computational resources.                   |          Megatron-DeepSpeed, DeepSpeed, pytorch-1.11 w/ CUDA-11.5          |   [bigscience-bloom-rail-1.0](https://bigscience.huggingface.co/blog/the-bigscience-rail-license)   |
|                                        [openai/clip-vit-large-patch14](https://github.com/openai/CLIP/blob/main/model-card.md)                                         | Zero Shot Image Classification |                                    The model was also developed to test the ability of models to generalize to arbitrary image classification tasks in a zero-shot manner.                                    |                         pytorch-1.11 w/ CUDA-11.5                          |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                                              [suno/bark](https://github.com/suno-ai/bark)                                                              |         Text-to-Speech         | Bark is a transformer-based text-to-audio model created by Suno. Bark can generate highly realistic, multilingual speech as well as other audio - including music, background noise and simple sound effects. |                         pytorch-1.11 w/ CUDA-11.5                          |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                                            [coqui/XTTS-v1](https://github.com/coqui-ai/TTS)                                                            |         Text-to-Speech         |                                        ⓍTTS is a Voice generation model that lets you clone voices into different languages by using just a quick 6-second audio clip.                                        |                         pytorch-1.11 w/ CUDA-11.5                          |                         [Coqui Public Model License](https://coqui.ai/cpml)                         |
|                                              [CompVis/stable-diffusion-v1-4](https://github.com/CompVis/stable-diffusion)                                              |         Text-to-Image          |                                         Stable Diffusion is a latent text-to-image diffusion model capable of generating photo-realistic images given any text input.                                         |                       diffusers transformers scipy5                        | [The CreativeML OpenRAIL M license](https://huggingface.co/spaces/CompVis/stable-diffusion-license) |
|                          [monster-labs/control_v1p_sd15_qrcode_monster](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster)                           |         Text-to-QRCode         |                                                                       This model is made to generate creative QR codes that still scan.                                                                       |                                 ControlNet                                 | [openrail++](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)  |
|                              [databricks/dolly-v2-12b](https://github.com/databrickslabs/dolly#getting-started-with-response-generation)                               |        Text Generation         |                       Databricks' dolly-v2-12b, an instruction-following large language model trained on the Databricks machine learning platform that is licensed for commercial use.                        |                          pytorch-1.11 w/ CUDA-11.                          |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                                     [EleutherAI/gpt-j-6b](https://github.com/EleutherAI/the-pile)                                                      |        Text Generation         |                                                                              Text generation from prompt. (Requires finetuning)                                                                               |                          pytorch-1.11 w/ CUDA-11.                          |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                                    [hotshotco/Hotshot-XL](https://github.com/hotshotco/Hotshot-XL)                                                     |         Text-to-Video          |                               Hotshot-XL is an AI text-to-GIF model trained to work alongside Stable Diffusion XL.Hotshot-XL can generate GIFs with any fine-tuned SDXL model.                                |                   pytorch-1.11 w/ CUDA-11, SDXL, Imagen                    | [CreativeML Open RAIL++-M License](https://huggingface.co/hotshotco/Hotshot-XL/raw/main/LICENSE.md) |
|                                            [deepset/roberta-base-squad2](https://github.com/deepset-ai/haystack-tutorials)                                             |        Text Generation         |           This is the roberta-base model, fine-tuned using the SQuAD2.0 dataset. It's been trained on question-answer pairs, including unanswerable questions, for the task of Question Answering.            |                                Transformers                                |                      [cc-by-4.0](https://creativecommons.org/licenses/by/4.0/)                      |
|                                            [timbrooks/instruct-pix2pix](https://github.com/timothybrooks/instruct-pix2pix)                                             |         Image-to-Image         |                                   PyTorch implementation of InstructPix2Pix, an instruction-based image editing model, based on the original CompVis/stable_diffusion repo.                                   |               diffusers accelerate safetensors transformers                |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                              [Salesforce/blip-image-captioning-large](https://github.com/salesforce/BLIP)                                              |         Image-to-Text          |                                                BLIP, a new VLP framework which transfers flexibly to both vision-language understanding and generation tasks.                                                 |                                transformers                                |                    [bsd-3-clause](https://opensource.org/license/bsd-3-clause/)                     |
|                                        [pszemraj/long-t5-tglobal-base-16384-book-summary](https://github.com/pszemraj/textsum)                                         |        Text Generation         |                                                                  Summarize long text and get a SparkNotes-esque summary of arbitrary topics!                                                                  |                                transformers                                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                                 [riffusion/riffusion-model-v1](https://github.com/riffusion/riffusion)                                                 |         Text-to-Audio          |                                                                   Riffusion is an app for real-time music generation with stable diffusion.                                                                   |                                transformers                                |     [CreativeML Open RAIL-M ](https://huggingface.co/spaces/CompVis/stable-diffusion-license/)      |
|                                                      [mosaicml/mpt-7b](https://github.com/mosaicml/llm-foundry/)                                                       |        Text Generation         |                                   MPT-7B is a decoder-style transformer pretrained from scratch on 1T tokens of English text and code. This model was trained by MosaicML.                                    |                                transformers                                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                      [togethercomputer/GPT-NeoXT-Chat-Base-20B](https://github.com/togethercomputer/OpenChatKit)                                       |        Text Generation         |                                   GPT-NeoXT-Chat-Base-20B-v0.16 is a 20B parameter language model, fine-tuned from EleutherAI’s GPT-NeoX with over 40 million instructions                                    |                                transformers                                |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                   [Ashishkr/query_wellformedness_score](https://huggingface.co/Ashishkr/query_wellformedness_score)                                    |      Text Classification       |                   Evaluate the well-formedness of sentences by checking grammatical correctness and completeness. Sensitive to case and penalizes sentences for incorrect grammar and case.                   |                          transformers,pytorch,jax                          |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                            [cardiffnlp/twitter-roberta-base-irony](https://github.com/cardiffnlp/tweeteval)                                            |      Text Classification       |                                              This is a roBERTa-base model trained on ~58M tweets and finetuned for irony detection with the TweetEval benchmark.                                              |                    transformers,pytorch,jax,tensorflow                     |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                           [papluca/xlm-roberta-base-language-detection](https://github.com/facebookresearch/fairseq/tree/main/examples/xlmr)                           |      Text Classification       |                                                        You can directly use this model as a language detector, i.e. for sequence classification tasks.                                                        | Transformers 4.12.5,Pytorch 1.10.0+cu111,Datasets 1.15.1,Tokenizers 0.10.3 |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
| [madhurjindal/autonlp-Gibberish-Detector-492513457](https://huggingface.co/madhurjindal/autonlp-Gibberish-Detector-492513457?text=I+Machine+Learning+but+no+tomato%21) |      Text Classification       |                     The primary goal of this project is to classify user input as either gibberish or non-gibberish, enabling more accurate and meaningful interactions with the system.                      |                  Transformers 4.12.5,Pytorch 1.10.0+cu111                  |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                     [facebook/detr-resnet-50](https://github.com/facebookresearch/fairseq/tree/main/examples/xlmr)                                     |      Text Classification       |                                                 DEtection TRansformer (DETR) model trained end-to-end on COCO 2017 object detection (118k annotated images).                                                  |                  Transformers 4.12.5,Pytorch 1.10.0+cu111                  |                    [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                    |
|                                           [princeton-nlp/sup-simcse-roberta-large](https://github.com/princeton-nlp/SimCSE)                                            |       Feature Extraction       |                                                                                              Feature Extraction                                                                                               |                  Transformers 4.12.5,Pytorch 1.10.0+cu111                  |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                                                       [openai/whisper-small](https://github.com/openai/whisper)                                                        |  Automatic Speech Recognition  |                                                                                              Feature Extraction                                                                                               |                  Transformers 4.12.5,Pytorch 1.10.0+cu111                  |                            [MIT](https://www.mit.edu/~amini/LICENSE.md)                             |
|                   [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B)                                           |         Text-to-Image          |                                                                    High-quality text-to-image generation                                                                                                         |                  PyTorch/Stable Diffusion                     |          [apache-2.0](https://choosealicense.com/licenses/apache-2.0/)                         |
| [stabilityai/stable-diffusion-xl-refiner-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0)   |     Image-to-Image             |          SDXL consists of an ensemble of experts pipeline for latent diffusion                                                                                                                              |                  PyTorch/Stable Diffusion                 | [CreativeML Open RAIL++-M License](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/blob/main/LICENSE.md) |
|                                [CLIP](https://huggingface.co/openai/clip-vit-large-patch14)                       | Zero-Shot Image Classification |                                                              Arbitrary image classification tasks in a zero-shot manner                                                                                              |                              PyTorch                      |               [MIT](https://github.com/openai/CLIP/blob/main/LICENSE) |
| [tapas-base-finetuned-wtq](https://huggingface.co/google/tapas-base-finetuned-wtq)                        |    Table Question Answering    |            TAPAS is a BERT-like transformers model pretrained on a large corpus of English data from Wikipedia in a self-supervised fashion                                                                 |             PyTorch,TensorFlow,Transformers                      | [apache-2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [whisper-large-v2 ](https://huggingface.co/openai/whisper-large-v2)                                              |      Automatic Speech Recognition      |     Whisper is a pre-trained model for automatic speech recognition (ASR) and speech translation. Trained on 680k hours of labelled data, Whisper models demonstrate a strong ability to generalise to many datasets and domains without the need for fine-tuning.          | PyTorch,TensorFlow,Transformers |  [apache-2.0](https://choosealicense.com/licenses/apache-2.0/) |
