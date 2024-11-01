# VQA with Audio using BLIP and Gradio
## Project Description
This project aims to develop an interactive application that answers visual questions based on an image uploaded by the user. The application utilizes a pre-trained model from Hugging Face's BLIP (Bootstrapped Language Image Pre-training) series, allowing users to ask questions related to the uploaded image. The response is generated audio formats, providing an engaging and versatile user experience.
## Model used in the project:
“Salesforce/blip-vqa-base” is a sophisticated model designed for visual question answering (VQA). It is part of the BLIP (Back-training of Language and Image) framework, which features both visual language understanding and generation tasks. The model leverages the Visual Transformer backbone and makes effective use of noisy web data by generating synthetic annotations and filtering out noisy ones. This approach has led to significant improvements in various visual language tasks, including text retrieval from images, image captioning, and visual question answering. 
It was the most suitable model for my project.
## Features:
- Image Upload: Users can upload an image, which will be analyzed by the AI model.
- Question Input: Users can ask a question related to the content of the uploaded image.
- Audio Response: The application generates an audio file of the answer, making the interaction more dynamic and accessible.
- Simple User Interface: Gradio is used to create an easy-to-use interface where users can upload images, ask questions, and receive answers in an audio format.
## Tools and Technologies:
- Hugging Face Transformers: Utilizing the BLIP model for Visual Question Answering (VQA) capabilities.
- Gradio: Creating an intuitive interface for image upload and question input with audio output.
- Google Text-to-Speech (gTTS): Converting text answers into spoken audio for a richer user experience.
- Python: The primary language for integrating the model, interface, and audio conversion.
- GitHub: For code versioning and project collaboration.
##  inputs:
- image: The image input provided by the user.
- question: The question input provided by the user.
## Outputs:
- voice answer: The voice output provided by the BLIP and gTTS model.
## Arabic language problems:
After research, it was found that there are significant limitations in available VQ&A models for Arabic. Models like BLIP are designed for English, and there are no equivalent Arabic models with the same capabilities. 
Moreover, datasets for this task are mainly in English, and developing an Arabic model from scratch would require extensive resources, which are beyond the project’s scope. Hence, using the English model is more feasible.
## The URLs:
- [Colab Notebook Link](https://colab.research.google.com/drive/1nBDQaz2k_4L3zv8b8FUp309pdEFrA0jV?usp=sharing)
- [Gradio Implementation](https://huggingface.co/spaces/saja003/VQA-with-Audio)
## Objectives:
- Enable users to interact with images through natural language questions.
- Provide audio responses to make the application more engaging and accessible.
- Develop a user-friendly interface that simplifies interaction with advanced AI models.
