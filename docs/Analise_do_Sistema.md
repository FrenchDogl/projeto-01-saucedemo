//Estou utilizando como base o site "https://example.cypress.io/"

//Qual o objetivo do sistema?
    //Seu objetivo é exibir testes E2E do framework "Cypress"

//Quem é o usuário?
    //De forma direta, seria primariamente quem está estudando programação, 
    //sendo JavaScript/Typescript para começar a entrar na parte de automatização
    //de testes. Em um caso mais incomum, seria um usuário comum (que não trabalha
    //nem estuda com programação) que está curioso sobre algum significado de 
    //um comando que possa ter ouvido falar

//Quais funcionalidades existem?
    //No site temos a parte de comandos, que nos mostram como encontrar, clicar ou
    //preencher alguma informação.
    //Na parte de utilitários temos alguns exemplos utilizando também outras 
    //bibliotecas juntamente com o cypress.
    //E por fim temos exemplos de usos da API do Cypress.

//Onde existem riscos?
    // Risco | Impacto | Prioridade
    // .Link quebrado | Usuário não está redirecionado para onde deveria | Médio
    // .Código incorreto | Usuário aprenderá de forma incorreta | Alta 
    // .Não descrição sobre o código | Usuário não entenderá para que serve | Alta
    // .Falta de exemplo | Usuário não entenderá se é o comando que quer utilizar, 
    // fazendo com que demore mais a resolver seu problema | Média 
    // .Não conseguir navegar entre as páginas | Impossibilita a utilização do Site | Alta
    // .Falta de testes negativos | Usuário não saberá o que fazer se der algum erro | Alto 
    // .Página não carregar | Experiência ruim para o usuário | Média 
    // .Texto aparecer desalinhado ou cortado | Usuário não saberá o que está escrito | Médio
    // .Erro ao carregar arquivos ou imagens | Funcionalidade fica indisponível | Alta
    // .Problemas ao utilizar em outros navegadores | Prejudica a experiência do usuário| Alta
    // .Botão não responder ao clique | Impossibilita a executar uma ação | Alta
    // .Layout desgorganizado em telas diferentes ou menores | Dificulta a utilização | Médio
    // .Página conter informações desatualizadas | Comando irá falhar por não estar atualizado | Alta
    // .Campo não aceitar copiar e colar | Reduz eficiência e praticidade | Baixa
    // .Resultado diferente do esperado | Pode comprometer a confiança no sistema | Alta

//O que aconteceria se uma funcionalidade falhasse?
    //Caso algum link quebrar ou ser alterado, isso faz com que tenhamos um 
    //problema de direcionamento dentro do site.
    //Se por algum descuido, algum comando ou até mesmo algum exemplo de como 
    //seria caso obtivesse sucesso não estiver correto, pode fazer com que o 
    //usuário quebre a cabeça por algo que o problema no final não é dele. 