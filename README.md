# convert_pytorch_to_keras
Convert Pytorch Model to Keras/Tensorflow 1.x Model using [pytorch2keras](https://github.com/nerox8664/pytorch2keras)

## Installation
- Clone Repository
- Create conda env from `environment.yml` (Package versions taken from [here](https://github.com/nerox8664/pytorch2keras/issues/118))
- Open Jupyter Notebook:
  - Create Torch tensor of desired input shape (for the torch model)
  - Provide path for `.pth` file
  - Paste in torch model code
  - Run Notebook
- Keras model definition should be stored in `k_model.json`
- Keras weights should be stored in `k_model.h5`