ssh-keygen -t ed25519 -C "mail"
: Enter file in which to save the key (/../../) : ".ssh/NAME" // либо оставляем пустой, либо ".ssh/NAME" .ssh - папка
Созданы 2 файла, один с .pub, другой без; .pub - публичный,
.pub является просто текстовым документом, открываем, копируем что внутри
вставить на GitHub -> settings -> ssh..
clone of repository : 2. В окне терминала введите
<git clone https://github.com/...>