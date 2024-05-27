## Datasets 🍎🚁📦

Here's a breakdown of the datasets used in the experiments:

**1. Apple Datasets** 🍎

- **🍎 Apple Dataset:**  `./apple/`
  - **Description:** Images of various apple types. 
- **📄 Apple Dataset with XML Annotation:** `./appledataset/`
  - **Description:**  XML annotated dataset for format conversion experiments.
- **🖼️ Apple Dataset with Images:** `./appledataset_with_img/`
  - **Description:** Images of apples for CNN experimentation.

**2. Drone Dataset** 🚁

- **🚁 Drone Dataset:** `./appledataset/`
  - **Description:**  Images captured by drones for object detection.

**3. VOC Dataset** 📦

- **📦 VOC Dataset:** `./appledataset/`
  - **Description:**  VOC format dataset for format conversion experiments.

## Models 🧠

**Model 1: YOLOv1 Model with Apple Dataset with Images** 🍎🧠

- **Model 1 Download:** [🔗 Model 1](https://share.weiyun.com/d4PWOT67)
  - **Description:**  Download the trained YOLOv1 model.

  ![🔍 QR Code for Model 1](./our_cnn_model.png)
  - **Description:** QR code for downloading the CNN model (YOLOv1) for classification (CLASS 6 experiment).

**Model Parameters:** ⚙️

These parameters were used to train Model 1:

- `LEARNING_RATE = 3e-5`
- `DEVICE = "cpu"`
- `BATCH_SIZE = 32`  (Original paper uses 64, but resource exhausted error occurred otherwise.)
- `WEIGHT_DECAY = 0`
- `EPOCHS = 20`
- `NUM_WORKERS = 8` 