# zutomayo_OCR
ずとまよ文字を認識するやつ/ゴリゴリTesseract使ってる  

# 備忘録
1. https://github.com/nguyenq/jTessBoxEditor からjTessBoxEditorのzipをDL,解凍 -> cd jTessBoxEditor
2. Tesseract/PyOCRを入れる
3. 環境変数設定 (自分は export TESSDATA_PREFIX="/usr/local/Cellar/tesseract/5.3.2/share/tessdata")
4. 起動 java -Xms128m -Xmx1024m -jar jTessBoxEditor.jar &
5. がくしゅうでーたとかつくってがくしゅう(->参考b)
6. ztmy.traineddataができたらもう完成みたいなもん
7. あとはOCRするだけ(->参考a)
8. 以上



  
# 参考:
a. https://danglingfarpointer.hatenablog.com/entry/2015/01/28/215629  
b. https://www.tdi.co.jp/miso/tesseract-ocr  

サイトにするのに参考:
  https://qiita.com/keito1024/items/dff19c95ca7c9b6c5d0c  
  https://qiita.com/quiye/items/2bb69e009bd12ea72f8c  
  https://github.com/jeromewu/tesseract.js-custom-traineddata  
  https://qiita.com/tinymouse/items/8b82f3578e167627d209
