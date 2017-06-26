##C++ BASIC SYNTAX  ##

Khi xem xét một chương trình C ++, nó có thể được định nghĩa như là một tập hợp các đối tượng giao tiếp thông qua việc gọi các phương thức của nhau. Bây giờ chúng ta hãy nhìn vào những gì lớp, đối tượng, phương pháp và các biến thể.

-  Object -Objects có các thuộc tính và hành vi. Ví dụ: Con chó có các thuộc tính - màu sắc, tên, giống cũng như hành vi - vẫy tay, sủa, ăn. Một đối tượng là một thể hiện của một lớp.

-  Lớp Class -A có thể được định nghĩa như một mẫu / kế hoạch chi tiết mô tả các hành vi / trạng thái mà đối tượng hỗ trợ kiểu của nó.

-  Phương pháp - Một phương pháp về cơ bản là một hành vi. Một lớp có thể chứa nhiều phương pháp. Đó là trong các phương pháp mà logics được viết, dữ liệu được thao tác và tất cả các hành động được thực hiện.

-  Các biến thể Ví dụ - Mỗi đối tượng có một tập các biến cá thể duy nhất. Trạng thái của một đối tượng được tạo ra bởi các giá trị được gán cho các biến dụ này.

## Cấu trúc một chương trình ##

Hãy để chúng tôi nhìn vào một mã đơn giản có thể in những từ Hello World .

include <iostream>
using namespace std;

// main() is where program execution begins.

int main() {

   cout << "Hello World"; // prints Hello World

   return 0;

}

 - Chúng ta hãy xem xét các phần khác nhau của chương trình trên:

- Ngôn ngữ C ++ định nghĩa một số tiêu đề, chứa thông tin cần thiết hoặc hữu ích cho chương trình của bạn. Đối với chương trình này, tiêu đề <iostream> là cần thiết.

- Dòng sử dụng không gian tên std; Nói với trình biên dịch để sử dụng không gian tên tiêu chuẩn. Không gian tên là một bổ sung tương đối gần đây cho C + +.

- Dòng tiếp theo // main () là nơi thực thi chương trình bắt đầu. Là một bình luận đơn có sẵn trong C + +. Ý kiến ​​một dòng bắt đầu bằng // và dừng lại ở cuối dòng.

- Dòng int main () là chức năng chính nơi thực hiện chương trình bắt đầu.

- Dòng kế tiếp cout << "Đây là chương trình C ++ đầu tiên của tôi"; Gây ra thông báo "Đây là chương trình C ++ đầu tiên của tôi" được hiển thị trên màn hình.

- Dòng tiếp theo trở lại 0; Chấm dứt hàm main () và làm cho nó trả lại giá trị 0 cho quá trình gọi.

## Biên dịch và thực hiện chương trình C ++ ##
Hãy xem cách lưu tệp tin, biên dịch và chạy chương trình. Hãy làm theo các bước dưới đây:

Mở trình soạn thảo văn bản và thêm mã như trên.

Lưu tập tin dưới dạng: hello.cpp

Mở dấu nhắc lệnh và đi đến thư mục nơi bạn đã lưu tệp tin.

Gõ 'g ++ hello.cpp' và nhấn Enter để biên dịch mã của bạn. Nếu không có lỗi nào trong mã lệnh của bạn, dấu nhắc lệnh sẽ đưa bạn tới dòng tiếp theo và sẽ tạo tập tin thực thi a.out.

Bây giờ, nhập 'a.out' để chạy chương trình của bạn.

Bạn sẽ có thể nhìn thấy 'Hello World' được in trên cửa sổ.

$ g++ hello.cpp
$ ./a.out
Hello World
Hãy chắc chắn rằng g ++ nằm trong đường dẫn của bạn và bạn đang chạy nó trong thư mục chứa file hello.cpp.

Bạn có thể biên dịch các chương trình C / C ++ sử dụng makefile. Để biết thêm chi tiết, bạn có thể kiểm tra Hướng dẫn Makefile .

## Semicolons & Blocks trong C ++ ##
Trong C + +, dấu chấm phẩy là một kết thúc tuyên bố. Nghĩa là, mỗi tuyên bố cá nhân phải được kết thúc với một dấu chấm phẩy. Nó chỉ ra sự kết thúc của một thực thể hợp lý.

Ví dụ, sau đây là ba câu lệnh khác nhau -

x = y;
y = y+1;
add(x, y);
Một khối là một tập hợp các câu lệnh có kết nối logic được bao quanh bởi các dấu ngoặc mở và đóng. Ví dụ:

{
   cout << "Hello World"; // prints Hello World  

   return 0;

}
C ++ không nhận ra sự kết thúc của dòng như một terminator. Vì lý do này, không có vấn đề gì ở một dòng bạn đưa một tuyên bố. Ví dụ:

x = y;
y = y+1;
add(x, y);
Cũng giống như

x = y; y = y+1; add(x, y);
## Định danh C ++ ##
Một định danh C ++ là một tên được sử dụng để xác định một biến, chức năng, lớp, mô-đun hoặc bất kỳ mục nào khác do người dùng định nghĩa. Một định danh bắt đầu với một chữ cái A đến Z hoặc a đến z hoặc một gạch dưới (_) theo sau bằng 0 hoặc nhiều chữ cái, dấu gạch dưới và chữ số (0 đến 9).

C ++ không cho phép ký tự chấm câu như @, $, và% trong các định danh. C ++ là một ngôn ngữ lập trình nhạy cảm. Do đó, nhân lực và nhân lực là hai định danh khác nhau trong C ++.

Dưới đây là một số ví dụ về các số nhận dạng có thể chấp nhận được -

mohd         zara      abc      move_name       a_123

myname50    _temp      j        a23b9             retVal

##  Trigraphs ##
Một vài ký tự có một biểu diễn thay thế, được gọi là trình tự trigraph. Một trigraph là một dãy gồm ba ký tự đại diện cho một nhân vật duy nhất và dãy đó luôn bắt đầu bằng hai dấu chấm hỏi.

Trigraphs được mở rộng bất cứ nơi nào chúng xuất hiện, bao gồm trong các chuỗi ký tự và literals ký tự, trong ý kiến, và trong các chỉ thị tiền xử lý.

Sau đây là chuỗi trình tự trigraph được sử dụng nhiều nhất -

Trigraph	Thay thế

?? =:	         #

?? /:	         \

?? '	:         ^

?? (	:         [

??)	     :         ]

??!	     :        |

?? <	 :        {

??>	      :       }

?? -      :   	~

Tất cả các trình biên dịch không hỗ trợ trigraphs và họ không nên sử dụng vì bản chất khó hiểu của họ.

Khoảng trắng trong C + +
Một dòng chỉ chứa khoảng trắng, có thể với một chú thích, được gọi là một dòng trống, và trình biên dịch C ++ hoàn toàn bỏ qua nó.

Khoảng trắng là thuật ngữ được sử dụng trong C ++ để mô tả khoảng trắng, các tab, các ký tự dòng mới và các nhận xét. Khoảng trắng chỉ ra một phần của câu lệnh từ trình biên dịch khác và cho phép trình biên dịch xác định vị trí một phần tử trong một câu lệnh, chẳng hạn như int, kết thúc và phần tử tiếp theo bắt đầu. Vì vậy, trong tuyên bố,

int age;
Phải có ít nhất một ký tự khoảng trắng (thường khoảng trống) giữa int và độ tuổi của trình biên dịch để có thể phân biệt chúng. Mặt khác, trong tuyên bố

fruit = apples + oranges;   // Get the total fruit
Không có ký tự khoảng trắng là cần thiết giữa trái cây và = hoặc giữa = và táo, mặc dù bạn được tự do đưa vào một số nếu bạn muốn cho mục đích dễ đọc.


