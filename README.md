# Lumen — atualizações do app Android

O app Lumen lê o `version.json` deste repositório ao abrir. Se o `versionCode` daqui for maior que o
do app instalado, ele obriga a atualização e baixa o APK da pasta `apk/`.

Não edite à mão: as versões são publicadas pelo script `publicar-atualizacao.sh` do projeto do app.
