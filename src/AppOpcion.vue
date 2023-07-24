<script>
//  MVVM MODELO VISTA VISTA-MODELO
// la vista es el template.
// modelo: a los datos

// esto es opciones:
export default {
  data() {
    return {
      message: 'Hello World!',
      variable:2000,
      variable2:100+200
    }
  }
}
</script>

<template>
  <h1>{{message}}</h1>
  variable:{{ variable }}<br>
  variable2:{{ variable2 }}<br>

</template>

