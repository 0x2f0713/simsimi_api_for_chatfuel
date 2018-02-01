# Simsimi API For Chatfuel

<h3>Yêu cầu:</h3>
	<ul>
		<li>Có hosting</li>
		<li>Có Fanpage</li>
		<li>Có tài khoản ChatFuel đã kết nối với Fanpage</li>
	</ul>
Lấy code từ file simsimi.php ở trên kia về, chỉ cần thay phần YOUR_KEY thành key của bạn là được, cách đăng ký key bạn có thể lên Google tìm.
Up file lên host, thiết lập ChatFuel phần JSON API với Method (Phương thức) là GET, URL bạn nhập link tới file simsimi.php mà bạn đã lấy ở trên, ví dụ: 
<code>https://www.yourdomain.com/filename.php?type=[type]&msg=[tinnhan]</code>
<h3>Giải thích:</h3>
[TYPE] có giá trị bằng 'voice' thì ngoài tin nhắn từ Simsimi còn có thêm file giọng nói của tin nhắn, nếu không muốn thì thay [TYPE] bằng giá trị khác.
[tinnhan] là tin nhắn của người dùng gửi đến bot.

