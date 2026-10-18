# DHAs-Website-B-n-h-ng
AI Agent chăm sóc khách hàng
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>DHAs Nguyễn Kiệm - Điện tử chính hãng</title>
<style>
  body {
    margin: 0; font-family: Arial, sans-serif;
    background-color: #000; /* đen */
    color: #fff; /* trắng */
  }
  header {
    background: linear-gradient(90deg, #FFD700, #228B22, #0000FF, #800080, #FF0000, #FFC0CB, #FFA500);
    padding: 15px 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  .logo {
    font-weight: bold;
    font-size: 24px;
    color: #fff;
  }
  .commitment {
    font-style: italic;
    margin-left: 20px;
    flex-grow: 1;
    color: #fff;
  }
  .header-right {
    display: flex;
    align-items: center;
    gap: 20px;
  }
  .cart, .account, .warranty {
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 5px;
    color: #fff;
  }
  .cart-icon {
    width: 24px; height: 24px;
    background: url('https://cdn-icons-png.flaticon.com/512/1170/1170678.png') no-repeat center/contain;
  }
  main {
    padding: 20px;
    background: #111;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 25px;
  }
  th, td {
    border: 1px solid #555;
    padding: 12px;
    text-align: left;
  }
  th {
    background: #222;
  }
  tbody tr:nth-child(odd) {
    background: #1a1a1a;
  }
  section.warranty-info {
    background: #222;
    padding: 15px;
    border-radius: 8px;
    line-height: 1.5;
    font-size: 14px;
  }
  footer {
    background: #111;
    color: #ccc;
    padding: 20px;
    font-size: 14px;
    text-align: center;
  }
  footer div {
    margin: 5px 0;
  }
  a {
    color: #FFA500;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  @media (max-width: 600px) {
    header {
      flex-direction: column;
      align-items: flex-start;
    }
    .commitment {
      margin: 10px 0;
    }
    .header-right {
      width: 100%;
      justify-content: space-between;
    }
  }
</style>
</head>
<body>

<header>
  <div class="logo">DHAs Nguyễn Kiệm</div>
  <div class="commitment">Điện tử chính hãng - Giá tốt Nguyễn Kiệm</div>
  <div class="header-right">
    <div class="cart" title="Giỏ hàng">
      <div class="cart-icon"></div>
      <div>3 sản phẩm - 185 triệu ₫</div>
    </div>
    <div class="account" title="Tài khoản (Đăng nhập/Đăng ký)">
      Đăng nhập / Đăng ký
    </div>
    <div class="warranty" title="Tra cứu bảo hành">
      Tra cứu bảo hành
    </div>
  </div>
</header>

<main>
  <table>
    <thead>
      <tr>
        <th>Sản phẩm</th>
        <th>Giá</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Iphone 18 Pro Max</td><td>70 triệu đồng</td></tr>
      <tr><td>Máy tính MacBook</td><td>105 triệu đồng</td></tr>
      <tr><td>Con chuột</td><td>5 triệu đồng</td></tr>
      <tr><td>Tai Nghe</td><td>3 triệu đồng</td></tr>
      <tr><td>Ipad</td><td>20 triệu đồng</td></tr>
      <tr><td>Cục dự phòng</td><td>3 triệu đồng</td></tr>
      <tr><td>Tivi</td><td>78 triệu đồng</td></tr>
      <tr><td>Cục sạc bluetooth</td><td>7 triệu đồng</td></tr>
    </tbody>
  </table>

  <section class="warranty-info">
    <h3>Thông tin bảo hành</h3>
    <h4>1. Chính sách Đổi trả (Hoàn tiền) – "An tâm dùng thử"</h4>
    <p>Để khách hàng hoàn toàn yên tâm về chất lượng sản phẩm, DHAs Nguyễn Kiệm:</p>
    <ul>
      <li>7 ngày đầu tiên (Lõi phần cứng từ nhà sản xuất): Đổi ngay máy mới cùng model (hoặc cùng giá trị) miễn phí. Nếu khách muốn hoàn tiền, cửa hàng hoàn trả 100% giá trị hóa đơn.</li>
      <li>Từ ngày thứ 8 đến ngày thứ 30: Nếu máy lỗi phần cứng, hỗ trợ đổi máy tương đương. Nếu trả máy/hoàn tiền, thu phí 15% - 20% tùy tình trạng hao mòn.</li>
      <li>Điều kiện: Máy không trầy xước, móp méo, còn nguyên hộp, phụ kiện và hóa đơn mua hàng.</li>
    </ul>

    <h4>2. Chính sách Bảo hành tiêu chuẩn</h4>
    <ul>
      <li>Máy mới (Fullbox): Bảo hành 12-24 tháng theo hãng (Apple, Asus, Dell, Samsung...)</li>
      <li>Máy đã qua sử dụng (99%): Bảo hành 6-12 tháng tại DHAs Nguyễn Kiệm</li>
      <li>Phụ kiện, linh kiện lẻ: Bảo hành 3-6 tháng</li>
      <li>Phạm vi: Bảo hành các lỗi phần cứng (nguồn, màn hình, mainboard, ổ cứng...)</li>
      <li>Từ chối bảo hành nếu sản phẩm rơi rớt, móp méo, vào nước, cháy nổ, tự ý mở, mất tem, sửa chữa ngoài cửa hàng.</li>
    </ul>

    <h4>3. Chính sách Bảo dưỡng miễn phí (Đặc quyền tại DHAs Nguyễn Kiệm)</h4>
    <ul>
      <li>Vệ sinh định kỳ miễn phí 6 tháng/lần cho Laptop và PC mua tại cửa hàng.</li>
      <li>Miễn phí thay keo tản nhiệt loại tốt trong 2 năm đầu.</li>
      <li>Hỗ trợ phần mềm trọn đời: cài hệ điều hành, driver, phần mềm văn phòng, tối ưu hệ thống.</li>
    </ul>
  </section>
</main>

<footer>
  <div>Địa chỉ: Nguyễn Kiệm, Phường Hành Thông, Thành Phố Hồ Chí Minh</div>
  <div>Hotline: <a href="tel:0123456789">0123456789</a></div>
  <div>Zalo: <a href="tel:0123456789">0123456789</a></div>
  <div>Messenger: <a href="https://m.me/DHAsNguyenKiem" target="_blank" rel="noopener noreferrer">DHAs Nguyễn Kiệm</a></div>
</footer>

</body>
</html>
// Dữ liệu cửa hàng
const storeInfo = {
  name: "DHAs Nguyễn Kiệm",
  address: "Nguyễn Kiệm, Phường Hành Thông, Thành Phố Hồ Chí Minh",
  hotline: "0123456789",
  zalo: "0123456789",
  messenger: "DHAs Nguyễn Kiệm",
  products: {
    "iphone 18 pro max": 70000000,
    "macbook": 105000000,
    "chuột": 5000000,
    "tai nghe": 3000000,
    "ipad": 20000000,
    "cục sạc dự phòng": 3000000,
    "tivi": 78000000,
    "cục sạc bluetooth": 7000000
  },
  warrantyPolicy: `- Chính sách Đổi trả (Hoàn tiền) – "An tâm dùng thử"
7 ngày đầu tiên (Lõi phần cứng từ nhà sản xuất): Đổi ngay máy mới cùng model (hoặc cùng giá trị) miễn phí. Hoàn tiền 100% nếu khách muốn trả.
Phí ship tùy khu vực (Nội thành gần 15k, Trung tâm 25k, Ngoại thành 35k-45k), freeship cho đơn hàng Laptop, PC, Điện thoại từ 5 triệu trở lên.
Khách được kiểm tra hàng trước khi thanh toán.
Từ ngày 8 đến 30: Hỗ trợ đổi máy lỗi phần cứng, thu phí trả máy 15%-20% tùy tình trạng.
Bảo hành tiêu chuẩn: Máy mới 12-24 tháng, máy 99% 6-12 tháng, phụ kiện 3-6 tháng.
Bảo dưỡng miễn phí: Vệ sinh định kỳ, tra keo tản nhiệt 2 năm, hỗ trợ phần mềm trọn đời.`,
  shippingInfo: `Phí ship:
- Nội thành gần: 15.000 VNĐ (Quận Phú Nhuận, Bình Thạnh, Tân Bình)
- Nội thành trung tâm: 25.000 VNĐ (Quận 1, 3, 4, 5, 10, 11)
- Ngoại thành & quận xa: 35.000-40.000 VNĐ (Quận 6, 7, 8, 12, Tân Phú, Bình Tân, Thủ Đức cũ)
- Huyện ngoại thành: 45.000 VNĐ (Hóc Môn, Bình Chánh, Nhà Bè)
- Quận Gò Vấp: Miễn phí
Freeship cho đơn hàng Laptop, PC, Điện thoại từ 5 triệu trở lên.`,
};

// Hàm xử lý câu hỏi khách hàng
function answerCustomerQuestion(question) {
  const q = question.toLowerCase();

  // Chào hỏi
  if (
    q.includes("xin chào") ||
    q.includes("chào") ||
    q.includes("hello") ||
    q.includes("hi")
  ) {
    return `Chào bạn! Tôi là trợ lý ảo của cửa hàng ${storeInfo.name}. Bạn cần mình giúp gì hôm nay?`;
  }

  // Hỏi về giá sản phẩm
  for (const product in storeInfo.products) {
    if (q.includes(product)) {
      const price = storeInfo.products[product];
      return `Sản phẩm ${product.charAt(0).toUpperCase() + product.slice(1)} hiện có giá là ${price.toLocaleString(
        "vi-VN"
      )} đồng. Bạn cần thêm thông tin gì về sản phẩm này không?`;
    }
  }

  // Hỏi về chính sách bảo hành
  if (
    q.includes("bảo hành") ||
    q.includes("đổi trả") ||
    q.includes("hoàn tiền") ||
    q.includes("chính sách")
  ) {
    return `Chính sách bảo hành và đổi trả của cửa hàng như sau:\n${storeInfo.warrantyPolicy}\nBạn có câu hỏi cụ thể nào về bảo hành không?`;
  }

  // Hỏi về phí giao hàng
  if (q.includes("phí ship") || q.includes("phí giao hàng") || q.includes("ship")) {
    return `Thông tin phí ship của cửa hàng:\n${storeInfo.shippingInfo}\nBạn vui lòng cung cấp khu vực để mình có thể báo phí ship chính xác hơn nhé!`;
  }

  // Hỏi về địa chỉ, liên hệ cửa hàng
  if (
    q.includes("địa chỉ") ||
    q.includes("liên hệ") ||
    q.includes("số điện thoại") ||
    q.includes("hotline") ||
    q.includes("zalo") ||
    q.includes("messenger")
  ) {
    return `Cửa hàng ${storeInfo.name} nằm tại: ${storeInfo.address}.\nHotline: ${storeInfo.hotline}\nZalo: ${storeInfo.zalo}\nMessenger: ${storeInfo.messenger}\nBạn cần hỗ trợ gì thêm không?`;
  }

  // Nếu không hiểu câu hỏi
  return `Rất tiếc, mình chưa có thông tin chính xác cho câu hỏi này. Bạn vui lòng liên hệ trực tiếp với nhân viên cửa hàng qua Hotline: ${storeInfo.hotline}, Zalo: ${storeInfo.zalo}, hoặc Messenger: ${storeInfo.messenger} để được hỗ trợ nhanh nhất nhé!`;
}

// Ví dụ sử dụng
console.log(answerCustomerQuestion("Chào bạn"));
console.log(answerCustomerQuestion("Giá Iphone 18 Pro Max là bao nhiêu?"));
console.log(answerCustomerQuestion("Chính sách bảo hành như thế nào?"));
console.log(answerCustomerQuestion("Phí ship tới Quận 1 là bao nhiêu?"));
console.log(answerCustomerQuestion("Địa chỉ cửa hàng ở đâu?"));
console.log(answerCustomerQuestion("Sản phẩm có màu đỏ không?"));
