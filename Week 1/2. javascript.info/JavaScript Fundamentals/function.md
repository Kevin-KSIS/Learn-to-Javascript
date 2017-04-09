
 ```
	// function declaration
	// Khi gọi thì không gian địa chỉ mới dc sử dụng
	function showMessage() {
		return;
	}

	function showMessage(a, b) {
		let localVar;
		globalVar = '';
		a = a || 1;
		b = b || 2;
		return;
	}

	// function expression
	// Khởi tạo không gian khi vừa khai báo
	let getVar = function();

	// arrow function
	let welcome = () => true;
	let welcome = a => a*2;
	let welcome = (a, b) => a + b;

	//multiline
	let sum = (a, b) => {  // the figure bracket opens a multiline function
	let result = a + b;
	return result; // if we use figure brackets, must use return
	};
	alert( sum(1, 2) ); // 3
 ```

## Đặt tên

 - Bắt đầu bằng động từ viết thường
 - Sau đó là danh từ miêu tả chức năng của function viết hoa

## Tricks

 - Tên hàm cũng như 1 biến, có thể gán cho biết khác

 ```
	b = function(){}
	let a = b;
	//execute function
	a();
 ```

 - Tên hàm nếu như được gọi ra không có `()` thì nó đại diện cho code hàm đó, tức trả về code 
