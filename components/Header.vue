<template>
    <div>
        <div class="container flex justify-between">
            <nuxt-link to="/" class="flex font-size-32 font-semibold">
            <img src="~/assets/img/logo.png" height="30" width="50" alt=""> Amar Shop
            </nuxt-link>

            <div class="w-96">
                <div class="border-gray-100 p-1 flex">
                    <div class="min-w-max">
                       <img src="~/assets/img/search.png" height="20" width="25" alt=""> 
                    </div>
                    <input type="search" placeholder="Search here ..">
                    <button class="bg-gray bs-button-bd" type="submit"> Search</button>
                </div>
            </div>

            <div class="min-max flex">
                <nuxt-link to="/"> <img src="~/assets/img/heart.png" height="20" width="25" alt=""></nuxt-link>
                 <nuxt-link to="/"> <img src="~/assets/img/shopping-bag-icon-png-22.jpg" height="20" width="25" alt=""><span>0</span></nuxt-link>
                 <nuxt-link to="/"> <img src="~/assets/img/user.png" height="20" width="25" alt=""><span>0</span></nuxt-link>
            </div>
        </div>
        <!-- <ul>
            <li><nuxt-link to="/">Home</nuxt-link></li>
            <li><nuxt-link to="/about">About</nuxt-link></li>
        </ul> -->
    </div>
</template>

<script>

export default {
    name: 'Header'
}
</script>
