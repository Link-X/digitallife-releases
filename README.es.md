# digitallife（数字人生）

[English](README.md) · [简体中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · **Español** · [Português](README.pt.md)

> Un monitor de actividad nativo para macOS —— **todos tus datos permanecen en tu propio Mac.**

digitallife registra discretamente lo que ocurre en tu Mac día a día: qué aplicaciones usas y durante cuánto tiempo, el consumo de red y batería/energía, los cambios en archivos, las aplicaciones instaladas y desinstaladas… y lo presenta todo mediante una elegante aplicación nativa de la barra de menús en forma de informes diarios / semanales / mensuales claros. Sin nube, sin cuenta, no se sube nada.

---

## 📸 Capturas de pantalla

<p align="center">
  <img src="images/en/01-overview.png" width="49%" alt="Overview">
  <img src="images/en/02-report.png" width="49%" alt="Report">
</p>
<p align="center">
  <img src="images/en/03-files.png" width="49%" alt="Files">
  <img src="images/en/04-apps.png" width="49%" alt="Apps">
</p>
<p align="center">
  <img src="images/en/05-clean.png" width="49%" alt="Clean">
  <img src="images/en/06-data.png" width="49%" alt="Data">
</p>

---

## ✨ Qué puedes ver

- **Tiempo de uso de las aplicaciones** y clasificaciones diarias (con iconos)
- **Tendencias de batería y energía**, ranking de consumo energético por aplicación (opcional)
- **Tráfico de red** por aplicación
- **Actividad de archivos**: creados / eliminados / modificados —— carpeta, tipo y aplicación de origen
- Clasificación de **CPU / memoria**
- **Títulos de ventana y tiempo de inactividad**, aplicaciones de la barra de menús / residentes en segundo plano
- Historial de **instalación / desinstalación** de aplicaciones
- **Análisis del espacio en disco** (localización de carpetas / archivos grandes) y **limpieza de archivos innecesarios**
- **Informes diarios / semanales / mensuales**, tiempo de pantalla comparado con el período anterior
- Los datos se pueden borrar por día / categoría, con **exportación JSON / CSV**

---

## 💻 Requisitos del sistema

- **macOS 13 (Ventura) o posterior**
- **Apple Silicon** (chip serie M)

---

## ⬇️ Descarga e instalación

1. Descarga la última `DigitalLife-<versión>.dmg` desde **[Releases](https://github.com/Link-X/digitallife-releases/releases/latest)**
2. Abre el DMG y **arrastra «数字人生» a «Aplicaciones»**
3. **Haz doble clic para abrir** —— la aplicación está **certificada (notarizada) por Apple**, por lo que no aparece ningún bloqueo de «dañado» / «desarrollador no verificado», ni hace falta «clic derecho → Abrir»
4. Tras el primer arranque, abre «权限设置…» (Permisos) desde la barra de menús y concede los permisos del sistema según se indica

### Permisos (concédelos según necesites; si falta uno, solo se limita esa función, nada más)

| Permiso | Uso |
|------|------|
| Acceso completo al disco | Historial del navegador, etc. |
| Accesibilidad | Identificar la aplicación en primer plano |
| Grabación de pantalla | Leer títulos de ventana (**no se hacen capturas**) |
| Automatización (Eventos del sistema) | Aplicación / ventana en primer plano |

---

## 🔒 Privacidad

Esto es lo que más le importa a digitallife:

- **El 100 % de tus datos permanece en local**, escrito en una base de datos en tu propio Mac, **sin ninguna transmisión por red**
- **La única solicitud de red** ocurre cuando **haces clic manualmente en «Buscar actualizaciones»** —— solo obtiene un número de versión y no envía ninguno de tus datos; por lo demás, la aplicación está totalmente sin conexión
- Para mayor protección, puedes **activar el cifrado de la base de datos** en los ajustes (la clave se guarda en el llavero del sistema)

---

## 🔄 Buscar actualizaciones

Menú de la aplicación **«关于数字人生» (Acerca de) → «检查更新» (Buscar actualizaciones)**: haz clic manualmente una vez; si hay una versión más reciente, se te avisará con un enlace de descarga. Sin sondeo en segundo plano ni descargas automáticas.

---

## 📄 Licencia

**Software propietario · Todos los derechos reservados (All Rights Reserved)** — Copyright © 2026 许道斌 (Daobin Xu).

- **El código fuente es cerrado**: salvo el autor, no se permite ningún uso, copia, modificación, ingeniería inversa ni distribución del código fuente sin autorización previa por escrito. **«Visible» no significa «utilizable».**
- **Aplicación oficial gratuita para uso no comercial**: las personas físicas (estudio / investigación / afición), las organizaciones sin ánimo de lucro, las instituciones educativas y de investigación y los organismos gubernamentales pueden **usar gratuitamente** la aplicación firmada y notarizada, sin modificar, publicada oficialmente en este repositorio.
- **Canal oficial, solo uso propio**: descárgala desde los [Releases](https://github.com/Link-X/digitallife-releases/releases/latest) de este repositorio para tu propio uso; **quedan prohibidas la redistribución, el reenvío, la copia, la modificación y la ingeniería inversa.**
- **El uso comercial requiere autorización**: cualquier uso comercial —— **incluido el uso por parte de una organización con ánimo de lucro (empresa / compañía) en el curso de su actividad, aun siendo de uso estrictamente interno por sus empleados** —— requiere autorización previa por escrito.

> «No comercial» significa un uso que no está destinado principalmente a una ventaja comercial o a una compensación económica: uso personal, organizaciones sin ánimo de lucro, instituciones educativas y de investigación, y organismos gubernamentales dentro de sus funciones no lucrativas / públicas.

Para consultas de licencia, contacta con **许道斌 (Daobin Xu)** (<15555537368xu@gmail.com>). Los términos bilingües completos están en [LICENSE](LICENSE).
