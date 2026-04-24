# Minecraft Modpack - Master
### Version Forge 1.20.1

## 📋 Yêu cầu hệ thống

- **Minecraft**: Java Edition 1.20.1
- **Java**: JDK 21 trở lên
- **Mod Loader**: Forge (47.4.10)

## 🚀 Hướng dẫn cài đặt

### Cách 1: Launcher

#### Với Launcher:
1. Tải và cài đặt [Launcher](https://)
2. Mở launcher và chọn **Explorer**
3. Chọn **versions** → **Unzip file modpack `.zip`** → Restart Launcher
4. Cấu hình RAM trong **Settings** → **Java** → **Maximum memory allocation**
5. Khởi chạy instance
6. Nhấn **Play** để tải mod và chơi

#### Với CurseForge Launcher:
1. Tải và cài đặt [Launcher](https://)
2. Mở launcher và chọn **Minecraft**
3. Nhấn **Create Custom Profile**
4. Import file `.zip` của modpack
5. Nhấn **Play** để tải mod và chơi

#### Với Prism Launcher:
1. Tải [Prism Launcher](https://)
2. Chọn **Add Instance** → **Import from zip**
3. Chọn file modpack `.zip`
4. Cấu hình RAM trong **Settings** → **Java** → **Maximum memory allocation**
5. Khởi chạy instance

### Cách 2: Cài đặt thủ công

1. **Cài đặt Mod Loader:**
    - Tải [Forge](https://files.minecraftforge.net/)
    - Chạy installer và chọn phiên bản Minecraft 1.20.1

2. **Mở thư mục Launcher**
   ```bash
   cd version

3. **Clone repo**
   ```bash
   git clone https://github.com/goraria/minecraft-modpack Master

4. **Play**
    - Mở lại Launcher
    - Chọn Master version và Play

5. **Vị trí thư mục**
   ```bash
   # Windows
   %appdata%\.minecraft\versions
   
   # macOS
   ~/Library/Application Support/minecraft/versions
   
   # Linux
   ~/.minecraft/versions

6. **Cài đặt mods:**
   ```bash
   # Windows
   %appdata%\.minecraft\mods
   
   # macOS
   ~/Library/Application Support/minecraft/mods
   
   # Linux
   ~/.minecraft/mods
