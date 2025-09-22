This repository contains tools and configurations for generating synthetic datasets used to train the Sen-SSum (Speech-to-Summary) models. The Sen-SSum pipeline integrates ESPnet for automatic speech recognition (ASR) and LLaMA-Factory for training large language models (LALMs).

🗂️ Project Structure
text
.
├── conf/                 # Configuration files
│   ├── train.yaml               # ESPnet training configuration
│   └── train_full_sft.yaml      # LLaMA-Factory training configuration
├── data/                 # Training datasets and processed data
└── README.md
⚙️ Components
1. ESPnet (ASR Module)
We use ESPnet for speech recognition preprocessing.

Repository: espnet/espnet

Pre-trained ASR Model: kamo-naoyuki/librispeech_asr

Training Configuration: conf/train.yaml

Data Directory: data/

2. LLaMA-Factory (LALM Training)
We use LLaMA-Factory for fine-tuning the large language model for summarization.

Repository: hiyouga/LLaMA-Factory

Pre-trained Model: Qwen/Qwen2-Audio-7B

Training Configuration: conf/train_full_sft.yaml

Data Directory: data/

