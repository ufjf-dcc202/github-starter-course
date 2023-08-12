# :wave: Fundamentos do GitHub

## 🤓 Visão geral do curso e objetivos de aprendizado

O objetivo deste curso é fornecer uma breve introdução ao GitHub. Também forneceremos materiais para aprendizado adicional e algumas ideias para você começar em nossa plataforma. 🚀

## :octocat: Git e GitHub

Git é um **Sistema de Controle de Versão (VCS) distribuído**, o que significa que é uma ferramenta útil para rastrear facilmente as alterações em seu código, colaborar e compartilhar. Com o Git, você pode rastrear as mudanças que faz em seu projeto para sempre ter um registro do que trabalhou e pode facilmente voltar a uma versão anterior, se necessário. Também torna mais fácil trabalhar com outras pessoas - grupos de pessoas podem colaborar no mesmo projeto e mesclar suas alterações em uma única fonte final!

O GitHub é uma maneira de usar o mesmo poder do Git online, com uma interface fácil de usar. Ele é usado no mundo do software e além para colaborar e manter o histórico de projetos.

O GitHub abriga algumas das tecnologias mais avançadas do mundo. Quer você esteja visualizando dados ou construindo um novo jogo, há toda uma comunidade e conjunto de ferramentas no GitHub que podem levar você ao próximo passo. Este curso começa com os fundamentos do GitHub, mas vamos explorar o resto posteriormente.

## :octocat: Compreendendo o fluxo do GitHub

O fluxo do GitHub é um fluxo de trabalho leve que permite experimentar e colaborar em seus projetos facilmente, sem o risco de perder seu trabalho anterior.

### Repositórios

Um repositório é onde ocorre o trabalho do seu projeto - pense nele como sua pasta de projeto. Ele contém todos os arquivos do seu projeto e o histórico de revisões. Você pode trabalhar em um repositório sozinho ou convidar outras pessoas para colaborar com você nesses arquivos.

### Clonagem

Quando um repositório é criado no GitHub, ele é armazenado remotamente na ☁️. Você pode clonar um repositório para criar uma cópia local em seu computador e depois usar o Git para sincronizar os dois. Isso facilita a resolução de problemas, a adição ou remoção de arquivos e o envio de commits maiores. Você também pode usar a ferramenta de edição de sua escolha em vez da interface do GitHub. A clonagem de um repositório também baixa todos os dados do repositório que o GitHub tem naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você experimentar com seu projeto e perceber que gostava mais de uma versão anterior.
Para saber mais sobre clonagem, leia ["Clonando um Repositório"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commits e push
**Commits** e **push** são como você pode adicionar as alterações feitas em sua máquina local ao repositório remoto no GitHub. Dessa forma, seu instrutor e/ou colegas podem ver seu trabalho mais recente quando você estiver pronto para compartilhá-lo. Você pode fazer um commit quando fez alterações em seu projeto que deseja "marcar". Você também pode adicionar uma **mensagem de commit** útil para lembrar a si mesmo ou a seus colegas que trabalho foi feito (por exemplo, "Adicionado um README com informações sobre nosso projeto").

Depois de ter um commit ou vários commits prontos para serem adicionados ao seu repositório, você pode usar o comando push para adicionar essas alterações ao seu repositório remoto. Fazer commits e push pode parecer novo no começo, mas prometemos que você vai se acostumar com isso 🙂

## 💻 Termos do GitHub que você deve conhecer

### Repositórios
Nós já mencionamos repositórios, eles são onde o trabalho do seu projeto acontece, mas vamos falar um pouco mais sobre os detalhes deles! À medida que você trabalha mais no GitHub, terá muitos repositórios, o que pode ser confuso no início. Felizmente, o seu ["painel do GitHub"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente pelos seus repositórios e a ver informações úteis sobre eles. Certifique-se de estar logado para vê-lo!

Repositórios também contêm **README**s. Você pode adicionar um arquivo README ao seu repositório para contar às outras pessoas por que seu projeto é útil, o que elas podem fazer com ele e como podem usá-lo. Estamos usando este README para comunicar como aprender Git e GitHub com você. 😄
Para saber mais sobre repositórios, leia ["Criando, Clonando e Arquivando Repositórios"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre READMEs"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches
Você pode usar branches no GitHub para isolar o trabalho que você não deseja mesclar em seu projeto final ainda. Branches permitem que você desenvolva recursos, corrija bugs ou experimente com segurança novas ideias em uma área isolada do seu repositório. Normalmente, você pode criar um novo branch a partir do branch padrão do seu repositório - main. Isso cria uma nova cópia de trabalho do seu repositório para você experimentar. Depois que suas novas alterações forem revisadas por um colega ou você estiver satisfeito com elas, você poderá mesclar suas alterações no branch padrão do seu repositório.
Para saber mais sobre branches, leia ["Sobre Branches"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
Um fork é outra maneira de copiar um repositório, mas geralmente é usado quando você deseja contribuir para o projeto de outra pessoa. Fazer um fork de um repositório permite que você experimente livremente com alterações sem afetar o projeto original e é muito popular ao contribuir para projetos de software de código aberto!
Para saber mais sobre forks, leia ["Fazer um fork de um repositório"](https://docs.github.com/pt/github/getting-started-with-github/fork-a-repo).

### Pull requests
Ao trabalhar com branches, você pode usar um pull request para informar outras pessoas sobre as alterações que deseja fazer e solicitar feedback. Depois que um pull request é aberto, você pode discutir e revisar as possíveis alterações com colaboradores e adicionar mais alterações, se necessário. Você pode adicionar pessoas específicas como revisores do seu pull request, o que mostra que você deseja receber feedback sobre suas alterações! Uma vez que um pull request estiver pronto, ele pode ser mesclado em seu branch principal.
Para saber mais sobre pull requests, leia ["Sobre Pull Requests"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues
Issues são uma maneira de rastrear melhorias, tarefas ou bugs para o seu trabalho no GitHub. Issues são uma ótima maneira de acompanhar todas as tarefas que você deseja trabalhar em seu projeto e informar aos outros o que você planeja fazer. Você também pode usar issues para informar a um projeto de código aberto favorito sobre um bug que você encontrou ou uma funcionalidade que você acha que seria ótima para adicionar!

Para projetos maiores, você pode acompanhar muitas issues em um quadro de projeto. Os Projetos do GitHub ajudam a organizar e priorizar seu trabalho e você pode ler mais sobre eles [neste documento "Sobre quadros de projeto"](https://docs.github.com/pt/github/managing-your-work-on-github/about-project-boards). Provavelmente, você não precisará de um quadro de projeto para suas tarefas, mas assim que passar para projetos maiores, eles são uma ótima maneira de organizar o trabalho da sua equipe! Você também pode vincular pull requests e issues para mostrar que uma correção está em andamento e fechar automaticamente a issue quando alguém mescla o pull request.
Para saber mais sobre issues e vinculá-las aos seus pull requests, leia ["Sobre Issues"](https://docs.github.com/pt/github/managing-your-work-on-github/about-issues).

### Seu perfil de usuário

Sua página de perfil conta às pessoas a história do seu trabalho por meio dos repositórios em que você está interessado, das contribuições que fez e das conversas que teve. Você também pode dar ao mundo uma visão única de quem você é com o seu perfil README. Você pode usar o seu perfil para informar futuros empregadores sobre você!
Para saber mais sobre o seu perfil de usuário e adicionar e atualizar o seu perfil README, leia ["Gerenciando Seu Perfil README"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Usando markdown no GitHub

Você pode ter percebido, mas você pode adicionar alguns estilos divertidos às suas issues, pull requests e arquivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) é uma maneira fácil de estilizar suas issues, pull requests e arquivos com uma sintaxe simples. Isso pode ser útil para organizar suas informações e torná-las mais fáceis de ler para os outros. Você também pode adicionar gifs e imagens para ajudar a transmitir seu ponto de vista!
Para saber mais sobre o uso da marcação do GitHub, leia ["Sintaxe Básica de Escrita e Formatação"](https://docs.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interagindo com a comunidade do GitHub

A comunidade do GitHub é vasta. Existem muitos tipos de pessoas que usam o GitHub em seu dia a dia - estudantes como você, desenvolvedores profissionais, entusiastas que trabalham em projetos de código aberto e exploradores que estão entrando no mundo do desenvolvimento de software por conta própria. Existem muitas maneiras de interagir com a comunidade maior do GitHub, mas aqui estão três lugares onde você pode começar.

#### Favoritando repositórios

Se você achar um repositório interessante ou quiser acompanhar, favorite-o! Quando você favorita um repositório, ele também é usado como um sinal para mostrar recomendações melhores em github.com/explore. Se você quiser voltar aos seus repositórios favoritos, pode fazer isso por meio do seu perfil de usuário.
Para saber mais sobre como favoritar repositórios, leia ["Salvando Repositórios com Estrelas"](https://docs.github.com/pt/github/getting-started-with-github/saving-repositories-with-stars).

#### Seguindo usuários

Você pode seguir pessoas no GitHub para receber notificações sobre a atividade delas e descobrir projetos em suas comunidades. Quando você segue um usuário, a atividade pública dele no GitHub aparecerá no seu painel, para que você possa ver todas as coisas legais em que eles estão trabalhando.
Para saber mais sobre como seguir usuários, leia ["Seguindo Pessoas"](https://docs.github.com/pt/github/getting-started-with-github/following-people).

#### Navegando no GitHub Explore

O GitHub Explore é um ótimo lugar para fazer exatamente isso ... explorar :smile: Você pode encontrar novos projetos, eventos e desenvolvedores para interagir.

Você pode conferir o site do GitHub Explore [em github.com/explore](https://github.com/explore). Quanto mais você interagir com o GitHub, mais personalizada será sua visualização no Explore.

## 📝 Próximos passos opcionais

* Abra um pull request e informe seu professor que você concluiu este curso.
* Crie um novo arquivo markdown neste repositório. Informe o que você aprendeu e do que ainda está confuso! Experimente com estilos diferentes!
* Crie o seu perfil README. Conte um pouco mais ao mundo sobre você! O que você tem interesse em aprender? No que você está trabalhando? Qual é o seu hobby favorito? Saiba mais sobre como criar o seu perfil README no documento, ["Gerenciando Seu Perfil README"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Vá para o painel do seu usuário e crie um novo repositório. Experimente as funcionalidades dentro desse repositório para se familiarizar com elas.
* [Nos diga o que você gostou ou não gostou sobre o conteúdo deste curso](https://support.github.com/contact/education). O que você gostaria de ver mais? O que seria interessante ou útil para a sua jornada de aprendizado?

## 📚 Recursos
* [Um vídeo curto explicando o que é o GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Recursos de aprendizado sobre Git e GitHub](https://docs.github.com/pt/github/getting-started-with-github/git-and-github-learning-resources)
* [Compreendendo o fluxo do GitHub](https://guides.github.com/introduction/flow/)
* [Como usar branches no GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiais interativos de treinamento do Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub Learning Lab](https://lab.github.com/)
* [Fórum da comunidade educacional](https://education.github.community/)
* [Fórum da comunidade do GitHub](https://github.community/)

  
