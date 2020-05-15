<h1 align="center">Welcome to TER Sentiment Analysis 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/Torilen/TER-Sentiment-Analysis#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Torilen/TER-Sentiment-Analysis/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/Torilen/TER-Sentiment-Analysis/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/Torilen/TER-Sentiment-Analysis" />
  </a>
</p>

> This repository is a compilation of our work on the Sentiment Analysis TER (Travaux Encadrés de Recherche) at University of Nantes and directed by Nicolas HERNANDEZ. You can see all the references we founded, all the codes we developed and all the links which was useful during the work 

## 🏠 [Homepage](https://github.com/Torilen/TER-Sentiment-Analysis)
## :link: [Useful Links](https://github.com/Torilen/TER-Sentiment-Analysis/blob/master/USEFULLINKS.md)
## :triangular_flag_on_post: [References](https://github.com/Torilen/TER-Sentiment-Analysis/blob/master/REFERENCES.md)

## Prerequisites

- python >=3.6

## Install

```sh
git clone https://github.com/Torilen/transformers-camembert.git
cd transformers-camembert
pip install .
pip install pytorch_transformers
pip install seqeval
cd ../
git clone https://github.com/Torilen/TER-LCF-ATEPC-FR.git
cd TER-LCF-ATEPC-FR/
```

## Usage

```sh
--dataset
--output_dir
--SRD
--learning_rate The initial learning rate for Adam
--use_bert_spc
--local_context_focus
--num_train_epochs Total number of training epochs to perform
--train_batch_size Total batch size for training
--dropout
--max_seq_length
--eval_batch_size Total batch size for eval
--eval_steps Evaluate per steps
--gradient_accumulation_steps Number of updates steps to accumulate before performing a backward/update pas
```

## Run tests

```sh
python train.py
```



Otherwise, you can use this Google Colab Notebook : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1bs6N0NWuKF4qmCLc0LQdBHKBEKc_3m_K?usp=sharing]

👤 **Aniss BENTEBIB , Amine BOULAHMEL

* GitHub: [@Torilen](https://github.com/Torilen)
* LinkedIn: [@aniss-bentebib-a449a8155](https://linkedin.com/in/aniss-bentebib-a449a8155)
* LinkedIn: [@amine-boulahmel-88743a113](https://linkedin.com/in/amine-boulahmel-88743a113)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

## 📝 License

Copyright © 2020 [Aniss BENTEBIB , Amine BOULAHMEL, Harry JANDU](https://github.com/Torilen).<br />
This project is [MIT](https://github.com/kefranabg/readme-md-generator/blob/master/LICENSE) licensed.

***
This readme was created with ❤️ and drop of sweat
