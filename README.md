# Integrating Spatial Configuration into Heatmap Regression Based CNNs for Landmark Localization

## Usage
This example implements the networks of the papers [Regressing Heatmaps for Multiple Landmark Localization Using CNNs](https://doi.org/10.1007/978-3-319-46723-8_27) and [Integrating Spatial Configuration into Heatmap Regression Based CNNs for Landmark Localization](https://doi.org/10.1016/j.media.2019.03.007).
Look into the subfolders of this repository for individual examples and more details.

You need to have the [MedicalDataAugmentationTool](https://github.com/christianpayer/MedicalDataAugmentationTool) framework downloaded and in you PYTHONPATH for the scripts to work.
If you have problems/questions/suggestions about the code, write me a [mail](mailto:christian.payer@gmx.net)!

### Train models
Run the `main.py` files inside the example folders to train the network.

### Train and test other datasets
In order to train and test on other datasets, modify the `dataset.py` files. See the example files and documentation for the specific file formats. Set the parameter `save_debug_images = True` in order to see, if the network input images are reasonable.

## Citation
If you use this code for your research, please cite our [MIA paper](https://doi.org/10.1016/j.media.2019.03.007) or [MICCAI paper](https://doi.org/10.1007/978-3-319-75541-0_20):

```
@article{Payer2019a,
  title   = {Integrating Spatial Configuration into Heatmap Regression Based {CNNs} for Landmark Localization},
  author  = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  journal = {Medical Image Analysis},
  volume  = {54},
  year    = {2019},
  month   = {may},
  pages   = {207--219},
  doi     = {10.1016/j.media.2019.03.007},
}
```

```
@inproceedings{Payer2016,
  title     = {Regressing Heatmaps for Multiple Landmark Localization Using {CNNs}},
  author    = {Payer, Christian and {\v{S}}tern, Darko and Bischof, Horst and Urschler, Martin},
  booktitle = {Medical Image Computing and Computer-Assisted Intervention - {MICCAI} 2016},
  doi       = {10.1007/978-3-319-46723-8_27},
  pages     = {230--238},
  year      = {2016},
}
```
