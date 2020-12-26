<template>
  <div class="card">
        <header class="card-header">
            <slot name="cardHeader"></slot>
        </header>
        <div class="card-image">
           <slot name="cardImage"></slot>
        </div>
        <div class="card-content">
            <slot></slot>
        </div>
        <footer class="card-footer">
            <slot name="cardFooter"></slot>
        </footer>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>