<div align="center">
  
<a href="https://arxiv.org/abs/2405.07346"><img src="https://img.shields.io/badge/Arxiv-2411:03795-red"></a>
  
</div>
<div>
  <h1>MINT-IQA: Quality Assessment for AI Generated Images with Instruction Tuning</h1> 
</div>
<img width="width: 80%" alt="829deda32314ffdebed7da1edc40ace" src="https://github.com/user-attachments/assets/ed8f1f96-ac69-42d7-b5b4-0c459f094c3c">

## 🛠️ Installation

Clone this repository:
```
git clone https://github.com/wangjiarui153/MINT-IQAL.git
```
Create a conda virtual environment and activate it:
```
conda create -n MINTIQA python=3.8
conda activate MINTIQA
```
Install dependencies using requirements.txt:
```
pip install -r requirements.txt
```
## 🚀 Weight and Database Download
The codes and inference weights can be downloaded from 
链接：https://pan.baidu.com/s/1dJNN9sL-cPytOm8vjEDEHQ 
提取码：k2vf 

The Database is in:
https://github.com/wangjiarui153/AIGCIQA2023

## 🌈 Inference

Set img_path in inference.py line29
Set the corresponding prompt to the image in inference.py line31
file setting in config/options_infer.py

```
python inference.py
```

## 📌 TODO
- ✅ Release the AIGCIQA2023 database
- ✅ Release the Inference code (stage1 and stage2)
- [ ] Release the training code (stage1 and stage2)


## 📧 Contact
If you have any inquiries, please don't hesitate to reach out via email at `wangjiarui@sjtu.edu.cn`

## 🎓Citations

If you find AIGV-Assessor is helpful, please cite:

```bibtex
@misc{wang2024understandingevaluatinghumanpreferences,
      title={Understanding and Evaluating Human Preferences for AI Generated Images with Instruction Tuning}, 
      author={Jiarui Wang and Huiyu Duan and Guangtao Zhai and Xiongkuo Min},
      year={2024},
      eprint={2405.07346},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2405.07346}, 
}
```


