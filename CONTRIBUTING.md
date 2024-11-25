# Como faço uma contribuição?

Nunca fez uma contribuição open-source antes? Está se perguntando como funcionam as contribuições neste projeto? Aqui está um guia rápido!

- Encontre uma issue que você queira resolver ou uma funcionalidade que queira adicionar.

- Faça um fork do repositório associado à issue para sua organização local do GitHub. Isso significa que você terá uma cópia do repositório em `seu-nome-de-usuario-GitHub/nome-do-repositorio`.

- Clone o repositório forkado para sua máquina local usando `git clone https://github.com/nome-de-usuario-github/nome-do-repositorio.git`. Por exemplo, para um repositório chamado "xyzRepo", você pode executar https://github.com/nome-de-usuario-github/xyzRepo.git.

- Crie uma nova branch para sua correção usando `git checkout -b nome-da-branch-aqui`. Por exemplo `git checkout -b main`

- Faça as alterações apropriadas para a issue que você está tentando resolver ou a funcionalidade que deseja adicionar.

- Use `git add insira-caminhos-dos-arquivos-alterados-aqui` para adicionar o conteúdo dos arquivos modificados ao "snapshot" que o git usa para gerenciar o estado do projeto, também conhecido como índice.

- Use `git commit -m "Insira uma mensagem curta das alterações feitas aqui"` para armazenar o conteúdo do índice com uma mensagem descritiva.

- Envie as alterações para o repositório remoto usando `git push origin nome-da-branch-aqui`.

- Envie um pull request para o repositório upstream.

- Dê um título ao pull request com uma breve descrição das alterações feitas e o número da issue ou bug associado à sua alteração. Por exemplo, você pode intitular uma issue assim **"Adicionada mais saída de log para resolver #4352"**.

- Na descrição do pull request, explique as alterações que você fez, quaisquer problemas que você acha que existem com o pull request que você fez e quaisquer dúvidas que você tenha para o mantenedor. Não tem problema se seu pull request não estiver perfeito (nenhum pull request é), o revisor poderá ajudá-lo a corrigir quaisquer problemas e melhorá-lo!

- Aguarde o pull request ser revisado por um mantenedor.

- Faça alterações no pull request se o mantenedor revisor recomendar.

- Comemore seu sucesso após seu pull request ser mesclado!

# Onde posso buscar ajuda?

Se precisar de ajuda, você pode fazer perguntas em nossa aba de **discussões**.
