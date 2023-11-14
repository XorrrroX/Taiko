# 太鼓練習器
基本上就是一個可以練習太鼓達人遊戲中經常出現的音符配置的練習器
## 打開後的畫面:
![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/92ee4079-a627-4339-a6e9-a1eb4d09af64)

## 設定畫面:
![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/611f25d1-b064-40de-80ba-0fdbdf5b4b07)

## 練習參數畫面:
![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/07597068-d87e-4c53-897e-86a1dbb04268)
- BPM: 音樂速度
- 一串長度: 一串連續音符的長度
- 串燒數量: 此次練習會有幾串連續的音符(以串為單位)
- 流速: 音符從出現到判定區的移動速度倍率(因為在BPM提高時,基礎流速也會提高)

## 全紅模式下的畫面(全藍同理):
![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/cb1b50fb-c958-46d4-b4cf-24c4280a6f86)
- 最左邊為連擊數,在沒打到音符時會歸零重新開始計算
- 連擊數右邊的白色圓圈為判定區,音符移動到那裡時要打擊它
- 右邊連在一起的五個紅色圓形為一串長度為五的音符(速度為16分音符)

## 結算畫面:
![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/f0cdaccf-1382-4131-9cb2-76c4725d0c99)
- 左上為成績
- 右邊上面的按鈕可以再來一次
- 而下面的按鈕會回到主選單(打開遊戲那裡)

## 其他模式的效果
 - ## 全紅或全藍模式:
    ![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/776889ef-3c02-4dbd-a480-0e68962d7ff5)
    - 紅色的音符和藍色的音符會以串為單位隨機出現
 - ## 紅紅或藍藍模式:
    ![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/4980b374-998f-4237-90bb-430db7ec4256)
    - 紅色的音符和藍色的音符會以兩顆音符為單位隨機出現,在一串結束時會重新計算,也就是如果上一串的尾巴是紅紅藍,那下一串會重新再抽一個顏色開始,而不是保證藍色
 - ## 隨機模式:
    ![image](https://github.com/XorrrroX/TaikoCode/assets/107466847/a2309f17-e489-4373-bcb5-4e775a4100d0)
    - 沒有任何限制,完全隨機生成
