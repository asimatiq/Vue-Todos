<template>
    <div>
        <div  v-bind:key="todo.id" v-for="todo in todos" class="todo-item-main">
            <Todoitem v-bind:todo="todo" />
        </div>
    </div>
</template>


<script>
import Todoitem from './Todoitem'; 

export default {
    name:"Todos",
    components:{
        Todoitem
    },
    props:["todos"]
}
</script>

<style scoped>

</style>