# SSEF-2025-Project
This is Github repo for models and additional information about SSEF 2025 paper Singing Voice "Synthesis for Choir Vocals via DiffSinger"

There are 3 models in total (Spanish, Pop English, and Latin)
Samples of recordings can be found in sample_validation_recordings folder. Both the original (gt) audio recordings and their respective predicted outputs (diff) can be found in each model's. 

Included in each model's results folder is lightning logs that can be opened via tensorboard, and other information
<pre>
tensorboard --logdir=path/to/lightning/logs
</pre>

Small dataset of Latin Bass vocals available in dataset folder, used for training Latin model. 
  
Credits:
- [DiffSinger colab](https://github.com/MLo7Ghinsan/DiffSinger_colab_notebook_MLo7) for Colab Training notebook
- [Paper](https://arxiv.org/abs/2105.02446) for the original DiffSinger paper
- [Tiger En dataset](https://github.com/openvpi/MakeDiffSinger/wiki/Public-datasets)  Tiger En dataset found here
- [Cantoria](https://doi.org/10.5281/zenodo.5878677) Cantoria dataset
