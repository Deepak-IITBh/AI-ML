Problem Statement: Develop a multilingual assistive model that helps visually impaired users by describing images in multiple Indian languages and narrating the descriptions via audio.
Workflow:
Use Vision Transformer (ViT)(/Any other model) to perform image classification or object detection, identifying objects in the scene.
Apply IndicTrans2(/Any other model) to translate the generated text descriptions into multiple Indian languages.
Use Whisper Model(/Any other model) to convert the text into speech and narrate the descriptions.
Dataset: You can use publicly available datasets such as MS-COCO for image-captioning tasks, which provide both images and descriptions. For Indian language translations, the FLORES dataset or IndicNLP resources can be helpful.
You are free to use any other datasets as well.
