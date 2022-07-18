
<template>
    <div class="d-flex">
        <div id="sidebar-container" class="bg-primary">
          <div class="menu">
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-briefcase d-block sub2"></i>Empleos</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-file-earmark-check d-block sub2"></i>Postulaciones</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-book d-block sub2"></i>Profesores</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-controller d-block sub2"></i>Cursos y retos</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-chat-text d-block sub2"></i> Preguntas</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-gem d-block sub2"></i>Premios</a>
            <a href="#" class="d-block p-2 text-center sub">
              <i class="bi bi-file-earmark-person d-block sub2"></i>CV</a>
            <a href="#" class="d-block p-2 text-center sub">PEAKU APP</a>
          </div>
        </div>
      </div>
</template>

<script>
export default{
  name: 'App-Lat'
}
</script>

<style scoped>
 #sidebar-container{
        margin-top: 3rem;
        min-height: 100vh;

      }
      .bg-primary{
        background-color: #fff !important;
        position: relative;
        position: fixed;
      }
      #sidebar-container .menu{
        width: 6rem;
      }
      .menu{
        margin: auto;
      }
      .menu a{
        width: 80% !important;
        font-weight: bold;
        text-decoration: none;
        color: #000;
        margin: 0px auto;
        font-size: 10px;
        
      }
      .sub{
        font-size: 12px;
      }
      .sub:hover{
        border-radius: 10px;
        background-color: rgba(111,202,255,.53333)
      }
      .sub2{
        font-size: 25px;
      }
</style>