# Testmycode-01
test4jen

## 💡 如何在 VS Code Web 維護這份筆記？

1.  **勾選清單**：當你完成一個目標，把 `[ ]` 改成 `[x]`，預覽畫面就會出現漂亮的勾選符號。
2.  **增加日期**：每次練習完，在「實作細節紀錄」下增加一個新的 `###` 日期標題。
3.  **雲端存檔**：
    * 如果你在 `github.dev` (按 `.` 進來的)：按左側的 **Source Control** 圖示，點擊 **Commit & Push**。
    * 如果你在 `vscode.dev` (本地掛載)：直接按 <kbd>Ctrl</kbd> + <kbd>S</kbd> 即可儲存到雲端硬碟。

這份範本讓你滿意嗎？如果有任何想增加的區塊（例如想放硬體電路圖的欄位），隨時跟我說！

# 🚧 CK369 開發練習進度表 (In Progress)

> **最後更新日期：** 2015-12-19  
> **目前階段：** 基礎環境配置與權限修復

---

## 📊 學習路徑追蹤
| 階段 | 練習目標 | 狀態 | 關鍵指令 / 筆記 |
| :--- | :--- | :---: | :--- |
| **Step 1** | **Git 全域設定與身分確認** | ✅ | `git config --global` |
| **Step 2** | **Linux 家目錄權限修正** | ✅ | `sudo chown -R` |
| **Step 3** | **準備交叉編譯環境 (Toolchain)** | ⏳ | 預計下載 Rockchip SDK |
| **Step 4** | **Hello World 驅動開發** | 📅 | 待定 |

---

## 📝 實作細節紀錄

### 🛠️ 1. Git 基礎設定
為了能在 CK369 的 Linux 系統中順利 Commit 程式碼，需先設定開發者身分：

```bash
# 設定使用者名稱
git config --global user.name "Allen"

# 設定使用者信箱
git config --global user.email "Allena@mtkic.com"
