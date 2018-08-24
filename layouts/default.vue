<template>
  <div>
    <nav class="navbar is-spaced" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <nuxt-link class="navbar-item logo" to="/">
            <img src="~/assets/hop.png"/>
          </nuxt-link>
        </div>
        <div class="navbar-menu">
          <div class="navbar-start">
             <navbar-item>
               <nuxt-link class="navbar-item logo" to="/styleguide">
                <span>Styleguide</span>
               </nuxt-link>
             </navbar-item>
          </div>
        </div>
    </nav>
    <nuxt/>
  </div>
</template>

<style>

</style>

