Step 0: replace the optimizer file: torch.optim.AdamW with the provided files
Step1: Download the dataset from Hugging Face: [pg_books-tokenized-bos-eos-chunked-65536]
Step2: Truncate - python3 truncate.py 2048 .pgbooks/truncated-2k
Step3: Train - bash train.sh