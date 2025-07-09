# 1Byte_PC

Este repositorio documenta mi paso a paso construyendo una computadora de 1 byte, **desde cero y por completo**.  
La idea es entender cómo funciona una CPU a nivel interno, **desde el bit hasta las instrucciones y saltos condicionales**, construyendo cada componente por mí mismo, con lógica binaria.

---

## 📌 Objetivo

Construir una computadora funcional de 1 byte capaz de ejecutar programas simples, usando puertas lógicas básicas, registros, una ALU, memoria y control de flujo.

No uso componentes prearmados: **cada bloque es diseñado y armado desde lo más bajo posible**, como si estuviera ensamblando el hardware desde el silicio.

---

## 🧱 Arquitectura

Actualmente mi computadora cuenta con:

- 📥 Entrada de datos
- 💾 Entrada de programa
- 🧮 ALU con:
  - Suma
  - Resta
  - AND, OR, NOR, NAND
  - Comparaciones: `==`, `!=`, `>`, `<`, `>=`, `<=`
- 📊 6 registros
- 📤 Salida de datos
- 🧭 Control de programa (saltos condicionales)
- 🧠 Instrucciones codificadas en 1 byte:
  - `00`: cargar valor en R0
  - `01`: guardar
  - `10`: operación ALU entre R1 y R2 → R3
  - `11`: comparar R3 y hacer salto según condición

---

## 🛠️ Herramientas

- [Turing Complete (juego)](https://store.steampowered.com/app/1857080/Turing_Complete/) – Aprendí la lógica base
- [Logisim Evolution](https://github.com/reds-heig/logisim-evolution) – Próxima etapa: replicar cada pieza visualmente
- GitHub + Markdown – Para documentar mi proceso y explicaciones

---

## 📚 ¿Por qué hago esto?

Porque quiero entender **cómo funciona una computadora desde adentro.**  
No me interesa solo programar en alto nivel, sino saber **cómo viaja el dato, cómo se opera, y cómo se controla.**  
Y si algún día puedo jugar al Tetris en ella, mejor.

---

## 📖 Documentación

Estoy documentando:
- Cada componente con su lógica
- Capturas de pantalla (Logisim o esquemas)
- Explicación técnica y en palabras simples
- Reflexiones del proceso

---

## ✍️ Autor

Matías Vidal – Explorando cómo una idea se convierte en instrucciones eléctricas.
