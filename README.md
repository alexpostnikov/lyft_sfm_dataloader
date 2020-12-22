# lyft_sfm_dataloader

## Get modified l5kit library
```bash
git clone git@github.com:alexpostnikov/l5kit.git
```

## Install library
```bash
cd l5kit/l5kit
pip install -e .[dev]
```

## Download dataset

https://self-driving.lyft.com/level5/data/
or
https://www.kaggle.com/c/lyft-motion-prediction-autonomous-vehicles/data


## Nodify Juputer Notebook

modify according to your data path 
```python
cur_dir = os.getcwd()
data_path = os.path.dirname(os.path.dirname(cur_dir))+'/dataset/lyft-motion-prediction-autonomous-vehicles'
```
