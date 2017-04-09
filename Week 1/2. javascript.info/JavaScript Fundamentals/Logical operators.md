
## || OR 
 
 ```
	alert( true || true );   // true
	alert( false || true );  // true
	alert( true || false );  // true
	alert( false || false ); // false
 ```

`result = value1 || value2 || value3;`

 - Xem xét từ trái sang phải
 - Nếu gặp true thì dừng lại và trả về giá trị đó
 - Nếu không sẽ trả về giá trị cuối cùng

## && AND

 ```
	alert( true && true );   // true
	alert( false && true );  // false
	alert( true && false );  // false
	alert( false && false ); // false
 ```
`result = value1 && value2 && value3;`
 - Xem xét từ trái sang phải
 - Chuyển đổi phần tử sang boolean, nếu phần tử là không phải true, dừng và trả lại giá trị đó
 - Nếu không sẽ trả về giá trị cuối cùng

> And được ưu tiên cao hơn Or

## Câu lệnh điều kiện với and
 
 - (x > 0) && alert( 'Greater than zero!' );

## ! NOT

`result = !value;`
 - Chuyển giá trị sang boolean
 - phủ định nó

`result = !!value;`
 - Kiểm tra sự tồn tại của 1 biến`p