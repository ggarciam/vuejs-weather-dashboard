<template>
    <div id="search">
        <input
                id="location-input"
                type="text"
                ref="input"
                placeholder="Lugar?"
                @keyup.enter="organizeAllDetails"
        >
        <button id="search-btn" @click="organizeAllDetails">
            <img src="./assets/Search.svg" width="24" height="24">
        </button>
        <label> {{ location }}</label>
    </div>
</template>

<script>
	export default {
		name: "Search"
	}
</script>

<style scoped>

</style>