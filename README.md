# Minecraft Technical Server 1.21.1 - Configuración Privada  

![Minecraft 1.21.1](https://img.shields.io/badge/Minecraft-1.21.1-green) ![Codespaces](https://img.shields.io/badge/GitHub-CodeSpaces-blue)  

Este repositorio es mi configuración personal para administrar mi servidor técnico de Minecraft **1.21.1** usando GitHub Codespaces.  

## 🛠️ Configuración  

### Archivos importantes:  
- `server/`: Carpeta del servidor (Paper/Fabric/Quilt, según versión).  
- `scripts/`:  
  - `start.sh`: Inicia el servidor con flags personalizados.  
  - `backup.sh`: Backup automático de mundos y configs.  
- `server.properties`: Configuración base del servidor.  

### Comandos útiles:  
```bash
# Iniciar servidor (con screen para persistencia)
./scripts/start.sh

# Backup manual (se ejecuta automáticamente cada 6h)
./scripts/backup.sh
```

## ⚙️ Mi Setup Técnico  
- **Versión**: Paper 1.21.1 (optimizado para granjas técnias).  
- **Flags de JVM**: `-Xms6G -Xmx6G -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions`.  
- **Plugins/Mods**: Carpet, Lithium, STAPI (privados).  

## 📂 Estructura  
```  
📦mc-server-1.21.1  
├── 📂server          # Core del servidor  
├── 📂backups         # Backups automáticos  
├── 📂scripts         # Scripts de gestión  
└── 📜README.md       # Esta guía  
```  

> 🔒 **Privado**: Este repo es solo para mi configuración personal. No está destinado a distribución pública.
