<template lang="html">
	<div class="sticky-top bg-dark">
		<nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-5">
			<router-link :to="{name: 'index'}" class="navbar-brand">高雄市立美術館 展覽介紹</router-link>
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarTogglerDemo02">
				<ul class="navbar-nav ml-auto mt-2 mt-lg-0">
					<li class="nav-item active">
						<router-link :to="{name: 'searchInfo'}" :class="'nav-link'">搜尋當期展覽</router-link>
					</li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">相關連結</a>
						<div class="dropdown-menu border-0" aria-labelledby="navbarDropdownMenuLink">
							<a class="dropdown-item" href="http://www.kmfa.gov.tw/home01.aspx?ID=1" target='_blank'>高雄市立美術館</a>
							<a class="dropdown-item" href="http://khm.org.tw/home01.aspx?ID=1" target='_blank'>高雄市立歷史博物館</a>
						</div>
					</li>
				</ul>
				<form class="form-inline my-2 my-lg-0">
					<input class="form-control mr-sm-2" type="search" placeholder="Search">
					<button class="btn btn-outline-primary my-2 my-sm-0" type="submit">Search</button>
				</form>
			</div>
		</nav>
	</div>
</template>

<script>
export default {}
</script>

<style lang="css" scoped>

</style>
