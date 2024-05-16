# capcafe's Vision Kit :rocket:

![68747470733a2f2f6d656469612e726f626f666c6f772e636f6d2f62616e6e65722e6a7065673f7570646174656441743d31363832353233363232333834](./assets/60797147/1793a92b-4ef7-469e-ae43-2a188ea9d2d3)

Welcome to the Vision Kit repository! 

Vision Kit is a set of tools to help you build a production-ready computer vision workflow, fast. It empowers developers to deploy computer vision models with ease, providing utilities to help at every step of the way.

## Features

- **Live Inference with Webcam:** Perform real-time object detection using your webcam in a Jupyter notebook.
- **Dependency Installation:** Automatically installs all the necessary dependencies to quickly get started.
- **Comprehensive Model Support:** Utilize Vision Kit for object detection, semantic segmentation, and image classification tasks within your projects.
- **Model Training Resources:** Access additional guides and materials to kickstart your own model training process.

## Installation

Run:

```
git clone https://github.com/capcafe/vision-kit-python
cd vision-kit-python && ./setup.sh
```

## Troubleshooting

If you encounter any errors during the installation process in Mac, try the following:

1. `ImportError: urllib3 v2.0 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with LibreSSL 2.8.3.`

```
brew install openssl@1.1
pip3 install urllib3==1.26.6
```

If the error persists or you encounter a different error, please open an issue in the project repository for further assistance.

## Getting Started

Once the installation is complete, a Jupyter notebook will open in your browser. Follow the instructions provided in the notebook to get started!


This repository includes the following demos:

- **Real-time Object Detection with Webcam**
- **Create and Re-train Models**
- **Experiment with Different Model Types**
- **Integrating Vision Kit Into Your Application**

## Feedback

We value your feedback on how we can improve the Vision Kit experience. If you encounter any issues or have suggestions, please leave an issue in the project's GitHub Issues section.