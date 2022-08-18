# Opencv_VirtualPen

專案名稱：虛擬畫筆

專案簡介：透過筆電內建的視訊鏡頭辨識畫筆顏色，進而實現在螢幕上畫畫的功能

===

若要使用請按以下步驟

step1. git clone https://github.com/bryant0108/Opencv_VirtualPen.git

step2. pip install -r requirements.txt

step3. 執行step0.偵測筆顏色.py （預設為藍綠黃）

選定您所想使用的畫筆 調整hsv值直至result畫面上僅出現畫筆為止

記錄下畫筆的hsv值 待會於step1.虛擬畫筆.py 中進行修改

藍=[14, 59, 160, 255, 175, 255]
綠=[47, 97, 169, 255, 148, 255]
黃=[22, 70, 214, 31, 255, 255]

step4. 執行step1.虛擬畫筆.py 調整hsv值以符合您的畫筆顏色

step5. 調整完畢即可在螢幕上畫畫囉～～～
