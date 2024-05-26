# Company-Track
12/05/2024
- Branch.csv hapus duplicate, whitespace, tanda ; dan placeholder/test branch. 
Total 390 rows x 2 columns.

- Item.csv hapus whitespace dan test item. 
Total 16844 rows x 3 columns.

- Stock.csv hapus whitespace dan tanda seperti "; . 
Total 55231 rows x 3 columns.

- Order.csv hapus whitespace dan tanda "; 
Mengganti format kolom POSDate dan POSDateTime menjadi datetype64. 
Total 2500495 rows x 9 columns.

- OrderItem.csv hapus whitespace.
Mengganti nilai missing value pada kolom Discount menjadi 0.
Merubah ,(koma) menjadi .(titik) pada kolom COGS, Price, TaxAmount, Discount, Subtotal dan merubah format kolom-kolom tersebut menjadi float64.
Total 4,687,643 rows x 10 columns.

14/05/2024
- OrderItem.csv membulatkan koma di kolom COGS, Price, TaxAmount, Discount, Subtotal dan merubahnya menjadi dtype int64.
Total 4,687,643 rows x 10 columns.

22/05/2024
Changed column names for consistency:
- Order.csv: “BranchId” to “BranchID”
- Branch.csv: “BranchId” to “BranchID”
- Item.csv: “ItemId” to “ItemID”
