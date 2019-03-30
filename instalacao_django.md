## Instalação do Django 

* Precisamos instalar o pip, no meu caso farei a instalação para python3
```
cd /opt
wget https://bootstrap.pypa.io/get-pip.py
python3 get-pip.py
```

* Agora precisamos instalar o Virtualenv.
> O virtualenv isolará seu código Python/Django em um ambiente organizado por projetos. Isso significa que as alterações que você fizer em um website não afetarão os outros projetos que você estiver desenvolvendo ao mesmo tempo.
Criar um novo diretório para o projeto dentro do meu diretório /home.
```
mkdir nome_projeto
cd nome_projeto
```
* Criar um virtualenv
```
python3 -m venv nome_desejado
```
> se der erro, usar o código abaixo:
```
sudo apt install python3-venv
```
* Agora é preciso iniciar o ambiente virtual
```
source nome_escolhido/bin/activate
```
* Antes de fazer isto, devemos garantir que temos instalada a última versão do pip, que é o software que usamos para instalar o Django:
```
python3 -m pip install --upgrade pip
```
* Instalando pacotes com requisitos

> O arquivo "requirements.txt" guarda as depenências que serão instaladas utilizando o pip install:
> Primeiramente, crie um arquivo requirements.txt dentro da pasta do seu projeto e adicione o seguinte texto ao arquivo:
```
Django~=2.1.7
```
**Lembrar de verificar a ultima versão oficial do Django**
* Agora, execute pip install -r requirements.txt para instalar o Django.
```
pip install -r requirements.txt
```

  

