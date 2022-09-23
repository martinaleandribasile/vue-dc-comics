<template>
    <div class="contContents">
        <div class="containerdef">
            <p>--> Content goes Here &lt;--</p>
        </div>
  </div>
</template>

<script>
export default {
name:'ContentDC'
}
</script>

<style scoped lang="scss">
 @mixin flexRowAlignCenter{
        display: flex;
        flex-direction: row;
        align-items: center;
    }
.contContents{ 
    background-color: black;
    height: 200px; 
    .containerdef{
        height: 100%;
    @include flexRowAlignCenter;
        p{
            @include flexRowAlignCenter;
            color: white;
            font-weight: bold;
        }
    }
}
</style>