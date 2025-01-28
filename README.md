# Repositório do Desafio de Projeto - Criação de um Phishing com o Kali Linux
Este projeto se faz em base objetiva a ser educativo e conscientizar, demonstrando:

▸ a facilidade em gerar links falsos de phishing;  
▸ sobre as práticas de phishing.

## Descrição
Neste desafio de projeto, foi proposto a criação um 'Phishing' para capturar credenciais (usuários e senhas de login), tendo como 'alvo' a página da rede social do Facebook.
A ferramenta utilizada foi o Social Engineering Toolkit (SEToolkit) que permitiu a criação de links de phishing.

## Ferramentas
• Kali Linux  
• Terminal Linux  
• SEToolkit

## Tecnologias
• VMware  
• Kali Linux  
• Git

## Nota de Atenção
▸ Todos os procedimentos foram realizados em ambiente controlado para testes éticos de segurança e fins educativos, atentando para:
* <b>Uso Responsável</b>
* <b>Legislação Vigente</b>
* <b>Propósito Educacional</b>

## Procedimentos
Primeiramente, instale a ferramenta, seguindo o passo a passo em: <a href='https://github.com/trustedsec/social-engineer-toolkit' target="_blank"> SEToolkit </a>
<br>
### Iniciando o SEToolkit
• Obs: A ferramenta é baseada em menus de seleção 
1. Abra o terminal 
2. Digite o comando: ```sudo su```
3. Digite sua senha
4. Digite o comando: ```setoolkit```
5. Selecione a opção: ```Social-Engineering Attacks```
6. Em seguida, selecione: ```Website Attack Vectors```
7. Agora selecione: ```Credential Harvester Attack Method```
8. Por fim, selecione: ```Site Cloner```
9. Ao ser apresentado um diálogo sobre o endereço de IP a ser usado, clique em ```Enter```, para que a ferramenta detecte o IP local da máquina e o marque como default
10. Digite o link https://www.facebook.com no terminal e pressione ```Enter```
11. Para acessar a página clonada e realizar o teste, utilize no navegador de sua preferência o IP que foi setado na etapa ```9```
12. Após a tentativa de conectar-se a página, um log será carregado no terminal do SeToolKit. Basta buscar pela credencial testada.
<br>
## Resultados do SEToolkit:  
<br>
<img src="https://raw.githubusercontent.com/j0hn-Macl4n3/dio.desafio.phishing/main/assets/img/setoolkit.png" width='50%'>
<br>
<img src="https://raw.githubusercontent.com/j0hn-Macl4n3/dio.desafio.phishing/main/assets/img/facebook.png" width='50%'>
<br>
<img src="https://raw.githubusercontent.com/j0hn-Macl4n3/dio.desafio.phishing/main/assets/img/terminalsetollkit.png" width='50%'>
<br>
