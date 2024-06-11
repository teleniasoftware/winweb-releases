# WinWeb Releases

<img src="https://github.com/teleniasoftware/winweb-releases/assets/66957545/6576bbbb-aa59-4b50-9318-5a30f3b56d3b" width="256" />



Lo scopo di questa repository è quello di contenere i rilasci dell'applicativo desktop per il TVox Client. 

## Sottoscrizione ai rilasci beta

Per ricevere le versioni in beta del TVox Client aprire manualmente il seguente file a seconda del sistema operativo:

<details>
    <summary>Windows</summary>
  
    %localappdata%\TVoxClient\settings.ini
</details>
<details>
    <summary>MacOS</summary>
  
    ~/Library/Application Support/TVoxClient/settings.ini
</details>
<details>
    <summary>Linux</summary>
  
    ~/.local/share/TVoxClient/settings.ini
</details>

A questo file aggiungere quindi la seguente riga e riavviare il TVox Client
```
betaVersions=true
```

Per disattivare la sottoscrizione al canale beta, rimuovere questa riga o impostare il valore a false.
