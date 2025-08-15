# 🚀 Script de Instalação de Setup para distribuições Linux

Este script automatiza a instalação dos principais aplicativos e ferramentas de desenvolvimento em distribuições Linux.

## ✅ Aplicativos que serão instalados:

- `Cinnamon`
- `OpenSSH`
- `snapd`
- `Google Chrome`
- `Chromium`
- `Discord`
- `Visual Studio Code`
- `Git`
- `Docker`
- `Docker-Compose`

## 📦 Como usar

#### 1. Baixar arquivo para instalações

```
$ sudo apt update && sudo apt install -y curl wget
```

- *Download via **curl**:*

```
$ curl -O https://raw.githubusercontent.com/alexandre11aa/linux-setup/main/<DISTRIBUICAO>.sh
```

- *Download via **wget**:*

```
$ wget https://raw.githubusercontent.com/alexandre11aa/linux-setup/main/<DISTRIBUICAO>.sh
```

#### 2. Dê permissão de execução

```
$ chmod +x <DISTRIBUICAO>.sh
```

#### 3. Execute o script

```
$ ./<DISTRIBUICAO>.sh
```

## ⚠️ Observações

O script precisa de acesso root. Ele pedirá sua senha de sudo no início.

Após o fim das instações, recomenda-se reiniciar o sistema, pois é necessário relogar ou o reiniciar para que o usuário possa por exemplo: garantir permissão de usar Docker sem sudo, e até mesmo ativer o Cinnamon.

## 🛠️ Requisitos

Conexão com a internet