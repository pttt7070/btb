<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beauty Blog</title>
</head>
<body>
  <header>
    <!-- Phần tiêu đề của trang web -->
	<video id="banner" style="width: 100%;" autoplay loop>
		<source src="PANMELA Beauty.mp4" type="video/mp4">
	</video>
	<div>
		<ul id="menu">
			<li><a id="logo" href="Trang chủ.html"><img src="Logo.svg" width="194px" height="50px" alt="Programing" style="padding-top: 5px; "></a></li>
			<li class="dropdown" style="padding-left: 100px;"><a href="Trang chủ.html" style="font-family: NotoSerifDisplay-Condensed; color: #ab5c72;"><strong>Trang chủ</strong></a></li>
			<li class="dropdown">
				<a class="dropbtn" href="Chuyên mục Skincare.html" style="font-family: NotoSerifDisplay-Condensed; color: #ab5c72;"><strong>Chuyên mục Skincare</strong></a>
				<div class="dropdown-content">
					<a href="Bài viết 1 - Nhận biết các loại da.html">Nhận biết các loại da</a>
					<a href="Bài viết 2 - Skincare cho da mụn.html">Skincare cho da mụn</a>
					<a href="Bài viết 3 - Skincare cho da dầu.html">Skincare cho da dầu</a>
					<a href="Bài viết 4 - Skincare cho da khô.html">Skincare cho da khô</a>
					<a href="Bài viết 5 - Skincare cho da thường.html">Skincare cho da thường</a>
				</div>
			</li>
			<li class="dropdown">
				<a class="dropbtn" href="Chuyên mục Makeup.html" style="font-family: NotoSerifDisplay-Condensed; color: #ab5c72;"><strong>Chuyên mục Makeup</strong></a>
				<div class="dropdown-content">
					<a href="Bài viết 6- Các bước trang điểm cơ bản.html">Các bước trang điểm cơ bản</a>
					<a href="Bài viết 7 - Trang điểm mặt.html">Trang điểm mặt</a>
					<a href="Bài viết 8 - Trang điểm mắt.html">Trang điểm mắt</a>
					<a href="Bài viết 9 - Trang điểm môi.html">Trang điểm môi</a>
				</div>
			</li>
			<li class="dropdown">
				<a class="dropbtn" href="Sản phẩm.html" style="font-family: NotoSerifDisplay-Condensed; color: #ab5c72;"><strong>Sản phẩm</strong></a>
				<div class="dropdown-content">
					<div class="dropdown-content11">
						<a href="Bài viết 13 - Beauty Skin.html">Beauty Skin</a>
					</div>
					<div class="dropdown-content22">
						<a href="#">Beauty Face</a>
							<div class="dropdown-content2">
								<a href="Bài viết 10 - Beauty Face - Trang điểm mặt.html"><span>Trang điểm mặt</span></a>
								<a href="Bài viết 11 - Beauty Face - Trang điểm mắt.html">Trang điểm mắt</a>
								<a href="Bài viết 12 - Beauty Face - Trang điểm môi.html">Trang điểm môi</a>
							</div>
					</div>
				</div>
			</li>
		</ul>
	</div>
	<style>
		#menu{
			list-style-type: none; /*xóa định dạng danh sách (xóa dấu chấm bắt đầu)*/
			margin: 0px;
			padding: 0px;	
			/* overflow: hidden; ẩn những j ở ngoài khung */
			display: flex; /*hiện thị thành hàng ngang*/
			position: sticky;
			top: 1px;
		}
		li a, .dropbtn {
			display: inline-block;
			text-align: center;
			padding: 10px 15px;
			text-decoration: none;
		}
		.dropdown{
			display: inline-block;
			padding: 20px 40px 20px 40px;
		}
		.dropdown-content{
			display: none; /*ẩn các menu con*/
			position: absolute;
			background-color: #fff3f3;
			min-width: 120px;
			z-index: 1;
		}
		.dropdown-content1{
			display: none;
			position: absolute;
			background-color: #fff3f3;
			min-width: 120px;
			z-index: 1;
			left: 120px;
			top: 0px;
		}
		.dropdown-content2{
			display: none; /*ẩn menu con*/
			position: absolute; /*định vị phần tử trong 1 phần tử cha với các giá trị top bot left right*/
			left: 120px; /*để menu con nằm cách bên trái phần tử cha 1 khoảng bằng 120px*/
			top: 0px;
			background-color: #fff3f3;
			min-width: 130px;
			z-index: 1; /*hiển thị đè lên các nội dung khác*/
			
		}
		.dropdown-content a{
			color: #502d25;
			padding: 10px 12px;
			text-decoration: none; /*xóa định dạng có sẵn (gạch chân) của thẻ a*/
			display: block;
			text-align: left;
		}
		.dropdown-content1 a{
			color: #502d25;
			padding: 10px 12px;
			text-decoration: none;
			display: block;
			text-align: left;
		}
		.dropdown-content2 a{
			color: #502d25;
			padding: 10px 12px;
			text-decoration: none;
			display: block;
			text-align: left;
		}
		.dropdown-content a:hover{background-color: #f2c4c4;}/*hiệu ứng di chuột vào thì thay đổi màu nền*/
		.dropdown:hover .dropdown-content {display: block;} /*khi di chuột vào thì hiển thị menu con */
		.dropdown .dropdown-content:hover .dropdown-content11{display: block;}
		.dropdown .dropdown-content:hover .dropdown-content22{display: block;}
		.dropdown .dropdown-content .dropdown-content11:hover .dropdown-content1 {display: block;}
		.dropdown .dropdown-content .dropdown-content22:hover .dropdown-content2 {display: block;}
	</style>
  </header>
  <main>
    <!-- Nội dung chính của trang web -->
	<div class="container">
		<h1>
			<span class="auto-type"></span>
		</h1>
	</div>
	<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
	<!-- hiểu như 1 thư viện có người lập trình sẵn -->
	<script>
		var typed = new Typed(".auto-type",{
			strings : ["ABOUT US", "VỀ CHÚNG TÔI"],
			typeSpeed : 150, /*tốc độ xuất hiện*/
			backSpeed : 150, /*tốc độ biến mất*/
			loop : true /*lặp lại*/
		})
	</script>
	<style>
		.container{
			width: 100%;
			font-family: NotoSerifDisplay-Condensed; 
			font-size: 25px; 
			color: #502d25;
			display: flex;
			align-items: center; /*căn giữa theo chiều ngang*/
			justify-content: center; /*căn giữa theo chiều dọc*/
		}
	</style>
	<div id="giới thiệu" style="display: flex;">
		<div style="font-family:NotoSerifDisplay-Condensed; font-size:20px; color:#502d25;" align="justify"  id="text" >
			<p>
				Chào mừng bạn đến với <mark style="background-color:#edb1b3">Panmela Beauty</mark>, không gian trực tuyến dành cho những ai đam mê làm đẹp. Đây là nơi bạn có thể khám phá các bí quyết chăm sóc da, trang điểm tự nhiên, và cập nhật xu hướng mỹ phẩm mới nhất. Chúng tôi tin rằng làm đẹp không chỉ là ngoại hình, mà còn là cách nuôi dưỡng sự tự tin và niềm vui trong cuộc sống.
				<!---Chào mừng bạn đến với <mark style="background-color:#edb1b3">Panmela Beauty</mark>, không gian trực tuyến dành riêng cho những ai đam mê và yêu thích việc chăm sóc sắc đẹp. Nơi đây không chỉ đơn thuần là một trang web chia sẻ kiến thức, mà còn là người bạn đồng hành, giúp bạn khám phá và tận hưởng những bí quyết làm đẹp tinh tế. Từ những mẹo nhỏ về chăm sóc làn da căng mịn, cho đến các bước trang điểm hoàn hảo để tôn lên vẻ đẹp tự nhiên, tất cả đều được đúc kết từ kinh nghiệm thực tế và sự cập nhật liên tục của các xu hướng thời trang, mỹ phẩm mới nhất.-->
				Chúng tôi tin rằng làm đẹp không chỉ là bề ngoài, mà còn là cách để mỗi người phụ nữ cảm nhận giá trị của bản thân, nuôi dưỡng sự tự tin và niềm vui trong cuộc sống. Với các bài viết chi tiết, dễ hiểu, cùng những gợi ý về sản phẩm chất lượng, <mark style="background-color:#edb1b3">Panmela Beauty</mark> sẽ là cẩm nang không thể thiếu cho mọi cô nàng hiện đại. Dù bạn là người mới bắt đầu học cách chăm sóc bản thân hay đã là một chuyên gia làm đẹp, chắc chắn bạn sẽ tìm thấy cho mình những bí quyết phù hợp để tỏa sáng theo cách riêng.
				Hãy để chúng tôi cùng bạn trên hành trình khám phá và yêu thương chính mình qua từng thói quen làm đẹp mỗi ngày!
			</p>
		</div>
		<div id="content">
			<img width="300px" height="300px" src="Picture/hình 1.jpg">	
		</div>
		
	</div>
	<div class="comment-icon">
		
			<input id="like" type="radio" name="ikon"  >			
			    <label for="like">&#128077;</label> <!--lable: thẻ mô tả-->
			
			<input id="heart" type="radio" name="ikon"  >
			    <label for="heart">&#129505;</label>
			
			<input id="haha" type="radio" name="ikon"  >
			    <label for="haha">&#128518;</label>
			
			<input id="angry" type="radio" name="ikon"  >
			    <label for="angry">&#128544;</label>
			
			<input id="sad" type="radio" name="ikon" >
		        <label for="sad">&#128546;</label>
	
    </div>
	<script>
		//chọn các phần tử input có class=comment icon để xử lý
		document.querySelectorAll('.comment-icon input').forEach((input) => {
    	//addEventListener('change'): Lắng nghe sự kiện thay đổi khi người dùng chọn một biểu tượng.
		input.addEventListener('change', () => {
        const selectedReaction = document.querySelector('.comment-icon input:checked + label').textContent;
        /*input:checked + label: Chọn biểu tượng (nội dung label) tương ứng với nút radio được chọn.*/
		alert("Cảm ơn bạn đã phản hồi");
		// alert: đưa ra thông báo...
    });
});
	</script>
	<style>
		#text{
			margin-right: 20px;
			justify-content: center;
		}
		.comment-icon{
			gap: 15px; /*khoảng cách giữa các cột, hàng*/
			font-size: 30px;
			cursor: pointer; /*chỉ định cách hiển thị của con trỏ chuột, pointer là chọn*/
			justify-content: left;
			display: flex;
		}
		.comment-icon input[type="radio"]{  /*ẩn định dạng nút chọn mặc định*/
			display: none; 
		}
		.comment-icon label:hover {/*khi di chuột tới thì phóng to 30% */
		transform: scale(1.3);
		}
		.comment-icon input[type="radio"]:checked + label { /*khi phần tử đã được chọn thì vẫn to 30%*/
		transform: scale(1.3);
		}
	</style>
  </main>
  	<div>
		<a href="#banner">
			<p style="font-size: 25px; background-color: #f8eeec; position: fixed; top: 85%; left: 95%;">&#128285;</p>
			<!--dùng position: fixed để cố định nút top trên trình duyệt-->
		</a>
	</div>
  	
  <div class="form">
	<div id="idd" style="padding: 30px; margin-left: 30px;">
		<img style="width: 500px; box-shadow: 0 4px 8px 0 #9e8a86, 0 6px 20px 0 #ac8c85;"src="form.svg">
	</div>
	<!--https://formsubmit.co/trasua7070@gmail.com-->
	<div id="dang-ki">
		<h1 style="margin-left: 90px;"><span>Đăng ký nhận thông tin</span></h1>
		<form id="registrationForm" class="form-reg" >
			<div class="form-group">
				<label for="fullname">Họ và tên</label><br>
				<input type="text" class="form-control" placeholder="Họ và tên" required name="username"><br>
			</div>
			<div class="form-group">
				<label for="numberphone">Số điện thoại</label><br>
				<input type="tel" class="form-control" placeholder="Số điện thoại" 
				pattern="[0]{1}[0-9]{9}" minlength="10" maxlength="10" required name="numberphone"><br>
				<!-- pattern dùng để thiết lập định dạng cho đầu vào,  
				 [0]{1} có nghĩa là số đầu tiên là số 0, [0-9]{9} nghĩa là 9 số tiếp theo có thể từ 0 đến 9 
				 minlength là chiều dài tối thiêu là 10
				 maxlength tối đa 10-->
			</div>
			<div class="form-group">
				<label for="email">Email</label><br>
				<input type="email" class="form-control" placeholder="your-email@gmail.com" required name="email"><br>
			</div>
			<div class="form-group">
				<label>
					<input type="radio" name="gender" value="male"> Nam
				</label>
				<label>
					<input type="radio" name="gender" value="female"> Nữ
				</label>
				<label>
					<input type="radio" name="gender" value="other"> Khác
				</label>
			</div>
			<input id="submit" type="submit" value="Đăng ký" class="form-submit">
		</form>
	</div>
	
	<script>
        document.getElementById('registrationForm').addEventListener('submit', function(event) {
            event.preventDefault(); // Ngăn chặn hành vi mặc định của form
            const formData = new FormData(event.target);// Thu thập dữ liệu từ form
            let textContent = 'Chào mừng bạn đến với Panmela Beauty, không gian trực tuyến dành cho những ai đam mê làm đẹp. Đây là nơi bạn có thể khám phá các bí quyết chăm sóc da, trang điểm tự nhiên, và cập nhật xu hướng mỹ phẩm mới nhất. Chúng tôi tin rằng làm đẹp không chỉ là ngoại hình, mà còn là cách nuôi dưỡng sự tự tin và niềm vui trong cuộc sống. Chúng tôi tin rằng làm đẹp không chỉ là bề ngoài, mà còn là cách để mỗi người phụ nữ cảm nhận giá trị của bản thân, nuôi dưỡng sự tự tin và niềm vui trong cuộc sống. Với các bài viết chi tiết, dễ hiểu, cùng những gợi ý về sản phẩm chất lượng, Panmela Beauty sẽ là cẩm nang không thể thiếu cho mọi cô nàng hiện đại. Dù bạn là người mới bắt đầu học cách chăm sóc bản thân hay đã là một chuyên gia làm đẹp, chắc chắn bạn sẽ tìm thấy cho mình những bí quyết phù hợp để tỏa sáng theo cách riêng. Hãy để chúng tôi cùng bạn trên hành trình khám phá và yêu thương chính mình qua từng thói quen làm đẹp mỗi ngày! \n'; // Đối tượng để lưu dữ liệu định dạng
          formData.forEach(function(value, key) {
          //sử dụng switch để định dạng nội dung sẽ có trong file tải về
		  switch (key) {
			  case 'username':
				  textContent += 'Họ và tên: ' + value + '\n';
				  break;
			  case 'numberphone':
				  textContent += 'Số điện thoại: ' + value + '\n';
				  break;
			  case 'email':
				  textContent += 'Email: ' + value + '\n';
				  break;
			  case 'gender':
				  let genderText = value === 'male' ? 'Nam' : value === 'female' ? 'Nữ' : 'Khác';
				  textContent += 'Giới tính: ' + genderText + '\n';
				  break;
			  default:
				  textContent += key + ': ' + value + '\n';
		  }
	  });	//Tạo một đối tượng Blob chứa nội dung văn bản (textContent).
            const blob = new Blob([textContent], { type: 'text/plain' });
            const url = URL.createObjectURL(blob); //Tạo URL tạm để tải xuống tệp.
            const a = document.createElement('a'); //Tạo một phần tử <a> để thực hiện tải xuống:
			//Đặt URL và tên tệp tải về là thông tin.txt.
            a.href = url;
            a.download = 'thông tin.txt';
            document.body.appendChild(a);
            a.click(); //tạo sự kiện click để tải xuống
            document.body.removeChild(a); //xóa phần tử a
            URL.revokeObjectURL(url); //giải phóng url tạm 
			//thông báo 
            alert('Đăng ký thành công! Thông tin đã được lưu.');
        });
    </script>
  </div>
  <hr>
	<div id="chuyen-tab" >
		<a style="background-color: #f2c4c4; padding: 10px;" href="Trang chủ.html">1</a>
		<a style="padding: 10px;" href="Chuyên mục Skincare.html">2</a>
		<a style="padding: 10px;" href="Chuyên mục Makeup.html">3</a>
        <a style="padding: 10px;" href="Sản phẩm.html">4</a>
	</div>
	<br>
  <footer>
    <img class="Banner" src="Footer.svg" alt="Programing">
	<p style="text-align:center;">Bản quyền © 2024 Trang web của tôi. Mọi quyền được bảo lưu.</p>
  </footer>
  <audio src="bibi.mp3" type="audio/mp3" autoplay> </audio>
  	
 	<div class="cursor"></div>
	<div class="cursor2"></div>
	<script>
		var cursor = document.querySelector('.cursor')
		var cursor2 = document.querySelector('.cursor2')
		//chọn 2 phần tử cursor để xử lý
		document.addEventListener('mousemove' , function(e){
		//tạo sự kiện xảy ra khi di chuyển chuột
			cursor.style.cssText = cursor2.style.cssText = "left: " + e.clientX + "px; top: " + e.clientY  + "px;";
		/*2 phần tử cursor di chuyển theo chuột, e.clientX và e.clientY: Lấy tọa độ x (theo chiều ngang) và 
		y (theo chiều dọc) của con trỏ chuột so với cửa sổ trình duyệt theo thời gian thực*/
		});
	</script>
  <style>
	.cursor{
		position: fixed;
		width: 30px;
		height: 30px;
		border: 1px solid salmon;
		border-radius: 50%; /*bo góc, 50% thành hình tròn*/
		left: 0; /*vị trí phần tử so với con chuột*/
		top: 0;
		transition: 0.1s; /*di chuyển trễ hơn 0,1s*/
		transform: translate(-50%, -50%); /*trục x, trục y - ra giữa*/
		pointer-events: none;/* Không gây cản trở cho tương tác chuột */
		z-index: 1000;	/*hiển thị trên các phần tử khác*/
	}
	.cursor2{
		position: fixed;
		width: 8px;
		height: 8px;
		background: #edb1b3;
		border-radius: 50%; /*bo góc, 50% thành hình tròn*/
		left: 0;
		top: 0;
		transition: 0.15s;
		transform: translate(-50%, -50%); /*trục x, trục y - ra giữa*/
		pointer-events: none;	
		z-index: 1000;	/*hiển thị trên các phần tử khác*/
	}
	body{
		background-color: #f8eeec;
	}
	.Banner{ 
		width:100%;
	}
	.form{
		display: flex;
	}
	#anh-bieu-mau{
		width: 50%;
	}
	#dang-ki{
		width: 50%;	
		margin-left: 10px;
	}
	.form-group {
		margin-left: 100px;
	}
	input{
		border: none;
		border-radius: 10px;
		margin-bottom: 10px;
		padding: 5px;
	}
	#submit{
		background-color: #ab5c72;
		margin-top: 10px;
		color: #f8eeec;
		padding-left: 15px;
		padding-right: 15px;
		margin-left: 90px;
	}
	#submit:hover{
		background-color: #502d25;
	}
	main{
		max-width: 1080px;
		margin: 0px auto;
	}
	hr{
		color: white; 
		background: white;
		border: 0;
		height: 1px;
	}
	label.ikon:hover { transform: scale(1.3); }

	a{
		color:#ab5c72;
		text-decoration: none;
	}
	#chuyen-tab{
        display: flex; /*hiển thị thành hàng ngang*/
        align-items: center; /*căn giữa theo chiều ngang*/
        justify-content: center; /*căn giữa theo chiều dọc*/
    }
    #chuyen-tab a:hover{
        display: inline-block; /*di chuột vào thì hiển thị dạng khối*/
        background-color: #f2c4c4; 
    }

  </style>
</body>
</html>
