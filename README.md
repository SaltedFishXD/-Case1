# 數位醫學 -Case1
### python 環境 
* 環境
    * python                    3.5.5
    * os(python 內建)
    * re(python 內建)
    * numpy                     1.18.1 
    * pandas                    0.23.0
    * scikit-learn              0.19.1

### 使用說明 

下載整個完整的資料夾，使用以上環境，
* 有這兩個檔案(這兩個檔案要用jupyter notebook開啟)
    * text_analyze_using_frequency.ipynb
        * 使用字詞頻率作分析，全部文章出現的詞減去unknown的詞
    * use_bag_of_word_and_machine_learning.ipynb
        * 使用bag of word選取有關鍵字的句子，並用有關鍵字的句子做機器學習，使用trainset的資料做train test split 做出來的accuracy可達0.9。而程式後半部測試testset，但不知道的每個txt file的true label，所以輸出僅輸出預測結果。![image](https://github.com/BunnyEricMarcus/-Case1/blob/main/testset_prediction.PNG)
