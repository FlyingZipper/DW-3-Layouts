<template>
    <div id="content-box" class="bg-teal" >
        <div id="content" class="container" >
            Content
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    #content-box{
        display: flex;
        flex-flow: column wrap;
        flex-grow: 1;
    }

    #content{
        width: 100%;
    }

    /* Add you CSS below */
    /* ---------------------------------------------------------------- */

    .bg-teal{
        background: rgb(148, 218, 218);
    }

</style>
