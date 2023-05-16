- `box-sizing`: kích thước của box \*
  _attributes_
  content-box: độ rộng của box = width + padding + border
  border-box: độ rộng width đã bao gồm padding + border
- `padding`, margin "SHORTHAND"
  padding: top right bottom left
  padding: top right-left bottom  
   padding: top-bottom right-left
  _margin: 0 auto;_
  -> canh giữa
- `border` (viền) : border-width border-style border-color
- `text-decoration`: màu mè cho chữ \*
- `display` \*
  _attributes_
  display: inline ;
  -> biến thành thẻ inline, hạn chế các css padding, margin
  display: block;  
   -> biến thành thẻ block
  display: inline-block
  -> không bị hạn chế css
  display: flex
  -> các phần tử nằm trên 1 hàng
  _flex-direction : attribute;_
  -> cách hiển thị phần tử
  _align-items: attribute ;_
  -> stretch: các cột cao bằng nhau
- `justify-content` : canh theo chiều ngang
- `column-gap` : khoảng cách giữa các cột
- `word-break`
  _attribute_
  -> break-all: cắt chữ bất kỳ
  -> break-word: cắt chữ theo từ
- `white-space`
  _attribute_
  -> nowrap: không cho chữ xuống hàng
- `text-overflow: ellipsis` : dấu ...
- `Biến CSS`
  _Khai báo_
  :root{
  -- tên biến (English): giá trị;
  }
  _Sử dung_
  var(--tên biến)
