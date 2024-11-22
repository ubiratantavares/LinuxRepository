# Plataforma: FIAP

## Curso: Linux Fundamentos

### Aula 1 - Introdução aos comandos linux

Sistema operacional utilizado Debian

Nota: não houve conteúdo significativo.

### Aula 2 - Comandos iniciais

* Manual de comandos

```bash
man ls
```
NOTA: comando q para sair

* Ajuda de comandos

```bash
ls --help
```

* Tornar outro usuário root
 
```bash
su
```

NOTA: informar a senha do usuário.

* retornar ao usuário anterior
 
```bash
exit
```

* Tornar outro usuário
 
```bash
su usuario
```

* instala o pacote sudo

```bash
apt install sudo
```

* remover o pacote sudo

```bash
apt remove sudo
```

* manter o repositorio atualizado

```bash
apt update
```

* faz uma comparação com o que encontra-se instalado

```bash
apt upgrade
```

* 

```bash
usermod -aG sudo hpoyatos
```

* 

```bash
sudo apt update
```


### Aula 3 - Gerenciamento de usuarios

* 

```bash
passwd
```

* 

```bash
sudo passwd root
```

* 

```bash
sudo adduser novousuario
```

* 

```bash
su novousuario
```

* 

```bash
sudo groupadd ti
```

* 

```bash
man usermod
```

* 

```bash
sudo usermod -aG ti hpoyatos
```

* 

```bash
sudo usermod -aG ti novousuario 
```

* 

```bash
sudo usermod -L novousuario 
```

* 

```bash
sudo usermod -U novousuario 
```

### Aula 4 - Arquivos e pastas

* principais diretorios do linux debian 

```bash
ls /
```

* 

```bash
ls -la /
```


* 

```bash
ls -la /dev
```

```bash
ls -lhu
```

```bash
ls -lhu /home
```

### Aula 5 - Criando e mudando de diretorio

### Aula 6 - Copiando, movendo e removendo arquivos

### Aula 7 - Visualizando conteudo de arquivos

### Aula 8 - Localizar e baixar arquivos

### Aula 9 - Cpmpressão de arquivos

### Aula 10 - Gerenciamento de redes (parte 1)

### Aula 11 - Gerenciamento de redes (parte 2)
