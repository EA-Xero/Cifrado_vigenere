# 🔐 Cifrado Vigenère Extendido en Java

Este proyecto implementa el **algoritmo de cifrado Vigenère** en Java, con una versión extendida del alfabeto que incluye:

- Números (`0–9`)
- Letras minúsculas (`a–z`) y mayúsculas (`A–Z`)
- La letra `ñ` y `Ñ`

Ideal para cifrar mensajes de forma simple, segura y personalizada a través de consola.

---

## 🧠 ¿Cómo funciona?

1. El usuario puede ingresar una **clave** para cifrar y descifrar mensajes.
2. Los mensajes se procesan carácter por carácter, sumando o restando el desplazamiento definido por la clave.
3. Si un carácter no pertenece al alfabeto definido, se deja tal cual.
4. También se puede **re-cifrar un mensaje con una nueva clave**.

---

## 📋 Funcionalidades

- ✅ Ingreso de clave de cifrado
- 🔐 Cifrado de mensajes
- 🔓 Descifrado de mensajes
- ♻️ Re-cifrado con una nueva clave
- 🧼 Validación de caracteres válidos
- 🖥️ Interfaz por consola

---

## 🧱 Estructura del código

- `Main.java`: contiene la interfaz por consola y el flujo principal del programa.
- `BigVigenere`: clase que implementa la lógica de cifrado y descifrado usando una matriz de alfabeto personalizado.

---
## ⚙️ Ejecucion
Hay dos formas de ejecutar el proyecto: **sin compilar** (usando el código ya compilado) o **compilando** el código desde el directorio fuente.
### Como Compilar y Ejecutar el programa
Antes de nada por favor descargar y ejecutar el compilador de Java (JDK) encontrado en: https://www.java.com/es/download/manual.jsp \
Una vez instalado proceder con el siguiente bloque de comandos:
```bash
  git clone https://github.com/EA-Xero/Cifrado_Vinegere.git
  cd Cifrado_Vinegere/src
  javac Main.java
  java Main
```
Una vez compilado solo necesitas ejecutar el comando cada vez que quieras ejecutar el archivo
```bash
    java Main
```