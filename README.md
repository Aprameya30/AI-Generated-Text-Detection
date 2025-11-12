# Ai-Generated-Text-Detection

# AI-Generated-Text-Detection

## Project structure

- Total files in archive: **92**
  - `[no-ext]`: 67 files
  - `.pkl`: 3 files
  - `.csv`: 1 files
  - `.txt`: 2 files
  - `.npy`: 3 files
  - `.py`: 2 files
  - `.md`: 1 files
  - `.sample`: 13 files

Key folders/files (detected):
- readme: ['Ai-Generated-Text-Detection/README.md']
- requirements: ['Ai-Generated-Text-Detection/requirements.txt', '__MACOSX/Ai-Generated-Text-Detection/._requirements.txt']
- notebooks: []
- py: ['Ai-Generated-Text-Detection/test.py', '__MACOSX/Ai-Generated-Text-Detection/._test.py']
- data: []
- models: []
- docs: []

## Requirements

- See `Ai-Generated-Text-Detection/requirements.txt` for exact Python package requirements.

## Setup

Example (with requirements.txt):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r Ai-Generated-Text-Detection/requirements.txt
```

## Usage

- No obvious training script found. Check notebooks or `src/` for training code.

### Inference / Evaluation

- Script: `Ai-Generated-Text-Detection/test.py`
- Script: `__MACOSX/Ai-Generated-Text-Detection/._test.py`
- Script: `Ai-Generated-Text-Detection/y_test.npy`
- Script: `Ai-Generated-Text-Detection/X_test.npy`

Example:
```bash
python Ai-Generated-Text-Detection/test.py --input sample.txt --output preds.csv
```


## Data

- Code references dataset loading; actual dataset may not be included in archive.


## Model & Training

- Uses BERT (transformers library) for classification. Check scripts: Ai-Generated-Text-Detection/test.py.


## Evaluation

- Typical metrics: accuracy, precision, recall, F1. Check notebooks or `evaluation.py` if present.


## Authors

- Project team (see repository files for contributors)


## Files of interest
