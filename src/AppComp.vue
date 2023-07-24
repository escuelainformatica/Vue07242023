<script setup>
    const message = "hola";
    let variable=2000;
    let variable2=200+300;
    let cliente={
        nombre:"john",apellido:"doe"
    };
    let paises=["chile","argentina","peru"];
</script>
<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col">
                <h1>{{ message }}</h1>
                variable:<b>{{ variable }}</b><br>
                variable2:<b>{{ variable2 }}</b><br>
                cliente:<b>{{ cliente.nombre }} {{ cliente.apellido }}</b><br>
                <ul>
                    <li v-for="pais of paises">{{ pais }}</li>
                </ul>
                <ul class="list-group">
                    <li v-for="pais of paises" class="list-group-item">{{ pais}}</li>

                </ul>
            </div>
        </div>
    </div>
</template>
