# iBeacon

## Passo 1 - Criar o Sample Project

Primeiro crie um projeto utilizando o `idf.py create-project ...` ou a extensão do VS Code. 

> TODO: criar uma doc de como configurar o ambiente.

# Passo 2 - Ativar o NimBLE

Em um ESP-IDF Terminal, na pasta do projeto criado no Passo 1, rode `idf.py menuconfig` para habilitar o BLE.

Vá em `Component config -> Bluetooth -> [X] Bluetooth`. Após habilitar o bluetooth irá aparecer a opção chamada `Bluetooth Host`, abra ela e selecione `NimBLE - BLE only`.

Agora seu BLE está ativado, salve e saia.

# Passo 3 - 


