###### AngularJS Là Gì ? AngularJS là một Framework được viết bằng Javascript. AngularJS không chỉ đơn giản là một thư viện mà nó còn là một framework. Khác với các thư viện Javascript như jQuery, AngularJS đưa ra hướng dẫn cụ thể hơn cách cấu trúc mã lệnh HTML và Javascript. Ví dụ bạn sẽ thấy khi sử dụng AngularJS, mã lệnh HTML thường được viết theo cấu trúc như sau:

```
 <div ng-app="">
  <p><input type="text" ng-model="name"></p>
  <p ng-bind="name"></p>
 </div>
```
 ###### Ở ví dụ trên chúng ta thấy trong một số thẻ HTML có các thuộc tính lạ với tiền tố ng- như ng-app, ng-model và ng-name. Trong AngularJS chugns được gọi là các chỉ dẫn hay directives. Các chỉ dẫn này có ý nghĩa như sau:
* Chỉ dẫn ng-app="" được dùng để giúp AngularJS đánh dấu ứng dụng sẽ được bắt đầu từ bằng nào trong HTML.
* Chỉ dẫn ng-model="name" được dùng để kết nối giá trị của trường <input> với giá trị của biến name trong ứng dụng AngularJS
* Chỉ dẫn ng-bind="name" dùng để gắn giá trị của biến name ở trên trở thành giá trị innerHTML của thẻ
