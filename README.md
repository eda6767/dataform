# dataform


Definition folder is where we create SQL files.

For creating a view we can type :

``` config {
type : "view"
}

SELECT 'a1' as product_code,
2 as value
UNION ALL
SELECT '2' as product_code,
3 as value
UNION ALL
SELECT 'a3' as product_code,
3 as value
```
