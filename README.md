# 東吳大學資科系2024年下半年LINE Bot實作課程

## 更新通知

2024/12/12
* 本次課程最後一個作業，使用OpenAI或者其他AI模型，開發一個LINE Bot，使用手機拍下你和這個LINE Bot對話兩次的問答畫面，問答的問題要有連續性，要看出LINE Bot有記住上一個問題的結果。問題範例：「AI 請簡介東吳大學資科系」(LINE Bot回答.....)；「AI 系主任是誰？」(LINE Bot回答.....)。

2024/12/09
* Kyle同學發現在MacOS 11之後，系統中的`5000`port被佔用，參考[Slido](https://app.sli.do/event/baDVeTLWj31KQuuzybqgdq)，新版程式碼已經這次課程使用的port統一改成`5051`，請重新下載本repo程式。

2024/12/06
* 使用Windows 11的同學，如果你發現系統中有好幾個linebot環境，是因為vscode在安裝`ipykernel`時，會自動建立一個新的環境的問題，解決方法參考[這邊](https://github.com/joshhu/sculinebot20242nd/issues/2)

2024/12/05
* conda設定有問題的同學，先參考[這邊](https://github.com/joshhu/sculinebot20242nd/issues/1)

2024/12/04
* B班使用MacOS的同學，如果出現IPV6的問題，請重新下載本repo程式，重新執行試試看，謝謝

2024/12/02
* 本次課程在本機端的程式編輯環境，規定使用Visual Studio Code，請同學們自行安裝。

## 注意事項

* 程式問題提問，請在[Issues](https://github.com/joshhu/sculinebot20242nd/issues)上提問，並且提供程式碼，錯誤訊息，以及問題描述，參考[這邊](https://github.com/joshhu/sculinebot2024/issues/10)的提問格式。
* 安裝miniconda，並且建立虛擬環境，MacOS參考[這邊](https://github.com/joshhu/sculinebot2024/issues/1)，Windows 10/11參考[這邊](https://github.com/joshhu/sculinebot2024/issues/3)
* 建立虛擬環境，並且安裝好套件。MacOS參考[這邊](https://github.com/joshhu/sculinebot2024/issues/2)，Windows 10/11參考[這邊](https://github.com/joshhu/sculinebot2024/issues/4)
* 如果是本機執行，請設定好幾個環境變數，參考[這邊](https://github.com/joshhu/sculinebot2024/issues/8)。
* 如果已經安裝Anaconda的，參考[這邊](https://github.com/joshhu/sculinebot2024/issues/5)
* 密鑰名稱為求符合PEP命名標準，統一使用下列格式：
    - LINE的channel secret：`LINE_CHANNEL_SECRET`
    - LINE的channel access token：`LINE_CHANNEL_ACCESS_TOKEN`
    - Ngrok的authtoken：`NGROK_AUTHTOKEN`
    - OpenAI的API key：`OPENAI_API_KEY`

## 課前準備
1. Google帳號，在Colab上執行程式
2. ngrok的帳號
3. LINE的帳號
4. OpenAI的帳號
5. 課程中遇到問題，在Slido上提問
6. 下課後問題，在本課程的Github上Issue提問(需註冊Github帳號)
7. 能執行Powershell的Windows電腦或者Terminal的Mac電腦

## 課程簡介
從頭開始開發一個LINE Bot，並且整合OpenAI API，讓LINE Bot能夠回答使用者的問題

## 課程目標
- 課前準備
- 開發環境安裝及測試
- LINE平台基礎知識
- 帳號申請及金鑰
- 基礎觀念及知識
- 程式碼撰寫及說明
- OpenAI API說明及整合

## 上課日期
均為下午15:10~18:00
### B班
- 2024/11/26
- 2024/12/03
- 2024/12/10

### A班
- 2024/11/28
- 2024/12/05 
- 2024/12/12

## 線上互動Slido連結
 本課程Slido互動平台：(https://app.sli.do/event/baDVeTLWj31KQuuzybqgdq)
 
## 教材內容
- `Codes`: 課程範例程式
- `Ref`: 課程參考資料
- `Slides`: 課程投影片
- `Videos`: 課程錄影
