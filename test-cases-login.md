# 🧪 Test Cases - Login

## TC-001: Login con credenciales válidas
**Precondición:** Usuario registrado

**Pasos:**
1. Ir a la página de login
2. Introducir email válido
3. Introducir contraseña válida
4. Click en "Login"

**Resultado esperado:**
El usuario accede correctamente al sistema

## TC-002: Login con email inválido
**Precondición:** Usuario registrado
**Pasos:**
1. Ir a login
2. Introducir email inválido (ej: test@)
3. Introducir contraseña
4. Click en "Login"

**Resultado esperado:**
Se muestra mensaje de error indicado email inválido

## TC-003: Login con contraseña incorrecta
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email válido
3. Introducir contraseña incorrecta
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error indicando credeniales incorrectas

## TC-004: Login de usuario no resgistrado
**Precondición:** Usuario no registrado
**Pasos:** 
1. Ir al login
2. Introducir email no registrado
3. Introducir contraseña 
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "Usuario no existe"

## TC-005: Login con respuesta lenta del servidor
**Precondición:** Usuario registrado
**Pasos:** 
1. Ir al login
2. Introducir credenciale válidas 
4. Click en "Login"
** Resultado esperado:**
El servidor muestra indiador de carga o meneja el timeout correctamente

## TC-006: Login con email vacio
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Dejar vacío el campo de email
3. Introducir contraseña valida
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "email requerido"

## TC-007: Login con contraseña vacía
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email
3. Dejar vacío el campo de contraseña
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "contraseña requerida"

## TC-008: Login con múltiples intentos fallidos
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email válido
3. Introducir contraseña incorrecta
4. 5. Repetir el intento 5 veces
** Resultado esperado:**
El sistema bloquea temporalmente o  muestra un captcha 

## TC-009: Login con intento de SQL injection
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email: ' OR '1'='1
3. Introducir cualquier contraseña
4. Click en "Login"
** Resultado esperado:**
Sistema rechaza input y no permite acceso


## TC-010: Login con espacios en blanco
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir espacios en el email ("    ")
3. Introducir contraseña válida
4. Hacer click en "Login"
** Resultado esperado:**
se valida como campo vacío 




   
