<template>
  <div class="entry-container mb-3 pointer p-2"
       @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <!-- titulo -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fwlight">2021, jueves</span>
    </div>
    <div class="entry-description">
        Elit in sit esse tempor dolor minim nisi esse Lorem. Sunt amet fugiat ad officia exercitation labore qui cupidatat. Consequat mollit ipsum ex in enim nulla adipisicing. Nisi veniam eu incididunt sunt. Mollit excepteur mollit consequat officia aute aliquip ipsum. Velit officia eu exercitation culpa eiusmod laborum laborum amet.
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover{
            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2s all ease-in;
        }

        .entry-description {
            font-size: 12px;
        }
    }

</style>