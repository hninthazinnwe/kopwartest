<template>
	<div class="header">
		<nav 
			class="navbar fixed-top" 
			id="navbar"
			:class="{ 'navbar--hidden': !showNavbar }"
		>
			<div class="container">
				<a class="navbar-brand" href="#">
					<img
							src="../assets/img/kopwar_logo.jpg"
							class="rounded-circle ms-5 mt-2 my-2"
							height="70"
							alt=""
							loading="lazy"
					/>
				</a>
				<ul class="navbar-nav d-flex justify-content-end flex-row px-5">
					<li class="nav-item">
						<a class="nav-link fw-bold active" href="#home">
							Home
						</a>
					</li>
					<li class="nav-item">
						<a class="nav-link fw-bold" href="#about">
							About
						</a>
					</li>
				</ul>
			</div>
		</nav>
	</div>
</template>
<script>
export default {
   name: 'header',
   data() {
			return{
				showNavbar: true,
				lastScrollPosition: 0
			}
   },
   methods: {
			onScroll () {
				window.pageYOffset>0?this.showNavbar=false:this.showNavbar=true;
			}
    },
    mounted () {
			window.addEventListener('scroll', this.onScroll)
    },
    Destroy () {
			window.removeEventListener('scroll', this.onScroll)
    }
}
</script>
<style>
	.header {
		width: 100%;
		background-color: #F2F3F7;
	}
	.logo {
		border-radius: 80%;
	}
	#navbar {
		padding: 0px 160px;
		overflow: hidden;
		box-shadow: none;
		transition: all 0.2s;
	}

	#navbar a {
		float: left;
		display: block;
		color: #000000;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
		font-size: 17px;
	}

	#navbar a:hover {
		color: #312ba7;
	}

	#navbar a.active {
		color: #5954cb;
	}

	#navbar.navbar--hidden {
		width: 100%;
		background-color: #ffffff !important;
		transition: all 0.5s;
		z-index: 999;
	}
	.fade-enter-active
	{
		transition: all 1s;
	}
	.fade-leave-active {
		transition: all 2s;
	}
	.fade-enter, .fade-leave-to  {
		opacity: 0;
	}
	@media (min-width: 768px) {
		#nav {
				padding: 0px 160px;
		}
	}
	@media (max-width: 768px) {
		#navbar {
				padding: 10px !important;
		}
	}
</style>