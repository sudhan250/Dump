# Dump
https://www.metagenomics.wiki/tools/16s/qiime/install/packagesnotfounderror
# create manual a new conda environment "qiime1", install using pip

conda create -n qiime1 python=2.7  # create conda environment "qiime1"  

conda activate qiime1    # open "qiime1" environment

pip install numpy        # install numpy (python)

pip install qiime        # install qiime-1 (python)

pip install h5py         # install h5py (python) for reading .biom files

pip install matplotlib==1.4.3

print_qiime_config.py -t # test qiime-1 configuration

https://matplotlib.org/stable/users/installing/index.html
