# who-openport


# Clássico backdoor, escrito na linguagem C.
 
# Em desenvolvimento.

"Quem abriu a porta?" 

Esse código tem por finalidade incluir um método de acesso a sistemas, remotamente, instalando o programa apenas uma vez na 
máquina. 

Garantido o acesso, o servidor poderá executar funções arbitrárias na máquina, e alterar o sistema. 

Depois de executado, o programa se encerra, ou seja, oculta-se como um processo qualquer, rodando como uma daemon, e mantém a conexão com o servidor. 

Diferentemente de outros backdoor open source, esse permite a conexão mesmo depois de encerrado o lado do cliente (backdoor), estou trabalhando para deixá-lo o melhor possível.

Estou implementando aos poucos. Ajudas são bem vindas.

Desenvolpment of a backdoor write in C. 

# Funções: 

# auto executáveis > executam junto com o programa principal.

(#) desativar anti-vírus 

(#) desativar firewall 

(#) copiar o software para o registro da máquina alvo 

(#) copiar software para inicialização junto aos demais programas 

(#) fork para criar um deamon > usado em combinação com a reverse shell 

# Funções arbitrárias:

# executadas pelo servidor 

(#) enviar arquivo para a máquina alvo

(#) fazer download de arquivos da máquina

( ) inicializar keylogger em modo passivo, enviando os arquivos para e-mail e/ou direto para o servidor. 

(#) informações sobre: ip, nome da máquina

( ) informações sobre: a rede da máquina alvo ( outras máquinas conectadas à mesma rede)
 
.... mais por vir. 
