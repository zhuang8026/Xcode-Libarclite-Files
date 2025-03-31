# Libarclite-Files

Xcode 模擬器打不開 SDK does not contain 'libarclite' at the path

ERROR : SDK does not contain 'libarclite' at the path '/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphonesimulator.a'; try increasing the minimum deployment target

1. 步驟一，打開 Finder 並且搜尋預期找到檔案的路徑
   - Finder -> 前往 -> 前往檔案夾 -> /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/
2. 檢查 arc 文件，沒有就建立 arc 文件
3. 將上述的資料全部 下載到 arc 文件中，即可
