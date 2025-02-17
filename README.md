# Sistema Automatizado de Gestão do Alojamento - TCC Técnico em Informática
Este projeto foi desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) do curso Técnico em Informática, com o objetivo de transformar um sistema totalmente manual em uma solução automatizada. O sistema foi desenvolvido utilizando JavaFX para a interface gráfica, CSS para estilização, XAMPP para gerenciamento do servidor e banco de dados, e phpMyAdmin para administração do banco de dados MySQL. O Apache e o MySQL são utilizados para rodar o servidor web e o banco de dados localmente.  

## Funcionalidades
O sistema automatiza diversas operações, incluindo:  
-Busca de alunos  
-Inserção e exclusão de alunos  
-Consultas de uso de piscina  
-Controle de uso de lavanderia  
-Controle de empréstimos de materiais no alojamento  
-Gestão de quartos  
-Criação de ocorrências no sistema  

Todas essas informações são armazenadas em um banco de dados local, garantindo a organização e a eficiência na gestão das operações.  

## Instruções para Execução  
Instalação do XAMPP:  
-Baixe e instale o XAMPP (disponível em https://www.apachefriends.org/pt_br/index.html).  
-Após a instalação, abra o XAMPP e ative os serviços Apache e MySQL.  
-Certifique-se de que a porta do MySQL esteja configurada como 3306.  

Configuração do Banco de Dados:  
-Acesse o phpMyAdmin através do painel do XAMPP.  
-O projeto contém um script chamado "alojamento" com o código sql do database. Basta copiar e colar na aba SQL no phpMyAdmin. 
-Certifique-se de que a conexão do banco de dados esteja configurada corretamente no sistema.  

Configuração do Projeto no NetBeans:    
-O projeto foi desenvolvido usando o NetBeans 8.2, pois esta versão já contém todos os arquivos .jar necessários para a compilação do projeto.  
-Importe o projeto no NetBeans e configure as conexões com o banco de dados.  

Execução do Sistema:  
-Após iniciar o XAMPP e conectar ao banco de dados, execute o programa no NetBeans.  
-O sistema estará pronto para realizar as funções de gerenciamento descritas acima.  
