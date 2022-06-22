## MyShell - Projeto SO2
Implementar um processador de comandos do Linux em C

# Características
- Exibe um prompt e aguarda entrada do usuário
- O comando exit deve sair do processador de comandos.
- Quando a entrada do usuário é o nome de um programa no path ou o caminho
completo ou relativo de um programa, o mesmo deve ser executado.
- Quando a entrada do usuário não é um programa ou comando válido, deve ser 
mostrada uma mensagem de erro adequada.
- Os argumentos digitados na linha de comando devem ser passados ao programa 
que será executado.
- O prompt deve ter o formato: [MySh] nome-de-usuario@hospedeiro:diretorio-atual$.
- No prompt, o caminho do diretório home do usuário deve ser substituído por ~, 
caso este faça parte do caminho atual. Exemplo: de /home/juquinha/aula para 
~/aula.
- Implemente o comando cd para mudar diretórios (quando recebe argumento) ou 
voltar ao diretório home do usuário (sem argumentos ou com o argumento ~).
- Mostre uma mensagem de erro adequada se cd falhar.
- Ctrl+Z e Ctrl+C não devem causar a parada ou interrupção do processador de 
comandos (apenas ignore a linha com o comando).
- Ctrl+D deve sair do processador de comandos, tal qual se o comando exit
tivesse sido utilizado.
- O processador de comandos deve permitir o uso de pipes. O símbolo | indica a 
separação entre cada programa, conectando a saída padrão do programa à esquerda 
com a entrada padrão do programa à direita através de um pipe.
