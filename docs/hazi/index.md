# Szorgalmi házi feladatok

A házi feladatok **opcionálisak, pluszpont és iMsc pont** szerezhető velük. A feladatok leírása található itt; a megoldások beadása GitHub Classroom segítségével történik.

!!! important "Működő kód"
    A feladatok során működő kódot, kódrészleteteket kell készíteni. A feladat lényege a valóságban működő és a kívánt funkciót ellátó kód készítése.

## A feladatok

1. [MSSQL szerveroldali programozás](mssql/index.md)
1. [ADO.NET adatelérés](adonet/index.md)
1. [Entity Framework](ef/index.md)
1. [MongoDB](mongodb/index.md)
1. [REST API Web API technológiával](rest/index.md)

## A feladatok beadása

Minden házi feladat megoldását egy személyre szóló git repository-ban kell beadni. Ennek pontos [folyamatát lásd itt](GitHub.md). Kérünk, hogy alaposan olvasd végig a leírást!

!!! danger "FONTOS"
    A házik elkészítése és beadás során az itt leírtak szerint **kell** eljárnod. A nem ilyen formában beadott házikat nem értékeljük.

    A beadás során a munkafolyamati hibákért (pl. nem megfelelő emberhez hozzárendelése, hozzárendelés elfelejtése) pontot vonunk le.

## Képernyőképek

A feladatok kérik, hogy készíts képernyőképet a megoldás egy-egy részéről, mert ezzel bizonyítod, hogy a megoldásod saját magad készítetted. **A képernyőképek elvárt tartalmát a feladat minden esetben pontosan megnevezi**. A képernyőkép készülhet a teljes desktopról is, de lehet csak a kért alkalmazásról készíteni.

!!! info ""
    A képernyőképeket a megoldás részeként kell beadni, így felkerülnek a git repository tartalmával együtt. Mivel a repository privát, azt az oktatókon kívül más nem látja. Amennyiben olyan tartalom kerül a képernyőképre, amit nem szeretnél feltölteni, kitakarhatod a képről.

## Szükséges eszközök

- Windows, Linux vagy MacOS: Minden szükséges program platform független, vagy van platformfüggetlen alternatívája.
- GitHub account és egy git kliens.
- MSSQL adatbázist használó feladatokhoz:
    - Microsoft SQL Server. Az _Express_ változat ingyenesen használható, avagy Visual Studio mellett feltelepülő _localdb_ változat is megfelelő. Van [Linux változata](https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-setup) is. MacOS-en Docker-rel futtatható.
    - [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms), vagy kipróbálható a platformfüggetlen [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download) is.
    - Adatbázis létrehozó script: [mssql.sql](https://raw.githubusercontent.com/bmeviauac01/adatvezerelt/master/docs/db/mssql.sql)
- MongoDB adatbázist használó feladathoz:
    - [MongoDB Community Server](https://www.mongodb.com/download-center/community)
    - [Robo 3T](https://robomongo.org/download)
    - Minta adatbázis kódja: [mongo.js](https://raw.githubusercontent.com/bmeviauac01/adatvezerelt/master/docs/db/mongo.js)
- REST API feladatokhoz: [Postman](https://www.getpostman.com/)
- Az első házi kivételével a C# programozós feladatokhoz:
    - Microsoft Visual Studio 2022 [az itt található beállításokkal](VisualStudio.md). Linux és MacOS esetén Visual Studio Code és a .NET SDK-val települő [dotnet CLI](https://docs.microsoft.com/en-us/dotnet/tools/) használható.
    - [.NET **6.0** SDK](https://dotnet.microsoft.com/download/dotnet/6.0)

        !!! warning ".NET 6.0"
            A feladat megoldásához **6.0** .NET SDK telepítése szükséges.

            Windows-on Visual Studio verzió függvényében lehet, hogy telepítve van (lásd [itt](VisualStudio.md#net-sdk-ellenorzese-es-telepitese) az ellenőrzés módját); ha nem, akkor a fenti linkről kell telepíteni (az SDK-t és _nem_ a runtime-ot.) Linux és MacOS esetén telepíteni szükséges.

## A feladatok kiértékelése

A feladatok kiértékelése részben **automatikusan** történik. A futtatható kódokat valóban le fogjuk futtatni, ezért minden esetben fontos a feladatleírások pontos követése (kiinduló kód váz használata, csak a megengedett fájlok változtatása, stb.)!

A kiértékelés eredményéről a GitHub-on kapsz szöveges visszajelzést (lásd [itt](GitHub.md)). Ha ennél több információra van szükséged, a _GitHub Actions_ webes felülete segítségül szolgálhat. Erről [itt](GitHub-Actions.md) találsz egy rövid ismertetőt.

!!! danger "Ellenőrzés"
    Egyes házikban (ahol a technológia ezt kényelmessé teszi) találsz unit teszteket. Ezen tesztek **segítenek** ellenőrizni a munkádat, de **nem helyettesítik saját ellenőrzésed**. Amikor feltöltöd a munkádat, alaposabb tesztelésen fog átesni a kódod.
