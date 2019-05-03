#Adicionando os arquivos

''' vi arquivo.txt
#!/bin/bash 

wget https://raw.githubusercontent.com/leandersonandre/shell-script/master/lista_usuarios.txt
--------

vi london.txt
#!/bin/bash 

wget https://github.com/leandersonandre/shell-script/blob/master/london.tar.gz?raw=true

tar -xvf london.tar.gz

-----

vi lisbon.txt
#!/bin/bash 

wget https://github.com/leandersonandre/shell-script/blob/master/lisbon.tar.gz?raw=true

tar -xvf lisbon.tar.gz

----------

vi newyork.txt
#!/bin/bash 

wget https://github.com/leandersonandre/shell-script/blob/master/newyork.tar.gz?raw=true

tar -xvf newyork.tar.gz

----------

vi vienna.txt
#!/bin/bash 

wget https://github.com/leandersonandre/shell-script/blob/master/vienna.tar.gz?raw=true

tar -xvf vienna.tar.gz

--------

vi trabalho_shell.txt

#!/bin/bash

 x=0
 while  [ $x -eq 0 ]
 do 

 echo " Banco shell"
 echo "infome o usuario"
 read usuario
 echo "Buscando informações..." 
 while read linha
 do
 
 if grep usuario lista_usuarios.txt ;
    then
    echo " Buscando informações"
    echo " Usuario encontrado"
    y=1
    break
 
    else
    echo " Buscando informações"
    echo " Usuario não encontrado"
    y=0
    break
 if
    
 done < lista_usuarios.txt

 if [ $y -eq 1 ] ; then
  x=1
  else
  x=0
  
  if
 
 
 
 done

  
 if [ usuario = "london" ]; then
   chmod a+x london.txt
   ./london.txt
 
 elif [ usuario = "newyork" ]; then
    chmod a+x newyork.txt
    ./newyork.txt
 
 elif [ usuario = "lisbon" ]; then
    chmod a+x lisbon.txt
    ./lisbon.txt
 
 else
    chmod a+x vienna.txt
    ./vienna.txt

 opcao=0
 while [ opcao -ne 3 ]
 do
 echo " Baixando dados do usuario..."
 echo " Download completo."
 echo " Selecione a opcao."
 echo " 1. Ver saldo."
 echo " 2. Ver extrato."
 echo " 3. sair."
 read opcao
 
 if [ opcao -eq 1 ]; then
   cat saldo.txt
 elif [ opcao -eq 2 ]; then
     cat extrato.txt

 else
    echo "opcao invalida"
 if

 done
 
 rm saldo.txt extrato.txt
 echo " Excluindo arquivos..."
 echo " Obrigada, volte sempre"
 echo " Bank shell"  '''

