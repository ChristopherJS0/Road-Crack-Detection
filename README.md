# Road-Crack-Detection
Using machine learning and object detection, this project shows how to train a model on a dataset of road cracks to detect them. Thanks to Yolov9, object detection has become much easier to program and detect certain objects using datasets of certain images.
For this project, I'll be training a Yolov9 model to detect road cracks.

The project is mainly programmed in google colab so we can make use of its remote GPU that makes training the model MUCH faster than if we trained a model on our local CPU or even GPU. 

If you'd like to use your own webcam to try and detect road cracks, you'll need to locally download Yolov9 onto your PC and install the created weight from the training.

References:
- Sateesh. (2024). Crack Dataset [Open Source Dataset]. Roboflow Universe. https://universe.roboflow.com/sateesh/crack-ekaue
- Chang, H.-S., Wang, C.-Y., Wang, R. R., Chou, G., & Liao, H.-Y. M. (2023). 
  YOLOR-Based Multi-Task Learning. arXiv preprint arXiv:2309.16921. 
- Wang, C.-Y., & Liao, H.-Y. M. (2024). YOLOv9: Learning What You Want to Learn 
  Using Programmable Gradient Information. arXiv preprint arXiv:2402.13616. 
