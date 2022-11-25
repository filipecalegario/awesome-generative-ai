# Generative Deep Art [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/filipecalegario/awesome-generative-deep-art/)


> A curated list of Generative Deep Art projects, tools, artworks, and models

 - [Prompt Engineering | Prompt Design | Prompt Craft](#prompt-engineering--prompt-design--prompt-craft)
  - [Stable Diffusion Inbox](#stable-diffusion-inbox)
    - [Stable Diffusion Deployed Web Tools](#stable-diffusion-deployed-web-tools)
    - [Web UI for Stable Diffusion via Google Colab](#web-ui-for-stable-diffusion-via-google-colab)
    - [References Collection about Stable Diffusion](#references-collection-about-stable-diffusion)
  - [Textual Inversion](#textual-inversion)
  - [Creative Uses of Text-to-Image Tools](#creative-uses-of-text-to-image-tools)
  - [Courses and Educational Materials](#courses-and-educational-materials)
  - [Exploring Images Databases](#exploring-images-databases)
  - [History](#history)
  - [Discussions and Philosophy](#discussions-and-philosophy)
    - [Promptism](#promptism)
  - [Image Synthesis](#image-synthesis)
    - [Collections](#collections)
    - [DALL-E 2](#dall-e-2)
    - [Latent Diffusion](#latent-diffusion)
    - [GLIDE](#glide)
    - [VQGAN+CLIP](#vqganclip)
    - [Famous models by big players](#famous-models-by-big-players)
    - [Text-to-image Google Colab Notebooks (Multiple Models)](#text-to-image-google-colab-notebooks-multiple-models)
  - [Image Upscaling](#image-upscaling)
  - [Image Restoration](#image-restoration)
  - [Online Tools and Applications](#online-tools-and-applications)
  - [Inbox](#inbox)
  - [Text-to-video](#text-to-video)
  - [How did they do it?](#how-did-they-do-it)
  - [Inbox: Text and Natural Language Processing](#inbox-text-and-natural-language-processing)
    - [OpenAI GPT-3](#openai-gpt-3)
  - [Papers and references for reading and understanding](#papers-and-references-for-reading-and-understanding)
  - [Interesting Instagram Accounts, Posts and Reels](https://github.com/filipecalegario/awesome-generative-deep-art/blob/main/README.md#interesting-instagram-accounts-posts-and-reels)
  - [Interesting Youtube Channels](#interesting-youtube-channels)
  - [Interesting GitHub Repositories](#interesting-github-repositories)
  - [Artists and Artworks](#artists-and-artworks)
  - [Galleries](#galleries)
  - [Selected examples of This X Does Not Exist](#selected-examples-of-this-x-does-not-exist)
  - [Pre-trained Models](#pre-trained-models)
  - [Neural Net Models](#neural-net-models)
  - [Latent Space Explorarion](#latent-space-explorarion)
  - [Other Related Awesome Lists](#other-related-awesome-lists)
  - [Notes, ideas for projects](#notes-ideas-for-projects)
  - [Improving Google Colab experience](#improving-google-colab-experience)
  - [Troubleshooting](#troubleshooting)
  - [Inbox for Adjacent or Related Pero No Mucho](#inbox-for-adjacent-or-related-pero-no-mucho)
  - [Contribute](#contribute)
  - [License](#license)

## Prompt Engineering | Prompt Design | Prompt Craft

* [CLIP Interrogator - a Hugging Face Space by pharma](https://huggingface.co/spaces/pharma/CLIP-Interrogator): image-to-text tool to figure out what a good prompt might be to create new images like an existing one
* [🔥🔥🔥] [Prompt book for data lovers II ❤️ - Google Slides](https://docs.google.com/presentation/d/1V8d6TIlKqB1j5xPFH7cCmgKOV_fMs4Cb4dwgjD5GIsg/edit#slide=id.g1834b964b0f_3_4): An open source exploration on text-to-image and data visualization
* [some9000/StylePile](https://github.com/some9000/StylePile): A helper script for AUTOMATIC1111/stable-diffusion-webui. Basically a mix and match to quickly get different results without wasting a lot of time writing prompts.
* [Artists To Study | All images generated with Google Colab TPUs + CompVis/stable-diffusion-v1-4 + Huggingface Diffusers](https://artiststostudy.pages.dev/): a systematic study of artists' styles made by [@camenduru](https://twitter.com/camenduru)
* [CLIP retrieval for laion5B](https://rom1504.github.io/clip-retrieval/?back=https%3A%2F%2Fknn5.laion.ai&index=laion5B&useMclip=false): CLIP retrieval using Laion5B. "It works by converting the text query to a CLIP embedding , then using that embedding to query a knn index of clip image embedddings".
* [rom1504/clip-retrieval](https://github.com/rom1504/clip-retrieval): Easily compute CLIP embeddings and build a CLIP retrieval system with them
* [PromptDesign | Reddit](https://www.reddit.com/r/PromptDesign/): Reddit community for "the art of communicating with natural language models"
* [Prompt Engineering and Zero-Shot/Few-Shot Learning [Guide] - inovex GmbH](https://www.inovex.de/de/blog/prompt-engineering-guide/): prompt engineering for text generation
* [clip-interrogator.ipynb - Colaboratory](https://colab.research.google.com/github/pharmapsychotic/clip-interrogator/blob/main/clip_interrogator.ipynb#scrollTo=rbDEMDGJrJEo): a tool for image-to-prompt
* [Useful Prompt Engineering tools and resources | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xcrm4d/useful_prompt_engineering_tools_and_resources/) 
* [PromptHero](https://prompthero.com/): Search the best prompts for Stable Diffusion, DALL-E and Midjourney
* [promptoMANIA](https://promptomania.com/): AI art community with prompt generator
* [Lexica](https://lexica.art/): search over 10M+ Stable Diffusion images and prompts
* [succinctly/text2image-prompt-generator · Hugging Face](https://huggingface.co/succinctly/text2image-prompt-generator): a GPT-2 model fine-tuned on the succinctly/midjourney-prompts dataset, which contains 250k text prompts that users issued to the Midjourney text-to-image service over a month period
* [The Prompter | vicc | Substack](https://theprompter.substack.com/): a newsletter about news, tips and thoughts around prompt engineering
* [(19) Nikhil Agrawal 📌 on Twitter](https://twitter.com/HeyNikhila/status/1570005481896255490): 11 AI Images Prompt websites to level up the image quality
* [Phraser](https://phraser.tech/): a tool that support prompt creation
* [PromptBase | Prompt Marketplace](https://promptbase.com/): PromptBase is a marketplace for DALL·E, Midjourney & GPT-3 prompts, where people can sell prompts and make money from their prompt crafting skills.
* [Professional AI whisperers have launched a marketplace for DALL-E prompts - The Verge](https://www.theverge.com/2022/9/2/23326868/dalle-midjourney-ai-promptbase-prompt-market-sales-artist-interview)
* [Visual Prompt Builder](https://tools.saxifrage.xyz/prompt): simple deck of illustrated card to combine modifiers for prompt building
* [Prompt Engineering Template - Google Sheets](https://docs.google.com/spreadsheets/d/1-snKDn38-KypoYCk9XLPg799bHcNFSBAVu2HVvFEAkA/edit#gid=0): spreadsheet with lists of modifiers for prompt building and a lot of interesting links for reference
* [Prompt Engineering: From Words to Art - Saxifrage Blog](https://www.saxifrage.xyz/post/prompt-engineering)
* [DALL·Ery GALL·Ery Resources](https://dallery.gallery/prompt-resources-tools-ai-art/): DALL·E 2 and AI art prompt resources & tools to inspire beautiful images
* [[2204.13988] A Taxonomy of Prompt Modifiers for Text-To-Image Generation](https://arxiv.org/abs/2204.13988) 
* [List of Aesthetics | Aesthetics Wiki | Fandom](https://aesthetics.fandom.com/wiki/List_of_Aesthetics) 
* [Artist Directory (Volcano Comparison) | AI Art Creation Wiki | Fandom](https://aiartcreation.fandom.com/wiki/Artist_Directory_(Volcano_Comparison)) 
* [The DALL·E 2 Prompt Book – DALL·Ery GALL·Ery](https://dallery.gallery/the-dalle-2-prompt-book/)
* [DALL·Ery GALL·Ery](https://dallery.gallery/): A guide to OpenAI's DALL·E – prompts, projects, examples, and tips
* [(2) MASSIVE 💥 DALL-E 2 ANIME ⚡︎ KEYWORDS + MODIFIERS LIST ★ : haaaaven](https://www.reddit.com/user/haaaaven/comments/w05f56/massive_dalle_2_anime_keywords_modifiers_list/): image prompt modifier collection by haaaaven
* [DrawBench](https://docs.google.com/spreadsheets/d/1y7nAbmR4FREi6npB1u-Bo3GFdwdOPYJc617rBOxIRHY/edit#gid=0): a list of prompts the Google Imagen is organizing as a benchmark
* [CLIP Prompt Engineering for Generative Art - matthewmcateer.me](https://matthewmcateer.me/blog/clip-prompt-engineering/): list of styles tested with Quick CLIP Guided Diffusion
* [Adobe should make a boring app for prompt engineers (Interconnected)](https://interconnected.org/home/2022/06/02/dalle)
* [[2206.00169] Discovering the Hidden Vocabulary of DALLE-2](https://arxiv.org/abs/2206.00169)
* [When SD just doesn't understand the prompt no matter how hard I try | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgwcab/when_sd_just_doesnt_understand_the_prompt_no/) 
* [It's very interesting how some prompts have very defined output but other specific ones are not | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgplii/its_very_interesting_how_some_prompts_have_very/)

## DreamBooth

* [Training Stable Diffusion with Dreambooth using Diffusers](https://huggingface.co/blog/dreambooth): experiments to analyze the effect of different settings in Dreambooth
* [fast-DreamBooth.ipynb - Colaboratory](https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb): train custom concepts from input images with this simplified DreamBooth colab
* [(1166) Como Criar Artes Incríveis com o seu Próprio Rosto Usando o Dreambooth! DE FORMA FÁCIL E DE GRAÇA! - YouTube](https://www.youtube.com/watch?v=3e4jwgqy-0A): tutorial in Portuguese on how to train DreamBooth with your own face

## Deforum

* [Deforum Stable Diffusion Animation - v5 Math Functions - Demo and Test - YouTube](https://www.youtube.com/watch?v=6snk7gw898g)
* [Deforum Stable Diffusion](https://colab.research.google.com/github/deforum/stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb#scrollTo=63UOJvU3xdPS): generating videos from scripted prompts

## Stable Diffusion Inbox

* [🔥🔥🔥] [SD GUIDE FOR ARTISTS AND NON-ARTISTS - Google Docs](https://docs.google.com/document/d/1R2UZi5G-DXiz2HcCrfAFLYJoer_JPDEoZmV7wy1tEz0/edit#): a Google Docs with in-depth tips, tricks, tutorials and more related to Stable Diffusion
* [NEWS][Canva Adds a Free and Unlimited AI Text-to-Image Generator | PetaPixel](https://petapixel.com/2022/11/10/canva-adds-a-free-and-unlimited-ai-text-to-image-generator/)
* [prompthero/midjourney-v4-diffusion · Hugging Face](https://huggingface.co/prompthero/midjourney-v4-diffusion): Stable Diffusion fine tuned on Midjourney v4 images, by [PromptHero](https://prompthero.com/)
* [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/): explained by Jay Alammar (Visualizing machine learning one concept at a time)
* [Img To Music](https://huggingface.co/spaces/fffiloni/img-to-music) a Hugging Face Space by fffiloni
* [Atlas KREA Stable Diffusion](https://atlas.nomic.ai/map/809ef16a-5b2d-4291-b772-a913f4c8ee61/9ed7d171-650b-4526-85bf-3592ee51ea31): An explorable map of KREA AI's Stable Diffusion Search Engine
* [TheLastBen/fast-stable-diffusion](https://github.com/TheLastBen/fast-stable-diffusion): fast-stable-diffusion, +25-50% speed increase + memory efficient + DreamBooth
* [NovelAI Improvements on Stable Diffusion | by NovelAI | Oct, 2022 | Medium](https://blog.novelai.net/novelai-improvements-on-stable-diffusion-e10d38db82ac)
* [ashawkey/stable-dreamfusion](https://github.com/ashawkey/stable-dreamfusion): A pytorch implementation of text-to-3D dreamfusion, powered by stable diffusion.
* [🔥🔥🔥] [JoePenna/Dreambooth-Stable-Diffusion](https://github.com/JoePenna/Dreambooth-Stable-Diffusion): Implementation of Dreambooth (https://arxiv.org/abs/2208.12242) with Stable Diffusion (tweaks focused on training faces)
* [🔥🔥🔥] [DreamBooth](https://dreambooth.github.io/): fine tuning text-to-image diffusion models for subject-driven generation
* [🔥] [Arki's Stable Diffusion Guides](https://stablediffusionguides.carrd.co/#one)
* [examples/stable-diffusion-finetuning at main · LambdaLabsML/examples](https://github.com/LambdaLabsML/examples/tree/main/stable-diffusion-finetuning): Fine Tuning Stable Diffusion
* [lkwq007/stablediffusion-infinity](https://github.com/lkwq007/stablediffusion-infinity): Outpainting with Stable Diffusion on an infinite canvas 
* [🔥🔥🔥] [ML News Stable Diffusion Takes Over! (Open Source AI Art) by Yannic Kilcher - YouTube](https://www.youtube.com/watch?v=xbxe-x6wvRw): video with examples, updates, and discussion about the impact of Stable Diffusion
* [Diffusion Models in Vision: A Survey | DeepAI](https://deepai.org/publication/diffusion-models-in-vision-a-survey): paper about the diffusion techniques which also discuss the relation with other generative deep learning models
* [ThereforeGames/txt2mask](https://github.com/ThereforeGames/txt2mask): Automatically create masks for Stable Diffusion inpainting using natural language
* [basujindal/stable-diffusion](https://github.com/basujindal/stable-diffusion): Optimized Stable Diffusion modified to run on lower GPU VRAM
* [Stable WarpFusion v0.5 (restricted to patreons)](https://www.patreon.com/sxela): conditioning video frames with Stable Diffusion by [@devdef](https://twitter.com/devdef)
* [nateraw/stable-diffusion-videos](https://github.com/nateraw/stable-diffusion-videos): Create videos with Stable Diffusion by exploring the latent space and morphing between text prompts

### Stable Diffusion Deployed Web Tools

* [Astria](https://www.astria.ai/): Tailor-made AI image generation
* [drawanyone](https://drawanyone.com/): generate drawings based on five input images
* [DiffusionBee](https://diffusionbee.com/): stable diffusion GUI App
* [getimg.ai](https://getimg.ai/): Generate photo-realistic images from text using Stable Diffusion
* [Enstil: Fast, open, AI-generated images](https://enstil.ai/?source=12)
* [Dezgo - Text-to-Image AI generator](https://dezgo.com/)
* [Baseten](https://app.baseten.co/apps/VqK2vYP/operator_views/pqvba2q): Stable Diffusion Demo
* [DreamStudio](https://beta.dreamstudio.ai/): Frontend for Stable Diffusion API by Stability.ai
* [Pollinations - pollinations/stable-diffusion-private](https://pollinations.ai/create/stablediffusion)
* [tencentarc/gfpgan – Run with an API on Replicate](https://replicate.com/tencentarc/gfpgan) 
* [andreasjansson/stable-diffusion-wip – Run with an API on Replicate](https://replicate.com/andreasjansson/stable-diffusion-wip) 
* [stability-ai/stable-diffusion – Run with an API on Replicate](https://replicate.com/stability-ai/stable-diffusion)
* [Osmosis.Studio](http://osmosis.studio/) : web-based content-aware collaborative design tool for generating AI ads that sell real products

### Web UI for Stable Diffusion via Google Colab

* [StableDiffusion_WebUI_Simplified.ipynb](https://colab.research.google.com/github/filipecalegario/awesome-generative-deep-art/blob/main/StableDiffusion_WebUI_Simplified.ipynb): versão em português do notebook para rodar a Web UI do Stable Diffusion no Google Colab de graça
* [GitHub - AUTOMATIC1111/stable-diffusion-webui: Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui): expanded Stable Diffusion web UI
* [GitHub - sd-webui/stable-diffusion-webui](https://github.com/hlky/stable-diffusion-webui): Stable Diffusion web UI
* [Stable_Diffusion_WebUi_Simplified.ipynb - Colaboratory](https://colab.research.google.com/github/pinilpypinilpy/sd-webui-colab-simplified/blob/main/Stable_Diffusion_WebUi_Simplified.ipynb#scrollTo=gk1TyBA0Arxt) 

### References Collection about Stable Diffusion

* [GitHub - awesome-stable-diffusion/awesome-stable-diffusion](https://github.com/awesome-stable-diffusion/awesome-stable-diffusion): Curated list of resources for the Stable Diffusion AI Model
* [Stable Diffusion General Updates Posted by u/ImeniSottoITreni | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xcclmf/can_we_please_make_a_general_update_on_all_the/?utm_source=share&utm_medium=web2x&context=3): a general update on all the "most important" news/repos available
* [List of Stable Diffusion systems | Reddit](https://www.reddit.com/r/StableDiffusion/comments/wqaizj/list_of_stable_diffusion_systems/)
* [Stable Diffusion Akashic Records | Maks-s/sd-akashic](https://github.com/Maks-s/sd-akashic): A compendium of information regarding Stable Diffusion (SD)
* [1 week of Stable Diffusion | multimodal.art](https://multimodal.art/news/1-week-of-stable-diffusion)
* [Voldy Guide](https://rentry.co/voldy): detailed beginners guide for Stable Diffusion
* [Dreamer's Guide to Getting Started w/ Stable Diffusion! | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xcq819/dreamers_guide_to_getting_started_w_stable/)
* [A collection of sites using Stable Diffusion (and other handy links) | Reddit](https://www.reddit.com/r/StableDiffusion/comments/wzj8kk/a_collection_of_sites_using_stable_diffusion_and/) 

## Textual Inversion

* [rinongal/textual_inversion](https://github.com/rinongal/textual_inversion): repo contains the official code, data and sample inversions of Textual Inversion paper
* [2208.01618 An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion](https://arxiv.org/abs/2208.01618): paper that describes the Textual Inversion technique
* [sd-concepts-library (Stable Diffusion concepts library)](https://huggingface.co/sd-concepts-library): Stable Diffusion Textual Inversion Concepts Library - browse through objects and styles taught by the community to Stable Diffusion and use them in your prompts!

## Creative Uses of Text-to-Image Tools

* [De-painting historical photographs | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgbug2/depainting_historical_photographs/) 
* [img2img animation with hands | Reddit](https://www.reddit.com/r/StableDiffusion/comments/x92itm/proof_of_concept_using_img2img_ebsynth_to_animate/)
* [VID 2 VID user script | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgo87s/wip_vid_2_vid_user_script/)
* [Seamless textures AI generator for Blender by Antonio Freyre | Twitter](https://twitter.com/merlino_games/status/1571205845819559936)
* ["Shattered" by Ronny Khalil | Twitter](https://twitter.com/ronnykhalil/status/1569956085905203200): using warp fusion to generate a shattered glass effect
* [Acid Dance by aiplague | Twitter](https://twitter.com/aiplague/status/1564989456318451714) 
* [Fused video by [@remi_molettee](https://twitter.com/remi_molettee)](https://twitter.com/remi_molettee/status/1568245586494738432)
* [Animation with Dall-e + AE | Reddit](https://www.reddit.com/r/MediaSynthesis/comments/xgeehe/animation_with_dalle_ae_patent_drawing_of_an/): Patent drawing of an electronic device that ...
* [You Describe & AI Photoshops Faces For You [StyleCLIP] - YouTube](https://youtu.be/d1OET63Ulwc)
* [Experimental Films + Machine Learning Week 7 Part 1 (Aphantasia with OpenAI CLIP) - YouTube](https://youtu.be/-FrIui8Mp-8)
* [GitHub - Sanster/lama-cleaner](https://github.com/Sanster/lama-cleaner): Image inpainting tool powered by SOTA AI Model

## Courses and Educational Materials

* [Words are Images | BustBright - Machine Learning Art](https://www.bustbright.com/product/words-are-images-7-week-online-class-starting-october-24th-2022-/331): 7-week Online class starting October 24th, 2022 by [Derrick Schultz](https://twitter.com/dvsch/)
* [Grokking Stable Diffusion.ipynb - Colaboratory - Part 1](https://colab.research.google.com/drive/1dlgggNa5Mz8sEAGU0wFCHhGLFooW_pf1?usp=sharing): notebook by [@johnowhitaker](https://twitter.com/johnowhitaker) exploring Stable Diffusion details
* [Grokking Stable Diffusion: Textual Inversion.ipynb - Colaboratory - Part 2](https://colab.research.google.com/drive/1RTHDzE-otzmZOuy8w1WEOxmn9pNcEz3u?usp=sharing): sequel to Grokking Stable Diffusion by [@johnowhitaker](https://twitter.com/johnowhitaker) that focus on Text Inversion
* [GitHub - johnowhitaker/aiaiart](https://github.com/johnowhitaker/aiaiart): Course content and resources for the AIAIART course
* [Implementation/tutorial of stable diffusion with side-by-side notes by labml.ai | Twitter](https://twitter.com/labmlai/status/1571080112459878401)

## Exploring Images Databases

* [Have I Been Trained?](https://haveibeentrained.com/): tool for searching 5.8 billion images used to train popular AI art models
* [laion-aesthetic-6pls](https://laion-aesthetic.datasette.io/laion-aesthetic-6pls/images): exploring 12 million of the 2.3 billion images used to train Stable Diffusion's image generator

## History

* [🔥🔥🔥][AI Timeline](https://www.fabianmosele.com/ai-timeline): A history of text-to-image ML models by Fabian Mosele
* [AI-Generated Art](https://www.v7labs.com/blog/ai-generated-art): From Text to Images & Beyond Examples
* [1 week of Stable Diffusion | multimodal.art](https://multimodal.art/news/1-week-of-stable-diffusion) 

## Discussions and Philosophy

* [🔥🔥🔥][Generative AI: A Creative New World | Sequoia Capital US/Europe](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/): report by Sequoia Capital about the possible applications of Generative AI
* [Synthetic Creativity - by Cavin - Deep Markets](https://deepmarkets.substack.com/p/synthetic-creativity)
* [Our Vision for the Future of Synthetic Media | by Victor Riparbelli | Medium](https://vriparbelli.medium.com/our-vision-for-the-future-of-synthetic-media-8791059e8f3a)
* [Deep Else](https://dejangrba.github.io/deep-else/): A Critical Framework for AI Art
* [How Photography Became An Art Form | Aaron Hertzmann’s blog](https://aaronhertzmann.com/2022/08/29/photography-history.html)
* [Text Is the Universal Interface - Scale](https://scale.com/blog/text-universal-interface?utm_source=tldrnewsletter) 
* [This artist is dominating AI-generated art. And he’s not happy about it. | MIT Technology Review](https://www.technologyreview.com/2022/09/16/1059598/this-artist-is-dominating-ai-generated-art-and-hes-not-happy-about-it/)
* [The REAL fight over AI art: StableDiffusion | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgu2uo/the_real_fight_over_ai_art/)
* [Rutkowski battling AI art overlord | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xgv0dw/rutkowski_battling_ai_art_overlord/)
* [Instead of mining cryptocoins with GPUs, are we now mining art? | Reddit](https://www.reddit.com/r/StableDiffusion/comments/xg8s8e/instead_of_mining_cryptocoins_with_gpus_are_we/) 
* [Using AI to create art is NOT art! | Reddit : ArtistLounge](https://www.reddit.com/r/ArtistLounge/comments/xczk89/using_ai_to_create_art_is_not_art/) 
* [Appreciating the Poetic Misunderstandings of A.I. Art | The New Yorker](https://www.newyorker.com/culture/infinite-scroll/appreciating-the-poetic-misunderstandings-of-ai-art?s=09)

### Promptism

* [promptism | Reddit](https://www.reddit.com/r/promptism/): Promptism is an art movement whose creators apply machine learning models trained with contrastive language-image pre-training (CLIP) techniques for image generation
* [The Promptist Manifesto – deeplearn.art](https://deeplearn.art/the-promptist-manifesto/)

## Image Synthesis
* [[arxiv/2211.11319] VectorFusion](https://arxiv.org/abs/2211.11319): Text-to-SVG by Abstracting Pixel-Based Diffusion Models
* [CHARL-E](https://www.charl-e.com/): Run Stable Diffusion on your M1 Mac
* [Parrot Zone](https://proximacentaurib.notion.site/proximacentaurib/parrot-zone-74a5c04d4feb4f12b52a41fc8750b205): a database of image synthesis references
* [Image Synth Link List](https://proximacentaurib.notion.site/39805c50735849cfa54b5d688587e12e?v=b9ea748623e342fdae02d07c86c668bf): a collection of links organized by the collective parrot zone
* [🔥] [altryne/awesome-ai-art-image-synthesis](https://github.com/altryne/awesome-ai-art-image-synthesis): A list of awesome tools, ideas, prompt engineering tools, colabs, models, and helpers for the prompt designer playing with aiArt and image synthesis. Covers Dalle2, MidJourney, StableDiffusion, and open source tools.
* [🔥🔥🔥] [Ai generative art tools](https://pharmapsychotic.com/tools.html): a massive list of shared Google Colab notebooks and tools organized by [@pharampsychotic](https://twitter.com/pharmapsychotic)
* [Introduction — PyTTI-Tools](https://pytti-tools.github.io/pytti-book/intro.html)
* [pixray/pixray](https://github.com/pixray/pixray): Pixray is an image generation system
* [pixray/pixray_notebooks](https://github.com/pixray/pixray_notebooks): pixray demo notebooks
* [dribnet/pixray-text2image – Run with an API on Replicate](https://replicate.com/dribnet/pixray-text2image) 
* [sberbank-ai/ru-dalle](https://github.com/sberbank-ai/ru-dalle): Generate images from texts. In Russian.
* [Pyttipanna](https://pyttipanna.xyz/): visual interface for Pytti by [@_staus](https://twitter.com/_staus). Pytti is created by [@sportsracer48](https://twitter.com/sportsracer48)

### Collections

* [AI art resources | Unlimited Dream Co.](https://www.unlimiteddreamco.xyz/resources): collection of AI art software, guides, inspiration, tools and other useful resources.
* [AI Library](https://library.phygital.plus/): catalog of AI tools and neural networks for creators
* [Post Reddit - MachineLearning](https://www.reddit.com/r/MachineLearning/comments/ldc6oc/p_list_of_sitesprogramsprojects_that_use_openais/): List of sites/programs/projects that use OpenAI's CLIP neural network for steering image/video creation to match a text description 
* [Top 41 AI Art Generators](https://aiartists.org/ai-generated-art-tools): Make AI Art, Paintings & More (2021 GUIDE) — AIArtists.org
* [10 Best AI Art Generators (2022) - Unite.AI](https://www.unite.ai/10-best-ai-art-generators/)
* [Get started with making AI art in 2022 – deeplearn.art](https://deeplearn.art/get-started-with-making-ai-art-in-2022/)
* [Text-to-Image Summary – Part 1 | Softology's Blog](https://softologyblog.wordpress.com/2021/06/10/text-to-image-summary/) 
* [🔥🔥] [Hitchhiker's Guide To The Latent Space: Community Notebook Document](https://docs.google.com/document/d/1ON4unvrGC2fSEAHMVb4idopPlWmzM0Lx5cxiOXG47k4/edit): great collection of interesting notebooks
* [Machine learning for arts](https://ml4a.net/)
* [🔥] [dvschultz/ml-art-colabs](https://github.com/dvschultz/ml-art-colabs): A list of Machine Learning Art Colabs

### DALL-E 2

* [lucidrains/DALLE2-pytorch](https://github.com/lucidrains/DALLE2-pytorch): Implementation of DALL-E 2, OpenAI's updated text-to-image synthesis neural network, in Pytorch
* [DALL-E 2’s Failures Are the Most Interesting Thing About It - IEEE Spectrum](https://spectrum.ieee.org/openai-dall-e-2): paper by Eliza Strickland

### Latent Diffusion

* [LatentVision_rynmurdock.ipynb - Colaboratory](https://colab.research.google.com/github/olaviinha/NeuralImageGeneration/blob/main/LatentVision_rynmurdock.ipynb) 
* [Latent_Diffusion_with_LAION_400M.ipynb - Colaboratory](https://colab.research.google.com/github/pharmapsychotic/latent-diffusion/blob/main/Latent_Diffusion_with_LAION_400M.ipynb)

### GLIDE

* ["GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models", Nichol et al 2021 (OpenAI's DALL-E successor: 5b-parameter diffusion models + noise-aware CLIP) : MediaSynthesis](https://www.reddit.com/r/MediaSynthesis/comments/rl3mee/glide_towards_photorealistic_image_generation_and/?utm_source=share&utm_medium=ios_app&utm_name=iossmf)
* [OpenAI paper: "GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models". Code and a smaller filtered model (300 million parameters vs 3.5 billion parameters in the paper) are available. : bigsleep](https://www.reddit.com/r/bigsleep/comments/rl5rgw/openai_paper_glide_towards_photorealistic_image/) 

### VQGAN+CLIP

* [VQ-GAN | Paper Explanation - YouTube](https://www.youtube.com/watch?v=wcqLFDXaDO8): explanation video about VQGAN with didactic visualizations
* [VQGAN+CLIP — How does it work?. The synthetic imagery (“GAN Art”) scene… | by Alexa Steinbrück | Aug, 2021 | Medium](https://alexasteinbruck.medium.com/vqgan-clip-how-does-it-work-210a5dca5e52) 
* [Introduction to VQGAN+CLIP - 🟧Sourceful](https://sourceful.us/doc/935/introduction-to-vqganclip)
* [How to use VQGAN+CLIP to generate images from a text prompt —tutorial for beginners | NightCafe Creator](https://medium.com/nightcafe-creator/vqgan-clip-tutorial-a411402cf3ad)
* [VQGAN + CLIP Keyword Modifier Comparison - NightCafe Creator](https://creator.nightcafe.studio/vqgan-clip-keyword-modifier-comparison)
* [~200 CLIP+VQGAN keywords tested on 4 subjects : bigsleep](https://www.reddit.com/r/bigsleep/comments/oq2pai/200_clipvqgan_keywords_tested_on_4_subjects/?utm_medium=android_app&utm_source=share)
* [AI Generated Art Scene Explodes as Hackers Create Groundbreaking New Tools CLIP+VQ-GAN | VICE](https://www.vice.com/en/article/n7bqj7/ai-generated-art-scene-explodes-as-hackers-create-groundbreaking-new-tools)
* [VQGAN+CLIP (with pooling)](https://colab.research.google.com/drive/1ZAus_gn2RhTZWzOWUpPERNC0Q8OhZRTZ#scrollTo=JX56bq4rEKIp): Generate images from text prompts with VQGAN and CLIP (z+quantize method)
* [~200 CLIP+VQGAN keywords on 4 subjects, by @kingdomakrillic  - Imgur](https://imgur.com/a/SALxbQm)
* [Experimentando o VQGAN+CLIP: gerador de imagens a partir de textos - YouTube Filipe Calegario](https://www.youtube.com/watch?v=Yy5NMTkN-Qc) 

### Famous models by big players
* [Imagen](https://imagen.research.google/): Google's Text-to-Image Diffusion Models
* [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/): Meta's creative control for AI image generation
* [DALL·E 2](https://openai.com/dall-e-2/): OpenAI system, evolution of the DALL-E launched in Jan 2021, that can create realistic images and art from a description in natural language.
* [Stable Diffusion](https://stability.ai/blog/stable-diffusion-announcement): Stability.Ai's text-to-image model that is a breakthrough in speed and quality meaning that it can run on consumer GPUs
* [LAION](https://laion.ai/): Large-scale Artificial Intelligence Open Network

### Text-to-image Google Colab Notebooks (Multiple Models)
* [VQGAN + CLIP + Gumbel](https://colab.research.google.com/drive/1tim3xTsZXafK-A2rOUsevckdl4OitIiw)
* [OpenAI DVAE+CLIP](https://colab.research.google.com/drive/10DzGECHlEnL4oeqsN-FWCkIe_sq3wVqt)
* [Text2Image VQGAN](https://colab.research.google.com/github/eps696/aphantasia/blob/master/CLIP_VQGAN.ipynb)
* [Improved Multi Perceptor VQGAN + CLIP](https://colab.research.google.com/drive/1peZ98vBihDD9A1v7JdH5VvHDUuW5tcRK)
* [Latent Majesty Diffusion v1.3](https://colab.research.google.com/github/multimodalart/MajestyDiffusion/blob/main/latent.ipynb)
* [CLIP Guided Decision Transformer](https://colab.research.google.com/drive/1V66mUeJbXrTuQITvJunvnWVn96FEbSI3)
* [CLIP Guided Diffusion](https://colab.research.google.com/drive/12a_Wrfi2_gwwAuN3VvMTwVMz9TfqctNj)
* [GLIDE](https://colab.research.google.com/github/openai/glide-text2im/blob/main/notebooks/text2im.ipynb)
* [PixelDirect](https://colab.research.google.com/drive/1F9ZOZnpV3uBPRDSESaAXYwzNZJQRJT75)
* [CLIP Guided Diffusion Secondary Model Method](https://colab.research.google.com/drive/1mpkrhOjoyzPeSWy2r7T8EYRaU7amYOOi)
* [Zoetrope](https://colab.research.google.com/drive/1LpEbICv1mmta7Qqic1IcRTsRsq7UKRHM)
* [Quick CLIP Guided Diffusion](https://colab.research.google.com/drive/1FuOobQOmDJuG7rGsMWfQa883A9r4HxEO)
* [MSE Regulized VQGAN+CLIP](https://colab.research.google.com/drive/1hf1seGOZctOJUznkhJNblLluXHbWLKZh)
* [CLIPRGB ImStack](https://colab.research.google.com/drive/1CcibxlLDng2yzcjLwwwSADRcisc1qVCs)
* [CLIP Guided Diffusion v4](https://colab.research.google.com/drive/1V66mUeJbXrTuQITvJunvnWVn96FEbSI3)
* [Simplified Google Colab Interface for the above models](https://sites.google.com/ear.com.br/aimodelgallery/home?authuser=1): series of interface simplification made by EAR+CIn Research project

## Image Upscaling
* [Model Database - Upscale Wiki](https://upscale.wiki/wiki/Model_Database): list of models for upscaling images
* [Gigapixel AI](https://www.topazlabs.com/gigapixel-ai): paid AI image upscaler delivering enhanced detail and resolution

## Image Restoration
* [TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN): GFPGAN aims at developing Practical Algorithms for Real-world Face Restoration

## Online Tools and Applications

* [Synthesia](https://www.synthesia.io/): AI Video Generation Platform [#avatar]
* [Studio D-ID](https://studio.d-id.com/): create video with still images synced with text-to-speech tool [#avatar]
* [starryai](https://www.starryai.com/): AI Art Generator App - AI Art Maker
* [ProsePainter](https://www.prosepainter.com/): an interactive tool to "paint with words." It incorporates guidable text-to-image generation into a traditional digital painting interface
* [ProsePainter: Image + Sketching Interface + CLIP! - YouTube](https://www.youtube.com/watch?v=mK4F32xNrdw&t=429s)
* [Cocreator AI](https://cocreator.ai/): creative computer agent (in wait list)
* [Runway ML](http://runwayml.com/): AI video creation suite
* [Hotpot.ai - Hotpot.ai](https://hotpot.ai/): set of AI Tools to post-process images
* [Toonify yourself by Justin Pinkney](https://www.justinpinkney.com/toonify-yourself/): turn a human face into a cartoon
* [deepart.io](https://deepart.io/): a online tool for applying style transfer
* [Artbreeder](https://www.artbreeder.com/): web-based tool to generate images by breeding existing images
* [Ostagram.ru](https://www.ostagram.me/): image style transfer plataform
* [cleanup.pictures](https://cleanup.pictures/): remove objects, people, text and defects from any picture for free
* [remove.bg](https://www.remove.bg/): remove background from images
* [Quick, Draw!](https://quickdraw.withgoogle.com/): Can a neural network learn to recognize doodling? A game to help NL by adding users drawing
* [LOVO AI](https://www.lovo.ai/): AI Voiceover & Text to Speech Platform with human-like voices
* [AIVA](https://www.aiva.ai/): The AI composing emotional soundtrack music

## Inbox
* [chaosreactor/awesome-generative-ai](https://github.com/chaosreactor/awesome-generative-ai): An awesome list of low- and no-code generative AI resources
* [steven2358/awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai): A curated list of modern Generative Artificial Intelligence projects and services
* [MubertAI/Mubert-Text-to-Music](https://github.com/MubertAI/Mubert-Text-to-Music): A simple notebook demonstrating prompt-based music generation via Mubert API
* [(5) Deforum notebook v0.5 for Stable Diffusion animations is out! Now with math automation, perspective flips, prompt weights, video masking and waifus! : StableDiffusion](https://www.reddit.com/r/StableDiffusion/comments/xuytx5/deforum_notebook_v05_for_stable_diffusion/) 
* [CLIPasso](https://clipasso.github.io/clipasso/): Semantically-Aware Object Sketching
* [(9) AK on Twitter: "DreamFusion: Text-to-3D using 2D Diffusion paper: https://t.co/euVCkNPzB0 abs: https://t.co/FO7nqjLrQA project page: https://t.co/BTvt1WQqIi DeepDream on a pretrained 2D diffusion model enables text-to-3D synthesis https://t.co/20zIElXJDN" / Twitter](https://twitter.com/_akhaliq/status/1575541930905243652?t=m17X6zyC0c8-VvIWjICc1w&s=33) 
* [DeCoDe Lab](http://decode.mit.edu/projects/creativegan/): CREATIVEGAN - Editing Generative Adversarial Networks for Creative Design Synthesis
* [yuval-alaluf/stylegan3-editing](https://github.com/yuval-alaluf/stylegan3-editing): Official Implementation of "Third Time's the Charm? Image and Video Editing with StyleGAN3" https://arxiv.org/abs/2201.13433
* [autonomousvision/projected_gan](https://github.com/autonomousvision/projected_gan): [NeurIPS'21] Projected GANs Converge Faster
* [These Bored Apes Do Not Exist: GAN to NFT Pipeline | Medium](https://medium.com/@nathancooperjones/these-bored-apes-do-not-exist-6bed2c73f02c)
* [apple/ml-no-token-left-behind](https://github.com/apple/ml-no-token-left-behind): PyTorch Implementation of No Token Left Behind: Explainability-Aided Image Classification and Generation
* [amrzv/awesome-colab-notebooks](https://github.com/amrzv/awesome-colab-notebooks): Collection of google colaboratory notebooks for fast and easy experiments
* [baowenbo/DAIN](https://github.com/baowenbo/DAIN): Depth-Aware Video Frame Interpolation (CVPR 2019)
* [Dain-App 1.0 [Nvidia Only] by GRisk](https://grisk.itch.io/dain-app): Depth-Aware Video Frame Interpolation (CVPR 2019)
* [Lucid Lyrics - AI Assisted Art](https://www.lucidlyricsart.com/): AI-Assisted Lyrical Interpretations by Walter Arnold
* [AI Image to sound [Melobytes.com]](https://melobytes.com/en/app/ai_image2sound) 
* [disco-diffusion/Local_Disco_Diffusion_v4_1.ipynb at main · Midgraph/disco-diffusion](https://github.com/Midgraph/disco-diffusion/blob/main/Local_Disco_Diffusion_v4_1.ipynb)
* [Audio to keyframe string](https://audio-keyframe-generator.glitch.me/): this tool is used to generate strings for the keyframes of AI animation notebooks, such as [this VQGAN+CLIP Animations notebook](https://colab.research.google.com/github/chigozienri/VQGAN-CLIP-animations/blob/main/VQGAN-CLIP-animations.ipynb), using the volume of audio tracks.
* [🔥🔥] [Pollinations.AI](https://pollinations.ai): a frontend hosting a set of curated notebooks that allow creating and experimenting with generative art. Their objective is to facilitate the creation and translation of multiple forms of human expressions.
* [🔥] [hive/notebooks at main · pollinations/hive](https://github.com/pollinations/hive/tree/main/notebooks): collection of notebooks used by Pollinations.AI 
* [ouhenio/StyleGAN3-CLIP-notebooks](https://github.com/ouhenio/StyleGAN3-CLIP-notebooks): A collection of Jupyter notebooks to play with NVIDIA's StyleGAN3 and OpenAI's CLIP for a text-based guided image generation.
* [k-l-lambda/stylegan-web](https://github.com/k-l-lambda/stylegan-web): A web porting for NVlabs' StyleGAN. 
* [🔥🚀] [S2ML Image Generator](https://colab.research.google.com/github/justin-bennington/S2ML-Generators/blob/main/S2ML_Image_Generator.ipynb): evolution of the first VQGAN+CLIP Google Colab notebook by Katherine Crownson maintained by Justin Bennington
* [🔥] [Create Variations on Images With Looking Glass 1.1 (ru-DALLE) - YouTube | Artificial Images](https://www.youtube.com/watch?v=37_Zjreghw4)
* [🔥🚀] [Looking Glass 1.1 (ru-DALLE)](https://colab.research.google.com/drive/11vdS9dpcZz2Q2efkOjcwyax4oob6N40G): Making ruDALL-E fine tuning quick and painless. Copyright (C) 2021 Bearsharktopus Studios
* [🔍] [NÜWA: Visual Synthesis Pre-training for Neural visUal World creAtion (ML Research Paper Explained) - YouTube | Yannic Kilcher](https://www.youtube.com/watch?v=InhMx1h0N40&t=603s) 
* [🔥] [yuval-alaluf/hyperstyle](https://github.com/yuval-alaluf/hyperstyle): Official Implementation for "HyperStyle: StyleGAN Inversion with HyperNetworks for Real Image Editing" https://arxiv.org/abs/2111.15666
* [🔥] [Vadim Epstein’s Aphantasia library](https://github.com/eps696/aphantasia): CLIP + FFT/DWT/RGB = text to image/video
* [mikaelalafriz/lucid-sonic-dreams](https://github.com/mikaelalafriz/lucid-sonic-dreams): syncs GAN-generated visuals to music
* [aakashjhawar/AvatarGAN](https://github.com/aakashjhawar/AvatarGAN): Generate Cartoon Images using Generative Adversarial Network
* [Greg Surma - Portfolio](https://gsurma.github.io/) 
* [crowsonkb (Katherine Crowson)](https://github.com/crowsonkb): who wrote [the tutorial of VQGAN+CLIP](https://sourceful.us/doc/935/introduction-to-vqganclip)
* [🔥] [dvschultz/stylegan3](https://github.com/dvschultz/stylegan3): Forked by Schultz from Stylegan3
* [Alias-Free Generative Adversarial Networks (StyleGAN3)](https://nvlabs.github.io/stylegan3/): NVidia official StyleGAN3 release page
* [🚀] [StyleGAN-NADA](https://stylegan-nada.github.io/): CLIP-Guided Domain Adaptation of Image Generators
* [Let's Talk Energy Usage of Generative Machine Learning](https://www.youtube.com/watch?v=3nViZGCkAhU&t=1276s)
* [StyleGAN: Use machine learning to generate and customize realistic images | by Jamshed Khan | Heartbeat](https://heartbeat.fritz.ai/stylegans-use-machine-learning-to-generate-and-customize-realistic-images-c943388dc672) 
* [Audio-reactive Latent Interpolations with StyleGAN](https://wavefunk.xyz/audio-reactive-stylegan)
* [DALL·E](https://openai.com/blog/dall-e/): Creating Images from Text
* [Alien Dreams: An Emerging Art Scene - ML@B Blog](https://ml.berkeley.edu/blog/posts/clip-art/)
* [DeepStory](https://www.deepstory.ai/#!/): A tale of co-creation between man & machine
* [SofGAN](https://www.unite.ai/sofgan-a-gan-face-generator-that-offers-greater-control/): A GAN Face Generator That Offers Greater Control - Unite.AI
* [DALL-E mini](https://huggingface.co/spaces/flax-community/dalle-mini): DALL·E mini is an AI model that generates images from any prompt you give!
* [DALL-E mini GitHub](https://github.com/borisdayma/dalle-mini)
* [DALL-E mini Project Report](https://wandb.ai/dalle-mini/dalle-mini/reports/DALL-E-mini--Vmlldzo4NjIxODA)
* [CLIPIT PixelDraw - Colaboratory](https://colab.research.google.com/github/dribnet/clipit/blob/master/demos/PixelDrawer.ipynb) 
* [CLIP Guided Diffusion HQ 512x512.ipynb - Colaboratory](https://colab.research.google.com/drive/1V66mUeJbXrTuQITvJunvnWVn96FEbSI3#scrollTo=X5gODNAMEUCR) 
* [Smooth Transitioning Between Position / Rotation / Zoom and Text Inputs by Keyframing Parameters: A Proof of Concept [15,000 Frames] : deepdream](https://www.reddit.com/r/deepdream/comments/pagqjx/smooth_transitioning_between_position_rotation/) 
* [justinpinkney/awesome-pretrained-stylegan2](https://github.com/justinpinkney/awesome-pretrained-stylegan2): A collection of pre-trained StyleGAN 2 models to download
* [Image Super-Resolution](https://idealo.github.io/image-super-resolution/) 
* [neural-dream Alternatives and Similar Photos & Graphics Apps | AlternativeTo](https://alternativeto.net/software/neural-dream/) 
* [Real GANs in AI | Hacker Noon](https://hackernoon.com/real-gans-in-ai): deep dive into what the generative models are, the recent developments in the field, and the usage of GANs in business
* [CoG 21](https://www.ea.com/seed/news/cog2021-adversarial-rl-content-generation): Adversarial Reinforcement Learning for Procedural Content Generation
* [GANshare | Towards Data Science](https://towardsdatascience.com/ganshare-creating-and-curating-art-with-ai-for-fun-and-profit-1b3b4dcd7376): Creating and Curating Art with AI 
* [GitHub Repositories of Hugging Face](https://github.com/huggingface)
* [AgaMiko/pixel_character_generator](https://github.com/AgaMiko/pixel_character_generator): Generating retro pixel game characters with Generative Adversarial Networks. Dataset "TinyHero" included.

## Text-to-video

[THUDM/CogVideo](https://github.com/THUDM/CogVideo): Text-to-video generation

## How did they do it?

* [Creep - YouTube](https://www.youtube.com/watch?v=c6LlG4g_9lk) by [Glenn Marshall Neural Art](https://www.youtube.com/channel/UCes-tiSj7VO6nNOsUB76lZw): how did they translated the images using VQGAN+CLIP? How did they seamlessly wander on the latent space?

## Inbox: Text and Natural Language Processing

* [Inside language models (from GPT-3 to PaLM) – Dr Alan D. Thompson – Life Architect](https://lifearchitect.ai/models/)
* [bigscience/bloom · Hugging Face](https://huggingface.co/bigscience/bloom): getting started with BLOOM
* [BLOOM](https://thenextweb.com/news/bloom-new-open-source-ai-model-bigger-than-gpt-3-large-language-model-llm): open-source 176-billion-parameter model aims to democratize large-language models
* [Top 10 GPT-3 Powered Applications to Know in 2022](https://www.analyticsinsight.net/top-10-gpt-3-powered-applications-to-know-in-2022/) 
* [Google AI Blog: Pathways Language Model (PaLM): Scaling to 540 Billion Parameters for Breakthrough Performance](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html) 
* [Riku.AI | The vault for your A.I. creations](https://riku.ai/) 
* [First look - Riku.ai - inference platform Mar/2022 - J1, GPT-3, Fairseq-13B, GPT-NeoX-20B, Cohere-XL - YouTube](https://www.youtube.com/watch?v=t6FESjmPeJ8) 
* [Rytr](https://rytr.me/): Rytr is an AI writing assistant that helps creating content
* [Charisma](https://charisma.ai/): Charisma is a platform for creating interactive stories with believable virtual characters
* [Authors A.I.](https://authors.ai/): AI-powered text analysis
* [DeepMind says its new language model can beat others 25 times its size | MIT Technology Review](https://www.technologyreview.com/2021/12/08/1041557/deepmind-language-model-beat-others-25-times-size-gpt-3-megatron/) 
* [Integrated AI: How to talk to AI for free using nine platforms (Megatron, GPT-3, GPT-J, Wudao, J1..) - YouTube](https://www.youtube.com/watch?v=yWM_8QwLyuY&list=LL&index=1&t=17s) by Dr Alan D. Thompson. The following references came from this video description
* [InferKit](https://app.inferkit.com/demo)
* [CopyHat](https://copyhat.com/)
* [Emerson on iOS](https://apps.apple.com/us/app/emerson...)
* [Jurassic-1](https://studio.ai21.com/)
* [EleutherAI | GPT-J-6B](https://6b.eleuther.ai/)
* [AIx](https://apps.aixsolutionsgroup.com/)
* [Wudao](https://pretrain.aminer.cn/os/qa)
* [Emerson on Telegram](https://www.quickchat.ai/emerson)

### OpenAI GPT-3
* [GPT-3 playground](https://beta.openai.com/playground)
* [Fine-tuning GPT-3](https://beta.openai.com/docs/guides/fine-tuning): how to customize a model for OpenAI's GPT-3

## Papers and references for reading and understanding

* [Casual GAN Papers Reading Club](https://casualgan.notion.site/casualgan/Casual-GAN-Papers-Reading-Club-327c158518e44d5296a5def74486c7e8): Community knowledge base for Casual GAN Papers
* [Casual GAN Papers](https://www.casualganpapers.com/): Easy to read summaries of popular AI papers
* [The Illustrated VQGAN](https://ljvmiranda921.github.io/notebook/2021/08/08/clip-vqgan/): illustrated explanation on how VQGAN works
* [CLIP: Connecting Text and Images](https://openai.com/blog/clip/): OpenAI's explanation on how CLIP works
* [VQGAN+CLIP — How does it work?. The synthetic imagery (“GAN Art”) scene… | by Alexa Steinbrück | Medium](https://alexasteinbruck.medium.com/vqgan-clip-how-does-it-work-210a5dca5e52)
* [The Methods Corpus | Papers With Code](https://paperswithcode.com/methods)
* https://ieeexplore.ieee.org/abstract/document/9043519: A State-of-the-Art Review on Image Synthesis With Generative Adversarial Networks
* [Utilizando redes adversárias generativas (GANs) como agente de apoio à inspiração para artistas](https://www.cin.ufpe.br/~tg/2020-1/TG_CC/tg_cco2.pdf): Trabalho de Graduação de Cláudio Carvalho no Centro de Informática - UFPE
* [GAN Lab](https://poloclub.github.io/ganlab/): Play with Generative Adversarial Networks in Your Browser!
* [[PDF] Music2Video: Automatic Generation of Music Video with fusion of audio and text | Semantic Scholar](https://www.semanticscholar.org/paper/Music2Video%3A-Automatic-Generation-of-Music-Video-of-Jang-Shin/38e37c3a7dc22bb3356552e93e6685b99ca04264)
* [[PDF] Active Divergence with Generative Deep Learning - A Survey and Taxonomy | Semantic Scholar](https://www.semanticscholar.org/paper/Active-Divergence-with-Generative-Deep-Learning-A-Broad-Berns/091c4ea2efaba23cd9024d8a063609c9a313b5cb)
* [[PDF] Automating Generative Deep Learning for Artistic Purposes: Challenges and Opportunities | Semantic Scholar](https://www.semanticscholar.org/paper/Automating-Generative-Deep-Learning-for-Artistic-Berns-Broad/f3479740d4ec7f91b6d7a01167e9c875a72d386e) 

## Interesting Instagram Accounts, Posts and Reels
* [science on Instagram: “Human evolution generated by AI Stable Diffusion”](https://www.instagram.com/reel/CjnYBJbqABH/?igshid=YmMyMTA2M2Y%3D)
* [Deep Music Visualizer](https://www.instagram.com/deep_music_visualizer/)
* [Lucid Sonic Dreams (@lucidsonicdreams)](https://www.instagram.com/lucidsonicdreams/) 

## Interesting Youtube Channels

* [Artificial Images](https://www.youtube.com/channel/UCaZuPdmZ380SFUMKHVsv_AA): Demos and explanations to make art using machine learning
* [Glenn Marshall Neural Art](https://www.youtube.com/user/glenniszen)
* [How to Generate Art - Intro to Deep Learning #8](https://www.youtube.com/watch?v=Oex0eWoU7AQ) 

## Interesting GitHub Repositories

* [dvschultz](https://github.com/dvschultz): Derrick Schultz's GitHub
* [dvschultz/ml-art-colabs](https://github.com/dvschultz/ml-art-colabs): collection of Google Colab Notebooks for ML Arts

## Artists and Artworks
* [(19) INFINITEYAY✨ on Twitter: "✨35 Artists Using AI With Under 1000 Followers That You Need To Follow Today✨ -- All these artists are fantastic and deserve way more followers. In no particular order here's my first list. More to come. Enjoy! 👇 #AIart #art #stablediffusion #midjourney #dalle2 #AI https://t.co/CTyq1dfsTs" / Twitter](https://twitter.com/infiniteyay/status/1583465675166609408?s=43&t=XvooFiMyC-YPv0i98HmjVQ) 
* [Computer Vision Art Gallery : CVPR 2021](https://computervisionart.com/): artworks dealing with computer vision technologies
* [Confluence](https://deviparikh.github.io/confluence/): a generative art project by Devi Parikh on BrainDrops.
* [Learning to See – Memo Akten | Mehmet Selim Akten | The Mega Super Awesome Visuals Company](http://www.memo.tv/works/learning-to-see/)
* [Neural Zoo | Sofia Crespo](https://neuralzoo.com/)
* [KRЯRL DЯAWINGS: Runway ML -- 3rd "Model" (based on long poses)](http://krrrl.blogspot.com/2020/08/runway-ml-3rd-model-based-on-long-poses.html)
* [Frea Buckler ~ Artist](https://www.freabuckler.com/): obras usadas para criar essa rede [(19) derrick has started yet another project on Twitter: "Just sent @buntworthy a demo StyleGAN model I trained / Twitter](https://twitter.com/dvsch/status/1255885874560225284)
* [(Non-)Human](https://www.ygzhang.com/non-human.html) 
* [Authentic Digital Art - Unknown Departure | SuperRare](https://superrare.com/artwork-v2/unknown-departure-16212) 
* [A Selection of Machine Learning Art Inspiration](https://www.youtube.com/watch?v=HNwXrHiHW7Q)
* [Top 25 AI Artists of 2021 (Photos, Profiles & History of AI Art)- AIArtists.org](https://aiartists.org/): AIArtists.org showcases leading artists using Artificial Intelligence, tools to make AI Art, and a timeline of AI Art History.
* [Helena Sarin – Artist Profile (Photos, Videos, Exhibitions) — AIArtists.org](https://aiartists.org/helena-sarin)
* [Images Generated By AI Machines (@images_ai) / Twitter](https://twitter.com/images_ai?s=08)
* https://www.instagram.com/refikanadol/
* [The Steampunk Circus Human Machine Collaboration - Video, Sound and Stories with AI / YouTube](https://www.youtube.com/channel/UCa1xYBYCzBoJ08U9lgbYAFw)

## Galleries

* [AICAN](https://aican.io/)
* [Ganvas Studio - Neural Network Paintings](https://ganvas.studio/)
* [Syn Feather Sweater / STRELITZIA – HATRA E STORE](https://hatroid.com/collections/synthetic-feather/products/syn-feather-sweater-strelitzia)

## Selected examples of This X Does Not Exist

* [This vessel does not exist.](https://thisvesseldoesnotexist.com/#/): A gallery of both authentic and fake vessels generated by machine learning software (StyleGAN)
* https://thispersondoesnotexist.com/ - gerador de rostos humanos 
* https://thisxdoesnotexist.com/ - site com vários exemplos de outros modelos

## Pre-trained Models

* [justinpinkney/awesome-pretrained-stylegan2](https://github.com/justinpinkney/awesome-pretrained-stylegan2): A collection of pre-trained StyleGAN2 models trained on different datasets at different resolution
* [A collection of pre-trained StyleGAN 2 models to download - Deep Learning | ReposHub](https://reposhub.com/python/deep-learning/justinpinkney-awesome-pretrained-stylegan2.html)
* [Modelo pretreinado com obras de arte moderna](https://twitter.com/MichaelFriese10/status/1213697331427545088)

## Neural Net Models

* [Yuheng-Li/MixNMatch](https://github.com/Yuheng-Li/MixNMatch)
* [lucidrains/lightweight-gan](https://github.com/lucidrains/lightweight-gan): 512x512 flowers after 12 hours of training, 1 gpu 256x256 flowers after 12 hours of training, 1 gpu Implementation of 'lightweight' GAN proposed in ICLR 2021
* [VQGAN+CLIP](https://docs.google.com/document/d/1Lu7XPRKlNhBQjcKr8k8qRzUzbBW7kzxb5Vu72GMRn2E/edit): This is a brief tutorial on how to operate VQGAN+CLIP by Katherine Crowson
* [rinongal/StyleGAN-nada](https://github.com/rinongal/StyleGAN-nada): Zero-Shot non-adversarial domain adaptation of pre-trained generators

## Latent Space Explorarion

* [Latent Space Exploration with StyleGAN2](https://amarsaini.github.io/Epoching-Blog/jupyter/2020/08/10/Latent-Space-Exploration-with-StyleGAN2.html)

## Other Related Awesome Lists

- [margaretmz/awesome-ai-art-design](https://github.com/margaretmz/awesome-ai-art-design): An awesome list: AI for art and design.
- [toxtli/awesome-machine-learning-jupyter-notebooks-for-colab](https://github.com/toxtli/awesome-machine-learning-jupyter-notebooks-for-colab): A curated list of Machine Learning and Deep Learning tutorials in Jupyter Notebook format ready to run in Google Colaboratory

## Notes, ideas for projects

* Video clip: music + lyrics => image + video
* Book: text => illustration
* Interfaces for editing parameters that can be exported as string. This string is the input for a notebook or model. "Copy string", "Paste string", "Export file", "Import file".

## Improving Google Colab experience
* [7 ways to load external data into Google Colab | by B. Chen | Towards Data Science](https://towardsdatascience.com/7-ways-to-load-external-data-into-google-colab-7ba73e7d5fc7) 
* [10 tricks for a better Google Colab experience | by Cyprien NIELLY | Towards Data Science](https://towardsdatascience.com/10-tips-for-a-better-google-colab-experience-33f8fe721b82)
* [Quickly share ML WebApps from Google Colab using ngrok for Free | by AbdulMajedRaja RS | Towards Data Science](https://towardsdatascience.com/quickly-share-ml-webapps-from-google-colab-using-ngrok-for-free-ae899ca2661a)
* [Jupyter Widgets for Interactivity in Google Colab](https://colab.research.google.com/notebooks/forms.ipynb#scrollTo=62YnDE7i9dqP): notebook with examples of using Jupyter Widgets in Colab, allowing interactive inputs
* [Jupyter Widgets official documentation](https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20Basics.html)

## Troubleshooting
![Looking_Glass_v1_1_-_Colaboratory](https://user-images.githubusercontent.com/299057/145653588-42e9b4c0-cb23-45a5-8a18-b7a60f5d8827.png) [Ref](https://stackoverflow.com/questions/69822304/google-colab-google-drive-can%c2%b4t-be-mounted-anymore-browser-popup-google-dri)

## Inbox for Related References
* [The Art of PNG Glitch](https://ucnv.github.io/pnglitch/)
* [HashLips/hashlips_art_engine](https://github.com/HashLips/hashlips_art_engine): tool used to create multiple different instances of artworks based on provided layers
* [archinetai/audio-diffusion-pytorch: Audio generation using diffusion models, in PyTorch.](https://github.com/archinetai/audio-diffusion-pytorch)
* [Dance Diffusion - a Hugging Face Space by harmonai](https://huggingface.co/spaces/harmonai/dance-diffusion)

## Tools for Batch Image Processing
[BIRME](https://www.birme.net/): Bulk Image Resizing Made Easy 2.0 (Online & Free)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Filipe Calegario has waived all copyright and
related or neighboring rights to this work.
