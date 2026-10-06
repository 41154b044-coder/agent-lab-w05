# 社團檔案整理報告 (01-club-files Report)

## 1. 整理摘要與分類說明
本次共整理 input/ 目錄下的 12 個文字檔案，依檔案性質歸納為 4 個分類資料夾，原始檔案皆完整保留未受任何修改。

- **01-proposals/（活動企劃與備案）**
  - proposal_final.txt：企劃第 1 版（戶外活動，時長 30 分鐘）。
  - proposal_final2.txt：企劃第 2 版（室內活動備案，時長 20 分鐘）。
  - ain_plan.txt：雨天備案原則（若遇雨則討論室內替代方案）。
  - 
ext_steps.txt：後續決策指示（需比較兩版提案，勿預設任一版已核准）。

- **02-announcements/（活動公告與文宣）**
  - nnouncement.txt：活動公告初稿（提醒攜帶筆記本，時間地點待定）。
  - nnouncement_copy.txt：活動公告副本（與 nnouncement.txt 內容完全相同）。
  - poster_text.txt：宣傳海報短標語。

- **03-logistics/（器材與預算）**
  - quipment_list.txt：所需器材清單（麥克筆 4 支、紙張 2 包）。
  - quipment_backup.txt：器材備份清單（與 quipment_list.txt 內容完全相同）。
  - udget_draft.txt：預估耗材預算草案（非正式核准開銷）。

- **04-meetings/（會議記錄與問卷回饋）**
  - meeting_notes.txt：會議決議（記錄下次會議決定室內或室外）。
  - eedback_questions.txt：活動滿意度回饋問卷題目草案。

---

## 2. 內容完全相同之檔案（已保留獨立副本）
透過 SHA256 雜湊值計算，以下兩組檔案內容完全相同：
1. nnouncement.txt 與 nnouncement_copy.txt
   - SHA256: c19164b1054ebf52236894c256070a7b51ea1ae767664ee65e52c8038efeb565
2. quipment_list.txt 與 quipment_backup.txt
   - SHA256: c21d53ba1f8d3ad0a1b65b6f38ef2f1cb75f0a454d6fa5c2c78f1ae95f32a773

> **處置**：遵循實習規範，兩者皆為個別檔案並分別保留在 output/ 中，不進行刪除或覆蓋。

---

## 3. 檔名相近但內容不同之版本
- proposal_final.txt：內容為 **Proposal v1: outdoor activity, 30 minutes.**
- proposal_final2.txt：內容為 **Proposal v2: indoor activity, 20 minutes.**

> **處置**：雖然檔名帶有 inal 與 inal2，但文字內容為截然不同的方案（戶外 vs 室內）。兩者均完整保留，避免因檔名誤判而遺失企劃備案。

---

## 4. 待確認與需人工作業之問題 (Issues for Human Review)
1. **正式定稿版本**：proposal_final.txt 與 proposal_final2.txt 尚未正式由幹部決議核定，需於下次會議比對決定。
2. **時間與地點**：nnouncement.txt 內之時間與地點仍標註為未定（undecided），正式發布前需補齊資訊。
3. **預算審核**：udget_draft.txt 載明為暫定提案（not an approved expense），須送交社團總務核准。
4. **冗餘備份清理**：nnouncement_copy.txt 與 quipment_backup.txt 確認為完全一致之副本，未來確認毋須多版本時可由人工決定是否清理。

---

## 5. 實際驗證紀錄
- [x] **原始檔案完整性**：比對 input/ 內 12 個檔案數量及雜湊值，無任何異動、刪除或覆蓋。
- [x] **副本產出數量**：output/ 下 4 個分類資料夾內共有 12 個檔案，一一對應原始檔案。
- [x] **內容一致性**：抽樣比對來源檔與目的檔內容完全一致。
- [x] **清單完整性**：產出 manifest.json，精確記錄 12 筆來源相對路徑、目標相對路徑與分類理由。
- [ ] **未確認部分**：各文件內容之業務合理性與正式核定狀況屬於社團行政判斷，需由幹部進行人工審查確認。