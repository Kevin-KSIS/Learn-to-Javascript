
## Boolean

## String 

 - Dựa theo quy tắc thứ tự unicode

## So sánh khác kiểu dữ liệu

 - Giữa số và chữ: convert chữ thành số
```
 let a = 0;
 alert( Boolean(a) ); // false
 let b = "0";
 alert( Boolean(b) ); // true
 alert(a == b); // true!
```

## So sánh null và undefined

 - null === undefined; // false
 - null == undefined; // true
```
 null > 0;  // (1) false
 null == 0; // (2) false
 null >= 0; // (3) true
 ---
 undefined > 0 // false 
 undefined < 0 // false 
 undefined == 0 // false 
```
 - Không sử dụng `>= > < <=` đối với null/undefined, hoặc kiểm tra trước khi thực hiện so sánh


