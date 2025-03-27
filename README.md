# 台灣農產品出口與生產量歷史統計
- 使用關聯圖(concept map)、泡泡圖(bubble chart)、堆疊折線圖(stacked area chart)呈現台灣歷年農產品出口與生產量
- 使用 D3.js 製作上述圖表

# 任務目標：
在不同年度區間：
- 台灣主要外銷水果的外銷國家有哪些(關聯圖)
- 台灣主要外銷水果生產概況(泡泡圖)
- 台灣主要外銷水果量(堆疊折線圖)

# Demo
https://107306010.github.io/Taiwan-Fruits-Data-Visualization/

# 使用說明
1. 可先透過時間滑桿，選擇感興趣的年度區間範圍
2. 利用水果與進口國間的關聯圖，選擇想知道水果，進而顯示該水果外貿情況
3. 在確定關注年份、水果後，即可操作泡泡圖獲取該水果在台各縣市不同年份實際的產量狀況
4. 也可透過出口累積圖，清楚理解各國在年對台的採購狀況，以理解各國對台的影響程度

# 圖表說明
- 關聯圖

  利用文字描述國家，將這些國家標籤圍繞成圓的想法來構思，並運用關聯圖的方式，將水果與國家間的關係串連起來，使用者可透過點選圖中央的水果列表，深化與加粗文字與連結線條，來顯示該水果與出口國間的關係。也為了讓使用者更清楚國家的粗略地理位置，也以洲為單位，使用顏色進行區隔。
- 泡泡圖

  此圖表提供不同年度的台灣各地區特定水果生產總量，可透過上方時間軸進行年度篩選，bubble半徑、顏色與實際產量用線性關係呈現，礙於畫面限制，有些時間bubble可能會在畫面之外，圖表有設計拖拉功能，點擊bubble外的地方即可進行拖拉。透過滑鼠hover至任一年度bubble後內部將會顯示各縣市bubble，並透過tooltip呈現實際產量，此外，可以點選各年度bubble會有zoom-in特效，以便更清楚查看詳細資訊，接著可以繼續點擊下一個bubble或是點擊外面zoom-out。年度的bubble亦可拖拉，加入些許互動性。
- 堆疊折線圖

  此圖目的是為了方便使用者在不同屬性間比較，從中發現台灣對特定國家出口量佔整體出口的趨勢變化，又因各國銷量加總可呈現水果整體出口變化，也希望這張圖表可以擁有觀察整體的功能。選擇水果和年度區間後，圖表直觀地呈現出各年度的銷量，並用顏色區隔不同國家。當滑鼠移到圖表上時，會出現當年度各國實際銷量的數字，方便使用者在資料數字較小時比較。滑鼠移到右邊國家的標籤上時，圖表會凸顯此國家的區塊，可以快速查找不同國家的銷量變化。（因為版面配置，將不呈現出口量過少的國家）
