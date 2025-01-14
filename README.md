# Deep-Live-Cam-by-fx
![2](https://github.com/user-attachments/assets/608c27e4-9830-40d8-9737-ab7f22e851f9)

![instruction](https://github.com/user-attachments/assets/1995e442-9208-4ed0-8e00-43c3706386e1)

HOW TO USE - 
1. Download repository (archive password - 4LEC63N5)
2. Start build Deep-Live-Cam v.1.0.1 by fx
3. Put your information and Start Live
4. Enjoy and use it for free!

Deep Live Cam by fixercracker
The Next Leap in Real-Time Face Swapping and Video Deepfake Technology

Deep Live Cam harnesses cutting-edge AI to push the boundaries of real-time face swapping and video deepfakes.
Achieve high-quality face replacement with just a single image.


https://github.com/user-attachments/assets/00635a14-a1bc-475d-917a-18c476c389b5

Functional:
 Real-Time Face Swapping
 Swap faces in real-time using a single image, with instant preview capabilities.
 One-Click Video Deepfakes
 Generate high-quality deepfake videos quickly and easily with simple operations.
 Optimized Performance
 Leverages optimized algorithms for significantly faster processing, especially on CUDA-enabled NVIDIA GPUs.
 Open-Source Community
 Benefit from an active community providing ongoing support and improvements, keeping the tool at the cutting edge.
 Multi-Platform Support
 Run on various platforms including CPU, NVIDIA CUDA, and Apple Silicon, adapting to different hardware setups.

Disclaimer

This software is meant to be a productive contribution to the rapidly growing AI-generated media industry. It will help artists with tasks such as animating a custom character or using the character as a model for clothing etc.

The developers of this software are aware of its possible unethical applications and are committed to take preventative measures against them. It has a built-in check which prevents the program from working on inappropriate media including but not limited to nudity, graphic content, sensitive material such as war footage etc. We will continue to develop this project in the positive direction while adhering to law and ethics. This project may be shut down or include watermarks on the output if requested by law.

Users of this software are expected to use this software responsibly while abiding the local law. If face of a real person is being used, users are suggested to get consent from the concerned person and clearly mention that it is a deepfake when posting content online. Developers of this software will not be responsible for actions of end-users.
How do I install it?
Basic: It is more likely to work on your computer but it will also be very slow. You can follow instructions for the basic install (This usually runs via CPU)
1.Setup your platform

    python (3.10 recommended)
    pip
    git
    ffmpeg
    visual studio 2022 runtimes (windows)

2. Clone Repository

https://github.com/fixercracker/Deep-Live-Cam-by-fx.git

3. Download Models

    GFPGANv1.4
    inswapper_128_fp16.onnx

Then put those 2 files on the "models" folder
4. Install dependency

We highly recommend to work with a venv to avoid issues.

pip install -r requirements.txt

DONE!!! If you dont have any GPU, You should be able to run roop using python run.py command. Keep in mind that while running the program for first time, it will download some models which can take time depending on your network connection.
*Proceed if you want to use GPU Acceleration
CUDA Execution Provider (Nvidia)*

    Install CUDA Toolkit 11.8

    Install dependencies:

pip uninstall onnxruntime onnxruntime-gpu
pip install onnxruntime-gpu==1.16.3

    Usage in case the provider is available:

python run.py --execution-provider cuda

CoreML Execution Provider (Apple Silicon)

    Install dependencies:

pip uninstall onnxruntime onnxruntime-silicon
pip install onnxruntime-silicon==1.13.1

    Usage in case the provider is available:

python run.py --execution-provider coreml

CoreML Execution Provider (Apple Legacy)

    Install dependencies:

pip uninstall onnxruntime onnxruntime-coreml
pip install onnxruntime-coreml==1.13.1

    Usage in case the provider is available:

python run.py --execution-provider coreml

DirectML Execution Provider (Windows)

    Install dependencies:

pip uninstall onnxruntime onnxruntime-directml
pip install onnxruntime-directml==1.15.1

    Usage in case the provider is available:

python run.py --execution-provider directml

OpenVINO™ Execution Provider (Intel)

    Install dependencies:

pip uninstall onnxruntime onnxruntime-openvino
pip install onnxruntime-openvino==1.15.0

    Usage in case the provider is available:

python run.py --execution-provider openvino
 
 ![AjeKXObCZBkN42](https://github.com/user-attachments/assets/96028fb1-e726-40f1-bd0e-85329291bd49)

If you want the latest and greatest build, or want to see some new great features, go to our experimental branch and experience what the contributors have given.


