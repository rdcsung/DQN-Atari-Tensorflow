# DQN-Atari-Tensorflow

Reimplementing "Human-Level Control Through Deep Reinforcement Learning" in Tensorflow

This may be the simplest implementation of DQN to play Atari Games.

The pretrained network would release soon!

## Prerequsite

1. Tensorflow (prefer with GPU CUDA supported)
2. opencv2
3. Arcade Learning Environment ( https://github.com/mgbellemare/Arcade-Learning-Environment )

In ubuntu:
```
>>> Install Tensorflow:(https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html)
-----------------------------------------------------------------
sudo apt-get install python-pip python-dev

# Ubuntu/Linux 64-bit, CPU only, Python 2.7
export TF\_BINARY\_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.11.0rc2-cp27-none-linux\_x86\_64.whl

# Ubuntu/Linux 64-bit, GPU enabled, Python 2.7
# Requires CUDA toolkit 8.0 and CuDNN v5. For other versions, see "Install from sources" below.
# export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow-0.11.0rc2-cp27-none-linux_x86_64.whl

sudo pip install --upgrade $TF_BINARY_URL

>>> Install ALE: (https://github.com/mgbellemare/Arcade-Learning-Environment)
-----------------------------------------------------------------
sudo apt-get install libsdl1.2-dev libsdl-gfx1.2-dev libsdl-image1.2-dev cmake
git clone https://github.com/mgbellemare/Arcade-Learning-Environment.git

cd Arcade-Learning-Environment
cmake -DUSE\_SDL=ON -DUSE\_RLGLUE=OFF -DBUILD\_EXAMPLES=ON .
make -j 4 && pip install .
```
## Setup and Run

```
git clone https://github.com/jderehag/DQN-Atari-Tensorflow.git

cd DQN-Atari-Tensorflow
python AtariDQN.py

```
## Reference
1. [asrivat1/DeepLearningVideoGames](https://github.com/asrivat1/DeepLearningVideoGames)
2. [gliese581gg/DQN_tensorflow](https://github.com/gliese581gg/DQN_tensorflow)




