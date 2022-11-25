<template>
  <header>
    <div class="container">
        <div class="left">
            <img src="@/img/dc-logo.png" class="logo">
        </div>
        <div class="right">
            <ul class="header-list">
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
            </ul>
        </div>
    </div>
  </header>
</template>

<script>
export default {
    name: 'HeaderPage',
}
</script>

<style lang="scss" scoped>
header {
    height: 120px;
}

.container {
    margin: 0 5rem;
    display: flex;
    justify-content: space-between;
}

.logo {
    width: 65px;
}

.left {
    padding: 2rem;
}

.right {
    height: 120px;
    display: flex;
    align-items: center;
}

.header-list {
    list-style-type: none;
    color: #303030;
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.header-list li {
    text-transform: uppercase;
}


</style>