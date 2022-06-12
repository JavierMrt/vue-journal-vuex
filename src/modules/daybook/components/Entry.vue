<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10} })"
  >
    <!-- Título -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">12</span>
        <span class="mx-1 fs-5">Junio</span>
        <span class="mx-2 fw-light">2022, sábado</span>
    </div>
    <div class="entry-description">
        Mollit duis tempor id aliqua ea culpa est aliqua excepteur. Nisi anim ad duis labore laborum reprehenderit commodo consectetur. Quis Lorem veniam veniam amet anim id dolore ut eiusmod ex. Eu nisi dolore irure culpa ipsum magna eu. Aute commodo do officia sint incididunt id. Occaecat ullamco nisi culpa culpa ex qui ullamco nulla quis eiusmod pariatur dolore. Laboris exercitation do officia consectetur aliquip magna aliquip.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount:  45);
        transition: 0.2s all ease-in;
    }

    .entry.description {
        font-size: 12px;
    }
}
</style>