# Object Localization with TensorFlow

The primary learning goal of this project is to create and train a multi-output convolutional neural network to perform object localization. Additionally, this project demonstrates the creation of custom callbacks and custom metrics in Keras.

## Project Structure

The hands-on project on Object Localization with TensorFlow is divided into the following tasks:

- Task 1: Introduction
- Task 2: Download and Visualize Data
- Task 3: Create Examples
- Task 4: Plot Bounding Boxes
- Task 5: Data Generator
- Task 6: Model
- Task 7: Custom Metric: IoU
- Task 8: Compile The Model
- Task 9: Custom Callback
- Task 10: Model Training

### Downloading and Preparing Data

The project uses OpenMoji emoji images for training. Run the following commands to download and extract the emoji dataset:

```bash
!wget https://github.com/hfg-gmuend/openmoji/releases/latest/download/openmoji-72x72-color.zip
!mkdir emojis
!unzip -q openmoji-72x72-color.zip -d ./emojis
```

## License

This project is open-source and available under the [MIT License](LICENSE).