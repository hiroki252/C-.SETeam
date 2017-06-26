## Comments in C++ ##
**Chúng ta có thể comments trên một dòng bằng cách**
	
		/* nội dung cần nghi chú */

       // Nội cung comment

**Chúng ta có thể comments một đoạn bằng cách**

    /*    
         Nội cung cần nghi chú 
			( một đoạn )

                               */


## DATE TYPEs C++ ##

**Các loại kiểu cơ bản trong c++**

![](https://www.nguyenvanquan7826.com/wp-content/uploads/2014/12/kieu.png)


**Typedef Declarations**

C++ cho phép chúng ta định nghĩa các kiểu dữ liệu của riêng mình dựa trên các kiểu dữ liệu đã có. Để có thể làm việc đó chúng ta sẽ sử dụng từ khoá typedef, dạng thức như sau:

typedef   existing_type   new_type_name ;

trong đó existing_type là một kiểu dữ liệu cơ bản hay bất kì một kiểu dữ liệu đã định nghĩa và new_type_name là tên của kiểu dữ liệu mới. Ví dụ

typedef char C;typedef unsigned int WORD;typedef char * string_t;typedef char field [50];

Trong trường hợp này chúng ta đã định nghĩa bốn kiểu dữ liệu mới: C, WORD, string_t và field kiểu char, unsigned int, char* kiểu char[50], chúng ta hoàn toàn có thể sử dụng chúng như là các kiểu dữ liệu hợp lệ:

C achar, anotherchar, *ptchar1;WORD myword;string_t ptchar2;field name;

typedef có thể hữu dụng khi bạn muốn định nghĩa một kiểu dữ liệu được dùng lặp đi lặp lại trong chương trình hoặc kiểu dữ liệu bạn muốn dùng có tên quá dài và bạn muốn nó có tên ngắn hơn.


**Enumerated Types**

Kiểu dữ liệu liệt kê dùng để tạo ra các kiểu dữ liệu chứa một cái gì đó hơi đặc biệt một chút, không phải kiểu số hay kiểu kí tự hoặc các hằng true và false. Dạng thức của nó như sau:

enum model_name {

value1 ,

value2 ,

value3 ,

.

.

} object_name ;


Ví dụ, chúng ta có thể tạo ra một kiểu dữ liệu mới có tên color để lưu trữ các màu với phần khai báo như sau:

enum colors_t {black, blue, green, cyan, red, purple, yellow, white};

Nếu chúng ta chỉ định một giá trị nguyên cho một giá trị nào đó của kiểu dữ liệu liệt kê (trong ví dụ này là phần tử đầu tiên) các giá trị tiếp theo sẽ là các giá trị nguyên tiếp theo, ví dụ:

enum months_t { january=1, february, march, april,

may, june, july, august,

september, october, november, december} y2k;

trong trường hợp này, biến y2k có kiểu dữ liệu liệt kê months_t có thể chứa một trong 12 giá trị từ january đến december và tương đương với các giá trị nguyên từ 1 đến 12, không phải 0 đến 11 vì chúng ta đã đặt january bằng 1



