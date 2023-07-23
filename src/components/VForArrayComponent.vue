<script setup>

const items = [

  {

    id: 1,

    title: "Item 1",

    description: "Description for Item 1"

  },

  {

    id: 2,

    title: "Item 2",

    description: "Description for Item 2"

  },

  {

    id: 3,

    title: "Item 3",

    description: "Description for Item 3"

  },

  {

    id: 4,

    title: "Item 4",

    description: "Description for Item 4"

  },

  {

    id: 5,

    title: "Item 5",

    description: "Description for Item 5"

  },

  {

    id: 6,

    title: "Item 6",

    description: "Description for Item 6"

  }

];

</script>


<template>
    <div class="container d-flex justify-content-center">
        <div class="col-lg-6">
            <div class="row ">
                <ul class="list-group" v-for="item in items" :key="item.id">
                    <li class="list-group-item  bg-dark text-light my-3" >
                        {{ item.title }} <br>
                        {{ item.description }}
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped></style>