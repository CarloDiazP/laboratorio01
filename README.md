<h1 align='center'>Laboratorio 1</h1>
<h3 align='center'>Git y GitHub</h3>
<p>Alumno: Carlo Rodrigo Diaz Portilla</p>
<h2>I. Objetivos</h2>
<p>Aprender a manejar un sistema de control de versiones de manera colaborativa con varios usuarios</p>
<h2>II. Temas a tratar</h2>
<ul>
	<li>Git</li>
	<li>Git-Hub</li>
</ul>
<h2>III. Desarrollo</h2>
<h3>A. git init</h3>
<p>Iniciamos el repositorio local, se crea directorio oculto .git</p>
<img src='./labImg/gitInit.jpeg'>
<h3>B. git config</h3>
<p>Configuramos el correo y nombre</p>
<img src='./labImg/gitConfig.jpeg'>
<h3>C. git status</h3>
<p>Crearemos un archivo, para este ejemplo HolaMundo.java</p>
<img src='./labImg/vimHolaMundo.jpeg'>
<p>Editamos el archivo con el template básico de java y guardaremos</p>
<img src='./labImg/vimHolaMundo2.jpeg'>
<p>Entonces ejecutaremos <code>git status</code> y notaremos que nos avisa que debemos agregar el archivo al staging area</p>
<img src='./labImg/gitStatus.jpeg'>
<h3>D. Archivo .gitignore</h3>
<p>El archivo .gitignore para indicar archivos que no queremos agregar al staging area</p>
<img src='./labImg/vimGitignore.jpeg'>
<p>No queremos agregar archivos .class y tampoco el mismo .gitignore</p>
<img src='./labImg/vimGitignore2.jpeg'>
<h3>E. git add</h3>
<p>Para agregar el archivo al staging area deberemos ejecutar <code>git add fileName</code></p>
<img src='./labImg/gitAdd.jpeg'>
<h3>F. git commit</h3>
<p>Una vez en el staging area, los archivos están listos para hacer commit</p>
<img src='./labImg/gitCommit.jpeg'>
<p>Haremos 2 commit más</p>
<img src='./labImg/gitCommit2.jpeg'>
<img src='./labImg/gitCommit3.jpeg'>
<h3>G. git show</h3>
<p><code>git show</code> nos muestra detalles acerca del commit actual</p>
<img src='./labImg/gitShow.jpeg'>
<h3>H. git log</h3>
<p><code>git log</code> para ver resumen de los commits realizados, podemos agregarle parámetros de formato como en el ejemplo</p>
<img src='./labImg/gitLog.jpeg'>
<h3>I. Conexión con el repositorio remoto(GitHub)</h3>
<p>Tendremos que ejecutar una serie de comandos para conectar con el repositorio remoto</p>
<img src='./labImg/gitConnect.jpeg'>
