# **Desafio-Phishing**


## Desafio Sobre Phishing usando Kali Linux


### Ferramentas

* Kali Linux
* setoolkit


### Configurando o Phishing no Kali Linux


* Acesso root: ```sudo su```
* Iniciando o setoolkit: ```setoolkit```
* Tipo de ataque: ```1-Social-Engineering Attacks```
* Vetor de ataque: ```2-Web Site Attack Vectors```
* Método de ataque: ```3-Credential Harveste Attack Method```
* Método de ataque: ```2-Site Cloner```
* URL para clone: http://www.facebook.com

### Resultados:

![Resultado](https://github.com/malfoymk/Desafio-Phishing/blob/main/image.png?raw=true)



# Algumas questões que enfrentei com o percurso!


## Apache

Tive um leve problema com o Apache encontrando erros na Porta, aqui vai como resolvi:


* Acesso: ```cd /etc/setoolkit```
* Localizar arquivos: ```ls```
* Acesso ao documento: ```gedit set.config```
* Localizar ```APACHE_SERVER=```
