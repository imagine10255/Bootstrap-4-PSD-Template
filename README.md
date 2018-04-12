# Bootstrap-4-PSD-Template
Bootstrap 4 PSD Template

## Psd Sample
- [bootstrap-v4-grid-artboards.psd](https://github.com/imagine10255/Bootstrap-4-PSD-Template/raw/master/bootstrap-v4-grid-artboards.psd)
- [bootstrap-v4-grid-xl-compatible](https://github.com/imagine10255/Bootstrap-4-PSD-Template/raw/master/bootstrap-v4-grid-xl-compatible.psd)

## Comparison Chart
- [bs4-vs-bs3.xlsx](https://github.com/imagine10255/Bootstrap-4-PSD-Template/raw/master/bs4-vs-bs3.xlsx) (差異表)
  * BS4 取消內建 非常難用的Glyphicons ICON Font
  * BS4 的 col-12, col-sm-12 等於 BS3 的 col-xs-12
  * BS4 在 <768 的尺寸，多設定了一個尺寸區間 (576px ~ 767px), 所以BS4針對 IPHONE5處理時，是含蓋到 575px 多了細節的空間, 而BS3是只含蓋到767px
  * BS4 在最大寬度上(Max container width) 與 BS3 不同
  * BS4 全面使用 rem 作為 尺寸計算單位, Root Size(Html FontSize) 為16px, 需注意Chrome最小FontSize為12px, 若將Root Size改為10px, 在除了FontSize 的 1rem 會以12px 為 Root


## Comarison 開發時注意
```javascript
// BS4 map BS3
$grid-breakpoints: (
  xs: 0,     // (0~575)    map bs3 size: 320,480
  sm: 576px, // (576~767)  map bs3 size: (如果想要補上576~767的細節作為480的替代，
             //                           但我們不改 sm 的 Grid 判定寬度)
  md: 768px, // (768~991)  map bs3 size: 750
  lg: 992px, // (992~1200) map bs3 size: 970
  xl: 1200px // (1200以上)  map bs3 size: 1170
)
```
