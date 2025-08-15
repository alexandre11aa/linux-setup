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
$ curl -O https://raw.githubusercontent.com/Centro-Universitario-de-Patos/AmbienteConfigs/main/<DISTRIBUIÇÃO>.sh
```

- *Download via **wget**:*

```
$ wget https://raw.githubusercontent.com/Centro-Universitario-de-Patos/AmbienteConfigs/main/<DISTRIBUIÇÃO>.sh
```

#### 2. Dê permissão de execução

```
$ chmod +x instalar_apps.sh
```

#### 3. Execute o script

```
$ ./instalar_apps.sh
```

## ⚠️ Observações

O script precisa de acesso root. Ele pedirá sua senha de sudo no início.

Após a instalação do Docker, é necessário relogar ou reiniciar o sistema para que o usuário atual tenha permissão de usar Docker sem sudo.

## 🛠️ Requisitos

Conexão com a internet