<template>
  <div class="entry-title d-flex justify-content-between p-2"> 
    <div>
        <span class="text-sucess fs-3 fw-bold">15</span>
        <span class="mx-1 fs-3 ">Junio</span>
        <span class="mx-2 fs-4 fw-light">2021, Miercoles</span>
    </div>
    <div>
        <button class="btn btn-danger mx-2">Borrar <i class="fa fa-trash-alt"></i></button>
        <button class="btn btn-primary">Subir foto <i class="fa fa-upload"></i></button>
    </div>
  </div>
<hr>

<div class="d-flex flex-column px-3 h-75">
    <textarea placeholder="¿Que sucedio hoy?"></textarea>
</div>
<Fab icon="fa-save"></Fab>
<img src="https://e1.pxfuel.com/desktop-wallpaper/119/143/desktop-wallpaper-4-landscape-spring.jpg" class="img-thumbnail">
</template>

<script>
import Fab from '@/modules/daybook/components/Fab.vue'

export default {
components: {
    Fab
}
}
</script>

<style lang="scss" scoped>
textarea {
font-size: 20px;
border: none;
height: 100%;
&:focus {
outline: none;
}
}

img {
    width: 200px;
    position: fixed;
    bottom: 150px;
    right: 20px;
    box-shadow: 0 5px 10px rgba(0,0,0,0.2);
}
</style>