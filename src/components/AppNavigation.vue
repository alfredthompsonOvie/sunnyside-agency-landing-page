<template>
	<nav>
		<div class="branding">
			<router-link :to="{name: 'home'}">
				<img src="../assets/images/logo.svg" alt="site logo" />
			</router-link>
		</div>

		<!-- mobile nav -->
		<!-- hamburger -->
		<button
			v-if="mobile"
			@click.prevent="mobileMenu = !mobileMenu"
			class="menu__btn"
			:class="{ active: mobileMenu }"
		>
			<img src="../assets/images/icon-hamburger.svg" alt="menu icon" />
		</button>
		<!-- mobile menu -->
		<ul class="mobileNav" v-if="mobileMenu">
			<li>
				<router-link to="#about" class="mobileNav__link">About</router-link>
			</li> 
			<li>
				<router-link :to="{name: 'services'}" class="mobileNav__link">Services</router-link>
			</li>
			<li>
				<router-link :to="{name: 'crojects'}" class="mobileNav__link">Projects</router-link>
			</li>
			<li>
				<router-link :to="{name: 'contact'}" class="mobileNav__link mobileNav__cta">Contact</router-link>
			</li>
		</ul>

		<!-- larger screen -->
		<ul class="nav__list" v-if="!mobile">
			<li>
				<a href="#" class="nav__link">About</a>
			</li>
			<li>
				<a href="#" class="nav__link">Services</a>
			</li>
			<li>
				<a href="#" class="nav__link">Projects</a>
			</li>
			<li>
				<a href="#" class="nav__link nav__cta">Contact</a>
			</li>
		</ul>
	</nav>
</template>

<script>
export default {
	name: "AppNavigation",
	data() {
		return {
			mobile: null,
			mobileMenu: null,
			windowWidth: null,
		};
	},
	created() {
		this.checkScreen();
		window.addEventListener("resize", this.checkScreen);
	},
	methods: {
		checkScreen() {
			this.windowWidth = window.innerWidth;

			if (this.windowWidth < 700) {
				this.mobile = true;
				this.mobileMenu = false;
				return;
			}
			this.mobile = false;
			this.mobileMenu = false;
			return;
		},
	},
};
</script>

<style scoped>
nav {
	position: absolute;
	top: 0;
	left: 0;
	right: 0;

	padding: 1.5em 2em;

	display: grid;
	grid-template-columns: 1fr 1fr;
	grid-template-rows: auto auto;
	justify-content: space-between;
	align-items: center;
}
.branding {
	grid-column: 1;
	grid-row: 1;
	justify-self: start;
}
.menu__btn {
	grid-column: 2;
	grid-row: 1;

	justify-self: end;
	display: inline-block;
	cursor: pointer;

	transition: all 0.3s linear;
}
.active {
	transform: rotate(360deg);
}

.mobileNav {
	grid-column: 1/-1;
	grid-row: 2;
	position: relative;
	top: 4em;

	background-color: var(--White);
	text-align: center;
	padding: 1em 0 2.2em;
}
.mobileNav::before {
	content: "";
	position: absolute;
	top: -2em;
	right: 0;
	background-color: var(--White);
	width: 2em;
	height: 2em;
	clip-path: polygon(100% 0, 100% 100%, 0 100%);
}
.mobileNav li {
	margin: 0.4em 0;
}
.mobileNav__link {
	display: inline-block;
	padding: 1em 3em;
	color: var(--DarkGrayishBlue);
	font-weight: var(--fw-bold);
	font-family: var(--ff-text);
}
.mobileNav__cta {
	background-color: var(--Yellow);
	border-radius: 40px;
}
@media (min-width: 700px) {
	nav {
		position: absolute;
		top: 0;
		left: 0;
		right: 0;

		padding: 1.5em 2em;

		display: flex;
		justify-content: space-between;
		align-items: center;
	}
	.nav__list {
		display: flex;
		gap: 2em;
	}
	.nav__link {
    color: var(--White);
    /* padding: 1em 2em; */
	}
  .nav__cta {
    background-color: var(--White);
    color: var(--VeryDarkDesaturatedBlue);
    text-transform: uppercase;
    border-radius: 40px;
    padding: 1em 2em;

  }
}
</style>
