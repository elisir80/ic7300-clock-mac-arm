# IC-7300 Clock Sync (macOS ARM)

Questo programma permette di sincronizzare l'orologio interno della radio Icom IC-7300 con l'ora del computer (locale o UTC) tramite il protocollo CI-V su connessione USB.

### [Scarica l'ultima versione / Download Latest Version](https://github.com/elisir80/ic7300-clock-mac-arm/releases/latest)

### Caratteristiche
- **Sistema Operativo:** macOS
- **Architettura:** Apple Silicon (ARM)
- **Funzionamento:** Rileva automaticamente la porta seriale dell'IC-7300 e invia i comandi CI-V per impostare data e ora precise.

---

### English
This program allows you to synchronize the internal clock of the Icom IC-7300 radio with the computer's time (local or UTC) using the CI-V protocol over a USB connection.
- **OS:** macOS
- **CPU:** Apple Silicon (ARM)
- **How it works:** It automatically detects the IC-7300 serial port and sends CI-V commands to set the precise date and time.

### Español
Este programa permite sincronizar el reloj interno de la radio Icom IC-7300 con la hora de la computadora (local o UTC) utilizando el protocolo CI-V a través de una conexión USB.
- **SO:** macOS
- **CPU:** Apple Silicon (ARM)
- **Cómo funciona:** Detecta automáticamente el puerto serie del IC-7300 y envía comandos CI-V para configurar la fecha y hora precisas.

### Русский
Эта программа позволяет синхронизировать внутренние часы трансивера Icom IC-7300 с временем компьютера (местным или UTC) по протоколу CI-V через USB-соединение.
- **ОС:** macOS
- **ЦПУ:** Apple Silicon (ARM)
- **Как это работает:** Программа автоматически определяет серийный порт IC-7300 и отправляет команды CI-V для установки точного времени и даты.

---

### Installazione / Installation / Instalación / Установка

- **IT:** Scarica il file ZIP, estrai l'applicazione e trascinala nella cartella `/Applications`.
- **EN:** Download the ZIP file, extract the app, and drag it to the `/Applications` folder.
- **ES:** Descargue el archivo ZIP, extraiga la aplicación y arrástrela a la carpeta `/Applications`.
- **RU:** Загрузите ZIP-архив, извлеките приложение и перетащите его в папку `/Applications`.

#### Risoluzione problemi / Troubleshooting / Resolución de problemas / Поиск и устранение неисправностей

In caso di problemi all'avvio (messaggio "Impossibile aprire l'app"), esegui il seguente comando nel terminale:
If you encounter issues launching the app (message "App cannot be opened"), run the following command in the terminal:
En caso de problemas al iniciar (mensaje "No se puede abrir la aplicación"), ejecute el siguiente comando en la terminal:
Если возникли проблемы с запуском (сообщение «Приложение невозможно открыть»), выполните следующую команду в терминале:

```bash
sudo xattr -r -d com.apple.quarantine /Applications/IC7300-Clock-Sync.app
```
