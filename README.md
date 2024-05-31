## Datasets 🍎🚁📦

- **🍎 Apple Dataset:**  [Apple Dataset](./apple/)
  - **Description:** Images of various apple types. 
- **📄 Apple Dataset with XML Annotation:** [Apple Dataset with XML Annotation](./appledataset/)
  - **Description:**  XML annotated dataset for format conversion experiments.
- **🖼️ Apple Dataset with Images:** [Apple Dataset with Images](./appledataset_with_img/)
  - **Description:** Images of apples for CNN experimentation.

**2. Drone Dataset** 🚁

- **🚁 Drone Dataset:** [Drone Dataset](./drone//)
  - **Description:**  Images captured by drones for object detection.

**3. VOC Dataset** 📦

- **📦 VOC Dataset:**[📦 VOC Dataset](./VOCdevkit/)
  - **Description:**  VOC format dataset for format conversion experiments.

## 🌆 **Cityscape Dataset**

- **New Dataset Path:** [Cityscape Dataset](./cityscapes/)
- **Download Link:** [🔗 Cityscape Dataset](https://share.weiyun.com/noJw0NYN)
- **QR Code:** 
![QR Code](./cityscapes_Dataset.png)

**3. FOOTBALL Dataset** ⚽

- **⚽ FOOTBALL Dataset:**[⚽ FOOTBALL Dataset](./FOOTBALL/)
  - **Description:**  FOOTBALL dataset for image segmentation experiments.


## Models 🧠

### **Model 1: YOLOv1 Model with Apple Dataset with Images** 🍎🧠

### **Model 1 Download:** [🔗 Model 1](https://share.weiyun.com/d4PWOT67)
  - **Description:**  Download the trained YOLOv1 model.

  ![🔍 QR Code for Model 1](./our_cnn_model.png)
  - **Description:** QR code for downloading the CNN model (YOLOv1) for classification (CLASS 6 experiment).

**Model Parameters:** ⚙️

These parameters were used to train Model 1:

- `LEARNING_RATE = 3e-5`
- `DEVICE = "cpu"`
- `BATCH_SIZE = 32`
- `WEIGHT_DECAY = 0`
- `EPOCHS = 20`
- `NUM_WORKERS = 8` 

### **Model 2: FAST-R-CNN model with Apple Dataset with Images** 🍎🧠
### **Model 2 Download:** [🔗 Model 2](https://share.weiyun.com/7dsljRk8)
  - **Description:**  Download the trained fast-r-CNN model.

  ![🔍 QR Code for Model 2](./our_fast_r_cnn_model.png)
  - **Description:** QR code for downloading the FAST-R-CNN model for classification (CLASS 7 experiment).

**Model Parameters:** ⚙️

These parameters were used to train Model 2:

- `n_epochs = 5`
- `lr=0.005`
- `momentum=0.9`
- `weight_decay=5e-4`
- `train_batch_size=4`
- `test_batch_size=4` 

### **Model 3: Football model model with FOOTBALL Dataset** ⚽
### **Model 3 Download:**
- **Download Link:** [🔗 Model 3](https://share.weiyun.com/P4Hf6DhG)
- **Description:** Download the trained football model for image segmentation (CLASS 8 first experiment).
  
  ![🔍 QR Code for Model 3](./football_best_model.png)
  
- **Description:** QR code for downloading `football_best_model`.

**Model Parameters:** ⚙️

- `n_epochs = 15`
- `lr = 3e-4`
- `train_batch_size = 8`
- `test_batch_size = 8`

### **Model 4: Unet1 model model with cityscape Dataset** 🌆

### **Model 4 Download:**
- **Download Link:** [🔗 Model 4](https://share.weiyun.com/P4Hf6DhG)
- **Description:** Download the trained Unet1 model trained on cityscape data.
  
  ![🔍 QR Code for Model 4](./our_unet1_model.png)
  
- **Description:** QR code for downloading `Unet1 model` for image segmentation (CLASS 8 second experiment).

**Model Parameters:** ⚙️

These parameters were used to train Model 4:

- `n_epochs = 30`
- `lr = 0.01`
- `train_batch_size = 4`
- `test_batch_size = 4`

We changed the parameters to:

- `train_batch_size = 32`
- `test_batch_size = 32`
- `num_worker = 8`

and trained the model with GPU in Google Colab. Here is the Colab code:

- **Colab Link:** [🔗 Colab Notebook](https://colab.research.google.com/drive/1a9t6KRsdDRqt3UE0LMjirYa0XOBQodop?usp=sharing)

### **Model 5: 6 Different model with cityscape Dataset** 🌆
### **Model 5 Download:**
- **Download Link:** [🔗 Model 5](https://share.weiyun.com/fLoanosX)
- **Description:** Download the `6 model` trained on cityscape data.
  
  ![🔍 QR Code for Model 5](./city6Model.png)
  
- **Description:** QR code for downloading `6 Different` for image segmentation (CLASS 8 3rd experiment).

**Model Parameters:** ⚙️

These parameters were used to train Model 5:

- `n_epochs = 20`
- `lr = 1e-4`
- `betas = (0.9, 0.999)`
- `eps = 1e-08`
- `weight_decay = 0`
- `amsgrad = False`
- `train_batch_size = 32`
- `test_batch_size = 32`

We changed the parameters to:

- `train_batch_size = 16`
- `test_batch_size = 16`

and trained the model with GPU in Google Colab. Here is the Colab code:

- **Colab Link:** [🔗 Colab Notebook](https://colab.research.google.com/drive/1ZMeCHdl2lxxmBRAOxQnDTColSGsw1o1R?authuser=1#scrollTo=gjqeHwEylXS2)
