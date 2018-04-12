# Bootstrap-4-PSD-Template
Bootstrap 4 PSD Template

- Psd Sample
  - bootstrap-v4-grid-artboards
  - bootstrap-v4-grid-xl-compatible
- Comparison Chart
  - bs4-vs-bs3

- BS4 vs BS3 差異 (差異表請見 bs4-vs-bs3.xlsx)
  * BS4 取消內建 非常難用的Glyphicons ICON Font
  * BS4 的 col-12, col-sm-12 等於 BS3 的 col-xs-12
  * BS4 在 <768 的尺寸，多設定了一個尺寸區間 (576px ~ 767px), 所以BS4針對 IPHONE5處理時，是含蓋到 575px 多了細節的空間, 而BS3是只含蓋到767px
  * BS4 在最大寬度上(Max container width) 與 BS3 不同
  * BS4 全面使用 rem 作為 尺寸計算單位, Root Size(Html FontSize) 為16px, 需注意Chrome最小FontSize為12px, 若將Root Size改為10px, 在除了FontSize 的 1rem 會以12px 為 Root