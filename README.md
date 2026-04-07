# 🐉 SA-MP Windows (Wine) Egg - Pterodactyl

Este repositorio contiene un **egg para Pterodactyl Panel** que permite ejecutar servidores de **SA-MP en versión Windows** usando **Wine**.

Este egg está pensado para quienes necesitan usar plugins o configuraciones que solo funcionan en entorno Windows.

---

## ⚠️ Importante

Este egg **NO instala automáticamente los archivos del servidor SA-MP**.

Debes subirlos manualmente después de crear el servidor.

---

## 📥 Cómo usar el Egg

### 1. Importar el Egg

1. Ve al **Panel de Administración de Pterodactyl**
2. Entra en **Nests → Import Egg**
3. Sube el archivo `.json` de este repositorio

---

### 2. Crear el servidor

1. Crea un nuevo servidor
2. Selecciona el egg: **SA-MP Windows (Wine)**
3. Configura los recursos (RAM, CPU, etc.)
4. Finaliza la creación

---

### 3. Subir archivos de SA-MP

Una vez creado el servidor:

1. Descarga el servidor oficial de SA-MP (`.zip`)
2. Extrae los archivos en tu PC
3. Súbelos al panel de Pterodactyl

Ejemplo de archivos necesarios:

```id="5b5y1l"
samp-server.exe
server.cfg
plugins/
scriptfiles/
```

---

## ▶️ Inicio

El servidor se ejecuta con:

```Startup Command id="u39g3y"
wine samp-server.exe
```

---

## 📜 Créditos

* SA-MP Team
* Pterodactyl Panel
* Wine Project
* hcgcloud
