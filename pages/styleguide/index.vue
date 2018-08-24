<template>
    <section>
        <div>
            <h1 class="title is-1 beer-title">American Pale Ale</h1>
        </div>
        <div class="columns">
            <div class="column">
                <img src="~/assets/beer.png"/>
            </div>
            <div class="column">
                    <section class="padded">
                        <blockquote>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur lobortis felis pharetra lacus accumsan viverra. Ut purus mi, blandit vehicula erat eu, tempor fringilla turpis.
                        </blockquote>
                        <h1 class="emojis">
                            🍊🌲
                        </h1>
                    </section>
            </div>
        </div> 
        <div class="container padded">
            <div class="tabs is-fullwidth">
                <ul>
                    <li><a>Style</a></li>
                    <li><a>Hops</a></li>
                    <li><a>Malt</a></li>
                    <li><a>Yeast</a></li>
                </ul>
            </div>
            <div class="columns">
                <div class="column">
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur lobortis felis pharetra lacus accumsan viverra. Ut purus mi, blandit vehicula erat eu, tempor fringilla turpis.
                    </p>
                </div>
                <div class="column">
                    <p>
                        <img src="~/assets/beer-style.png"/>
                    </p>
                </div>
            </div>
        </div>   
    </section>
</template>

<script>

</script>

<style>
.beer-title {
    text-align: center;
    padding-bottom: 20px;
}

.padded {
    padding:0% 10%;
}

.emojis{
    font-size: 300%
}
</style>