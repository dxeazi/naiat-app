### Descripción

Hola, soy Nallely Campos. Desarrollé NaiatApex con React y CSS como proyecto final de LatinasCodeCamp2023; es una aplicación de tipo bancario. Cuenta con un formulario de inicio de sesión validado por usuario y contraseña. Si estos son incorrectos o están incompletos, muestra un mensaje para revisar los datos ingresados; si son correctos, permite el acceso.

Una vez que el usuario inicia sesión, el programa muestra un mensaje de bienvenida y se puede hacer clic en las opciones del menú lateral. El menú cuenta con iconos y descripciones emergentes (tooltips).

+ Los usuarios pueden cambiar su PIN.
+ Consultar el valor monetario de sus acciones y el valor de las mismas en el mercado.
+ Elegir cuántas acciones desean comprar o vender.
+ Agregar dinero a su cuenta (cada depósito se asocia con la fecha en que se realizó, el monto depositado, y esta cantidad se suma al saldo actual).
+ Consultar un estado de cuenta que incluye los datos del usuario, los movimientos de su cuenta, un botón para imprimir la información mostrada en pantalla y la fecha de impresión.
+ Al finalizar la sesión, la aplicación muestra un mensaje de despedida y redirige a la pantalla de inicio de sesión con los campos del formulario vacíos y listos para ser usados nuevamente.


### Autor
- Github - [@dxeazi](https://github.com/dxeazi/)
  (antes "@tercodiablo")
- Front-End Mentor - [@tercodiablo](https://www.frontendmentor.io/profile/tercodiablo)


### Construido con

- REACT
- CSS 
- Flexbox

## Ejemplo en vivo

Github: https://github.com/dxeazi/naiat-app211    --tooltips y corrección de algunos errores (bugs)

CodeSandBox: https://codesandbox.io/s/react-naiat-login-csbtd-nsp8n5  --primera versión

## Contrataciones y contacto

Correo electrónico: dxeazi@proton.me

## Notas

Los datos como nombre y apellido, cambios de PIN, compra y venta de acciones, depósitos y saldo se almacenan en el host local (localStorage).

El proyecto está hecho únicamente para la versión web; la versión móvil aún está en desarrollo.

Para acceder, por favor utiliza los siguientes datos-->
Usuario: "naiat"
PIN: "1932"

## Agradecimientos / Aprendizajes
Aprender a usar React DOM, rutas de React-router y NavLinks para llamar a múltiples componentes o páginas basados en URLs, en una sola ventana. Por ejemplo:

~~~  
<BrowserRouter>
      <Routes>
        <Route path="/" element={<Layout />}>
          <Route index element={<Home />} />
        </Route>
      </Routes>
    </BrowserRouter>
~~~
