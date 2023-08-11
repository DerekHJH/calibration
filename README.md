This folder largely borrows from [this repo](https://github.com/megvii-research/FQ-ViT). While the original repo focuses on the full quantization of ViT (as seen in vit_quant.py), this folder focuses on the usage and modification of different quantization components (as seen in subfolder models/ptq).

For now, users need to pay attention to only one file: test_toy.py. This file contains the code for running the toy example. The other files are for reference only.

## Getting Started

### Environment

- torch 2.0
- cuda 11.7

### Run

```bash
python test_toy.py toy
```

After you are familiar with test_toy.py, you can try to run test_quant.py. This file contains the code for quantizing the whole ViT model. Refer to the original_readme.md for more details.