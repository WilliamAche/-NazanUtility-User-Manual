---
title: crud
description: 'blog description'
published: true
slugs:
    - crud
---


  <div class="wy-grid-for-nav">
    <nav data-toggle="wy-nav-shift" class="wy-nav-side stickynav">
    <div class="wy-side-scroll">
      <div class="wy-side-nav-search">
        <a href=".." class="icon icon-home"> Manual de Usuario NazanUtility</a>
      </div>
      <div class="wy-menu wy-menu-vertical" data-spy="affix" role="navigation" aria-label="main navigation">
                <ul>
                    <li class="toctree-l1"><a class="reference internal" href="blog/home">Inicio</a>
                    </li>
                </ul>
                <ul>
                    <li class="toctree-l1"><a class="reference internal" href="blog/dahsboard/">Panel de control</a>
                    </li>
                </ul>
                <ul>
                    <li class="toctree-l1"><a class="reference internal" href="blog/store/">Tienda</a>
                    </li>
                </ul>
                <ul>
                    <li class="toctree-l1"><a class="reference internal" href="blog/banks/">Bancos</a>
                    </li>
                </ul>
                <ul>
                    <li class="toctree-l1"><a class="reference internal" href="blog/regions/">Regiones</a>
                    </li>
                </ul>
                <ul class="current">
                    <li class="toctree-l1 current"><a class="reference internal current" href="blog/crud">Registros</a>
          </li>
                </ul>
      </div>
    </div>
    </nav>
    </div>
 <section data-toggle="wy-nav-shift" class="wy-nav-content-wrap">
      <nav class="wy-nav-top" role="navigation" aria-label="top navigation">
        <i data-toggle="wy-nav-top" class="fa fa-bars"></i>
        <a href="..">Manual de Usuario NazanUtility</a>
      </nav>
       <div class="wy-nav-content">
        <div class="rst-content">
          <div role="navigation" aria-label="breadcrumbs navigation">
  <ul class="wy-breadcrumbs">
    <li><a href="..">Docs</a> &raquo;</li>
    <li>Registros</li>
    <li class="wy-breadcrumbs-aside">
    </li>
  </ul>
  <hr/>
</div>
<div role="main">
            <div class="section">
                <h2 id="zona-de-botones"><center>Zona de botones</center></h2>
<p>Se ubica debajo del menú superior y del título correspondiente a ese módulo; asimismo, contiene dos (2) secciones con funcionalidades básicas para realizar las actividades inherentes para cada módulo.</p>
<p><center><img src="assets/img/btn.png" ></center></p>
<h2 id="seccion-uno"><center>Sección Uno </center></h2>
<p>En esta sección se encuentra cuatro (4) botones que permiten llevar a cabo acciones características de cada módulo. Dichas acciones se relacionan con la vista, exportación, edición, creación y/o eliminación de la data. A continuación se explica cada botón de izquierda a derecha:</p>
<p><center><img src="assets/img/4btn.png" ></center></p>
<h2 id="buscador"><center>Buscador<center></h2>
<p>Por medio de este botón con el icono de una lupa, se puede buscar alguna data a través de las características asociadas a su id, nombre u otro factor. Ya que, al darle clic a este botón, nos dirige automáticamente a un formulario básico, en el cual se debe llenar alguno de los campos para poder hacer la búsqueda; y a continuación darle clic al botón de buscar, y este cargara la data.</p>
<p><center><img src="assets/img/search.gif" ></center></p>
<h2 id="sincronizador"><center>Sincronizador</center></h2>
<p>A través de este botón con icono de 2 flechas, al darle clic se recarga automáticamente la data y se actualizara.</p>
<p><center><img src="assets/img/reload.gif" ></center></p>
<h2 id="nuevo"><center>Nuevo</center></h2>
<p>Este botón con signo de <b>+</b> , sirve para generar un nuevo registro. Al hacer clic sobre “Nuevo”, la vista cambiará a un formulario que mostrará los campos a rellenar para hacer posible la creación de una nueva data. No obstante, para poder guardar el dato, deben estar llenos los campos obligatorios, y de esta manera aparecerá el botón de guardar.</p>
<p><center><img src="assets/img/new.gif" ></center></p>
<h2 id="exportar-excel"><center>Exportar excel</center></h2>
<p>El boton con icono de nube y una flecha, inicia el proceso de exportación de la información mostrada en la tabla o lista, hacia un archivo excel.</p>
<p><center><img src="assets/img/download.gif" ></center></p>
<h2 id="editar"><center>Editar</center></h2>
<p>Para poder editar un registro, se necesita primero seleccionarlo en la tabla o lista de datos; para ello, se debe dar clic en el registro que se quiere modificar, y aparecerá el botón de editar que tiene icono de un lapiz en la parte de la zona de botones en la sección (1) uno. Con este botón se desplegará un formulario que permite editar la mayoría de los campos del registro seleccionado.</p>
<p>A través de este formulario, se puede también eliminar activar o desactivar el registro. No obstante, el único campo de no puede ser modificado es el campo del Id.</p>
<p><center><img src="assets/img/edit.gif" ></center></p>
<h2 id="eliminar"><center>Eliminar</center></h2>
<p>Esté botón, no permite eliminar data, sino simplemente desactivarla, ya que, el administrador por medio de la base de datos se encargará de eliminar dicho dato.</p>
<p>Para poder utilizar esta función, se necesita primero seleccionarlo en la tabla o lista de datos; para ello, se debe dar clic en el registro que se quiere procesar, y aparecerá el botón de eliminar en la parte de la zona de botones en la sección (1) uno. </p>
<p>Con este botón se desplegará una ventana modal con un aviso que indica que dicho dato no puede ser eliminado, sino que solo puede ser activado o desactivado. Por lo tanto, solo el administrador  podrá eliminarlo por medio de la base de datos, no los usuarios.</p>
<p><center><img src="assets/img/delete.gif" ></center></p>
<h2 id="seccion-dos"><center>Sección Dos</center></h2>
<p>En está sección, se encuentran 3 botones funcionales, y un filtro de búsqueda, que se explicarán a continuación:</p>
<p><center><img src="assets/img/filt.png" ></center></p>
<h2 id="boton-para-mostrar-todos-los-datos"><center>Botón para mostrar todos los datos</center></h2>
<p>Al ejecutar este botón con icono de <b>☑</b> se desplegará en la tabla de contenido la totalidad de los registros creados sin importar el estado en el que se encuentren.</p>
<p><center><img src="assets/img/all.gif" ></center></p>
<h2 id="activos"><center>Activos</center></h2>
<p>Este botón proporciona los registros que están en estado activo y están siendo utilizados por la aplicación para generar estadísticas y vistas. Al hacer clic sobre el botón <b>“Activos”</b> (que esta representada por una carita feliz) estará desplegando la lista de registros activos y disponibles para ser utilizados por la herramienta. </p>
<p><center><img src="assets/img/on.gif" ></center></p>
<h2 id="inactivos"><center>Inactivos</center></h2>
<p>Este tercer botón expone los registros que están en estado inactivo y no están siendo utilizados por la aplicación para generar estadísticas y vistas. Al hacer clic sobre el botón <b>“Inactivos”</b> (que es representado por una carita triste), estará desplegando la lista de registros inactivos, que no se encuentran disponibles para ser utilizados por la herramienta.</p>
<p><center><img src="assets/img/off.gif" ></center></p>
<h2 id="filtro-de-busqueda"><center>Filtro de Búsqueda</center></h2>
<p>Dentro de esta barra se coloca el dato que se quiere conseguir en los registros. Se debe tomar en cuenta el parámetro establecido en el selector de dato.</p>
<p><center><img src="assets/img/filtr.gif" ></center></p> 
            </div>
          </div>
          <footer>
    <div class="rst-footer-buttons" role="navigation" aria-label="footer navigation">
        <a href="blog/regions/" class="btn btn-neutral" title="Regiones"><span class="icon icon-circle-arrow-left"></span> Anterior</a> 
    </div>
  <hr/>
</footer>
        </div>
      </div>
  </section>
  </div>
<div class="rst-versions" role="note" aria-label="versions">
  <span class="rst-current-version" data-toggle="rst-current-version">
    <span><a href="blog/regions/" style="color: #fcfcfc;">&laquo; Anterior</a></span>
  </span>
</div>