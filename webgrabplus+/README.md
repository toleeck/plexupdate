webgrabplus+ запускаю кроном один раз в три дня такой командой в кроне
```bash
15      0       1-30/3  *       *       /home/wg++/run.sh && sed -i '/title lang="en"/d' /var/www/html/epg/epg.xml
```
то есть после создания и подготовки ЕПГ из неё sed-ом удаляю строки с заголовками на английском языке. пока не понял как удалить эти заголовки непосредственно через wg++