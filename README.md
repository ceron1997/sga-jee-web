<p><b>Descripción del Proyecto</b></p>

<p>Este proyecto es una aplicación Java EE que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar)
    sobre una base de datos MySQL utilizando varias tecnologías de Java EE. Además, cuenta con una interfaz de usuario
    web que utiliza PrimeFaces para mostrar los registros de la base de datos a los usuarios.</p>

<p><b>Características Principales</b></p>

<p>El proyecto incluye las siguientes características:</p>
<p><b>- Operaciones CRUD en base de datos MySQL:</b> Interactúa con una base de datos MySQL para realizar operaciones
    CRUD sobre la entidad <i>Persona</i> utilizando servicios RESTful.</p>

<p><b>- Capa web con PrimeFaces:</b> Desarrollaste una interfaz de usuario web con PrimeFaces, un marco de componentes
    para JavaServer Faces (JSF). Se utiliza una tabla de datos (<i>p:dataTable</i>) para mostrar las personas,
    permitiendo la edición, eliminación y adición de nuevos registros.</p>

<p><b>- Interacción con la base de datos:</b> La aplicación utiliza JPA (Java Persistence API) para manejar la
    persistencia de datos con MySQL, permitiendo un acceso más eficiente a los datos.</p>

<p><b>- Componentes de PrimeFaces:</b> Se utilizaron varios componentes de PrimeFaces, como <i>p:dataTable</i> para
    mostrar datos en una tabla, <i>p:dialog</i> para diálogos modales, y <i>p:commandButton</i> para botones con
    acciones asociadas. Además, se implementaron solicitudes asincrónicas con <i>p:ajax</i> para mejorar la experiencia
    del usuario.</p>

<p><b>- Manejo de eventos:</b> Se implementaron listeners de eventos para manejar acciones del usuario, como editar o
    eliminar una persona.</p>

<p><b>- Capas de la aplicación:</b> El diseño de la aplicación sigue un enfoque de capas, incluyendo una capa de
    presentación (PrimeFaces), una capa de servicio (servicios RESTful y <i>PersonaService</i>), y una capa de
    persistencia (JPA para manejar la base de datos MySQL).</p>

