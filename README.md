# NaiatApex

Idioma / Language: **Español** | [English (#english-version)](#english-version)

---

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
- Github - [@dxeazi](https://github.com) (antes "@tercodiablo")
- Front-End Mentor - [@tercodiablo](https://frontendmentor.io)


### Construido con

- REACT
- CSS 
- Flexbox

## Ejemplo en vivo

Github: https://github.comnaiat-app211    --tooltips y corrección de algunos errores (bugs)

CodeSandBox: https://codesandbox.io  --primera versión

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

---

<span id="english-version"></span>
<details>
  <summary><b>🌐 Click here to read the English version (Click aquí para leer la versión en Inglés)</b></summary>
  <br>

### Description

Hi I'm Nallely Campos, I developed NaiatApex with React and CSS as a final project of LatinasCodeCamp2023, it is a bank-type app. It has a login-form  validated by a username and password, if they are incorrect or incomplete displays a message to review the input; if they are correct, it allows access.

Once the user is logged, the program displays a welcome message and you can clic on options from the sidebar-menu. The menu has icons and tooltips.

+ The user(s) can change their PIN 
+ Check the monetary value of their share and the value of them in the market 
+ Choose how many shares you want to sell or buy 
+ Add money to your account (each deposit is associated with the date it was made, the amount deposited, and this amount is added to the current balance)
+ Check a balance sheet, that includes the user's data, their account movements, a button to print the info showed on screen and the date of printing.
+ At the end of the session, the app displays a farewell message and redirects to the login screen with the form fields cleared and ready to be used once again.


### Author
- Github - [@dxeazi](https://github.com) (before "@tercodiablo")
- Front-End Mentor - [@tercodiablo](https://frontendmentor.io)


### Built with

- REACT
- CSS 
- Flexbox

## Live example

Github: https://github.comnaiat-app211    --tooltips and fixed some bugs

CodeSandBox: https://codesandbox.io  --first version

## Hiring and contact me

Email: dxeazi@proton.me

## Notes

Data such as first and last name, PIN changes, purchase and sale of shares, deposits and balance are stored in the local host.

The project is made for web version only, the mobile version is still under development.

To access, please use the following data-->
Username: "naiat". 
PIN: "1932"

## Acknowledgments
Learn how to use React DOM, React-routes paths and NavLinks to call multiple components or pages based on urls, in a single window. For example:

~~~  
<BrowserRouter>
      <Routes>
        <Route path="/" element={<Layout />}>
          <Route index element={<Home />} />
        </Route>
      </Routes>
    </BrowserRouter>
~~~

</details>
