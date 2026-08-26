# Enunciado — NFC NDEF y Host Card Emulation

Construir una práctica Android que permita experimentar con tres roles NFC:

1. **lector**: detectar etiquetas y decodificar registros NDEF de texto y URI;
2. **escritor**: escribir un registro NDEF de texto sencillo en una etiqueta compatible y escribible;
3. **Host Card Emulation**: exponer un AID de demostración y responder a una selección ISO-DEP desde otro lector NFC.

La práctica debe detectar la disponibilidad real del hardware y tratar de forma segura los dispositivos que no soporten NFC/HCE. Se requiere un dispositivo físico compatible para las pruebas completas.

No existe una base de datos asociada.
