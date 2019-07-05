<template>
    <div>
        <h1>EWHA EMOJI</h1>
        <div >
            <ul class="nav">
                <li>
                    <a class="a">메인</a>
                </li>
                <li >
                    <a class="a">지원하기</a>
                </li>
                <li>
                    <a class="a">결과</a>
                </li>
            </ul>
        </div>
    </div>
    <!-- <section class="section section--menu" id="Prospero">

	<h2 class="section__title">EWHA EMOJI</h2>

	<nav class="menu menu--prospero">

		<ul class="menu__list">
			<li class="menu__item menu__item--current">
				<a class="menu__link">메인</a>
			</li>
			<li class="menu__item">
				<a class="menu__link">지원하기</a>
			</li>
			<li class="menu__item">
				<a class="menu__link">결과</a>
			</li>
			
		</ul>
		
	</nav>

</section> -->
</template>

<script>
export default {

}
</script>

<style scoped>
h1 {
  color: #2F3b52;
  font-weight: 900;
  margin: 2.5rem 0 1.5rem;
}

.nav {
    display:flex;
    background-color: #2F3b52;
    justify-items: center;
    list-style: none;
    margin:0px;
    padding:0px;
} 

.nav li {
    flex: 1;
    color: white;
    border: 0.5px solid #b1adad3d;
    padding:0.5rem;
    cursor:pointer;
} 

ul.nav li {
    -webkit-transition: background-color 0.3s linear;
    -moz-transition: background-color 0.3s linear;
    -ms-transition: background-color 0.3s linear;
    -o-transition: background-color 0.3s linear;
    transition: background-color 0.3s linear;
}

ul.nav li:hover {
    background-color: #f6151569;
}

/* .menu {
	line-height: 1;
	margin: 0 auto 3em;
}

.menu__list {
	position: relative;
	display: -webkit-flex;
	display: flex;
	-webkit-flex-wrap: wrap;
	flex-wrap: wrap;
	margin: 0;
	padding: 0;
	list-style: none;
}

.menu__item {
	display: block;
	margin: 1em 0;
}

.menu__link {
	font-size: 1.05em;
	font-weight: bold;
	display: block;
	padding: 1em;
	cursor: pointer;
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	-webkit-touch-callout: none;
	-khtml-user-select: none;
	-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.menu__link:hover,
.menu__link:focus {
	outline: none;
}

/* Prospero */

/* .menu--prospero .menu__link {
	position: relative; */
	/* display: block; */
	/* margin: 0.5rem;
	padding: 0.75em 0;
	text-align: center;
	color: #b5b5b5;
	transition: color 0.3s;
}

.menu--prospero .menu__link:hover,
.menu--prospero .menu__link:focus {
	color: #929292;
}

.menu--prospero .menu__item--current .menu__link {
	color: #d94f5c;
}

.menu--prospero .menu__link::before {
	content: '';
	position: absolute;
	left: 0;
	bottom: 0;
	width: 100%;
	height: 4px;
	background: #d94f5c;
	transform: scale3d(0, 1, 1);
	transition: transform 0.1s;
}

.menu--prospero .menu__item--current .menu__link::before {
	transform: scale3d(1, 1, 1);
	transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
	transition-duration: 0.3s;
}  */
</style>
