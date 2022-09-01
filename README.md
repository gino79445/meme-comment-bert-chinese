# meme-comment-bert-chinese

ktrain is a lightweight wrapper for the deep learning library TensorFlow Keras (and other libraries) to help build, train, and deploy neural networks and other machine learning models. Inspired by ML framework extensions like fastai and ludwig, 
ktrain is designed to make deep learning and AI more accessible and easier to apply for both newcomers and experienced practitioners.

### Below is what you can do with this program:

主要是由梗圖迷因下面留言來判斷其梗圖是否含有地獄梗，資料總共約10285筆。

資料來源自facebook及instagram，透過爬蟲程式來進行抓取，其中因instagram大部分不含地獄梗圖留言且大副分會有tag(@name)的留言格式，因此需先把其刪掉。


使用遷移式學習，模型選擇為bert且藉由ktrain來訓練，準確率約為79%

**將train移至程式所在資料夾**

**result:**

<img src="https://github.com/gino79445/meme-comment-bert-chinese/blob/main/result.png?raw=true" style="width:400px" />




