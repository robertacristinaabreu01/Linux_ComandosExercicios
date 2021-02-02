# Linux_ComandosExercicios

Abaixar espelho Mint
link: https://youtu.be/ZhLjvy23rrs
Curso em video.
https://www.linuxmint.com/download_lmde.php
https://ubuntu.com/

Mint PASSO A PASSO

gerenciador de atualização/configurarSNAPSHOT do SISTEMA dar "ok" - mesma coisa que backup pelo Windows
Assitente de configuração - >Selecionar Níveis de Backup / 2, 3, 3, 6, 3 ->cria o backup e depois atualiza (botão)

Fontes de Aplicativos 
Repositórios Oficiais - Espelhos (1°Principal Federal do paraná e 2°base debian.debian.org)
depois botão instalar atualizações

Configuração GRUB- PC
Selecionar o DEV/SDA (HD)

________________________________________
configurações instalação Debian SEM INTERFACE
1 °parte 
Abre a Máq virtual
Click no Novo
E preenche:
Dados da máquina
1024 MB memória
Novo disco rìgido virtual
VDI
Dinamicamente alocado
8.00GB
2°parte
Seleciona a máquina
Click em configurações
Geral : coloca login e senha no descritivo pra vc não esquecer depois(opcional)
Sistema: 
Selecione placa mãe: 1°óptico e 2° disco rìgido o resto sem seleção
Processador : 2
Aceleração não muda
Selecione Monitor
Tela :Memória de video 128mb
Selecione Armazenamento
Click no vazio e seleciona a pasta do arquivo
Selecione Rede
Deixe com NAT

Depois q vc instalar a parte do vídeo ( tutorial do professor) volte no sistema e tira a seleção de óptico.
Qdo pedir espelho no video coloque NÃO
Seleção de Software somente SSH e utilitários Standard
Segue bem o video principalmente na parte do parcionamento. Deixa com EXt 3 pq as atividades ele pede com essa Ext.

____________________________________________________________

***EXEMPLOS DE EDITORES DE VIDEO E IMAGENS***
GIMP - similar ao PHOTOSHOP
Inscape - Blender
Steam - jogos 
wine - emplementação de windows para linux
synaptic -  gerenciador de pacotes
alguns programas precisam instalar algumas bibliotecas
como chrome:  chromium, chromium-l10n, widewine, chromium ublock-origin, libre2-3, liminzip1

__________________________________________________________________

APT --> TERMINAL

apt moo --> mostra uma vaca no terminal ...kkk
apt-get update
apt install "pacote" (apt install chromium)[instala]
apt remove chromium[desinstalar]
apt-get autoremove (desinstala e remove as dependências)
apt-get autoclean (limpando e removendo todos os arquivos .deb (pacotes) contidos nos diretórios)
htop --> mostra qto esta usando de HD
dpkg -->manipula os pacotes
dpkg --remove pacote (precisa estar na pasta--> dpkg --remove code_amd64.deb)
apt clean --> limpa os repositórios
sudo apt autoremove --> deleta todos os pacotes que não estão sendo mais usados
programa --version --> mostra a versão do programa
ls --> listar pastas e arquivos
ls -la --> lista pastas , arquivos e as demais informações e ls --all  ---> mostra os arquivos ocultos tb
ls -l --> permissões e lista as pastas
cd Documentos --> entra na pasta Documentos
cd ..  --> sai da pasta
ls -l -h --> lista de forma mais simples para o usuário o tamanho do arquivo
cd ~  ---> entra no diretório do usuário














