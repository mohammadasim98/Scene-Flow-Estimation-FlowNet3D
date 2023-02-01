# Scene-Flow-Estimation-FlowNet3D
Scene Flow Estimation Experiment using FlowNet3D and a custom extension for 3D Applications in TensorFlow

# Prerequisites
This implementation uses the custom extension for 3D applications in TensorFlow namely tensorflow3d. The library is built with bazel and follows similar folder structure as in the official TensorFlow. It is recommended to use a docker container to run such experiments and build process and for easy prototyping. 

Here is the repository for the custom extensions: https://github.com/mohammadasim98/tensorflow3d

### Note: The python wheels generated from the build files are platform specific and for different machine and OS, it must be rebuilt and installed.


# Setup
Follow the steps in the above link and install the library on your system. Then clone this repository in a separate folder (any except the custom library i.e., tensorflow3d).

```bash
  git clone https://github.com/mohammadasim98/Scene-Flow-Estimation-FlowNet3D
```

Now you start your own experiments.


# Reference

@article{liu:2019:flownet3d,
  title={FlowNet3D: Learning Scene Flow in 3D Point Clouds},
  author={Liu, Xingyu and Qi, Charles R and Guibas, Leonidas J},
  journal={CVPR},
  year={2019}
}

