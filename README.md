# Linux_Terminal_CMD

**Comando lista -> ls:**\
Usado para verificar arquivos presentes no diretório atual\
Ao utilizá-lo em conjunto com "-l", verificamos informações sobre tais arquivos\
Ao utilizá-lo com " -lh", verificamos permissões \
Ao utilizá-lo com " -a", podemos deixar todos os arquivos visíveis 

**Comando verificar diretório -> pwd:**\
Usado para verificar em que repositório estamos localizados

**Comando mudar de diretório -> cd**\
Usado para mudar diretório atual: cd PATH\
Ao utilizá-lo em conjunto com " ..", voltaremos um diretório atrás\
Ao utilizá-lo em conjunto com " ~", voltaremos ao diretório inicial (home)\
Ao utilizá-lo em conjunto com " -", voltaremos ao diretório anterior\
Ao utilizá-lo em conjunto com " /", voltaremos ao diretório raiz (root)

**Comando limpar -> clear**\
Ao utilizá-lo, todos os processos exibidos no terminal serão apagados

**Comando lista de discos -> lsblk**\
Usado para virificar lista de discos e reportições presentes na máquina

**Comando criar diretório -> mkdir**\
Usado para criar um novo diretório dentro do diretório atual mkdir NAME

**Comando remover diretório -> rmdir**\
Usado para remover um diretório existente no diretório atual rmdir NAME

**Comando para remover arquivos -> rm**\
Usado para remover arquivos de dentro de diretórios rm NAME_FILE\
Ao utilizá-lo em conjunto com *TYPE, removemos todos os arquivos do tipo especificado

**Comando copiar -> cp**\
Usado para copiar um arquivo para outro diretório cd ARQUIVO PATH\
Ao utilizá-lo em conjunto com " *.* ", copiamos todos os arquivos dentro do diretório\
Ao utilizá-lo com " -r", copiamos de forma recursiva, tanto arquivos quanto conteúdo\
Ao utilizá-lo com " -i", se existir um arquivo com o mesmo nome do copiado, o copiado é substituido

**Comando mover -> mv**\
Usado para mover arquivos ou diretórios para outro diretório mv NAME PATH\

**Comando descompactar -> unzip**\
Usado para extrair arquivos compactados no mesmo diretório em que está localizado\

**Comando para verificar tipo -> file NAME**\
Usado para verificar o tipo do arquivo desejado

**Atualizar repositórios com nível de adm -> sudo apt update**\
Usado para preparar o ambiente para instalar aplicações utilizando o terminal\

**Instalar novas aplicações -> sudo apt install NAME**\
Usado para instalar aplicações via cmd\

**Remover aplicações instaladas -> sudo apt remove NAME**\
Usado para remover aplicações instaladas\

**Comando concatenate -> cat name**\
Usado para exibir conteúdo de arquivo 

**Comando visualização expandida -> less PATH**\
Usado para exibir conteúdo de um arquivo de forma expandida\
Possui alguns comandos para navegação: q (usado para sair da página), 
page up, page down, up e down (navegação utilizando teclas), 
g(ir para início do arquivo de texto), G(ir para o final do arquivo de texto), 
/search(procurar texto específico dentro do arquivo de texto no formato /TEXTO)

**Comando modificar para executável -> chmod +x NAME**\
Usado para mudar permissão para ser executável

_nano Script SH_
**Comando para iniciar o nano e criar arquivo sh-> nano NAME.sh**\
Usado para iniciar um arquivo sh utilizando nano

_vi Script SH_
**Comando para iniciar o nano e criar arquivo sh-> vi NAME.sh**\
Usado para iniciar um arquivo sh utilizando vi
