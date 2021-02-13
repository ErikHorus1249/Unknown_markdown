**Định dạng tài nguyên thống nhất** (**URI**-Uniform Resource Identifier) là một chuỗi ký tự được sử dụng để xác định, nhận dạng một tên hoặc một tài nguyên. Việc xác định như vậy cho phép tương tác với các thể hiện tài nguyên trên mạng(thường là **World Wide Web**) sử dụng các giao thức cụ thể. Lược đồ chỉ định một cú pháp chuẩn và các giao thức liên quan để xác định mỗi URI.

URI xác định việc nhận dạng cho tài nguyên trên mạng qua tên bằng URN, hay là qua địa chỉ bằng **URL** hay là cả hai.

## Cấu trúc

Theo tiêu chuẩn hiện hành [RFC 3986](https://tools.ietf.org/html/rfc3986) một URI được cấu tạo từ 5 phần: `scheme` (Sự xếp đặt), `authority` (nhà cung cấp), `path` (đường dẫn), `query` (truy vấn) và `fragment` (phân mảnh), trong đó chỉ có `scheme` và `path` là bắt buộc phải có trong mỗi URI: Cú pháp chung chung là

URI = scheme ":" hier-part [ "?" query ] [ "#" fragment ]

(URI = đề án ":" phần ở đây [ "?" truy vấn ] [ "#" phân mảnh ]))

Theo đó `hier-part` là cho một `authority` tùy chọn và `path`. Nếu có `authority`, nó bắt đầu với hai dấu gạch chéo, và đường dẫn phải bắt đầu với một dấu gạch chéo. Tiêu chuẩn làm rõ các thành phần này với hai ví dụ:

  foo://example.com:8042/over/there?name=ferret#nose
  \_/   \______________/\_________/ \_________/ \__/
   |           |            |            |        |
scheme     authority       path        query   fragment
   |   _____________________|__
  / \ /                        \
  urn:example:animal:ferret:nose
![](https://i.imgur.com/QZuTJxv.png)
## Mối quan hệ giữa URL và URN

**URI** có thể được phân loại như là nhận dạng ([URL](https://vi.wikipedia.org/wiki/URL "URL")), như tên gọi ([URN](https://vi.wikipedia.org/wiki/URN "URN")), hoặc là cả hai. Một [Định danh tài nguyên thống nhất](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%8Bnh_danh_t%C3%A0i_nguy%C3%AAn_th%E1%BB%91ng_nh%E1%BA%A5t "Định danh tài nguyên thống nhất") ([Uniform Resource Name](https://vi.wikipedia.org/wiki/Uniform_Resource_Name "Uniform Resource Name") - [URN](https://vi.wikipedia.org/wiki/URN "URN")) có chức năng giống như [tên](https://vi.wikipedia.org/wiki/T%C3%AAn "Tên") của một người, trong khi một [định vị tài nguyên thống nhất](https://vi.wikipedia.org/wiki/URL "URL") ([Uniform Resource Locator](https://vi.wikipedia.org/wiki/URL "URL") - [URL](https://vi.wikipedia.org/wiki/URL "URL")) tương tự như [địa chỉ](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%8Ba_ch%E1%BB%89 "Địa chỉ") đường phố của người đó. Nói cách khác: URI xác định việc nhận dạng cho [đối tượng](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%91i_t%C6%B0%E1%BB%A3ng "Đối tượng") qua tên bằng URN, hay là qua địa chỉ bằng URL.

Hệ thống mã số [ISBN](https://vi.wikipedia.org/wiki/ISBN "ISBN") sử dụng để nhận dạng sách cung cấp 1 ví dụ rất cụ thể về [URN](https://vi.wikipedia.org/wiki/URN "URN"). Chỉ số [ISBN](https://vi.wikipedia.org/wiki/ISBN "ISBN") **0486275574 (urn:isbn:0-486-27557-4)** cho biết đây là một ấn bản truyện kịch [Romeo và Juliet](https://vi.wikipedia.org/wiki/Romeo_v%C3%A0_Juliet "Romeo và Juliet") của [Shakespeare](https://vi.wikipedia.org/wiki/William_Shakespeare "William Shakespeare"). Để tìm cuốn sách này, phải cần địa chỉ cuốn sách đó chính là địa chỉ [URL](https://vi.wikipedia.org/wiki/URL "URL"). Đường dẫn địa chỉ [URL](https://vi.wikipedia.org/wiki/URL "URL") của cuốn sách trên hệ thống [Unix](https://vi.wikipedia.org/wiki/Unix "Unix") sẽ có địa chỉ như là: file:///home/username/RomeoAndJuliet.pdf, đây là đường dẫn [tập tin](https://vi.wikipedia.org/wiki/T%E1%BA%ADp_tin "Tập tin") được lưu trên [ổ cứng](https://vi.wikipedia.org/wiki/%E1%BB%94_%C4%91%C4%A9a_c%E1%BB%A9ng "Ổ đĩa cứng") [máy tính](https://vi.wikipedia.org/wiki/M%C3%A1y_t%C3%ADnh "Máy tính"). Vì vậy [URN](https://vi.wikipedia.org/wiki/URN "URN") và [URL](https://vi.wikipedia.org/wiki/URL "URL") luôn có mục đích hỗ trợ & bổ sung cho nhau.

**Reference** 
- [Wikipedia](https://en.wikipedia.org/wiki/Uniform_Resource_Identifier)

