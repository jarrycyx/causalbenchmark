## Dataset Download

<!-- **Source Code for Generation Pipeline:** [CausalTime](https://github.com/jarrycyx/UNN/tree/main/CausalTime) -->

**Generated Datasets:** [BaiduNetdisk](https://pan.baidu.com/s/1yU6CpHG_7KSv2UoIl4BSJg?pwd=4ins) 

<!-- If the download link is invalid, please [contact us](../). -->

<!-- [TsinghuaCloud](https://cloud.tsinghua.edu.cn/d/3f1ca39aa8b64c0c8fc9/)   -->

## Usage

Dataset is in the format of `.npy` file, which can be loaded by `np.load()` in Python with numpy package. The downloaded zip contains following files:

- medical
    - gen_data.npy: generated data of shape (Sample_num, Time_step, 2*Node_num)
    - graph.npy: ground truth graph H of shape (Node_num, Node_num)
- pm25
    - ...
- traffic
    - ...
- load_data.py: a script to load and show the data shape.


By running `python load_data.py`, you can load the data and show the shape of the data. Note that ground truth graph H is only the upper left corner of the ground truth causal graph $A$. See our [paper](../paper) for more details.

## Updata log

### Version 1.0
Uploaded on 2023/10/9.