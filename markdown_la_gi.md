#Markdown Là Gì

<a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a> là ngôn ngữ đánh dấu văn bản được tạo ra bởi John Gruber. Markdown sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản và văn bản được viết bằng **Markdown** sẽ có thể được chuyển đổi sang HTML. Ngược lại các văn bản được viết bằng HTML cũng có thể được chuyển đổi sang Markdown.

Trong bài viết này chúng ta sẽ tìm hiểu tại sao cần sử dụng <a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a> và sử dụng nó như thế nào.

## Tại Sao Cần Dùng Markdown
Sự phổ biến của HTML khiến ngôn ngữ đánh dấu này được sử dụng rộng rãi trong các ứng dụng sử dụng internet từ các trang web tới nội dung email hay rất nhiều các tài liệu hướng dẫn online cũng đều sử dụng ngôn ngữ này. Tuy nhiên một vấn đề gặp phải của HML đó là cú pháp của ngôn ngữ này không được thân thiện lắm với người dùng. Ví dụ khi chúng ta có 1 đoạn văn bản HTML gồm 1 tiêu đề và 3 đoạn văn thì mã lệnh trông sẽ giống như sau:

    <h1>Tiêu Đề</h1>
    <p>Đoạn văn thứ nhất</p>
    <p>Đoạn văn thứ 2</p>
    <p>Đoạn văn thứ 3</p>

Nếu như không có kiến thức về ngôn ngữ HTML thì bạn rất khó có thể đọc được nôi dung của đoạn văn bản trên. Và ngay cả khi bạn đã hiểu về HTML thì đoạn mã trên vẫn gây rối mắt.

Markdown giải quyết vấn đề trên bằng việc đưa ra cú pháp để giúp đánh dấu văn bản một cách dễ hiểu và ngắn gọn hơn. Vẫn như ví dụ trên nhưng sử dụng Markdown thì kết quả sẽ như sau:


    ## Tiêu Đề
    Đoạn văn thứ 3

    Đoạn văn thứ 2
    
    Đoạn văn thứ 3

Rõ ràng bạn thấy được cách viết thứ 2 ngắn gọn và dễ hiểu hơn rất nhiều so với cách viết đầu tiên dùng HTML.

## Sử Dụng Markdown
Phần này chúng ta sẽ  tìm hiểu một số cú pháp phổ biến được sử dụng trong <a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a>.

Để đánh dấu các thẻ *heading* bằng ngôn ngữ Markdown chúng ta sẽ sử dụng ký tự **#**. Thẻ `<h1>` sử dụng một dấu **#** các thẻ `<h2>`, `<h3>`... sẽ sử dụng lần lượt 2, 3 cho tới 6 dấu **#**. Ví dụ đoạn mã HTML như sau:

```html
<h3>Thẻ H3</h3>
```

Khi viết bằng ngôn ngữ Markdown sẽ như sau:

    ### Thẻ H3

Để đánh dấu văn bản với thẻ in đậm `<strong>` và in nghiêng `<em>` trong HTML, khi chuyển sang <a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a> chúng ta sử dụng lần lượt cặp dấu **** **** và cặp dấu ****. Ví dụ đoạn mã HTML sau:

```html
Chữ <strong>in đậm</strong> và chữ <em>in nghiêng</em>
```

Sẽ tương đương với:

    Chữ **in đậm** và chữ *in nghiêng*

Để dánh dấu 1 danh sách không có thứ tự (unorder list) chúng ta sử dụng dấu **-** hoặc **+** hoặc ***** trước mỗi dòng. Ví dụ một danh sách trong HTML như sau:

```html
<ul>
<li>Xe đạp</li>
<li>Xe hơi</li>
<li>Xe gắn máy</li>
</ul>
```

Sẽ tương đương với:

    - Xe đạp
    - Xe hơi
    - Xe gắn máy


Để đánh dấu một danh sách có thứ tự bạn sử dụng các số thay vì các dấu như ở trên. Ví dụ như sau:


    1. Xe đạp
    2. Xe hơi
    3. Xe gắn máy

Để đánh dấu hình ảnh dúng ta sử dụng cú pháp như ở dưới đây:

    ![Học Lập Trình Online](http://hoclaptrinh.org/logo.png)

Trong đó phần văn bản đặt trong cặp dấu *[]* được dùng tương đương với giá tị của thuộc tính *alt* trong thẻ `<img>` còn địa chỉ liên kết được đặt trong cặp dấu *()* được dùng tương đương với giá trị của thuộc tính *src* trong thẻ `<img>`.

Để đánh dấu một liên kết chúng ta sử dụng cú pháp như sau:

    [Học Lập Trình Online](http://hoclaptrinh.org)

Gần tương tự như khi đánh dấu hình ảnh, với cách đánh dấu sử dụng ngôn ngữ <a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a> như trên thì đoạn văn bản bên trong *[]* sẽ tương đương với giá trị của thuộc tính *title* trong thẻ `<a>` và liên kết đặ trong *()* sẽ tương đương với giá trị thuộc tính *href* trong thẻ `<a>`.

Tới đây chúng ta đã kết thúc việc tìm hiểu về cách sử dụng ngôn ngữ <a href="http://www.hoclaptrinh.org/bai-viet/Markdown-La-Gi" title="Markdown Là Gì">Markdown</a> để đánh dấu văn bản.
