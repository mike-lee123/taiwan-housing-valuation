# 全台首購｜成交、GIS與現金流

可直接部署到 Streamlit Community Cloud 的完整單檔 Python 專案。預設臺北市北投區；支援全台 22 縣市、368 個鄉鎮市區。

## 功能特色
- **實價登錄可比估值**：同路段、屋齡、坪數、樓層之多維度案例篩選與四分位距區間估值。
- **GIS 空間圖台**：內建內政部國土測繪中心 (NLSC) 正射航照影像與通用電子地圖，支援多邊形面積與距離量測。
- **Google Earth 3D 聯動**：一鍵開啟 Google Earth Web 3D 視角俯瞰街廓，並支援將成交案例動態匯出為 KML 檔案。
- **房貸與家庭現金流**：本息攤還、寬限期試算、升息壓力情境與緊急預備金缺口分析。

## 部署至 Streamlit Cloud
1. 將本資料夾推送到 GitHub 儲存庫 `main` 分支。
2. 登入 https://share.streamlit.io ，建立 App。
3. Main file path 設定為 `app.py`，自訂專屬 App URL 即可取得永久網址。
