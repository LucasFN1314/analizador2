<template>
  <div>
    
  </div>
</template>

<script>
export default {
    data() {
        return {
            rows: [],
        }
    },
    methods: {

    },
    mounted() {
        /*
            1 - THIS.ROWS SERÁ LA VARIABLE DE IMPRESIÓN FINAL.
            2 - AL EJECUTAR UNA ACCIÓN SE MODIFICA VARIABLE LOCAL Y SE ALMACENA 
                AL FINAL DE LA EJECUCION EN LA VARIABLE DE IMPRESIÓN.
            3 - EL FILTRADO POR LISTA: RECIBIRÁ UNA LISTA CON LOS VALORES 
                CORRESPONDIENTES A UNA DETERMINADA CABECERA. 
                EJEMPLO:
                    [
                        {
                            DEPARTAMENTO: SERVICIO_1, SERVICIO_2, SERVICIO_3
                        }
                    ]
                ÉSTA FUNCION BUSCARÁ LAS FILAS QUE CONTENGAN EN UNA DETERMINADA
                COLUMNA, UN VALOR ASIGNADO A LA CABECERA. UNA VEZ ENCONTRADO
                INSERTARÁ UNA COLUMNA CON LA CABECERA Y AGRUPARÁ LAS FILAS
                SEGÚN CABECERA Y VALOR DE COLUMNA (ORDENADO).
                
            4 - ELIMINACIÓN DE FILAS: RECIBIRÁ UN ARGUMENTO Y UNA COLUMNA.
                TODA FILA QUE EN DESIGNADA COLUMNA CONTENGA UN VALOR
                EQUIVALENTE AL ARGUMENTO, SERÁ ELIMINADA.

            5 - 
        */
    },

}
</script>

<style>

</style>