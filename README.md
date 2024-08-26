# Co(ve)rtex: ML Models as storage channels and their (mis-)applications


Note: We will update this repository gradually. Currently We are making the artifacts ready. Once it is ready, We will make it available...


## Table of Contents

- [Prerequisites](#Prerequisites)
- [Usage](#Usage)
- [Algorithm](#Algorithm)
- [Codes](#codes)
- [Directories](#directories)
- [License](#license)
- [Contact](#contact)
- [Citation](#citation)


### Prerequisites

- Google colab
- python 3.10.12
- reedsolo 1.6.1
- crc 4.1.0
- tensorflow
- numpy
- matplotlib
- keras
- random


### Usage

Using ML models as a storage channel


### Algorithm

## Covertex in Black-box setting

<img width="673" alt="blackbox covertex" src="https://github.com/Mamun5011/Covertex-ML-Models-as-Storage-channel/assets/39150506/a2cc9b9b-fe57-4452-aaff-65b80f530093">


### Codes

- COSINE_Baseline_Inband_Outband_Detection.ipynb (visualize cosine similarity metrics for Baseline vs In-band vs out-of-band samples)
- LOF_Baseline_Inband_Outband_Detection.ipynb (visualize local outlier factor (LOF) metrics for Baseline vs In-band vs out-of-band samples)
- Combinatorial Error Correction_CEC.ipynb (CEC implementation)
- Reed_Solomon_Error_Correction.ipynb (RS implementation)
- Chernoff_Bound.ipynb (By using Monte Carlo simulation, we estimate the number of reads necessary to guarantee with a high probability that the most common class is the correct class)
- PSNR_Calculation.ipynb (Calculate the PSNR between Sender and Receiver)
- Features_Analysis_Covertex_DG.ipynb (visualize the TSNE figures for feature analysis of the covertex-DG)
- Pruning_Covertex_DG_Channel.ipynb (prune the coertex-DG model and see how it affects the channel accuracy)
- Fine_Pruning_Covertex_DG_Channel.ipynb ( Fine Pruning --> defense of backdoor attack applied to the covertex-DG model and see how it affects the channel accuracy)
- Retraining_Covertex_DG_Channel.ipynb (retrain the coertex-DG model using a fractionj of baseline data and see how it affects the channel accuracy)
- Random_Data_Transfer_Through_Lenet5 ( random data transfer through Lenet-5 trained with MNIST)
  

### Directories
- Cosine_metrics_Data (Contains all of the saved data for cosine similarity measurement for baseline, malicious and out-of-band patches)
- GAN for CIFAR10 (Gan file for generating the data from same distribution of CIFAR10)
- Gan for MNIST (Gan file for generating the data from same distribution of MNIST)
- Multiple Reading ( contains the code for How multiple reading optimization improve the performance of the channel)
- saved_Models (contains the drive link for saved model so that one can load the direct trained model instead of training the model from the scratch)

### License

This project is licensed under the [MIT License](https://github.com/Mamun5011/Covertex-ML-Models-as-Storage-channel/blob/main/LICENSE).


### Contact

For any questions or concerns, contact mmamu003@ucr.edu

### Citation

If you find our work helpful, please cite our papers on privacy and security of ML as follows, thanks! Also Stay tuned for more interesting works!


<div>
  <pre id="bibtex-entry">
@article{mamun2023deepmem,
  title={DeepMem: ML Models as storage channels and their (mis-) applications},
  author={Mamun, Md Abdullah Al and Alam, Quazi Mishkatul and Shaigani, Erfan and Zaree, Pedram and Alouani, Ihsen and Abu-Ghazaleh, Nael},
  journal={arXiv preprint arXiv:2307.08811},
  year={2023}
}
  </pre>
</div>



