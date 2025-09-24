# mmBERT-QA 
使用mmBERT 模型實作中文抽取式問答系統。 

這個 repo 是 NTU 機器學習課程 HW7 的實作：用 BERT-type 模型（mmBERT / macBERT 類）做中文抽取式問答（Extractive QA）。
目標是把文章內的片段找出來當答案（不是自己生成句子）。 
練習「微調預訓練語言模型」並實作一個簡單的 QA pipeline： 
- 從載模型、斷詞(tokenize)、製作訓練資料、到訓練、驗證、最後做測試提交（CSV）。
- 學會處理長篇文章（超過模型最大 token 限制）的方法：滑窗（doc_stride）。
- References: https://huggingface.co/hfl/chinese-macbert-large
