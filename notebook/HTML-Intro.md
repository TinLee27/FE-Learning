# Cấu trúc file HTML 
![alt](../images/cau%20truc%20html.jpg)

# Comment trong HTML 

- Làm sao để comment trong html
   
   -  <p class=ggg> Ctrl + / </p>
# Các thẻ HTML thông dụng
- <h class="the">h</h> dùng để ghi tiêu đề ( Từ h1 đến h6 cỡ chữ sẽ giảm dần )
- <h class="the">p</h> để ghi nội dung 
- <h class="the">img</h> để chèn hình ảnh 
- <h class="the">a</h> để chứa đường link
- <h class="the">ul,li</h> để ghi danh sách
- <h class="the">ol</h> cũng như ul nhưng có đánh số thứ tự
- <h class="the">table</h> để làm bản
- <h class="the">input</h> để tạo ô nhập dữ liệu
- <h class="the">button</h> để tạo nút
- <h class="the">div</h> để tạo nhóm
# Attribute trong HTML 
- <p class="ggg"> Attribute </p> là thuộc tính của thẻ được ghi ở trong thẻ mở 
<style>
   .the{
      color:yellow
   }
   .ggg{color:red
   }
   </style>
# <span style="text-decoration:underline"> Các thuộc tính thường gặp  </span>  
-  Thuộc tính <h class="att"> `href` </h> của thẻ a để chứa địa chỉ link trong thẻ a mà thẻ a dẫn tới 
-  Thuộc tính <h class="att"> `title` </h> là tiêu đề của nội dung (và ảnh)
-  Thuộc tính <h class="att"> `alt` </h> để hiển thị tiêu đề của ảnh khi ảnh không load được
<style>
   .att{
      color: blue;
   }
</style>
# Thực hành sử dụng CSS 
- Độ ưu tiên trong CSS 
  -   Inline=1000
  -   #id=100
  -   .class=10
  -   tag=1  

# Sử dụng biến trong CSS 
   
      :root{
         --tên biến:giá trị
      }

<span style="text-decoration:underline"> EX: </span>
      
:root {

   --Tindeeptry:color

}  
# Các đơn vị trong CSS (CSS Units)
- px
- %
- rem,em
- vh,vw
# Các hàm trong CSS 
- var là hàm sử dụng biến
 
 <span style="text-decoration:underline">Ex:</span>
    


     h1 {
  
        color: var(--color)

      } 

     p {
      
       color: var(--heading-color)
   
      }
- rgb (red,green,blue) là hàm chỉnh mã màu, rgba (alpha) cũng như rgb nhưng có thể chỉnh độ trong suốt
 
    
<span style="text-decoration:underline">Ex:</span>

    .box {

        color: rgb(0,100,255)

    }

    
    
    .box2 {
    
        bachkground-color:rgba(200,125,255,0.75)
    
    } 
 


