# BART Finetuning on AMI Meetings Corpus

### Setup 💻

```bash
git clone https://github.com/RyanDsilva/bart-finetuning-ami.git

pip install -r requirements.txt

python run_bart_sum.py \
--data_dir=./data \
--model_type=bart \
--model_name_or_path=bart-large \
--learning_rate=3e-5 \
--train_batch_size=8 \
--eval_batch_size=8 \
--output_dir=./results \
--do_train
--do_predict
```
