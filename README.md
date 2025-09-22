# AGSD-make-synthetic-dataset-for-Sen-SSum
# The Sen-SSum models were established by ESPnet and LLAMA-FACTORY (We trained LALM by LLAMA-FACTORY) .

# 1.ESPnet
# we give the code, the train Configuration, the data.
ESPnet: https://github.com/espnet/espnet.git
Pre-trained ASR Model: https://huggingface.co/espnet/kamo-naoyuki_librispeech_asr_train_asr_conformer5_raw_bpe5000_frontend-truncated-b76af5
Train Configuration: conf/train.yaml
Train Data: data

# 2. LLAMA-FACTORY (LALM)
LALM: https://github.com/hiyouga/LLaMA-Factory.git
Pre-trained LALM Model:
