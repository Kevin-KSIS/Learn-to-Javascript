
## Thẻ source
![sourcepane]('./pic/source.png')

- `Resource zone`: cây thư mục
- `Source zone`: chi tiết source
- `Information`: để debug

## Thẻ console
![console]('./pic/console.png')

## Breakpoints
![breakpoint]('./pic/breakpoint.png')

- Click phải chọn `Edit breakpoint` tạo điều kiện, câu lệnh sẽ dừng lại nếu điều kiện `true`
- Có thể đặt breakpoint trong code bằng command `debugger;`

## Debugger
- *Watch*: xem giá trị của bất kì biểu thức nào
- *Call stask*: hiển thị các function lồng nhau
- *Scope*: giá trị các biến gồm local và global

## Tracing
- Continue execution (F8): bỏ qua breakpoint
- Run next command (F10): chạy lệnh tiếp theo
- Make the step - stepinto (F11): nhảy vào hàm con
- Shift + F11: tiếp tục chạy đến hết function hiện tại
- Enable/disable all breakpoints.
- Enable/disable automatic pause in case of an error
- Continue to here
