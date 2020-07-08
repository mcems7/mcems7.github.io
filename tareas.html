<!doctype html>
<html>
<head>
  <title>Ejercicio 2</title> 
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
</head>
<body>
  <div id="aplicacion">
      <div id="listado-tareas">
  <form v-on:submit.prevent="agregarTarea">
    <label for="nueva-tarea">Nueva tarea</label>
    <input
      v-model="nuevaTareaTexto"
      id="nueva-tarea"
      placeholder="Escriba aquí su tarea"
    >
    <button>+</button>
  </form>
  <ul>
    <li
      is="tarea-item"
      v-for="(tarea, index) in tareas"
      v-if="tarea.estado==verTareas"
      v-bind:key="tarea.id"
      v-bind:titulo="tarea.titulo"
      v-bind:estado="tarea.estado"
      v-on:estadoterminada="tarea.estado='Terminada'"
      v-on:estadopendiente="tarea.estado='Pendiente'"
    ></li>
  </ul>
  <button  v-on:click="verTareas='Pendiente'">Ver tareas Pendiente</button>
  <button  v-on:click="verTareas='Terminada'">Ver tareas Terminadas</button>
    
</div>
  </div>
  
  <script src="https://cdn.jsdelivr.net/npm/vue"></script>   

  <script>
    Vue.component('tarea-item', {
  template: `\
    <li>\
      {{ titulo }} {{ estado }}\
      <button v-show="estado==\'Pendiente\'" v-on:click="$emit(\'estadoterminada\')">Marcar como Terminada</button>\
      <button v-show="estado==\'Terminada\'" v-on:click="$emit(\'estadopendiente\')">Marcar como Pendiente</button>\
    </li>\
  `,     
  props: ['titulo', 'estado']
})

new Vue({
  el: '#listado-tareas',
  data: {
    nuevaTareaTexto: '',
    tareas: [
      {
        id: 1,
        titulo: 'Ejercicio hola mundo',
        estado: 'Pendiente',
      },
      {
        id: 2,
        titulo: 'Administración de tareas',
        estado: 'Pendiente',
      },
      {
        id: 3,
        titulo: 'Peticiones asincronas',
        estado: 'Pendiente',
      }
    ],
    sigTareaId: 4,
    verTareas: 'Pendiente'
  },
  methods: {
    agregarTarea: function () {
      this.tareas.push({
        id: this.sigTareaId++,
        titulo: this.nuevaTareaTexto,
        estado: 'Pendiente',
      })
      this.nuevaTareaTexto = ''
    }
  }
})
  </script>
</body>
</html>
