# BART Finetuning on AMI Meetings Corpus

### Setup 💻

```bash
git clone https://github.com/RyanDsilva/bart-finetuning-ami.git

pip install -r requirements.txt

python train.py \
--data_dir=./data \
--model_type=bart \
--model_name_or_path=bart-large \
--learning_rate=3e-5 \
--train_batch_size=4 \
--eval_batch_size=4 \
--output_dir=./outputs \
--do_train
```
