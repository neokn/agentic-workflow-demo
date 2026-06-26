---

on:                        # 觸發時機：開新 issue 時

  issues:

    types: [opened]

 

permissions: read-all      # 預設唯讀（安全）

 

safe-outputs:              # 允許的寫入動作（受控）

  add-comment:

---

 

# Issue 釐清小幫手

 

分析目前這個 issue，如果描述不夠清楚就友善地詢問需要補充的細節。


