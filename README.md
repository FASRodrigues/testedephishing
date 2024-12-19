# testedephishing
Teste de Phishing
1. Preparação do Ambiente
•	Instalação do Kali Linux: Criação de VM da distro no Virtual Box.
•	Ferramentas Necessárias: setoolkit
2. Configuração do SET (Social Engineering Toolkit)
•	Iniciar o SET: Abra o terminal, para acessar todos os recursos é necessário logar com usuário root (sudo su), depois digite setoolkit para iniciar o Social Engineering Toolkit.
•	Selecionar Opção de Phishing: No menu principal, escolha a opção de Social-Engineering Attacks.
•	Selecionar Web Attack Vectors: Escolha Website Attack Vectors e depois Credential Harvester Attack Method.
3. Configuração do Site de Phishing
•	Selecionar Site Cloner: Escolha a opção Site Cloner para clonar um site legítimo.
•	Inserir URL do Site Alvo: Digite a URL do site que deseja clonar (por exemplo, uma página de login de rede social). No exercício proposto o site foi http://www.facebook.com
•	Configuração do Servidor: Configure o servidor para hospedar a página clonada. O SET irá gerar um link de phishing. Como o exercício era interno, dentro da própria rede foi usado o IP da estação virtual: 192.168.100.104
4. Distribuição do Link de Phishing
•	Enviar o Link: Por ser tratar de teste interno não houve a necessidade de expandir o teste para mais usuários consegui capturar as informações necessárias durante o teste. 
•	Monitorar Credenciais: Quando as vítimas inserirem suas credenciais no site clonado, o SET capturará essas informações.
Considerações de Segurança
•	Uso Ético: Realize simulações de phishing apenas em ambientes controlados e com permissão explícita.
•	Educação e Treinamento: Utilize os resultados para educar e treinar usuários sobre os riscos de phishing e como se proteger
