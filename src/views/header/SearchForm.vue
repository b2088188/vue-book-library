<template>
	<form class="search">
		<input
			type="text"
			placeholder="Please Search a Book Name"
			class="search__field"
			name="searchfield"
		/>
		<button class="btn search__btn">
			<i class="search__icon" />
			<span>Search</span>
		</button>
	</form>
</template>

<script>
export default {
	name: "SearchForm",
};
</script>

<style lang="scss" scoped>
// .search {
// 	margin-left: 30rem;
// 	margin-top: 2.5rem;
// 	width: 50%;

// 	&__field {
// 		padding: 0 2rem;
// 		height: 5rem;
// 		width: 30rem;
// 		display: inline-block;
// 		border: none;
// 		border-radius: 3rem 0 0 3rem;
// 		font-size: 1.7rem;
// 		font-weight: 600;
// 		font-family: inherit;
// 		line-height: 1.7;
// 		color: inherit;

// 		&:focus {
// 			outline: none;
// 		}

// 		&::-moz-placeholder {
// 			color: $color-grey-dark-2;
// 		}

// 		&:-ms-input-placeholder {
// 			color: $color-grey-dark-2;
// 		}

// 		&::placeholder {
// 			color: $color-grey-dark-2;
// 		}
// 	}

// 	&__btn {
// 		background-image: linear-gradient(
// 			to right,
// 			$color-tiffany-default,
// 			$color-sky-blue
// 		);
// 		color: $color-white;
// 		padding: 1rem;
// 		transform: translateX(-7rem);
// 		display: inline-block;
// 		width: 20rem;
// 		height: 5rem;
// 		border: none;
// 		border-radius: 3rem;
// 		transition: all 0.3s;

// 		&:hover {
// 			box-shadow: 0 1rem 1.5rem rgba($color-black, 0.2);
// 		}

// 		span {
// 			font-size: 2rem;
// 			font-weight: 200;
// 		}
// 	}

// 	&__icon {
// 		width: 20%;
// 		height: 60%;
// 		fill: $color-white;
// 	}
// }
</style>
