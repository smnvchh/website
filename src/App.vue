<template>
    <div>
        <div class="post">
            <div><strong>Название: </strong>Пост о JavaScript</div>
            <div><strong>Описание: </strong>JavaScript универс яз прог</div>
            <div><strong>Hi: </strong>Hello</div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            likes: 0,
            dislikes: 0,
        }
    },
    methods: {
        addLike(){
            this.likes += 1;
        },
        addDislike(){
            this.dislikes += 1;
        }
    }    
    
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
</style>