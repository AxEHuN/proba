# REST Client Visual Studio Code használata

1. Első lépésként létrehoztam a Visual Code Studio-ban egy html filet.
2. A file első sorában meg kell adni hogy milyen kérést szeretnénk küldeni aztán után egy szóközzel elválasztva megadjuk az URL linket amire a küldést szeretnénk elvégezni.
```POST http://httpbin.org/post  HTTP/1.1```
[first](first.png)
> Továbbá megtudunk még adni a kéréshez különböző funkciókat, például ha egy
> tetszőleges tartalmat szeretnénk küldeni a szervernek, akkor meg adhatjuk például
```
Content-Type: application/xml
<request>
    <name>sample</name>
    <time>Wed, 21 Oct 2015 18:27:50 GMT</time>
</request>
``` 
3. A "Send Request" opcióval elküldjük a kérést az URL felé.
[second](second.png)
