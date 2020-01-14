# Date Translation
Sequence2Sequence model to translate date strings into the standard date format.
```
Dec 10, 1865 --> 1865-12-10
December 25, 1991 --> 1991-12-25
Saturday June 10 1741 --> 1741-06-10
```
This is for educational purposes to learn about seq2seq models and attention mechanisms.

### Helpful Resources
1. Bahdanau https://arxiv.org/pdf/1409.0473.pdf
2. Luong https://arxiv.org/pdf/1508.04025.pdf
3. https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html
4. https://distill.pub/2016/augmented-rnns/

### Installation
1. Install <a href="https://docs.conda.io/en/latest/">conda</a>.
2. Create and activate conda env
```bash
conda create -n date python=3.7
conda activate date
```
3. Install python packages.
```
pip install -r requirements.txt
```

### Run
0. Activate the conda env.
```
conda activate date
```
1. Start your jupyter notebook.
```
jupyter notebook
```
2. Run the notebooks in sequential order. The first notebook to run starts with `00_`
