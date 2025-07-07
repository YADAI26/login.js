<div align="center">

**TECNOLOGICO NACIONAL DE MEXICO**  
**INSTITUTO TECNOLÓGICO DE OAXACA**

Departamento de Ingeniería en Sistemas Computacionales  

Materia: Programación Web  
"Login Enlace de repositorio"

Profesora: Martínez Nieto Adelina

Estudiante:  
Salinas Montesinos Cintia Yadai  
Grupo: VSI  

Oaxaca, Oaxaca, a 07 de julio de 2025.

</div>

 # LOGIN-PETSHOP

## Presentación del Producto: Login PetShop

El login de PetShop es una interfaz de autenticación moderna y atractiva diseñada específicamente para una tienda de mascotas. 
La página presenta un diseño elegante con efectos de cristal esmerilado que crea una experiencia visual sofisticada y acogedora para los usuarios.

--

Explicación de la documentación
## El proyecto está compuesto por..

Estructura HTML (login.html)
- Formulario de autenticación con campos de email y contraseña
- Botones de redes sociales (Facebook, Twitter, Google)
- Sección de presentación con logo y mensaje de bienvenida
- Imagen decorativa de mascota

2. Estilos CSS (loging.css)

- Diseño responsivo con efectos visuales modernos
- Implementación de glassmorphism con backdrop-filter: blur(20px)
- Layout flexbox para organización de elementos
- Gradientes y transiciones suaves

 ---
 
##  🔧 Principales Métodos del Login

## 1. Método de Redirección Principal
Maneja el envío del formulario y redirige al usuario tras el login

```javascript

function redireccionar(e) {
  e.preventDefault(); // Evita que el formulario recargue la página
  window.location.href = "tienda.html"; // Redirige a la tienda
}
```

## 2. Método de Autenticación con Google
Placeholder para implementar login con Google OAuth

```javascript
function loginConGoogle() {
  // Lógica para autenticación con Google
}
```

## 3. Validación HTML5
- Validación automática de formato email
- Campos obligatorios antes de envío
- No requiere JavaScript adicional
- 
``` html
<input type="email" placeholder="Correo electrónico" required />
<input type="password" placeholder="Contraseña" required />
```

## 4. Manejo de Eventos del Formulario
- Captura el evento submit del formulario
- Ejecuta la función de redirección
- Previene comportamiento por defecto
``` html
<form onsubmit="redireccionar(event)">
```
## 5 Estilos visuales de CSS
- Estilos CSS Destacados
Efectos Visuales:
- Glassmorphism: backdrop-filter: blur(20px) con transparencia
- Gradientes: Botón con linear-gradient(135deg, #54135fda, #be21a4)
- Sombras: Box-shadow para profundidad visual
- Transiciones: Efectos hover suaves  
como se presenta en esta parte del codigo:

``` css
.login-box {
  display: flex;
  width: 900px;
  height: 500px;
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(20px);
  border-radius: 30px;
  box-shadow: 0 0 25px rgba(0, 0, 0, 0.5);
  overflow: hidden;
  z-index: 1;
}
```

Este login combina funcionalidad práctica con un diseño visualmente atractivo que refleja la naturaleza amigable y cálida de una tienda de mascotas. 
Creando una primera impresión positiva para los usuarios.ReintentarClaude puede cometer errores. Verifique las respuestas.

*"Más que una tienda, un hogar para tus mascotas"* 🐾  

---  


## A continuacion presentaremos unas capturas de pantalla del codigo HTML

![image](https://github.com/user-attachments/assets/a832fa82-af82-490d-9237-c8ff2b0d2641)

# Del codigo CSS

![image](https://github.com/user-attachments/assets/0daebe99-8cb2-4398-baca-21ae822f40b6)

## Consola del navegador mostrando resultados:

## LOGIN

El cual puedes iniciar con tu correo y cualquier contraseña 

![image](https://github.com/user-attachments/assets/57617b34-fc69-4b32-8fa8-b61fca08775f)

A l entrar al LOGIN te da una pag principal de la tienda de articulos en este caso PETSHOP 

![image](https://github.com/user-attachments/assets/bdf7a3d7-4a43-495b-b834-189bbaba265f)


## GIT HUB PAGE
https://yadai26.github.io/login.js/














