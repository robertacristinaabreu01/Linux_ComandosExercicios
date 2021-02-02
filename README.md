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

apt moo  --> mostra uma vaca no terminal ...kkk

apt-get update

apt install "pacote" (apt install chromium)[instala]

apt remove chromium[desinstalar]
apt-get autoremove (desinstala e remove as dependências)

apt-get autoclean (limpando e removendo todos os arquivos .deb (pacotes) contidos nos diretórios)
apt clean --> limpa os repositórios

htop --> mostra qto esta usando de HD

dpkg -->manipula os pacotes
dpkg --remove pacote (precisa estar na pasta--> dpkg --remove code_amd64.deb)
sudo apt autoremove --> deleta todos os pacotes que não estão sendo mais usados

programa --version --> mostra a versão do programa

ls --> listar pastas e arquivos
ls -la --> lista pastas , arquivos e as demais informações e ls --all  ---> mostra os arquivos ocultos tb
ls -l --> permissões e lista as pastas
ls -l -h --> lista de forma mais simples para o usuário o tamanho do arquivo

cd Documentos --> entra na pasta Documentos
cd ..  --> sai da pasta
cd ~  ---> entra no diretório do usuário

ls /bin  ---> mostra a lista de comandos
ls /dev  ---> aonde fica tudo da maquina, exemplo: usb, cpu
ls /home --> minha área de usuário
ls /proc --> informações sore o sistema

lscpu --> dentro do proc formatando de uma forma diferente

pwd -->  /home/roberta
mkdir --> cria pasta (mkdir linux)
touch oi.txt  --> cria um arquivo zerado
editores de texto (vim, nano)
nano oi,txt --> abrir o arquivo ( salvar usa-se ^o, e sair ^x)

ls --help --> mostra todos os parâmetros
man ls  --> mostra o manual

history  --> mostra todos os comandos usados

!92 ou ls -lh são o mesmo comando

cd Documentos / ls pasta / ls -a ou ls --all  --> para ver tudo

criar pasta dentro da pasta Linux (cria na sequencia)
mkdir - p Cursos/Hardware/Módulos\ 1/
ou
mkdir -p "Cursos/Hardware/Módulo 2/"

Lista as pastas recursivamente
ls -R Cursos
ls -R -l -a Cursos/

![exemplo no terminal](https://github.com/robertacristinaabreu01/Linux_ComandosExercicios/blob/main/exLinux2.PNG)

![exemplo no terminal2](https://github.com/robertacristinaabreu01/Linux_ComandosExercicios/blob/main/exLinux.PNG)

arvores de diretórios --> ls -Rla <==> ls -R -l -a

![exemplo no Terminal3](https://github.com/robertacristinaabreu01/Linux_ComandosExercicios/blob/main/exLinux3.PNG)


criar a pasta sem precisar entrar na pasta , vc vai precisar do caminho até lá

![exemplo de crar sem entrar](https://github.com/robertacristinaabreu01/Linux_ComandosExercicios/blob/main/exLinux4.PNG)


cat Linux.txt  --> só pra ver o que em dentro do arquivo

como deletar a pasta mas que tem arquivo dentro
rm Linux/oi.txt
rmdir Linux

ou

rm -rf Cursos/

![comandos de remover](https://github.com/robertacristinaabreu01/Linux_ComandosExercicios/blob/main/exLinux5.PNG)











