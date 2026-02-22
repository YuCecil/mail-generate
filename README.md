# 信件生成器

批量個人化信件草稿產生工具，支援 Excel / CSV 匯入與 Outlook 相容 HTML 輸出。

## 功能

- 貼上 Excel / Google Sheets 資料，或上傳 CSV / TSV 檔案
- 自動偵測 To / CC / BCC 欄位（支援中英文欄位名稱）
- 群組合併模式：相同鍵值的列合併為一封信，Email 以分號串接
- 富文字編輯器（粗體、斜體、清單、超連結、文字色彩等）
- 變數替換：在主旨 / 內文以 `{欄位名稱}` 自動代入每位收件人資料
  - 支援修飾語：`{姓名:姓}`（取首字）、`{Email:前}`（@ 前段）
- 所有草稿預覽
- 一鍵複製為 Outlook 相容 HTML 格式

## 技術

- 純 HTML + Vanilla JavaScript + Tailwind CSS
- 無後端，完全在瀏覽器執行，不傳送任何資料

## 使用方法

直接開啟 `mailgenerate.html`，或部署至任何靜態主機。
