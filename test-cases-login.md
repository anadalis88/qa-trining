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

## TC-005: login demorado
**Precondición:** Usuario registrado
**Pasos:** 
1. Ir al login
2. Introducir email 
3. Introducir contraseña 
4. Click en "Login"
** Resultado esperado:**
Se muestra mesaje de error "El servidor tarda demasiado en responder"

   
