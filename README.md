# Co(ve)rtex: ML Models as storage channels and their (mis-)applications


Note: I will update this repository gradually. Currently reorganizing all codes. Once it is ready, I will make it available...


## Table of Contents

- [Prerequisites](#Prerequisites)
- [Usage](#Usage)
- [Algorithm](#Algorithm)
- [Codes](#codes)
- [License](#license)
- [Contact](#contact)
- [Citation](#citation)


### Prerequisites

- Google colab
- python 3.10.12


### Usage

Using ML models as a storage channel


### Algorithm

## Covertex in Black-box setting

<img width="473" alt="blackbox covertex" src="https://github.com/Mamun5011/Covertex-ML-Models-as-Storage-channel/assets/39150506/a2cc9b9b-fe57-4452-aaff-65b80f530093">


### Codes

- COSINE_Baseline_Inband_Outband_Detection.ipynb (visualize cosine similarity metrics)
- LOF_Baseline_Inband_Outband_Detection.ipynb (visualize local outlier factor (LOF) metrics)

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
  <button onclick="copyToClipboard()">Copy</button>
</div>

<script>
  function copyToClipboard() {
    const bibtexEntry = document.getElementById('bibtex-entry').innerText;
    navigator.clipboard.writeText(bibtexEntry).then(function() {
      console.log('Copied to clipboard successfully!');
    }, function(err) {
      console.error('Could not copy text: ', err);
    });
  }
</script>
