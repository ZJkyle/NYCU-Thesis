# 陽明交通大學碩博士論文 XeLaTeX 模板

[nycu-thesis](https://github.com/indigo40123/NYCU-Thesis-Template)
Template are developed based on XeLaTeX + xeCJK.

Online version powered by Overleaf could be found here:
https://www.overleaf.com/latex/templates/national-yang-ming-chiao-tung-university-nycu-thesis-template/zgjfrxhcdcmj

## 目錄結構說明

- `main.tex`：主控檔，串接所有內容
- `chapters/`：各章節內容（建議每章一檔，如 1-intro.tex）
- `abs/`：中英文摘要
- `appx/`：附錄
- `author/`：作者資訊
- `figures/`：所有圖檔
- `tables/`：所有表格
- `bib/`：參考文獻
- `config/`：格式、字型等設定
- `notes/`：研究筆記（可自行新增）
- `drafts/`：草稿（可自行新增）
- `scripts/`：自動化腳本（可自行新增）

## 下載
  你可以 clone 這個 repos, 或是到[這裡](https://github.com/indigo40123/NYCU-Thesis-Template)下載最新版本

## 快速上手

- 完整編譯論文：
  ```bash
  make
  ```
- 清除中間檔：
  ```bash
  make clean
  ```
- 只預覽 intro 章節：
  ```bash
  xelatex preview-intro.tex
  ```

## 章節分檔建議

- 每章一檔，檔名建議 `1-intro.tex`、`2-background.tex` ...
- main.tex 用 `\input{chapters/1-intro.tex}` 串接
- 章節檔案只寫內容，不要有 `\documentclass`、`\begin{document}`、`\end{document}`

## 進階

- 進階用法、細節請參考 `README.pdf`
- 若需自動化腳本、Makefile 增強、VSCode 設定等，請見 scripts/ 或洽詢作者

## 說明
   進階的使用教學請參考 [README.pdf](https://github.com/indigo40123/NYCU-Thesis-Template/README.pdf)


## Acknowledgement
   此模板的前身是交大 borting chen同學的 [nctu-thesis](https://github.com/borting/nctu-thesis) 
   此模板的貢獻為更新陽交大的封面頁,Latex設定及格式還參考了Chun Sing Leung學長以及以下幾位的模板. Thank you.
   
* 台科大 hdj 與 saiba 兩位學長的 [ntust-thesis template](https://code.google.com/archive/p/ntust-thesis/downloads)
* 交大 Po-hao Huang 同學的 [nctu-thesis template](https://github.com/Po-haoHuang/nctu-thesis)
* 交大 Chiehmin (FatMinMin) 同學的 [nctu-thesis](https://github.com/chiehmin/nctu-thesis)
* 台大 [qcl](https://github.com/qcl/qcl-master-thesis) 與 [tzhuan](https://github.com/tzhuan/ntu-thesis) 兩位同學的 ntu-thesis template

## License
   此模板係採用[創用 CC 姓名標示-非商業性-相同方式分享 3.0 台灣 授權條款](https://creativecommons.org/licenses/by-nc-sa/3.0/tw/legalcode)授權.
