# 🧪 Test Cases - Login

## TC-001: Login con credenciales válidas
**Precondición:** Usuario registrado

**Pasos:**
1. Ir a la página de login
2. Introducir email válido
3. Introducir password válido
4. Click en "Login"

**Resultado esperado:**
El usuario accede correctamente al sistema

## TC-002: Login con email inválido
**Precondición:** Usuario registrado
**Pasos:**
1. Ir a login
2. Introducir email inválido (ej: test@)
3. Introducir password
4. Click en "Login"

**Resultado esperado:**
Se muestra mensaje de error

## TC-003: Login con contraseña invalida
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email válido
3. Introducir contraseña inválida(ej: tester1)
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error

## TC-004: Login de usuario no resgistrado
**Precondición:** Usuario no registrado
**Pasos:** 
1. Ir al login
2. Introducir email 
3. Introducir contraseña 
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "Usuario no registrado"

## TC-005: Login demorado
**Precondición:** Usuario registrado
**Pasos:** 
1. Ir al login
2. Introducir email 
3. Introducir contraseña 
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "El servidor tarda demasiado en responder"

## TC-006: Login con email vacio
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Dejar vacío el campo de email
3. Introducir contraseña valida(ej: tester1)
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "debe introducir un email válido"

## TC-007: Login con contraseña vacía
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email
3. Dejar vacío el campo de contraseña
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "debe introducir una contraseña válida"

## TC-008: Login con múltiples intentos fallidos
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email
3. Dejar vacío el campo de contraseña
4. Click en "Login"
5. Repetir la operación al menos 5 veces
** Resultado esperado:**
Se bloquea temporalmente al usuario o se muestra un captcha (seguridad)

## TC-009: Login con caracteres especiales o intento de SQL injection
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email
3. Escribir caracteres especiales (ej:*, '1)
4. Click en "Login"
5. Repetir la operación al menos 5 veces
** Resultado esperado:**
Sistema rechaza imput y fala


## TC-010: Login con espacios en blanco ("   ")en campos
**Precondición:**Usuario registrado

**Pasos:** 
1. Ir al login
2. Introducir email
3. Escribir el usuario y dejar espacios vacíos(ej: "@tes   t")
5. Repetir la operación al menos 5 veces
** Resultado esperado:**
Validación como campo vacío 




   
