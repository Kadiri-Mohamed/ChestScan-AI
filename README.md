
# ChestScan AI

ChestScan AI is an experimental deep learning project
for classifying chest X-ray images into NORMAL and PNEUMONIA.

## Models

- CNN from scratch
- MobileNetV2 transfer learning
- MobileNetV2 fine-tuning

## Project structure

- `src/config.py`: project configuration
- `src/data.py`: dataset loading and preparation
- `src/model.py`: model architectures
- `src/train.py`: model training
- `src/fine_tuning.py`: MobileNetV2 fine-tuning
- `src/evaluate.py`: test evaluation
- `notebooks/`: experiments

## Setup

```bash
python -m venv .venv
```

Activate the environment, then install dependencies:

```bash
python -m pip install -r requirements.txt
```

Place the dataset in the expected directory structure,
with `train` and `test` folders inside `data/`.

## Run

```bash
python -m src.train
python -m src.fine_tuning
python -m src.evaluate
```

## Disclaimer

This project is for educational and research purposes only.
It is not a validated medical diagnostic tool.
