# SSEF-2025-Project
This is Github repo for models and additional information about SSEF 2025 paper Singing Voice "Synthesis for Choir Vocals via DiffSinger"

There are 3 models in total (Spanish, Pop English, and Latin)
Both the original (ground truth) audio recordings and their respective predicted outputs can be found in each model's respective results folder. 
Included in the results folder are also lightning logs that can be opened via tensorboard
<pre>
tensorboard --logdir=path/to/lightning/logs
</pre>

Small dataset of Latin Bass vocals available in dataset folder, used for training Latin model. 
  
Credits:
- [DiffSinger colab](https://github.com/MLo7Ghinsan/DiffSinger_colab_notebook_MLo7) for Colab Training notebook
- [Paper](https://arxiv.org/abs/2105.02446) for the original DiffSinger paper
- [Tiger En dataset](https://github.com/openvpi/MakeDiffSinger/wiki/Public-datasets)  Tiger En dataset found here
- [Cantoria](https://doi.org/10.5281/zenodo.5878677) Cantoria dataset
