
### List of image captioning apps with dockerized python application and web interface

---

Image captioning is a task that involves generating a textual description of an image.
It has been an active research area in deep learning and computer vision in recent years, 
and several approaches have been proposed to solve this problem.

This repo contains implementations of various state-of-the-art image captioning methods that have been dockerized 
and prepared for easy deployment. 

In this case the goal is to provide a simple and user-friendly back-end application for image captioning
that can be accessed through a web interface implemented in FasAPI.

| # | Name | Description | Bild status                                                                                                                                                                                                                    | Docker image                                                                                              | Web interface |
|---|---|---|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|---|
| 1 | [Image captioning with PyTorch and the COCO dataset](https://github.com/bkocis/image-captioning-application-pytorch) | This repo contains a general image captioning application using PyTorch and the COCO dataset. The application is dockerized and can be deployed on a cloud service. The application is also wrapped in a web-server API interface using FastAPI. | [![Python application](https://github.com/bkocis/image-captioning-applications/actions/workflows/python-app.yml/badge.svg)](https://github.com/bkocis/image-captioning-applications/actions/workflows/python-app.yml)  | [Docker image](https://github.com/bkocis/image-captioning-application-pytorch/pkgs/container/application) | [Web interface](https://image-captioning-application-pytorch.herokuapp.com/) |
| 2 | [Image captioning with Tensorflow and the Flickr8k dataset](https://github.com/bkocis/image-captioning-application-tensorflow) | This repo contains a general image captioning application using Tensorflow and the Flickr8k dataset. The application is dockerized and can be deployed on a cloud service. The application is also wrapped in a web-server API interface using FastAPI. |  [![Python application](https://github.com/bkocis/image-captioning-application-tensorflow/actions/workflows/python-app.yml/badge.svg)](https://github.com/bkocis/image-captioning-application-tensorflow/actions/workflows/python-app.yml)  | [Docker image]()                                                                                          | [Web interface]()                                                                                         |


---
Related references

- [Overview of image captioning approaches](https://towardsdatascience.com/image-captioning-in-deep-learning-9cd23fb4d8d2)

- [TF tutorial on image captioning](https://www.tensorflow.org/tutorials/text/image_captioning)

- [Implementation from the Keras docs](https://keras.io/examples/vision/image_captioning/)

- [ViT-GPT2 implementation from HuggingFace](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)

- [Image understanding using BridgeTower implementation from HuggingFace](https://huggingface.co/docs/transformers/main/model_doc/bridgetower) 


---