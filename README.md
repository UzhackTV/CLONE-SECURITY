<!DOCTYPE html>
<html>
<head>
	<title>Instagram</title>

	<meta charset="utf8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<link rel="shortcut icon" href="http://alumni.umh.es/files/2017/06/Instagram_logo_2016.svg_.png">
	<link rel="stylesheet" type="text/css" href="css/instagram.css">

<style type="text/css">
	body{
		margin: 0px;
		padding: 0px;
		background-color: #fafafa;
		font-family: arial, sans-serif;
	}

	a{
		color: #3897f0;
		text-decoration: none;
	}

	a, button, input{
		outline: none;
	}

	button, a{
		cursor: pointer;
	}

	button{
		width: 100%;
    	border-radius: 3px;
   		font-size: 13px;
   		box-sizing: border-box;
		background-color: #3897f0;
   		border: 1px solid #efefef;
   		color: #ffffff;
   		font-weight: bold;
   		padding: 6px;
   		margin-bottom: 8px;
	}

	#header{
		width: 100%;
		height: 50px;
		background-color: #dd356c;
		padding: 10px 15px;
		box-sizing: border-box;
		display: flex;
		justify-content: space-between;
		color: #ffffff;
		font-size: 14px;
		font-weight: bold;
	}
		#header div{
			width: 300px;
			height: 100%;
		}
		#header div span{
			width: 100%;
			display: block;
			font-size: 12px;
		}
		#header div button{
			width: auto;
			height: 100%;
			background: none;
			border-radius: 3px;
			border: solid 1px #ffffff;
			float: right;
			padding: 6px 10px;
			box-sizing: border-box;
			color: #ffffff;
			font-weight: bold;
			font-size: 13px;
		}


		#login{
			width: 800px;
			height: auto;
			display: table;
			margin: 0px auto;
			margin-top: 15px;
			padding: 25px;
			box-sizing: border-box;
			display: flex;
			justify-content: space-between;
		}
			#login img{
				width: 400px;
				height: 620px;
				padding: 20px;
				box-sizing: border-box;
				float: left;
			}
			#login .login{
				width: 350px;
				height: auto;
				display: table;
				float: right;
				position: relative;
			}
			#login .login .top{
				margin-top: 0px;
			}
			#login .login div{
				width: 100%;
				height: auto;
				display: table;
				background-color: #ffffff;
				border: 1px solid #e6e6e6;
				padding: 25px 35px;
				box-sizing: border-box;
				margin-bottom: 10px;
				color: #262626;
    			font-size: 14px;
			}
			#login .login div img{
				width: 100%;
				height: 50px;
				padding: 0px 60px;
				box-sizing: border-box;
				margin-bottom: 10px;
			}
			#login .login div span{
				font-size: 18px;
			    line-height: 20px;
			    margin: 15px 0px;
			    text-align: center;
			    color: #999;
			    width: 100%;
			    display: flex;
			}
			#login .login div form{
				position: relative;
			}
			#login .login div input{
				width: 100%;
				background: 0 0;
   				border: 1px solid #efefef;
    			border-radius: 3px;
    			font-size: 13px;
    			padding: 8px;
    			box-sizing: border-box;
    			margin-bottom: 8px;
			}
			#login .login div form a{
				position: absolute;
				right: 10px;
				top: 110px;
			    color: #003569;
			}
			#login .login div input:focus{
				color: #262626;
				border: solid 1px #cccccc;
			}
			#login .login div input[type='submit']{
				background-color: #3897f0;
   				border: 1px solid #efefef;
   				color: #ffffff;
   				font-weight: bold;
   				padding: 6px;
			}
			#login .login div .veya{
				width: 100%;
				height: auto;
				padding: 0px;
				box-sizing: border-box;
				display: flex;
				border: 0px;
				margin: 10px 0px;
			}
			#login .login div .veya div{
				width: 100%;
				height: 1px;
				background-color: #c7c7c7;
				margin: 0px 8px;
				float: left;
				padding: 0px;
				box-sizing: border-box;
				margin-bottom: 10px;
				color: #999;
    			font-size: 14px;
    			display: flex;
			}
			#login .login div .veya .v_d{
				width: 40px;
				height: 20px;
				text-align: center;
				margin: 0px;
				margin-top: -8px;
				background: none;
				border: none;
				color: #4b4f56;
				font-size: 14px;
			}
			#login .login div .icon-facebook{
				font-size: 14px;
			    line-height: 20px;
			    margin: 0px;
			    color: #ffffff;
			    width: auto;
			    height: auto;
			    display: inline-block;
			}
			#login .login .text{
				padding: 0px;
				text-align: center;
				margin-top: 20px;
				background: none;
				border: 0px;
			}
			#login .login .app{
				width: 400px;
				height: auto;
				border: 0px;
				position: absolute;
				left: -25px;
				bottom: -70px;
				padding: 0px;
				background: none;
				display: flex;
			}
			#login .login .app h2{
				display: block;
			}
			#login .login .app a{
				width: 100%;
				height: 40px;
				margin: 0px 5px;
			}
			#login .login .app a img{
				width: 100%;
				height: 40px;
				padding: 0px;
			}


		#bottom{
			width: 940px;
			height: auto;
			display: table;
			margin: 0px auto;
			margin-top: 15px;
			margin-bottom: 30px;
			padding: 5px;
			box-sizing: border-box;
			display: flex;
			justify-content: space-between;
		}
			#bottom ul, li{
				margin: 0px;
				padding: 0px;
				list-style-type: none;
				float: left;
			}
			#bottom li{
				margin-right: 15px;
			}
			#bottom li a{
				font-weight: bold;
			    color: #003569;
			    font-size: 11px;
			}
			#bottom span{
				float: right;
				font-size: 12px;
			    color: #999;
			    font-weight: bold;
				padding: 4px;
			    box-sizing: border-box;
			}
	@media all and (min-width: 100px) and (max-width: 950px) {
			body{
				background-color: #ffffff;
			}

			#header div{
				width: auto;
			}


			#login{
				width: 100%;
				margin-top: 15px;
				padding: 25px;
			}
				#login .logoo{
					display: none;
				}
				#login .login{
					width: 100%;
					height: auto;
					margin-bottom: 40px;
				}
				#login .top{
					margin-top: 0px;
				}
				#login .login div{
					width: 100%;
					padding: 0px 15px;
					margin-bottom: 10px;
					border: 0px;
				}
				#login .login div img{
					padding: 0px 40px;
				}
				#login .login div form{
					margin-bottom: 40px;
				}
				#login .login .text{
					margin-top: 50px;
					margin-bottom: 20px;
				}
				#login .login .app{
					width: 100%;
					position: relative;
					left: 0px;
					bottom: 0px;
					display: flex;
					flex-flow: row wrap;
					margin-bottom: -35px;
				}
				#login .login .app .app1, .app2{
					flex: 1;
				}
				#login .login .app .app3{
					width: 100%;
					display: flex;
					flex-wrap: wrap;
					justify-content: center;
					margin: 5px 0px;
				}
				#login .login .app .app3 img{
					width: 120px;
				}
				#login .login .app a{
					width: auto;
					height: 40px;
					margin: 0px 5px;
				}


			#bottom{
				width: 100%;
				margin-bottom: 0px;
				margin-top: 0px;
				flex-flow: row wrap;
				text-align: center;
			}
				#bottom li{
					margin: 0px 10px;
				}
				#bottom span{
					width: 100%;
					text-align: center;
				}
	}
</style>
</head>
<body>
<div id="header">
	<div class="left">
		Instagram
		<span>Iltimos Login parolingizni yozing.</span>
	</div>

	<div class="right">
		<button>YUBORISH</button>
	</div>
</div>

<div id="login">
	<img class="_824m9" src="/static/images/homepage/screenshot1.jpg/aafd8c6b005d.jpg">
<img class="_824m9" src="/static/images/homepage/screenshot2.jpg/2d9d7248af43.jpg">
<img class="_824m9 _4je3h" src="/static/images/homepage/screenshot3.jpg/629d23a3c7b2.jpg">
<img class="_824m9 _9i1mm" src="/static/images/homepage/screenshot4.jpg/001bc33056c1.jpg">
<img class="_824m9" src="/static/images/homepage/screenshot5.jpg/f5ae123ab1e2.jpg">
	<div class="login">
		<div class="top">
			<img src="https://i.hizliresim.com/PrQMdQ.png">
			<form>
				<input type="text" name="" placeholder="Kullanıcı adı">
				<input type="password" name="" placeholder="Şifre">
				<a href="">Unuttun mu?</a>

				<input type="submit" name="" value="Giriş Yap">
			</form>
		</div>

		<div style="text-align: center;">
			Hesabın yok mu? <a href="">Kaydol</a>
		</div>

		<div class="text">
			Uygulamayı indir.
		</div>

		<div class="app">
			<a href="" class="app1">
				<img src="https://www.instagram.com/static/images/appstore-install-badges/badge_ios_turkish-tr.png/4d13ab7e9dd0.png">
			</a>

			<a href="" class="app2">
				<img src="https://www.instagram.com/static/images/appstore-install-badges/badge_android_turkish-tr.png/1cf9ecacfe15.png">
			</a>

			<a href="" class="app3">
				<img src="https://www.instagram.com/static/images/appstore-install-badges/badge_microsoft_turkish-tr.png/e894b9285d25.png">
			</a>
		</div>
	</div>
	<!--
	<div class="login">
		<div>
			<img src="https://i.hizliresim.com/PrQMdQ.png">

			<span>Arkadaşlarının fotoğraf ve videolarını görmek için kaydol.</span>

			<button><span class="icon-facebook"> Facebook ile Giriş Yap</span></button>

			<div class="veya">
				<div></div>

				<div class="v_d">YADA</div>
				
				<div></div>
			</div>

			<form>
				<input type="text" name="" placeholder="Cep Telefonu Numarası veya E-posta">
				<input type="text" name="" placeholder="Adı Soyadı">
				<input type="text" name="" placeholder="Kullanıcı Adı">
				<input type="password" name="" placeholder="Şifre">

				<input type="submit" name="" value="Kaydol">
			</form>

			<span style="margin: 0px; font-size: 14px;">Kaydolarak, Koşullarımızı ve Gizlilik İlkemiz kabul etmiş olursun.</span>
		</div>

		<div style="text-align: center;">
			Hesabınız var mı? <a href="">Giriş Yap</a>
		</div>
	</div>
	-->
</div>

<div id="bottom">
	<ul>
		<li><a href="">HAKKIMIZDA</a></li>
		<li><a href="">DESTEK</a></li>
		<li><a href="">BLOG</a></li>
		<li><a href="">BASIN</a></li>
		<li><a href="">API</a></li>
		<li><a href="">İŞ FIRSATLARI</a></li>
		<li><a href="">GİZLİLİK</a></li>
		<li><a href="">KOŞULLAR</a></li>
		<li><a href="">DİZİN</a></li>
		<li><a href="">DİL</a></li>
	</ul>

	<span>© 2017 INSTAGRAM</span>
</div>
</body>
</html>
