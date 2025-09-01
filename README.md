# shaikhmansooraligithub.io-<!DOCTYPE html>
<html lang="en">

<head>
	<title>Rishabh Mishra Portfolio</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">

	<link rel="stylesheet" href="css/open-iconic-bootstrap.min.css">
	<link rel="stylesheet" href="css/animate.css">

	<link rel="stylesheet" href="css/owl.carousel.min.css">
	<link rel="stylesheet" href="css/owl.theme.default.min.css">
	<link rel="stylesheet" href="css/magnific-popup.css">

	<link rel="stylesheet" href="css/aos.css">

	<link rel="stylesheet" href="css/ionicons.min.css">

	<link rel="stylesheet" href="css/flaticon.css">
	<link rel="stylesheet" href="css/icomoon.css">
	<link rel="stylesheet" href="css/style.css">



	<style>
		/*======================================
//--//-->   ABOUT
======================================*/

		.about-mf .box-shadow-full {
			padding-top: 4rem;
			padding-bottom: 4rem;
		}

		.about-mf .about-img {
			margin-bottom: 2rem;
		}

		.about-mf .about-img img {
			margin-left: 10px;
		}


		.skill-mf .progress {
			/* background-color: #cde1f8; */
			margin: .5rem 0 1.2rem 0;
			border-radius: 0;
			height: .7rem;
		}

		.skill-mf .progress .progress-bar {
			height: .7rem;
			background-color: #ffbd39;
		}


		/* Animation styles */
		#typing-animation {
			position: relative;
			font-size: 30px;
			font-weight: bold;
			color: rgb(255, 255, 255);
			overflow: hidden;
			white-space: nowrap;
			animation: typing 3s steps(20, end) infinite;
		}

		#typing-animation:before {
			content: "";
			/* position: absolute; */
			top: 0;
			left: 0;
			width: 0;
			height: 100%;
			background-color: #ccc;
			animation: typing-cursor 0.5s ease-in-out infinite;
		}

		@keyframes typing {
			from {
				width: 0;
			}

			to {
				width: 100%;
			}
		}

		@keyframes typing-cursor {
			from {
				width: 5px;
			}

			to {
				width: 0;
			}
		}


		/* project image zoom effect */

		.zoom-effect {
			overflow: hidden;
			transition: transform 0.3s ease-out;
		}

		.zoom-effect:hover {
			transform: scale(1.1);
		}
	</style>


</head>

<body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">


	<nav class="navbar navbar-expand-lg navbar-dark ftco_navbar ftco-navbar-light site-navbar-target" id="ftco-navbar">
		<div class="container">
			<a class="navbar-brand" href="index.html">Mansoor Ali</a>
			<button class="navbar-toggler js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse"
				data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
				<span class="oi oi-menu"></span> Menu
			</button>

			<div class="collapse navbar-collapse" id="ftco-nav">
				<ul class="navbar-nav nav ml-auto">
					<li class="nav-item"><a href="#home-section" class="nav-link"><span>Home</span></a></li>
					<li class="nav-item"><a href="#about-section" class="nav-link"><span>About</span></a></li>
					<li class="nav-item"><a href="#resume-section" class="nav-link"><span>Resume</span></a></li>
					<li class="nav-item"><a href="#project-section" class="nav-link"><span>Projects</span></a></li>
					<li class="nav-item"><a href="#contact-section" class="nav-link"><span>Contact</span></a></li>
				</ul>
			</div>
		</div>
	</nav>
	<section id="home-section" class="hero">
		<div class="home-slider  owl-carousel">
			<div class="slider-item ">
				<div class="overlay"></div>
				<div class="container">
					<div class="row d-md-flex no-gutters slider-text align-items-end justify-content-end"
						data-scrollax-parent="true">
						<div class="one-third js-fullheight order-md-last img"
							style="background-image:url(images/new_image\ .jpg); width: 40%; height: 1vh;">
							<div class="overlay"></div>
						</div>
						<div class="one-forth d-flex  align-items-center ftco-animate"
							data-scrollax=" properties: { translateY: '70%' }">
							<div class="text">
								<span class="subheading">Hello!</span>
								<h1 class="mb-4 mt-3">I'm <span>Mansoor Ali</span></h1>

								<!-- Element to contain animated typing -->
								<span id="typing-animation"></span>

								<script>

									// Initialize the typing animation
									const typingAnimationElement = document.getElementById('typing-animation');

									// Create an array of typing text
									const typingTexts = [
										'Shaikh',
										'Data Analyst',
									];

									// Create a function to display the typing animation for a given text
									function playTypingAnimation(text) {
										// Loop through each character and add it to the element
										for (let i = 0; i < text.length; i++) {
											setTimeout(() => {
												typingAnimationElement.textContent += text[i];
											}, i * 200); // Increase the delay to slow down the typing animation
										}

										// Once the animation is complete, reset the text and start over
										setTimeout(() => {
											typingAnimationElement.textContent = '';
											playTypingAnimation(typingTexts[(typingTexts.indexOf(text) + 1) % typingTexts.length]);
										}, text.length * 200);
									}

									// Start the typing animation loop
									playTypingAnimation(typingTexts[0]);

								</script>

								<br>
								<br>
								<h2>A Data Analyst</h2>
								<!-- <h2 class="d-flex" style="margin-bottom: 0">With over 5 years of experience</h2> -->
								<!-- <br> -->
								<p><a href="" class="btn btn-primary py-3 px-4">LINKEDIN</a>
									<a href="https://github.com/Mansoor-alib/MansoornAli"
										class="btn btn-white btn-outline-white py-3 px-4">My works</a>
								</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>



	<section class="ftco-about img ftco-section ftco-no-pb" id="about-section">
		<div class="container">
			<div class="row">
				<div class="row d-flex align-items-stretch">
					<!-- <div class="row d-flex"> -->
					<div class="col-md-6 col-lg-5 d-flex">
						<div class="img-about img d-flex align-items-stretch">
							<div class="overlay">
								<div class="row">
									<div class="col-sm-6 col-md-5">
										<div class="about-img">
											<img src="images/new_image .jpg" class="img-fluid rounded b-shadow-a" alt="">
										</div>
									</div>
									<!-- Details next to profile image -->
									<div class="col-sm-6 col-md-7">
										<div class="about-info">
											<p><span class="title-s">Name: </span> <span>Mansoor Ali</span></p>
											<p><span class="title-s">Job Role: </span> <span>Data Analyst</span>
											</p>
											<p><span class="title-s">Fresher: </span> <span>Fresher</span>
											</p>
											<p><span class="title-s">Address: </span> <span>Mumbai, India</span></p>
										</div>
									</div>
								</div>

								<div class="skill-mf">
									<p class="title-s">Skills</p>
									<span>SQL</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 95%;"
											aria-valuenow="95" aria-valuemin="0" aria-valuemax="100"></div>
									</div>

									<span>PYTHON</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%"
											aria-valuenow="85" aria-valuemin="0" aria-valuemax="100"></div>
									</div>

									<span>Data Visualization</span> <span class="pull-right">90%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 90%"
											aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
									</div>

									<span>Statistical Analysis</span> <span class="pull-right">67%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 85%"
											aria-valuenow="85" aria-valuemin="0" aria-valuemax="100"></div>
									</div>

									<span>Machine Learning</span> <span class="pull-right">80%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 80%"
											aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
									</div>
								</div>
							</div>
						</div>
					</div>

					<div class="col-md-6 col-lg-7 pl-lg-5 pb-5">
						<div class="row justify-content-start pb-3">
							<div class="col-md-12 heading-section ftco-animate">

								<h1 class="big">About</h1>
								<h2 class="mb-4">About Me</h2>

								<p>I am a motivated and detail-oriented aspiring Data Analyst with a strong foundation
									in SQL, Excel, Power BI, and Python. I enjoy working with data to uncover patterns,
									solve problems, and create meaningful insights that support decision-making. As a
									quick learner, I am eager to apply my analytical skills and contribute to real-world
									projects while continuing to grow in the field of data analytics</p>
								<ul class="about-info mt-4 px-md-0 px-2">
									<li class="d-flex"><span>Profile:</span> <span>Data Analytics</span>
									</li>
									<li class="d-flex"><span>Domain:</span> <span>Retail, Ecommerce, BFSI &amp; Digital
											Marketing</span></li>
									<li class="d-flex"><span>Education:</span> <span>BCOM CURRENTY SECOND YEAR</span>
									</li>
									<li class="d-flex"><span>Language:</span> <span>Hindi</span></li>
									<li class="d-flex"><span>BI Tools:</span> <span>Microsoft Power BI, Looker</span>
									</li>
									<!-- <li class="d-flex"><span>Other Skills:</span> <span>Cloud, PySpark, Excel, Git,
											JIRA, Google Analytics &amp; SEO</span></li> -->
									<li class="d-flex"><span>Interest:</span> <span>Traveling, Travel Photography,
											Teaching</span></li>

								</ul>
							</div>
						</div>


						<div class="counter-wrap ftco-animate d-flex mt-md-3">
							<div class="text">
								<p class="mb-4">
									<span class="number" data-number="07">0</span> <span>+</span>
									<span>&nbsp; Projects completed</span>
								</p>
								<p><a href=https://www.linkedin.com/in/mansoor-shaikh-7b0361372/details/skills/
										class="btn btn-primary py-3 px-3">LinkedIn</a></p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>




	<section class="ftco-section ftco-no-pb" id="resume-section">
		<div class="container">
			<div class="row justify-content-center pb-5">
				<div class="col-md-10 heading-section text-center ftco-animate">
					<h1 class="big big-2">Resume</h1>
					<h2 class="mb-4">Resume</h2>
					<p>Motivated and detail-oriented aspiring Data Analyst with strong foundational skills in SQL,
						Excel, Python, and Power BI. Passionate about turning raw data into actionable insights to
						support business decisions. Eager to apply analytical and problem-solving skills in a dynamic
						organization.</p>
				</div>
			</div>

			<div class="row">
				<h1 class="big-4">FRESHER</h1>
				<div class="underline"></div>
			</div>
			<br>

			<div class="row">
				<!-- <div class="col-md-6">
					<div class="resume-wrap ftco-animate">
				    	<span class="date">2021-Present</span>
						<h2>Senior Data Analyst</h2>
						<span class="position">Merkle</span>
						<p class="mt-4">Merkle, a leading CXM and media company with over 10K+ professionals globally.
							It's a part of Dentsu International.
						<ul>
							<li>Analysed ad campaigns, clickstream, and customer surveys data, identified an increasing
								demand and launched a strategic product line.</li>
							<li>Developed time series forecasting models to predict sales and optimize marketing
								budgets, got model performance of 92%.</li>
							<li>Designed and executed A/B tests, performed rigorous statistical analysis. Led to 20% MoM
								increase in the conversion rate.</li>
						</ul>
						</p>
					</div>

				</div> -->

				<div class="col-md-6">
					<!-- <div class="resume-wrap ftco-animate">
						<span class="date">2018-2021</span>
						<h2>Senior Data Analyst</h2>
						<span class="position">iQuanti</span>
						<p class="mt-4">iQuanti is a data-driven digital marketing analytics and solutions company,
							helps top 100 global brands.
						<ul>
							<li>Performed in-depth market research and analysis to create online pages. Resulted in
								~100% website growth and 30% increase in conversion rate YoY.</li>
							<li>Delivered multiple training and mentorship sessions on analytical tools like SQL, MS
								Excel, Power BI, Tableau and Python.</li>
							<li>Performed migration and enhancements for merchandising dashboard, involved data
								integration and its feature improvement.</li>
						</ul>
						</p>
					</div> -->

				</div>
			</div>

			<br>
			<br>

			<div class="row">
				<h1 class="big-4">Education</h1>
				<div class="underline"></div>
			</div>
			<br>

			<div class="row">
				<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2025-2026</span>
						<h2>SYBCOM SECOND YEAR</h2>
						<span class="position">Akbar Peer Bhoy College</span>
						<!-- <p class="mt-4">Grade: First class distinction.</p> -->
					</div>
				</div>

				<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">2017-2018</span>
						<h2>Higher Secondary School</h2>
						<span class="position">Maulana Azad High School</span>
						<!-- <p class="mt-4">Grade: First class distinction.</p> -->
					</div>
				</div>
			</div>

			<div class="row justify-content-center mt-5">
				<div class="col-md-6 text-center ftco-animate">
					<p> <a href="D:\Certificate Data Analytics\fresher_2_page_resume[1].docx"
							class="btn btn-primary py-4 px-5">Download CV</a></p>
				</div>
			</div>
		</div>
	</section>



	<section class="ftco-section" id="project-section">
		<div class="container">
			<div class="row justify-content-center mb-5 pb-5">
				<div class="col-md-7 heading-section text-center ftco-animate">
					<h1 class="big big-2">Projects</h1>
					<h2 class="mb-4">Projects</h2>
					<p>Below are the sample Data Analytics projects on Excel, SQL, Power BI.</p>
				</div>
			</div>
			<div class="row d-flex">
				<div class="col-md-4 d-flex ftco-animate">
					<div class="blog-entry justify-content-end">
						<a href="https://github.com/Mansoor-alib" class="block-20 zoom-effect"
							style="background-image: url(images/cardashboard.png);">
						</a>
						<div class="text mt-3 float-right d-block">

							<h3 class="heading">
								<a href="https://github.com/Mansoor-alib">Data
									Analyst Using Power BI & SQL For Car Dashboard</a>
							</h3>
							<p>The Car Store Data Dashboard is designed to provide a comprehensive view of vehicle
								sales, inventory levels, customer preferences, and revenue performance in a single
								interactive platform. It aims to help management and sales teams monitor business
								trends,</p>
						</div>
					</div>
				</div>
				<div class="col-md-4 d-flex ftco-animate">
					<div class="blog-entry justify-content-end">
						<a href="https://github.com/Mansoor-alib" class="block-20 zoom-effect"
							style="background-image: url('images/creditcard.png');">
						</a>
						<div class="text mt-3 float-right d-block">

							<h3 class="heading"><a href="https://github.com/Mansoor-alib">Data
									Analyst Using Power BI & SQL For Credit Card Dashboard</a></h3>
							<p>Provide an overview of total credit card transactions, revenue, and active accounts.

								Monitor customer spending patterns and credit utilization rates.

								Analyze performance by card type, category, and location.</p>
						</div>
					</div>
				</div>
				<div class="col-md-4 d-flex ftco-animate">
					<div class="blog-entry">
						<a href="https://github.com/Mansoor-alib" class="block-20 zoom-effect"
							style="background-image: url('images/proj_3.jpg');">
						</a>
						<div class="text mt-3 float-right d-block">

							<h3 class="heading"><a href="https://github.com/Mansoor-alib">Power
									BI Sales dashboard Project for Beginners</a></h3>
							<p>Designed a power bi dashboard for Madhav Store to track and analyze the online sales data
								acorss India.</p>
						</div>
					</div>
				</div>
			</div>
			<br>
			<!-- added justify-content-center to center align the last two projects -->
			<!-- <div class="row d-flex justify-content-center">
				<div class="col-md-4 d-flex ftco-animate">
					<div class="blog-entry justify-content-end">
						<a href="https://github.com/Mansoor-alib" class="block-20 zoom-effect"
							style="background-image: url('images/proj_4.jpg');">
						</a>
						<div class="text mt-3 float-right d-block">

							<h3 class="heading"><a href="https://github.com/Mansoor-alib">Sales Forecast-
									Time Series Forecasting</a></h3>
							<p>Used multiple machine learning models to forecast sales (retail store) and performed time
								series analysis.</p>
						</div>
					</div>
				</div>
				<div class="col-md-4 d-flex ftco-animate">
					<div class="blog-entry justify-content-end">
						<a href="https://github.com/Mansoor-alib" class="block-20 zoom-effect"
							style="background-image: url('images/proj_5.jpg');">
						</a>
						<div class="text mt-3 float-right d-block">

							<h3 class="heading"><a href="https://github.com/Mansoor-alib">Customer
									Segmentation using clustering model</a></h3>
							<p>Developed a ML model to give various recommendations of financial products &amp; services
								on target customer groups.</p>
						</div>
					</div>
				</div>
			</div> -->
		</div>
	</section>

	<section class="ftco-section ftco-no-pt ftco-no-pb ftco-counter img" id="section-counter">
		<!-- <div class="container">
			<div class="row d-md-flex align-items-center">
				<div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
					<div class="block-18">
						<div class="text">
							<strong class="number" data-number="20">0</strong>
							<span>Achievements</span>
						</div>
					</div>
				</div>
				<div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
					<div class="block-18">
						<div class="text">
							<strong class="number" data-number="30">0</strong>
							<span>Projects</span>
						</div>
					</div>
				</div>
				<div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
					<div class="block-18">
						<div class="text">
							<strong class="number" data-number="1000">0</strong>
							<span>Mentored Students</span>
						</div>
					</div>
				</div>
				<div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
					<div class="block-18">
						<div class="text">
							<strong class="number" data-number="500">0</strong>
							<span>Cups of coffee</span>
						</div>
					</div>
				</div>
			</div>
		</div> -->

		<div class="ftco-section ftco-hireme img margin-top" style="background-image: url(images/bg_1.jpg)">
			<!-- <div class="container"> -->
			<div class="row justify-content-center">
				<div class="col-md-7 ftco-animate text-center">
					<h2>More projects on<span> Github </span> </h2>
					<div class="heading">
						<h4> I love to solve business problems &amp; uncover hidden data stories </h4>
						<br>
						<p><a href="https://github.com/Mansoor-alib/shaikhmansoorali" class="btn btn-primary py-3 px-5">GitHub</a></p>
					</div>
				</div>
			</div>
			<!-- </div> -->
		</div>
	</section>



	<section class="ftco-section contact-section ftco-no-pb" id="contact-section">
		<div class="container">
			<div class="row justify-content-center mb-5 pb-3">
				<div class="col-md-7 heading-section text-center ftco-animate">
					<h1 class="big big-2">Contact</h1>
					<h2 class="mb-4">Contact Me</h2>
					<p>Below are the details to reach out to me!</p>
				</div>
			</div>

			<div class="row d-flex contact-info mb-5">
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box p-4 text-center">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-map-signs"></span>
						</div>
						<h3 class="mb-4">Address</h3>
						<p>Mumbai, India</p>
					</div>
				</div>
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box p-4 text-center">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-phone2"></span>
						</div>
						<h3 class="mb-4">Contact Number</h3>
						<p><a href="tel://0101010101">+91 93 72 36 34 97</a></p>
					</div>
				</div>
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box p-4 text-center">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-paper-plane"></span>
						</div>
						<h3 class="mb-4">Email Address</h3>
						<p><a href="mailto:info@yoursite.com">shaikhmansoorali974@gmail.com</a></p>
					</div>
				</div>
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box p-4 text-center">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-globe"></span>
						</div>
						<h3 class="mb-4">Download Resume</h3>
						<p><a href="#">resumelink</a></p>
					</div>
				</div>

				<div class="container">
					<br>
					<br>
					<div class="row justify-content-center">
						<div class="col-md-7 ftco-animate text-center">
							<h2>Have a<span> Question? </span>
								 <!-- <a href="https://forms.gle/uLaTShUKXraAvHJ77"
									class="btn btn-primary py-3 px-5">Click Here</a> </h2> -->
						</div>
					</div>
					<br>
					<!-- <ul class="ftco-footer-social list-unstyled d-flex justify-content-center align-items-center mb-0">
						<li class="ftco-animate normal-txt">Find me on </li>
						<li class="ftco-animate"><a href="https://www.youtube.com/@RishabhMishraOfficial"><span
									class="icon-youtube"></span></a></li>
						<li class="ftco-animate"><a href="https://www.linkedin.com/in/rishabhnmishra/"><span
									class="icon-linkedin"></span></a></li>
						<li class="ftco-animate"><a href="https://twitter.com/rishabhnmishra"><span
									class="icon-twitter"></span></a></li>
						<li class="ftco-animate"><a href="https://twitter.com/rishabhnmishra"><span
									class="icon-facebook"></span></a></li>
						<li class="ftco-animate"><a href="https://www.instagram.com/rishabhnmishra/"><span
									class="icon-instagram"></span></a></li>
					</ul> -->
					<br>
				</div>
			</div>
	</section>




	<footer class="ftco-footer ftco-section">
		<div class="container">
			<div class="row">
				<div class="col-md-12 text-center">

					<p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
						Copyright &copy;
						<script>document.write(new Date().getFullYear());</script> All rights reserved | This template
						is made with <i class="icon-heart color-danger" aria-hidden="true"></i> by <a
							href="https://colorlib.com" target="_blank">Colorlib</a>
						<!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
					</p>
				</div>
			</div>
		</div>
	</footer>


	<!-- loader -->
	<div id="ftco-loader" class="show fullscreen"><svg class="circular" width="48px" height="48px">
			<circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee" />
			<circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10"
				stroke="#F96D00" />
		</svg></div>


	<script src="js/jquery.min.js"></script>
	<script src="js/jquery-migrate-3.0.1.min.js"></script>
	<script src="js/popper.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/jquery.easing.1.3.js"></script>
	<script src="js/jquery.waypoints.min.js"></script>
	<script src="js/jquery.stellar.min.js"></script>
	<script src="js/owl.carousel.min.js"></script>
	<script src="js/jquery.magnific-popup.min.js"></script>
	<script src="js/aos.js"></script>
	<script src="js/jquery.animateNumber.min.js"></script>
	<script src="js/scrollax.min.js"></script>

	<script src="js/main.js"></script>

</body>

</html>
{
  "name": "clark",
  "firstRun": false,
  "exportConfig": true,
  "fileConfigs": [],
  "fileTree": {
    "expandedDirs": [],
    "hideSystemFiles": true,
    "systemFiles": [
      ".*",
      "desktop.ini",
      "prepros.config",
      "$RECYCLE.BIN",
      "prepros.cfg",
      "prepros-6.config",
      "Prepros Export"
    ],
    "hideUnwatchedFiles": false
  },
  "imports": [
    {
      "path": "scss/style.scss",
      "imports": [
        "scss/bootstrap/bootstrap.scss",
        "scss/bootstrap/_variables.scss",
        "scss/bootstrap/_functions.scss",
        "scss/bootstrap/_mixins.scss",
        "scss/bootstrap/_root.scss",
        "scss/bootstrap/_reboot.scss",
        "scss/bootstrap/_type.scss",
        "scss/bootstrap/_images.scss",
        "scss/bootstrap/_code.scss",
        "scss/bootstrap/_grid.scss",
        "scss/bootstrap/_tables.scss",
        "scss/bootstrap/_forms.scss",
        "scss/bootstrap/_buttons.scss",
        "scss/bootstrap/_transitions.scss",
        "scss/bootstrap/_dropdown.scss",
        "scss/bootstrap/_button-group.scss",
        "scss/bootstrap/_input-group.scss",
        "scss/bootstrap/_custom-forms.scss",
        "scss/bootstrap/_nav.scss",
        "scss/bootstrap/_navbar.scss",
        "scss/bootstrap/_card.scss",
        "scss/bootstrap/_breadcrumb.scss",
        "scss/bootstrap/_pagination.scss",
        "scss/bootstrap/_badge.scss",
        "scss/bootstrap/_jumbotron.scss",
        "scss/bootstrap/_alert.scss",
        "scss/bootstrap/_progress.scss",
        "scss/bootstrap/_media.scss",
        "scss/bootstrap/_list-group.scss",
        "scss/bootstrap/_close.scss",
        "scss/bootstrap/_toasts.scss",
        "scss/bootstrap/_modal.scss",
        "scss/bootstrap/_tooltip.scss",
        "scss/bootstrap/_popover.scss",
        "scss/bootstrap/_carousel.scss",
        "scss/bootstrap/_spinners.scss",
        "scss/bootstrap/_utilities.scss",
        "scss/bootstrap/_print.scss",
        "scss/bootstrap/vendor/_rfs.scss",
        "scss/bootstrap/mixins/_deprecate.scss",
        "scss/bootstrap/mixins/_breakpoints.scss",
        "scss/bootstrap/mixins/_hover.scss",
        "scss/bootstrap/mixins/_image.scss",
        "scss/bootstrap/mixins/_badge.scss",
        "scss/bootstrap/mixins/_resize.scss",
        "scss/bootstrap/mixins/_screen-reader.scss",
        "scss/bootstrap/mixins/_size.scss",
        "scss/bootstrap/mixins/_reset-text.scss",
        "scss/bootstrap/mixins/_text-emphasis.scss",
        "scss/bootstrap/mixins/_text-hide.scss",
        "scss/bootstrap/mixins/_text-truncate.scss",
        "scss/bootstrap/mixins/_visibility.scss",
        "scss/bootstrap/mixins/_alert.scss",
        "scss/bootstrap/mixins/_buttons.scss",
        "scss/bootstrap/mixins/_caret.scss",
        "scss/bootstrap/mixins/_pagination.scss",
        "scss/bootstrap/mixins/_lists.scss",
        "scss/bootstrap/mixins/_list-group.scss",
        "scss/bootstrap/mixins/_nav-divider.scss",
        "scss/bootstrap/mixins/_forms.scss",
        "scss/bootstrap/mixins/_table-row.scss",
        "scss/bootstrap/mixins/_background-variant.scss",
        "scss/bootstrap/mixins/_border-radius.scss",
        "scss/bootstrap/mixins/_box-shadow.scss",
        "scss/bootstrap/mixins/_gradients.scss",
        "scss/bootstrap/mixins/_transition.scss",
        "scss/bootstrap/mixins/_clearfix.scss",
        "scss/bootstrap/mixins/_grid-framework.scss",
        "scss/bootstrap/mixins/_grid.scss",
        "scss/bootstrap/mixins/_float.scss",
        "scss/bootstrap/utilities/_align.scss",
        "scss/bootstrap/utilities/_background.scss",
        "scss/bootstrap/utilities/_borders.scss",
        "scss/bootstrap/utilities/_clearfix.scss",
        "scss/bootstrap/utilities/_display.scss",
        "scss/bootstrap/utilities/_embed.scss",
        "scss/bootstrap/utilities/_flex.scss",
        "scss/bootstrap/utilities/_float.scss",
        "scss/bootstrap/utilities/_overflow.scss",
        "scss/bootstrap/utilities/_position.scss",
        "scss/bootstrap/utilities/_screenreaders.scss",
        "scss/bootstrap/utilities/_shadows.scss",
        "scss/bootstrap/utilities/_sizing.scss",
        "scss/bootstrap/utilities/_stretched-link.scss",
        "scss/bootstrap/utilities/_spacing.scss",
        "scss/bootstrap/utilities/_text.scss",
        "scss/bootstrap/utilities/_visibility.scss"
      ]
    },
    {
      "path": "scss/bootstrap/_mixins.scss",
      "imports": [
        "scss/bootstrap/vendor/_rfs.scss",
        "scss/bootstrap/mixins/_deprecate.scss",
        "scss/bootstrap/mixins/_breakpoints.scss",
        "scss/bootstrap/mixins/_hover.scss",
        "scss/bootstrap/mixins/_image.scss",
        "scss/bootstrap/mixins/_badge.scss",
        "scss/bootstrap/mixins/_resize.scss",
        "scss/bootstrap/mixins/_screen-reader.scss",
        "scss/bootstrap/mixins/_size.scss",
        "scss/bootstrap/mixins/_reset-text.scss",
        "scss/bootstrap/mixins/_text-emphasis.scss",
        "scss/bootstrap/mixins/_text-hide.scss",
        "scss/bootstrap/mixins/_text-truncate.scss",
        "scss/bootstrap/mixins/_visibility.scss",
        "scss/bootstrap/mixins/_alert.scss",
        "scss/bootstrap/mixins/_buttons.scss",
        "scss/bootstrap/mixins/_caret.scss",
        "scss/bootstrap/mixins/_pagination.scss",
        "scss/bootstrap/mixins/_lists.scss",
        "scss/bootstrap/mixins/_list-group.scss",
        "scss/bootstrap/mixins/_nav-divider.scss",
        "scss/bootstrap/mixins/_forms.scss",
        "scss/bootstrap/mixins/_table-row.scss",
        "scss/bootstrap/mixins/_background-variant.scss",
        "scss/bootstrap/mixins/_border-radius.scss",
        "scss/bootstrap/mixins/_box-shadow.scss",
        "scss/bootstrap/mixins/_gradients.scss",
        "scss/bootstrap/mixins/_transition.scss",
        "scss/bootstrap/mixins/_clearfix.scss",
        "scss/bootstrap/mixins/_grid-framework.scss",
        "scss/bootstrap/mixins/_grid.scss",
        "scss/bootstrap/mixins/_float.scss"
      ]
    },
    {
      "path": "scss/bootstrap/_utilities.scss",
      "imports": [
        "scss/bootstrap/utilities/_align.scss",
        "scss/bootstrap/utilities/_background.scss",
        "scss/bootstrap/utilities/_borders.scss",
        "scss/bootstrap/utilities/_clearfix.scss",
        "scss/bootstrap/utilities/_display.scss",
        "scss/bootstrap/utilities/_embed.scss",
        "scss/bootstrap/utilities/_flex.scss",
        "scss/bootstrap/utilities/_float.scss",
        "scss/bootstrap/utilities/_overflow.scss",
        "scss/bootstrap/utilities/_position.scss",
        "scss/bootstrap/utilities/_screenreaders.scss",
        "scss/bootstrap/utilities/_shadows.scss",
        "scss/bootstrap/utilities/_sizing.scss",
        "scss/bootstrap/utilities/_stretched-link.scss",
        "scss/bootstrap/utilities/_spacing.scss",
        "scss/bootstrap/utilities/_text.scss",
        "scss/bootstrap/utilities/_visibility.scss"
      ]
    },
    {
      "path": "scss/bootstrap/bootstrap-grid.scss",
      "imports": [
        "scss/bootstrap/_functions.scss",
        "scss/bootstrap/_variables.scss",
        "scss/bootstrap/mixins/_breakpoints.scss",
        "scss/bootstrap/mixins/_grid-framework.scss",
        "scss/bootstrap/mixins/_grid.scss",
        "scss/bootstrap/_grid.scss",
        "scss/bootstrap/utilities/_display.scss",
        "scss/bootstrap/utilities/_flex.scss",
        "scss/bootstrap/utilities/_spacing.scss"
      ]
    },
    {
      "path": "scss/bootstrap/bootstrap-reboot.scss",
      "imports": [
        "scss/bootstrap/_functions.scss",
        "scss/bootstrap/_variables.scss",
        "scss/bootstrap/_mixins.scss",
        "scss/bootstrap/_reboot.scss",
        "scss/bootstrap/vendor/_rfs.scss",
        "scss/bootstrap/mixins/_deprecate.scss",
        "scss/bootstrap/mixins/_breakpoints.scss",
        "scss/bootstrap/mixins/_hover.scss",
        "scss/bootstrap/mixins/_image.scss",
        "scss/bootstrap/mixins/_badge.scss",
        "scss/bootstrap/mixins/_resize.scss",
        "scss/bootstrap/mixins/_screen-reader.scss",
        "scss/bootstrap/mixins/_size.scss",
        "scss/bootstrap/mixins/_reset-text.scss",
        "scss/bootstrap/mixins/_text-emphasis.scss",
        "scss/bootstrap/mixins/_text-hide.scss",
        "scss/bootstrap/mixins/_text-truncate.scss",
        "scss/bootstrap/mixins/_visibility.scss",
        "scss/bootstrap/mixins/_alert.scss",
        "scss/bootstrap/mixins/_buttons.scss",
        "scss/bootstrap/mixins/_caret.scss",
        "scss/bootstrap/mixins/_pagination.scss",
        "scss/bootstrap/mixins/_lists.scss",
        "scss/bootstrap/mixins/_list-group.scss",
        "scss/bootstrap/mixins/_nav-divider.scss",
        "scss/bootstrap/mixins/_forms.scss",
        "scss/bootstrap/mixins/_table-row.scss",
        "scss/bootstrap/mixins/_background-variant.scss",
        "scss/bootstrap/mixins/_border-radius.scss",
        "scss/bootstrap/mixins/_box-shadow.scss",
        "scss/bootstrap/mixins/_gradients.scss",
        "scss/bootstrap/mixins/_transition.scss",
        "scss/bootstrap/mixins/_clearfix.scss",
        "scss/bootstrap/mixins/_grid-framework.scss",
        "scss/bootstrap/mixins/_grid.scss",
        "scss/bootstrap/mixins/_float.scss"
      ]
    },
    {
      "path": "scss/bootstrap/bootstrap.scss",
      "imports": [
        "scss/bootstrap/_functions.scss",
        "scss/bootstrap/_variables.scss",
        "scss/bootstrap/_mixins.scss",
        "scss/bootstrap/_root.scss",
        "scss/bootstrap/_reboot.scss",
        "scss/bootstrap/_type.scss",
        "scss/bootstrap/_images.scss",
        "scss/bootstrap/_code.scss",
        "scss/bootstrap/_grid.scss",
        "scss/bootstrap/_tables.scss",
        "scss/bootstrap/_forms.scss",
        "scss/bootstrap/_buttons.scss",
        "scss/bootstrap/_transitions.scss",
        "scss/bootstrap/_dropdown.scss",
        "scss/bootstrap/_button-group.scss",
        "scss/bootstrap/_input-group.scss",
        "scss/bootstrap/_custom-forms.scss",
        "scss/bootstrap/_nav.scss",
        "scss/bootstrap/_navbar.scss",
        "scss/bootstrap/_card.scss",
        "scss/bootstrap/_breadcrumb.scss",
        "scss/bootstrap/_pagination.scss",
        "scss/bootstrap/_badge.scss",
        "scss/bootstrap/_jumbotron.scss",
        "scss/bootstrap/_alert.scss",
        "scss/bootstrap/_progress.scss",
        "scss/bootstrap/_media.scss",
        "scss/bootstrap/_list-group.scss",
        "scss/bootstrap/_close.scss",
        "scss/bootstrap/_toasts.scss",
        "scss/bootstrap/_modal.scss",
        "scss/bootstrap/_tooltip.scss",
        "scss/bootstrap/_popover.scss",
        "scss/bootstrap/_carousel.scss",
        "scss/bootstrap/_spinners.scss",
        "scss/bootstrap/_utilities.scss",
        "scss/bootstrap/_print.scss",
        "scss/bootstrap/vendor/_rfs.scss",
        "scss/bootstrap/mixins/_deprecate.scss",
        "scss/bootstrap/mixins/_breakpoints.scss",
        "scss/bootstrap/mixins/_hover.scss",
        "scss/bootstrap/mixins/_image.scss",
        "scss/bootstrap/mixins/_badge.scss",
        "scss/bootstrap/mixins/_resize.scss",
        "scss/bootstrap/mixins/_screen-reader.scss",
        "scss/bootstrap/mixins/_size.scss",
        "scss/bootstrap/mixins/_reset-text.scss",
        "scss/bootstrap/mixins/_text-emphasis.scss",
        "scss/bootstrap/mixins/_text-hide.scss",
        "scss/bootstrap/mixins/_text-truncate.scss",
        "scss/bootstrap/mixins/_visibility.scss",
        "scss/bootstrap/mixins/_alert.scss",
        "scss/bootstrap/mixins/_buttons.scss",
        "scss/bootstrap/mixins/_caret.scss",
        "scss/bootstrap/mixins/_pagination.scss",
        "scss/bootstrap/mixins/_lists.scss",
        "scss/bootstrap/mixins/_list-group.scss",
        "scss/bootstrap/mixins/_nav-divider.scss",
        "scss/bootstrap/mixins/_forms.scss",
        "scss/bootstrap/mixins/_table-row.scss",
        "scss/bootstrap/mixins/_background-variant.scss",
        "scss/bootstrap/mixins/_border-radius.scss",
        "scss/bootstrap/mixins/_box-shadow.scss",
        "scss/bootstrap/mixins/_gradients.scss",
        "scss/bootstrap/mixins/_transition.scss",
        "scss/bootstrap/mixins/_clearfix.scss",
        "scss/bootstrap/mixins/_grid-framework.scss",
        "scss/bootstrap/mixins/_grid.scss",
        "scss/bootstrap/mixins/_float.scss",
        "scss/bootstrap/utilities/_align.scss",
        "scss/bootstrap/utilities/_background.scss",
        "scss/bootstrap/utilities/_borders.scss",
        "scss/bootstrap/utilities/_clearfix.scss",
        "scss/bootstrap/utilities/_display.scss",
        "scss/bootstrap/utilities/_embed.scss",
        "scss/bootstrap/utilities/_flex.scss",
        "scss/bootstrap/utilities/_float.scss",
        "scss/bootstrap/utilities/_overflow.scss",
        "scss/bootstrap/utilities/_position.scss",
        "scss/bootstrap/utilities/_screenreaders.scss",
        "scss/bootstrap/utilities/_shadows.scss",
        "scss/bootstrap/utilities/_sizing.scss",
        "scss/bootstrap/utilities/_stretched-link.scss",
        "scss/bootstrap/utilities/_spacing.scss",
        "scss/bootstrap/utilities/_text.scss",
        "scss/bootstrap/utilities/_visibility.scss"
      ]
    }
  ],
  "projectView": {
    "selectedView": "file-tree"
  },
  "fileWatcher": {
    "enabled": true,
    "watchedExtensions": [
      "less",
      "sass",
      "scss",
      "styl",
      "md",
      "markdown",
      "coffee",
      "js",
      "jade",
      "haml",
      "slim",
      "ls",
      "kit",
      "png",
      "jpg",
      "jpeg",
      "ts",
      "pug",
      "css",
      "html",
      "htm",
      "php"
    ]
  },
  "pathFilters": [
    "node_modules",
    ".*",
    "bower_components",
    "prepros.config",
    "Prepros Export",
    "prepros-6.config",
    "prepros.cfg",
    "wp-admin",
    "wp-includes"
  ],
  "server": {
    "port": 8003,
    "assignNewPortAutomatically": true,
    "enable": true,
    "proxy": {
      "enable": false,
      "url": ""
    }
  },
  "browser-sync": {
    "enable": false,
    "clicks": true,
    "forms": true,
    "scroll": true
  },
  "live-reload": {
    "enable": true,
    "animate": true,
    "delay": 0
  },
  "ftp-deploy": {
    "connectionType": "ftp",
    "remotePath": "",
    "uploadTimeout": 20000,
    "uploadOnChange": false,
    "ftp": {
      "secure": false,
      "keepAlive": true,
      "host": "",
      "port": 21,
      "user": "",
      "password": ""
    },
    "sftp": {
      "host": "",
      "port": 22,
      "usePrivateKey": false,
      "username": "",
      "password": "",
      "privateKey": "",
      "passphrase": ""
    },
    "pathFilters": [
      "config.rb",
      "prepros.config",
      "prepros-6.config",
      "node_modules",
      "Prepros Export",
      ".git",
      ".idea",
      ".sass-cache",
      ".hg",
      ".svn",
      ".cache",
      ".DS_Store",
      "*.sass",
      "*.scss",
      "*.less",
      "*.pug",
      "*.jade",
      "*.styl",
      "*.haml",
      "*.slim",
      "*.coffee",
      "*.ls",
      "*.kit",
      "*.ts"
    ],
    "history": []
  },
  "file-type-sass": "{\"compilers\":[\"node-sass\",\"autoprefixer\",\"minify-css\"]}",
  "file-type-less": "{\"compilers\":[\"less\",\"autoprefixer\",\"minify-css\"]}",
  "autoprefixer": {
    "browsers": "last 5 versions"
  },
  "file-type-pug": "{\"compilers\":[\"pug\"]}",
  "file-type-css": "{\"compilers\":[\"autoprefixer\",\"cssnext\",\"minify-css\"]}",
  "file-type-javascript": "{\"compilers\":[\"concat-js\",\"babel\",\"uglify-js\"]}",
  "file-type-stylus": "{\"compilers\":[\"stylus\",\"autoprefixer\",\"minify-css\"]}",
  "file-type-markdown": "{\"compilers\":[\"markdown\"]}",
  "file-type-haml": "{\"compilers\":[\"haml\"]}",
  "file-type-slim": "{\"compilers\":[\"slim\"]}",
  "file-type-coffee-script": "{\"compilers\":[\"coffee-script\",\"uglify-js\"]}",
  "file-type-livescript": "{\"compilers\":[\"livescript\",\"uglify-js\"]}",
  "file-type-kit": "{\"compilers\":[\"kit\"]}",
  "uglify-js": {
    "ie8": false,
    "compress": {
      "sequences": true,
      "properties": true,
      "dead_code": true,
      "drop_debugger": true,
      "unsafe": false,
      "unsafe_comps": false,
      "unsafe_math": false,
      "unsafe_proto": false,
      "unsafe_regexp": false,
      "conditionals": true,
      "comparisons": true,
      "evaluate": true,
      "booleans": true,
      "loops": true,
      "unused": true,
      "toplevel": false,
      "top_retain": "",
      "hoist_funs": true,
      "hoist_vars": false,
      "if_return": true,
      "join_vars": true,
      "collapse_vars": true,
      "reduce_vars": true,
      "warnings": true,
      "negate_iife": true,
      "pure_getters": false,
      "pure_funcs": [],
      "drop_console": false,
      "expression": false,
      "keep_fargs": true,
      "keep_fnames": false,
      "passes": 1,
      "keep_infinity": false,
      "side_effects": true,
      "global_defs": []
    },
    "output": {
      "ascii_only": false,
      "beautify": false,
      "comments": "",
      "indent_level": 4,
      "indent_start": 0,
      "inline_script": false,
      "keep_quoted_props": false,
      "max_line_len": false,
      "preamble": "",
      "preserve_line": false,
      "quote_keys": false,
      "quote_style": 0,
      "semicolons": true,
      "shebang": true,
      "width": 80
    }
  },
  "cssnext": {
    "customProperties": true,
    "applyRule": true,
    "calc": false,
    "nesting": true,
    "customMedia": true,
    "mediaQueriesRange": true,
    "customSelectors": true,
    "attributeCaseInsensitive": true,
    "colorRebeccapurple": true,
    "colorHwb": true,
    "colorGray": true,
    "colorHexAlpha": true,
    "colorFunction": true,
    "fontVariant": true,
    "filter": true,
    "initial": true,
    "rem": true,
    "pseudoElements": true,
    "pseudoClassMatches": true,
    "pseudoClassNot": true,
    "pseudoClassAnyLink": true,
    "colorRgba": true,
    "overflowWrap": true
  },
  "file-type-typescript": "{\"compilers\":[\"typescript\",\"uglify-js\"]}",
  "babel": {
    "useBabelRc": true,
    "presets": {
      "babel-preset-es2015": true
    },
    "plugins": {
      "babel-plugin-syntax-jsx": true,
      "babel-plugin-transform-react-jsx": true,
      "babel-plugin-transform-async-to-generator": true,
      "babel-plugin-transform-class-properties": true,
      "babel-plugin-transform-object-rest-spread": true
    }
  },
  "file-type-png": "{\"compilers\":[\"png\"]}",
  "file-type-jpg": "{\"compilers\":[\"jpg\"]}"
}
