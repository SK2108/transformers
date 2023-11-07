# Transformers

Transformers is an opinionated library (Hugging Face)

## Getting started

- Install the libraries required

```markdown
!pip install transformers datasets
```

- Pick and install a machine learning framework

Pytorch

```markdown
pip install torch
```

TensorFlow

```markdown
pip install tensorflow
```

## Creating an environment

- Use the command below to create an environment

```markdown
python -m venv .env
```

- Activate the environment

On Linux or Mac

```markdown
source .env/bin/activate
```

On Windows

```markdown
.env/Scripts/activate
```

Once this is done, you can install Transformers with the following command

```markdown
pip install transformers
```

## Check if Transformers has been installed correctly

- Run this command

```markdown
python -c "from transformers import pipeline; print(pipeline('sentiment-analysis')('we love you'))"
```

## Datasets

## Helpful links

- [Transformers: Philosophy](https://huggingface.co/docs/transformers/philosophy)

- [Transformers: Installation](https://huggingface.co/docs/transformers/installation)

- [Datasets, Hugging Face](https://huggingface.co/docs/datasets/nlp_load)
