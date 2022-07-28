# Guia para Contribuição

Antes de qualquer coisa, verifique se sua proposta de alteração não foi discutida em outro lugar. Leia o [README](README.md) do repositório, consulte as [issues](https://github.com/joaofaveri/pull-request-na-pratica/issues) (tanto as abertas quanto as fechadas) e as [Pull Requests](https://github.com/joaofaveri/pull-request-na-pratica/pulls) já existentes. Não precisa ficar horas e horas analisando tudo, mas uma rápida pesquisa por palavras-chave já é suficiente para evitar retrabalho.

Se não encontrar sua ideia em nenhum lugar do repositório, você está pronto para iniciar sua contribuição. Mas não esqueça de ler atentamente este Guia, para verificar quais as orientações específicas.

## Abrindo uma issue

Você deve abrir uma [issue](https://github.com/joaofaveri/pull-request-na-pratica/issues) nas seguintes situações:

- Relatar um erro que você não conseguiu resolver por conta própria
- Discutir um tópico relacionado ao projeto ou uma ideia
- Propor uma nova funcionalidade

## Abrindo uma Pull Request

Normalmente, as Pull Requests vão ser utilizadas nos seguintes casos:

- Submeter correções de código
- Realizar uma contribuição que já foi solicitada ou que já foi discutida em uma issue

Considerando que se trata de um repositório visando o aprendizado dessa ferramenta de contribuição em projetos open source, você poderá submeter códigos simples nas linguagens HTML, CSS e JavaScript, utilizando os templates disponibilizados no diretório ``templates``. Para cada linguagem, há um documento diferente, que atendem às particularidades de cada linguagem. Procure observar os comentários em cada arquivo, que indicam trechos de código que não devem ser alterados e orientam a respeito do conteúdo esperado. Faça uma cópia do template desejado, renomeie em conformidade com o conteúdo a ser enviado e salve na pasta ``resources``.

Abaixo, o link para cada um dos templates:

- [HTML](templates/sample-code-html-template.md)
- [CSS](templates/sample-code-css-template.md)
- [JavaScript](templates/sample-code-javascript-template.md)

Não esqueça de realizar cada uma das seguintes etapas:

1. Faça o **fork do repositório** e clone o seu conteúdo localmente. Conecte seu repositório local ao repositório original como ``upstream``, adicionando-o como remoto. Para manter sua cópia local sincronizada, realize com frequência o comando ``pull`` do Git. Assim, mantendo sua versão sempre atualizada, ao submeter o Pull Reques, menores serão as chances de conflitos no código durante o ```merge``.
2. Cria um novo ``branch``. Evite alterações diretamente no main.
3. Ao enviar o Pull Request, faça referência a qualquer issue relevante, por exemplo, informando na mensagem "Closes #17". Com isso, ao sendo aceita a Pull Request, o GitHub irá automaticamente fechar a issue correspondente.
4. Sempre que necessário, inclua imagens que possam ilustrar com maior precisão as razões e o resultado de suas alterações. No GitHub, ao fazer Pull Request, basta arrastar e soltar a imagem no corpo da mensagem.
5. Teste suas alterações! Tenha certeza de que sua contribuição não impactará o projeto.

## Após o envio do Pull Request

Mesmo em um projeto ativo, é possível que sua contribuição não receba uma resposta. Procuraremos analisar e responder todas as Pull Requests o quanto antes. De qualquer forma, se entender que está demorando mais do que deveria, comente no mesmo tópico, solicitando educadamente uma avaliação aos responsáveis. Não entre em contato em particular. A comunicação pública em projetos de código aberto é essencial.

Pode ocorrer de alguém solicita alterações em sua contribuição. Quando isso ocorrer, seja responsivo. Se não souber como fazer alterações, pesquise o problema ou peça ajuda se precisar.

Caso sua contribuição não tenha sido aceita, não estando claras as razões para tal, é perfeitamente razoável solicitar esclarecimentos aos responsáveis. Em última análise, respeite essa decisão, afinal, são os mantenedores do repositório. Não discuta, nem seja hostil.