<template>
  <div>

  <b-nav>
    <b-nav-item active to="/">Home</b-nav-item>
    <b-nav-item to="/ping">Ping</b-nav-item>
    <b-nav-item to="/persons">CRUD Person</b-nav-item>
    <b-nav-item to="/alumnos">CRUD Alumno</b-nav-item>
    <b-nav-item to="/docentes">CRUD Docente</b-nav-item>
    <b-nav-item to="/rol">CRUD Rol</b-nav-item>
    <b-nav-item to="/sesiones">CRUD Sesión</b-nav-item>
    <b-nav-item to="/tareas">CRUD Tarea</b-nav-item>
    <b-nav-item to="/niveles">CRUD NivelEducativo</b-nav-item>
    <b-nav-item to="/grados">CRUD GRADO</b-nav-item>
    <b-nav-item to="/login">Login</b-nav-item>
    <b-nav-item to="/logout">Salir</b-nav-item>
  </b-nav>
  <b-container >

    <router-view/>
    </b-container >
  </div>
</template>


<style>
.appx {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
