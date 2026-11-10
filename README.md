Скомпилировать clamui.po файл через консоль
```bash
msgfmt clamui.po -o clamui.mo
```
При Root правах создать папку ru (не жесткая/символическая ссылка а обычная папка) по пути /var/lib/flatpak/app/io.github.linx_systems.ClamUI/current/6709803f607167d75f1f35aa05ae6c1580d4808e65adac720fb161ef9a51f337/files/share/locale

В папке ru создать папку LC_MESSAGES

В папку LC_MESSAGES скопировать файл clamui.mo

В вашем случаи я не могу дать гарантии что папка locale будет существовать так как на разных компьютерах она может как присутствовать так и отсутствовать исходя из моих наблюдений
