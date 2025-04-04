## 深入資訊
`List.Transpose` 會將清單的清單中的列和欄交換。例如，一個包含 5 個子清單 (每個子清單有 10 個項目) 的清單，將被轉換為 10 個清單，每個清單有 5 個項目。此節點會視需要插入空值，確保每個子清單都有相同的項目數。

在此範例中，我們產生一個從 0 到 5 的數字清單和另一個從 A 到 E 的字母清單，然後使用 `List.Create` 將兩者合併。`List.Transpose` 會產生 6 個清單，每個清單有 2 個項目: 1 個數字和 1 個字母。請注意，由於其中一個原始清單比另一個長，因此 `List.Transpose` 為不成對的項目插入了空值。
___
## 範例檔案

![List.Transpose](./DSCore.List.Transpose_img.jpg)
