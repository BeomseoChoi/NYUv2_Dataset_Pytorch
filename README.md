# NYU Depth V2 Dataset

## How To Use
```shell
pip install nyu-depth-v2
```

```python
from torchvision import transforms
from nyuv2.NYUv2Dataset import NYUv2Dataset

transform_image = transforms.Compose([ ... ])
transform_depth = transforms.Compose([ ... ])

dataset = NYUv2Dataset(
    "./dataset", 
    True, 
    transform_image,
    transform_depth)
```

This requires `torch`, `torchvision`, `einops`, `numpy`, `h5py`, `opencv-python`,  `pathlib`.

## Working python version
- `python310`
