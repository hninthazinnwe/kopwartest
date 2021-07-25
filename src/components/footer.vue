<template>
	<div class="footer">
		<div class="d-flex justify-content-center pattern-1">
			<div class="row">
				<div class="col-lg-3">
					<img class="rounded-circle" src="../assets/img/kopwar_logo.jpg" alt="" width="50">
					<p class="small">KOPWAR is an online store. Begin as a foodservice provider to business and other service. By using our app, you will never need to go to Market and get your hand dirty.</p>
				</div>
				<div class="col-lg-2"></div>
				<div class="col-lg-2"></div>
				<div class="col-lg-5">
					<h2 class="h5 mb-4">Contact Info</h2>
					<ul class="list-unstyled mr-4 mb-3">
						<li class="mb-2">Shwe Hintha Road 2, No. 58, Hlaing Township,Yangon </li>
						<li class="mb-2"><a href="tel:09447407050">09447407050</a></li>
						<li class="mb-2"><a href="mailto:sane.l.wunn@gmail.com">sane.l.wunn@gmail.com</a></li>
						</ul>
						<ul class="list-inline mb-0">
						<li class="list-inline-item"><a href="#"><i class="fab fa-facebook-f fa-2x"></i></a></li>
						<li class="list-inline-item"><a class="social-link" href="#"><i class="fab fa-twitter fa-2x"></i></a></li>
						<li class="list-inline-item"><a class="social-link" href="#"><i class="fab fa-google-plus fa-2x"></i></a></li>
						<li class="list-inline-item"><a class="social-link" href="#"><i class="fab fa-instagram fa-2x"></i></a></li>
					</ul>
				</div>
			</div>
		</div>
		<div class="copyrights">       
			<div class="container text-center pt-5 py-4">
				<p class="mb-0 text-muted text-sm"> Copyright © Kopwar Website 2021.</p>
			</div>
		</div>
	</div>
</template>
<script>
export default {
	name: 'footer'
}
</script>
<style scoped>
	.footer {
		position: relative;
		font-family: "Montserrat", sans-serif;
		padding: 80px 250px;
	}
	.pattern-1::before {
		content: '';
		position: absolute;
		background: url(../assets/img/pattern.png);
		width: 265px;
		height: 325px;
		right: 0px;
		bottom: 100px;
		top: 0px;
		background-repeat: no-repeat;
		z-index: 1;
	}
	a {
		text-decoration: none;
		color: #777777!important;
	}
</style>