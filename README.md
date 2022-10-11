 README
<html>
<head>
<title> Mi pagina web</title>
</head>
 <frameset rows="100,*">
         <frame id="frmSuperior" name="frmSuperior" src="encabezado.html" />
         <frameset cols="150,*">
             <frame id="frmIzquierda" name="frmIzquierda" src="izquierda.html" />
             <frame id="frmCuerpo"    name="frmCuerpo"    src="cuerpo.html" />
         </frameset>
        <noframes>
            <body>Su navegador no soporta frames</body>
        </noframes>
    </frameset>
</html>
