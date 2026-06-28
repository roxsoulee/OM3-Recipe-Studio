# [分享] OM-3 Recipe Studio：Recipe JPG / OES 手動配方工具公開測試

Release URL:
https://github.com/roxsoulee/OM3-Recipe-Studio/releases/tag/v0.9-public-beta

Internal build: v1.11.3l_ExportOESDialogEncodingFix

SHA256: B2312BE63651A46E938B9311886E3329FAF0B9B8D52AA6B301B56980609D8A43

本版補上 OES 匯出的重新命名流程，並修正 OES 匯出視窗中文亂碼。

本版已統一程式內各彈出視窗的圖示。

這是一個獨立製作的 Windows 工具，目標是幫 OM SYSTEM OM-3 使用者整理、測試與交換手動 recipe。它不是 OM SYSTEM / OM Digital Solutions / Olympus / OM Workspace 官方工具。

主要功能：

- 以 OM SYSTEM OM-3 為基準測試。
- 支援 Color / Mono recipe 編輯。
- 支援讀取 Recipe JPG 並回填參數。
- 支援匯出 Recipe JPG。
- 支援匯入 / 匯出 OM Workspace `.oes` recipe。
- 可載入預覽影像，做 Before / After / Compare 參考。
- 可顯示 JPG / OES 內的 WB 資訊，但 WB 請在相機上手動設定。
- 可設定輸出資料夾。
- Windows onefile EXE，免安裝。

注意事項：

- 目前只以 OM-3 測試，其他 OM SYSTEM / Olympus 機型不保證適用。
- Preview 是近似參考，最後顏色仍可能和相機拍攝或 OM Workspace 輸出不同。
- EXE 未簽章，Windows SmartScreen 可能跳警告。
- 歡迎 OM-3 使用者回報 bug、無法讀取的 recipe、OES 匯入差異或 UI 問題。
