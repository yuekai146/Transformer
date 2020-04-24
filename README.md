## Requirements
- Pytorch version >= 1.2.0 (**https://pytorch.org/**)
- numpy (pip3 install --user numpy)
- apex (**https://github.com/apex/apex**)
- fairseq version >= 0.8.0 (pip3 install --user fairseq) (for test purpose, **https://github.com/pytorch/fairseq**)
- Moses (For preprocessing sentence pairs, **https://github.com/moses-smt/mosesdecoder**)

## Data
- I use all WMT2014 German-English parallel dataset.
- You can download raw data at **http://www.statmt.org/wmt14/translation-task.html**.
- Data preprocessing is done by Moses (**https://github.com/moses-smt/mosesdecoder**)
- You can refer to **https://github.com/pytorch/fairseq/blob/master/examples/translation/prepare-wmt14en2de.sh** for data preprocessing scripts.

## Training
```
bash run.sh
```

## Testing
```
bash score.sh
```
