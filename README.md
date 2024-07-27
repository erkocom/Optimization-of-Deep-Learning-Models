This project is about the optimization, fine-tuning, and compatibility of the EfficientDet-Lite3 model with EdgeTPU. For more information, you can read the article (in Turkish).

**Summary**:

In recent years, with the advancement of technology, the concept of artificial intelligence has entered every aspect of our lives. Although deep learning techniques used in the field of artificial intelligence yield very successful results, they are often costly in terms of price and time. To mitigate these drawbacks, especially to reduce the time spent on inference by models, the simplification technique of full integer post-training quantization has been applied. Additionally, it is intended to run the model on EdgeTPU, which enables inference faster than on traditional CPUs and GPUs.

The deep learning model used in the study is EfficientDetLite3, an object detection model in the field of image processing. To train the model, a dataset consisting of 75 bird's-eye view photos of cars and 75 photos of trucks was prepared. The trained model was evaluated according to COCO evaluation metrics. It was achieved to run 273 out of the 424 operations of the model on EdgeTPU.
