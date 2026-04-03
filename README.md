FAQ:  
Q. Is this software open source?  
A. It is not currently open source, but may become so in the future.  

Q. What language is it developed in? What environment is required?  
A. Pure Java. The runtime environment is fully packaged; no .NET packages are required.  

FAQ:  
Q. 本軟體開源嗎?  
A. 目前不開源 未來可能會開源  

Q. 用什麼語言開發的? 需要什麼環境  
A. 純Java 已將runtime時環境完整打包 無須.NET套件  

---

Known / In-progress  
This has not yet been confirmed. Please let me know if you spot any issue or have any suggestions.

已知問題 / 排程計畫  
目前暫無確認，若有任何錯誤或相關建議請回報給我

---

Thanks to HaRepacker, WzComparerR2 and other contributors for the information provided;  
including, but not limited to, the Wzlib, Spine, Snow2 decryption, ChaCha20 decryption, PKG1 and PKG2 decryption algorithms  

感謝 Harepacker、WzComparerR2等相關作者提供的資訊  
包含但不限於 Wzlib、Spine、Snow2解密、ChaCha20解密、PKG1、PKG2解密算法  

---

⚠⚠⚠ Important Notice ⚠⚠⚠  
This editor is primarily designed for my own convenience, so the UI design may not suit every user’s preferences.  
This editor has not yet been fully tested; you should back up your files before making any edits or saving them.  
The file may take a little while to load; please be patient.  

⚠⚠⚠注意事項⚠⚠⚠  
本編輯器主要為我個人使用方便 因此UI設計上可能並非適合每個使用者習慣  
本編輯器尚未經過完整測試，進行任何編輯存檔前應先將檔案進行備份  
檔案載入速度可能稍慢，請耐心等候  

---

Editor Features
01. Automatic file version matching for IV alignment analysis
02. Supports analysis of versions to KMST 1.2.1199
03. Supports analysis of .ms files and PKG2 files
04. Customisable hotkeys / lt rb box colours / anchor colours
05. Recursive search function: Search specific files or all files
06. Improved tab functionality based on HaRepacker: Rename and close unused tabs
07. Support for opening files in side-by-side view for easy addition and comparison
08. Light and dark colour schemes
09. Image zoom from 20% to 1600%
10. Video parsing support: extract frames or the entire video as PNG or GIF
11. Spine parsing support: extract frames or the entire video as PNG or GIF
12. If there are _outlink or _inlink nodes under a Canvas node, images can be automatically filled in with a single click;
    This feature is available provided that the corresponding _Canvas file has been opened;
    What is a corresponding _Canvas file? 
    If Data\Character\Weapon\Weapon_000.wz is already open,
    you must also open the _Canvas_000 ~ XXX.wz files under the Data\Character\Weapon_Canvas\ path to restore the images.
13. Supports Skills, Reactors, Mobs, Morphs and any other elements displaying lt/rb anchors; customisable toggles are also available
14. Supports parsing of various PNG compression formats from existing versions; compression settings can also be adjusted directly within the editor:
    Supported formats include BGR-A4444 / BGR-A8888 / DXT3 / DXT5 / BC7
    The BC7 compression format has not yet been implemented (many versions do not support it; there are currently no plans to implement it)
15. Supports direct loading of entire folders; individual IMG files can be loaded without being nested within a WZ file
16. For IMG / XML / Node elements, first- and second-level nodes can be expanded or collapsed
17. Selecting multiple Canvas nodes allows animation playback via F5 if a Sub node is selected directly and contains Canvas nodes, playback is also possible

編輯器特點
01. 自動匹配檔案版本 針對IV對齊解析
02. 支援解析版本至 KMST 1.2.1199 (KMS 1.2.413)
03. 支援解析 .ms檔案 PKG2加密檔案
04. 個性自定義快捷鍵 / 繪製框顏色 / 錨點顏色
05. 遞迴式搜尋功能 可針對指定檔案或是全部檔案進行搜尋
06. 基於HaRepacker的分頁功能進行改進 可重新命名以及關閉無用分頁
07. 支援左右雙側開啟檔案 方便新增以及對照
08. 深淺雙色模式
09. 圖片縮放 50% ~ 1600% 不失真
10. 支援影片解析 可做做單幀 / 完整影片提取PNG或GIF
11. 支援Spine解析 可做做單幀 / 完整影片提取PNG或GIF
12. Canvas節點下若有 _outlink / _inlink節點 可以直接一鍵補圖
	可補圖條件為已開啟同源_Canvas檔案
	何謂同源_Canvas檔案? 
	若已開啟Data\Character\Weapon\Weapon_000.wz
    必須同時開啟Data\Character\Weapon\_Canvas\這個路徑下的 _Canvas_000 ~ XXX.wz 即可補回圖片
13. 支援Skill、Reactor、Mob、Morph等任何有lt rb錨點顯示 也可自訂開關
14. 支援現有版本各種PNG壓縮格式解析 也可在編輯器內直接調整壓縮格式
	其壓縮格式包含了 BGR-A4444 / BGR-A8888 / DXT3 / DXT5 / BC7
	BC7壓縮格式尚未實作(許多版本不支援 目前無實作打算)
15. 支援直接載入整個資料夾 載入單一IMG無須掛載於Z檔案下
16. 針對 IMG / XML / Node 可做一級 / 二級節點展開 收回也同理
17. 選取多個Canvas節點可做F5動畫播放 若直接選擇Sub節點 且該節點下有Canvas節點也可直接播放

---

https://github.com/user-attachments/assets/6d9aaa5d-d20c-444e-89db-1bf46204c173



https://github.com/user-attachments/assets/1817a589-ed55-470e-989a-af9d66fc5db0



https://github.com/user-attachments/assets/e8a9ea6a-becd-44c9-b424-54f71d49ddd5



https://github.com/user-attachments/assets/efe86d6b-893f-4c6e-80b7-7c40e6b70fea



https://github.com/user-attachments/assets/0c7bb285-a50a-40fe-ba0c-3c215766cf34


Please note that I have developed this software in my spare time.  
As such, it is unlikely that any issues or new features will be addressed or added immediately.  
If you have any issues, please submit them via the issues page and I will get round to dealing with them when I can.  

This software is free forever. If anyone attempts to charge you for it, they are definitely a scammer.  
If you’d like to show your support, why not buy me a coffee?  

請注意，我是利用閒暇時間開發這套軟體的。  
因此，任何問題或新功能都不太可能立即獲得處理或新增。  
若您遇到任何問題，請透過問題回報頁面提交，我將在有空時盡快處理。  

本軟體永久免費。若有人試圖向您收取費用，那絕對是詐騙。  
如果您想表達支持，何不請我喝杯咖啡呢？  
