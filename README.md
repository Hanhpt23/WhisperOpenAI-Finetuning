# WhisperOpenAI-Finetuning


conda create -n B python=3.9
conda activate B

# Install dependent libraries
pip install -r requirement.txt

# Login to HuggingFace
huggingface-cli login ----> insert API

# Loggifn to wandb
wandb login ---> insert API


For training, run the file script
```slurm server
sbatch scripts/german/base/germanmed-v1.sh
```
