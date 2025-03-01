1. Instale o Python: Certifique-se de que o Python está instalado no seu sistema. Você pode baixá-lo do site oficial python.org.

2. Abra o VSCode: Inicie o Visual Studio Code.

3. Abra o terminal: Você pode abrir o terminal integrado no VSCode pressionando
Ctrl +
 
 (a tecla de acento grave) ou indo em "Terminal" > "Novo Terminal".

4. Navegue até o diretório do seu projeto: Use o comando 
cd
 para mudar para o diretório onde você deseja criar o ambiente virtual.

5. Crie o ambiente virtual: Execute o seguinte comando no terminal:
   

   python -m venv nome_do_ambiente
   

   Substitua 
nome_do_ambiente
 pelo nome que você deseja dar ao seu ambiente virtual.

6. Ative o ambiente virtual:
   - No Windows, use:
     

     .\nome_do_ambiente\Scripts\activate
     

   - No macOS ou Linux, use:
     

     source nome_do_ambiente/bin/activate
     


7. Verifique se o ambiente está ativo: Você deve ver o nome do seu ambiente virtual no início da linha do terminal.

8. Instale pacotes: Agora você pode instalar pacotes usando 
pip
, e eles serão instalados apenas dentro do seu ambiente virtual.

9. Desative o ambiente virtual: Quando terminar, você pode desativar o ambiente virtual digitando:
   

   deactivate
   


10. Configuração do Python no VSCode: Para garantir que o VSCode use o Python do seu ambiente virtual, você pode selecionar o interpretador Python. Pressione 



Para verificar a versão do Python : 

No terminal digite:
python --version 

para criar um ambiente virtual
python -m venv venv

para ativar o ambiente virtual
.\venv\Scripts\activate.psi - no powershell
.\venv\Scripts\activate.bat - no cmd

para desativar o ambiente virtual 
deactivate

comando para liberar o venv no powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

Alteração da Política de Execução
A política de execução ajuda a proteger contra scripts não confiáveis.
A alteração da política de execução pode implicar exposição aos riscos de
segurança descritos no tópico da ajuda about_Execution_Policies em
https://go.microsoft.com/fwlink/?LinkID=135170. Deseja
alterar a política de execução?
[S] Sim  [A] Sim para Todos  [N] Não  [T] Não para Todos  
[U] Suspender  [?] Ajuda (o padrão é "N"): Set-ExecutionPolicy -Scope CurrentUser 
-ExecutionPolicy RemoteSigned

Digite: sim ou yes