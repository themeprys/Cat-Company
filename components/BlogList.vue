<template>
  <div>
    <div class="container">
        <div class="row g-5 mb-5" v-for="item in blogList" :key="item.id">
            <div class="col-4">
                <img src="/img/placeholder/640x480.jpg" class="img-fluid" alt=""/>                
            </div>
            <div class="col">
                <h1>Lorem Ipsum</h1>
                <p>Posted on 30 Oct 2022</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, labore, repudiandae porro culpa quo officiis voluptatum ex quos voluptatibus dolorum soluta deleniti. Tenetur dolorum repellat dolorem expedita, illum similique distinctio.</p>
                <nuxt-link to="/" class="btn btn-primary">
                    Read More
                </nuxt-link>
            </div>

        </div>
    </div>
  </div>
</template>

<script>
export default {
data() {
    return {
        blogList: [
            {
                id: '1',
            },
            {
                id: '1',
            },
            {
                id: '1',
            },
            {
                id: '1',
            },
            {
                id: '1',
            },                                                
        ]
    }
}
}
</script>

<style>

</style>