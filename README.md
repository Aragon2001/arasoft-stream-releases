# Arasoft Stream · Versiones

Instaladores y actualizaciones de **Arasoft Stream**, el sistema de pantalla y música para comercios de **Arasoft Solutions**.

Este repositorio **solo contiene las versiones publicadas** (no el código fuente). Es público para que las computadoras de los negocios puedan descargar las actualizaciones sin contraseñas.

## Instalar

1. Abra la [última versión](../../releases/latest) y descargue `ArasoftStream-Setup-X.Y.Z.exe`.
2. Ejecútelo en la PC del negocio. Si Windows muestra «Windows protegió su PC», toque **Más información → Ejecutar de todas formas**.
3. Siga el asistente: carpeta, PIN del panel, inicio automático y firewall.

Incluye Node.js: no hay que instalar nada más.

## Actualizar

Desde el panel: **Ajustes → Actualizaciones → Actualizar ahora**. Se conservan los anuncios, la música, la configuración y el PIN.

También puede ejecutar el instalador nuevo encima del anterior.

## Archivos de cada versión

| Archivo | Para qué |
|---|---|
| `ArasoftStream-Setup-X.Y.Z.exe` | Instalador completo (primera instalación o actualización manual). |
| `ArasoftStream-update-X.Y.Z.zip` | Paquete que descarga el panel al actualizar. |
| `latest.json` | Versión, notas y verificación SHA-256 que consulta el panel. |
