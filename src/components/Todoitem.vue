<template>
    <div class="todo-item">
        <p >{{ todo.title }}</p>
    </div>
</template>

<script>
export default {
    name:"Todoitem",
    props:["todo"]
}
</script>

<style scoped>
    .todo-item{
        color: blueviolet;
    }
</style>