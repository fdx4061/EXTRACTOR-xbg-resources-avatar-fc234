# XBG Texture and material Extractor
**Supported games:** *Avatar: The Game, Far Cry 2, Far Cry 3, Far Cry 4*


<a name="english"></a>
## 🇬🇧 English Description

Utility for automatic extraction of textures and materials from `.xbg` files. No more manual hex editing to locate embedded files — everything is neatly extracted and ready to use!

### Usage Instructions:
1. Place your `.xbg` files in the same directory as `EXTRACTOR.exe`.  
2. Run `EXTRACTOR.exe`.  
3. A file named `PATH.ini` will be generated, containing default paths to unpacked resource folders.  
4. Open `PATH.ini` and add the full paths to your own unpacked resource directories.  
   - Only the **first uncommented line** will be used.  
   - To disable a path, prepend it with a semicolon (`;`) — e.g., `;C:\MyUnpackedFiles`  
5. After running the tool again, it will automatically extract all textures and materials referenced by your `.xbg` files into organized subfolders, preserving the original directory structure.

### Benefits:
* ✅ Instant access to all embedded assets
* ✅ Preserved folder hierarchy
* ✅ Simple configuration via `PATH.ini`

---

<a name="русский"></a>
## 🇨🇳 по Русски

Утилита для автоматического извлечения текстур и материалов из файлов `.xbg`. Больше никакого ручного поиска путей через Hex-редакторы — инструмент сделает всё за вас.

### Инструкция:
1. Поместите ваши `.xbg` файлы в ту же папку, где находится `EXTRACTOR.exe`.
2. Запустите `EXTRACTOR.exe`. Программа создаст файл конфигурации `PATH.ini`.
3. Откройте `PATH.ini` и добавьте полные пути к вашим папкам с распакованными ресурсами.
   - Используется только **первая незакомментированная строка**.
   - Чтобы отключить путь, добавьте точку с запятой (`;`) в начало строки.
4. Запустите инструмент снова. Он автоматически извлечет все текстуры и материалы, на которые ссылаются `.xbg` файлы.
5. Все данные будут разложены по подпапкам с сохранением оригинальной структуры.

### Преимущества:
* ✅ Мгновенный доступ ко всем ассетам
* ✅ Сохранение иерархии папок
* ✅ Поддержка игр: **Avatar, FC2, FC3, FC4**
