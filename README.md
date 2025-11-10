# Minecraft Server 1.21.1 - Configuración Privada  

![Minecraft 1.21.1](https://img.shields.io/badge/Minecraft-1.21.1-green) ![Tailscale](https://img.shields.io/badge/Tailscale-5C3EE8) ![Python](https://img.shields.io/badge/Python-MSX.py-blue)  

**Repositorio privado** con mi configuración personal para administrar mi servidor técnico de Minecraft 1.21.1 usando:  
- 🐍 `MSX.py` (mi script personal de gestión)  
- � **Tailscale** como puente de conexión  
- 💻 GitHub Codespaces para administración remota  

---

## 🖥️ Configuración Actual  

### 📌 Stack Técnico  
- **Core**: PaperMC 1.21.1 (optimizado para granjas)  
- **Gestión**: Script `MSX.py` (arranque/backups/plugins)  
- **Conexión**: Tailscale (IP privada `100.x.x.x`)  
- **JVM Args**: `-Xms6G -Xmx6G +Aikar's Flags`  

### 📂 Estructura  
```  
📦mc-1.21.1  
├── 📜MSX.py                # Script principal (start/stop/backup)  
├── 📂server/               # Instancia PaperMC  
│   ├── 📂plugins           # Carpet/Lithium/etc  
│   └── 📂worlds            # Mundos técnicos  
├── 📂tailscale/            # Config VPN  
└── 📂backups/              # Backups automáticos (cada 6h)  
```
