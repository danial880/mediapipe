![MediaPipe](docs/images/mediapipe_small.png)

## Installation

#### Step1

Install the following dependencies.

```bash
    $ sudo apt install python3-dev
    $ sudo apt install -y protobuf-compiler

    # Needed to build opencv from source.
    $ sudo apt install cmake
```
#### Step2

Install and link OpenCV with mediapipe.

```bash
    $ sudo bash setup_opencv.sh
```
#### Step3

Install the required Python packages.

```bash
    mediapipe$ pip3 install -r requirements.txt
```
#### Step4

Generate and install MediaPipe package.

```bash
    mediapipe$ python3 setup.py gen_protos
    mediapipe$ python3 setup.py install --link-opencv
```

