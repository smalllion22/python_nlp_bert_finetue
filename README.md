# python_nlp_bert_finetue 中文句子情緒分類

## 訓練資料來源
- [Datasets:Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset](https://huggingface.co/datasets/Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset)

## 基礎模型
- [google-bert/bert-base-chinese](https://huggingface.co/google-bert/bert-base-chinese)

## 安裝套件
- torch (版本號 2.5.1+cu124)
- torchvision (版本號 0.20.1+cu124)
- torchaudio (版本號 2.5.1+cu124)
- transformers (版本號 4.48.3)
- datasets (版本號 3.3.1)
- evaluate (版本號 0.4.3)
- accelerate (版本號 1.3.0)
- scikit-learn (版本號 1.6.1)
  
(版本號可用 pip list，或是 conda list 來檢視)


## 說明
這個微調後的模型主要用於進行情緒分類，將文本分為八種類別：平淡語氣、開心語調、悲傷語調、憤怒語調、驚奇語調、厭惡語調、疑問語調和關切語調。使用 Chinese_Multi-Emotion_Dialogue_Dataset 資料集進行訓練，並轉換文字標籤為數字。

## 成果
### 執行成果
<img width="952" alt="image" src="https://github.com/user-attachments/assets/4a9efb91-9dcc-4fac-95ac-85296d6b1013" />

...
### 影片連結
https://drive.google.com/file/d/1PhPJfOHC-WHrkSG9DDrYKnwHv_FZmOCp/view?usp=drive_link
...


