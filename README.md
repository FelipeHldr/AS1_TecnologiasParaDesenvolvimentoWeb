# Atividade Somativa 1 Tecnologias Para Desenvolvimento Web

Com base no conhecimento obtido durante as 4 primeiras semanas, crie uma nova aplicação em React exatamente igual da figura abaixo. No componente, você deverá colocar um título de Login, 2 inputs (e-mail e senha), um botão de validação (Acessar) e uma label. Ao clicar no botão “Acessar”, deverá verificar se o campo de e-mail é igual a “eduardo.lino@pucpr.br” e senha igual a “123456” (você poderá colocar seu e-mail e senha desejado, o importante é a lógica da construção da aplicação). Caso os valores sejam iguais aos valores do enunciado, deverá ser mostrado a mensagem “Acessado com sucesso!” na label abaixo do botão. Caso algum dos dois campos estejam com valores diferentes do enunciado, deverá ser mostrado a mensagem “Usuário ou senha incorretos!”.



# Atividade Somativa 2 DevOps

Com base no conteúdo estudado até o momento, realize a Atividade proposta a seguir.
Imagine que você foi convidado para fazer parte da empresa de tecnologia XYZ.
A partir disso, o gestor da equipe de TI dessa empresa pede para criar uma pipeline com testes de segurança para garantir que a aplicação web não esteja vulnerável. À medida que o desenvolvedor cria uma nova feature, envia o resultado para o Telegram.
Para esta Atividade, serão analisados:
1. Criação de uma pipeline, a qual terá uma aplicação web (escolhida nos exercícios anteriores).
2. Essa aplicação precisará estar hospedada no Docker Hub e possuir um teste de segurança, utilizando SAST ou DAST, conforme veremos na próxima semana (semana 8).
3. Envio da notificação para o Telegram após o Pull Request (PR). Caso utilize o GitLab, consulte esta página como referência: https://docs.gitlab.com/ee/ci/variables/predefined_variables.html, assim como a pipeline de exemplo: https://gitlab.com/michelleamesquita/devsecops2/.
4. Criação de uma pipeline com as fases build, test e deploy (a produção pode ser feita utilizando o Ngrok, caso não utilize a nuvem, visto que para o GitLab encontrar a aplicação e testá-la, precisa que esteja hospedada na internet).
A entrega da atividade deve ser feita na semana 8, em um documento com o link do repositório Git, com o print da pipeline, mostrando que você conseguiu rodar uma aplicação web, podendo conter ou não alguma vulnerabilidade na aplicação e fazendo o deploy.
