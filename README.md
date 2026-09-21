# NTU 微型調度路線圖

臺大校園 YouBike 微型調度路線規劃工具。

## 使用方式

直接以瀏覽器開啟 `index.html` 即可使用。地圖支援：

- 檢視臺大校園與長興街宿舍區四站（男七、男一、男六、基隆長興路口東側）
- 顯示既有微型調度路線
- 新增、編輯與刪除自訂路線
- 以瀏覽器 `localStorage` 保留自訂路線

## 外部服務

頁面透過網路載入 Leaflet、Leaflet PolylineDecorator 與 OpenStreetMap 圖磚，因此完整地圖功能需要網路連線。

## 檔案

- `index.html`：完整單頁應用程式，包含樣式、站點資料、預設路線與互動邏輯。

