# 洋蔥西歐字母形碼（拉丁字母、希臘字母、西里爾字母）介紹

## 前言

自創自製的，用形碼邏輯編碼西歐三大字母。依 Unicode 官方文件，給西歐字母編碼（編碼範圍見下方第二張圖），匯入輸入法架構，快速直出，某些還是需選字，但比爬符號表少很多。可以打出：越南文 việt ngữ 、俄文 дьбж 、德文 ß 、法文 É 、捷克語 ýú 、東歐西里爾文字……等。字根不用全記，只需記住常用的，建議可先記「音號碼」的編碼，就可打出許多拉丁語系的字母，如：法文、捷克文、越南文…等帶音號的拉丁字母。

進階範例說明：https://github.com/oniondelta/Latin_Greek_Cyrillic_Rime_Files/blob/main/README_explanation.md

## RIME 設定檔

純西歐字母方案：https://github.com/oniondelta/Latin_Greek_Cyrillic_Rime_Files/tree/main/4in1 ，其 [opencc 檔](https://github.com/oniondelta/Latin_Greek_Cyrillic_Rime_Files/tree/main/opencc) 

以下〔啟始鍵〕只針對純西歐字母方案（檔案：en_wel.schema.yaml，方案名：✪EuropeLetter-Onion✪ ），注音或拼音內嵌的西歐字母方案〔啟始鍵〕則不相同，有些則使用〔後綴〕。

小寫包含無法被歸類為大小寫和符號字符；拉丁字母包含：IPA Extensions、Phonetic、Spacing Modifier Letters 進格修飾符號…等

- 「 ; 」 + 字母 ⇒〔拉丁- 小寫〕

- 「 ; 」「 ; 」 + 字母 ⇒〔拉丁 - 大寫〕

- 「 ' 」「 ; 」 + 字母 ⇒〔Combining Diacritical Marks 組合字符〕

- 「 \] 」 + 字母 ⇒〔Cyrillic 西里爾- 小寫〕

- 「 \] 」「 \] 」 + 字母 ⇒〔Cyrillic 西里爾 - 大寫〕

- 「 ' 」「 \] 」 + 字母 ⇒〔Cyrillic 西里爾 - 組合字符〕

- 「 \[ 」 + 字母 ⇒〔Greek 希臘文- 小寫〕

- 「 \[ 」「 \[ 」 + 字母 ⇒〔Greek 希臘文 - 大寫〕

- 「 ' 」 + 字母⇒〔全形- 小寫〕

- 「 ' 」「 ' 」 +字母 ⇒〔全形 - 大寫〕

## 用《香草輸入法》可匯入 cin 檔打字！

cin 檔：https://github.com/oniondelta/Latin_Greek_Cyrillic_Rime_Files/tree/main/cin

cin 為舊版，有些編碼會和 rime 方案不同

- 後綴「 ; 」大寫。

- 後綴「 ; 」「 ; 」組合變音標記。

- 後綴「 \[ 」希臘字母。  後綴「 ; 」「 \[ 」希臘字母大寫。

- 後綴「 \] 」西里爾字母。  後綴「 ; 」「 \] 」西里爾字母大寫。後綴「 ; 」「 ; 」「 \] 」西里爾字母組合變音標記。

- 後綴「 ' 」全形字母。後綴「 ; 」「 ' 」全形字母大寫。

## 編碼說明

![介紹1](https://raw.githubusercontent.com/oniondelta/latin-greek-cyrillic-rime/main/latin-greek-cyrillic-2020_cht-1.jpg)
![介紹2](https://raw.githubusercontent.com/oniondelta/latin-greek-cyrillic-rime/main/latin-greek-cyrillic-2020_cht-2.jpg)

## 贊助 Donate

方案已持續更新六年以上！大改、新創、新增非常多功能！做了許多圖文說明！花了族繁不及備載的心力！

贊助 (Donate) 支持，讓 Rime 洋蔥一系列方案更新更有動力！

- #### [以〈綠界〉贊助 Donate](https://p.ecpay.com.tw/D555162)

    [![donate1](https://payment.ecpay.com.tw/Upload/QRCode/202010/QRCode_170c287e-2db8-4b50-b87f-8d36500a3958.png)](https://p.ecpay.com.tw/D555162)

- #### [以〈歐付寶〉贊助 Donate](https://qr.opay.tw/q1ql7)

    [![donate2](https://payment.opay.tw/Upload/Broadcaster/2294343/QRcode/QRCode_7AC0FA1CAD39F0B66CFD5513A2173D1A.png)](https://qr.opay.tw/q1ql7)

- #### [以〈TWQR〉贊助 Donate](https://qr.opay.tw/N6RTD)

    [![donate3](https://payment.opay.tw/Upload/TWQRSticker/20250912/1/2294343.png)](https://qr.opay.tw/N6RTD)

- #### [以〈PayPal〉贊助 Donate（非台灣用）](https://paypal.me/onioninput)

    [![donate4](https://github.com/user-attachments/assets/5ae6b20c-939d-4781-9f82-6865043ffeac)](https://paypal.me/onioninput)


