<h2>Challenge para Desarrollador Frontend</h2>
<aside>
    <h3>Objetivo</h3>
    <p>
        Desarrollar una aplicación web con <strong>Typescript</strong>, <strong>Vue 3</strong> y <strong>vuetify</strong> con caracteristicas similares a una red social enfocada en visualizar y comentar Pokemones
    </p>
</aside>
<hr></hr>
<aside>
    <h3>Requerimientos</h3>
    <ol>
        <li>
            <h4>Primera instancia: Identificación de un usuario</h4>
            <p>Si bien no contemplamos de un backend para registro e inicio de sesión de un usuario es importante guardar datos como el nombre de usuario y un avatar en el localstorage para poder utilizarlo en una modificación posterior y poder identificar un usuario en cuestión</p>
            <ul>
                <li>Crear una pantalla principal en donde el usuario ponga sus datos.</li>
                <li>Podes añadir todos los datos que requieras utilizar. Como recomendación minima un nombre de usuario y un avatar.</li>
                <li>Almacenar información en LocalStorage o una DB local del navegador.</li>
                <li>Redirigir a la sección principal.</li>
                <li>Realizar validaciones necesarias, con mensajes amigables para el usuario.</li>
            </ul>
        </li>
        <li>
            <h4>Segunda instancia: Página principal</h4>
            <p>La página principal debe constar de dos secciones una para mostrar los pokemones (Principal), segunda sección difusiones sobre pokemones</p>
            <h4>Sección de Pokemones</h4>
            <ul>
                <li>Una interfaz en la cual se muestren pokemones en modo de tarjeta</li>
                <li>Debe tener la posibilidad de darle "Me Gusta" y "Comentar"</li>
                <li>Los me gusta deben poder ponerse y sacarse. Tambien debe quedar guardado si le dio me gusta el usuario y cuantos me gusta tiene</li>
                <li>Los comentarios deben poder editarse y eliminarse</li>
                <li>Debe tener un botón de "Crear Difusión" con la posibilidad de añadirlo como difusión en la segunda sección</li>
            </ul>
            <h4>Sección de Difusiones</h4>
            <ul>
                <li>Las difusiones se crean desde la sección de pokemones</li>
                <li>Una vez creada una difusión esta podrá editarse solo dentro de la proxima hora</li>
                <li>Las difusiones no pueden borrarse</li>
                <li>Deben tener comentarios con la posibilidad de responderlos</li>
                <li>Posibilidad de darle "Me Gusta" "No me Gusta" a la difusión y a los comentarios en ella.</li>
            </ul>
        </li>
        <li>
            <h4>Tecnologías</h4>
            <ul>
                <li>Typescript</li>
                <li>Vue3</li>
                <li>Vuetify (Excluyente)</li>
            </ul>
        </li>
        <li>
            <h4>Pautas de Evaluación</h4>
            <p>Se evaluarán los siguientes aspectos en la creación de la aplicación</p>
            <ul>
                <li>
                    <strong>Elegancia del código</strong> en cuanto a buenas prácticas en desarrollo con typescript y vue3.
                </li>
                <li>
                    <strong>Organización del proyecto</strong> y <strong>Estructuración Modular.</strong>
                </li>
                <li>
                    <strong>Manejo de validaciones</strong> para evitar posibles errores, como caída del servidor o error en endpoints.
                </li>
                <li>
                    <strong>UX/UI</strong> en cuanto a una interfaz intuitiva y agradable para el usuario
                </li>
                <li>
                    <strong>Diseño responsivo</strong> con variabilidad de ajustes a diferentes pantallas manteniendo el requisito anterior.
                </li>
            </ul>
        </li>
        <li>
            <h4>Documentación de importancia</h4>
            <ul>
                <li>
                    Para la obtención de Pokemones utilizar <a href="https://pokeapi.co/">PokeAPI v2</a>
                </li>
                <li>
                    Para gestionar los me gusta y comentarios de los pokemones utilizar
                    <a href="https://67d81f029d5e3a10152d7c98.mockapi.io/api/v1/pokemon">MockApi pokemon</a>, ten en cuenta que no tiene validaciones de esquemas. Para la documentación de endpoints visita <a href="https://github.com/mockapi-io/docs/wiki/Quick-start-guide">MockApi Docs</a>.
                </li>
                <li>
                    Para gestionar las difusiones de los pokemones utilizar <a href="https://67d81f029d5e3a10152d7c98.mockapi.io/api/v1/collab-chat">MockApi collab-chat</a>. Para la documentación de endpoints visita <a href="https://github.com/mockapi-io/docs/wiki/Quick-start-guide">MockApi Docs</a>.
                </li>
            </ul>
        </li>
    </ol>
</aside>