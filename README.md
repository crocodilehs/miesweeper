# 踩地雷簡易版

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/crocodilehs/miesweeper/blob/main/minesweeper.ipynb)

最近踩地雷玩上癮，所以做一下踩地雷，順便用來複習Python，但是因為筆電送修，只好用Colab做文字版的踩地雷。
使用ChatGPT幫忙處理空白延伸的bug。自己寫的空白延伸有bug，開方塊會開過頭，似乎是因為以下原因：
1. 只有判斷下一個要挖的有沒有挖過(空白)，沒有考慮到下一個方塊是不是已經挖過(數字)。
2. 挖下一個之前沒有先檢查是否已經打開過，如果已經打開就要跳過。
