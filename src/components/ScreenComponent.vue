<template>
    <div>

    </div>
</template>

<script>
class columna {
    constructor(id, col_pos, cells,) {
        this.filas = [];
    }

    añadir_fila(fila) {
        this.filas.push(fila);
    }

    filtrar_por_listado(lista) {
        lista.map((val_bag) => {
            val_bag.values.map((val) => {
                // AGRUPAR ROWS DONDE LA COL INDICADA = VAL

            });
        });
    }

    añadir_menu_estatico(acciones) {
        // acciones = [{'nombre':'Filtrar por listado', 'funcion': 'filtrar_por_listado'} ]

        /*
            EJEMPLO
            <script type="text/javascript">
            function changeColor(color) {
                document.querySelector('.example').style
                    = `color: ${color}`;
            }
              
            function evaluateFunction() {
                stringFunction = "changeColor";
                param = 'green';
                window[stringFunction](param);
            }
        */
    }
}

class archivo {
    constructor(data) {
        this.data = data;
    }
}

class tabla {
    constructor() {
        this.columnas = [];
    }

    añadir_columna(columna) {
        this.columnas.push(columna);
    }
}

class menu_flotante {
    constructor() {

    }
}

class menu_estatico {
    constructor(col_id) {

    }
}

export default {
    data() {
        return {
            rows: [],
            cols: [],
        }
    },
    methods: {
        agregar_columna() {

        },

        separar_en_hojas(columna, valor) {

        },

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

            5 - CONTEO: SE DETERMINA LA COLUMNA A ANALIZAR Y SE DEBE ESPECIFICAR
                QUE COLUMNA SERA LA VARIABLE MINIMIZADA.

            6 - SUMA: DEBE DEFINIRSE UNA COLUMNA COMO VALOR INDICATIVO DE BLOQUE.
                UNA VEZ DEFINIDO EL BLOQUE, SE CONTABILIZARA LA COLUMNA INDICADA
                DEJANDO EL RESULTADO EN LA CABECERA DEL BLOQUE. DE SER POSIBLE
                SE AGREGARA EN LA PRIMER FILA DEL BLOQUE EN SU FINAL.

            7 - PORCENTAJE EN RELACION: SE DETERMINARA UNA COLUMNA CONTABLE,
                UNA COLUMNA IDENTIFICATORIA DE BLOQUE. SE DEBE INDICAR UNA
                FILA DEL BLOQUE Y UNA COLUMNA (X, Y) PARA ELEGIR LA CELDA
                REFERENCIAL PARA EL CALCULO PORCENTUAL.
                DEBE TAMBIEN ELEGIRSE UNA COLUMNA PARA EL ALMACENAJE DEL
                RESULTADO.

            9 - CREACION MANUAL DE FILAS Y COLUMNAS.

            10 - DIVIDIR EN HOJAS POR BLOQUE: DEFINIR COLUMNA CABECERA DE BLOQUE.
        */
    },

}
</script>

<style>

</style>