# Questões de Revisão de Segurança do Protocolo

## Informações Básicas

| Nome do Protocolo                          |     |
| ------------------------------------------ | --- |
| Site                                       |     |
| Link para Documentação                     |     |
| Contato Principal (Nome, Email, Telegram)  |     |
| Link para Whitepaper, se houver (opcional) |     |

## Detalhes do Código

| Link para o Repositório a ser auditado              |     |
| --------------------------------------------------- | --- |
| Hash do Commit                                      |     |
| Número de Contratos no Escopo                       |     |
| Total de SLOC para contratos no escopo              |     |
| Pontuação de Complexidade                           |     |
| Com quantos protocolos externos o código interage   |     |
| Cobertura geral de testes para código sob auditoria |     |

### Contratos no Escopo

_Você pode executar `tree ./src/ | sed 's/└/#/g; s/──/--/g; s/├/#/g; s/│ /|/g; s/│/|/g'` para obter uma saída adequada que funciona com pandoc para todos os arquivos em `./src/`_

```
*Coloque aqui os contratos dentro do escopo.*
```

## Detalhes do Protocolo

Conte-nos um pouco sobre seu protocolo.

| Status Atual                                                     |     |
| ---------------------------------------------------------------- | --- |
| O projeto é um fork de um protocolo existente                    |     |
| Especifique o protocolo (apenas se Sim para pergunta anterior)   |     |
| O projeto usa rollups?                                           |     |
| O protocolo será multi-chain?                                    |     |
| Especifique a(s) rede(s) em que o protocolo está/será implantado |     |
| O protocolo usa oráculos externos?                               |     |
| O protocolo usa AMMs externos?                                   |     |
| O protocolo usa provas de conhecimento zero?                     |     |
| Quais tokens ERC20 você espera que interajam com os contratos    |     |
| Quais tokens ERC721 você espera que interajam com os contratos?  |     |
| Tokens ERC777 devem interagir com o protocolo?                   |     |
| Existem processos off-chain (bots keeper etc.)                   |     |
| Se sim para o anterior, por favor explique                       |     |

## Riscos do Protocolo

Diga-nos quais riscos você considera aceitáveis. Ignoraremos a avaliação de alguns riscos com base neste feedback.

| Devemos avaliar riscos relacionados à centralização?                                 |     |
| ------------------------------------------------------------------------------------ | --- |
| Devemos avaliar os riscos de admin malicioso capturando fundos dos usuários?         |     |
| Devemos avaliar riscos relacionados a tokens ERC20 deflacionários/inflacionários?    |     |
| Devemos avaliar riscos devido a tokens com taxa na transferência?                    |     |
| Devemos avaliar riscos devido a tokens com rebase?                                   |     |
| Devemos avaliar riscos devido à pausa de contratos externos?                         |     |
| Devemos avaliar riscos associados a oráculos externos (se existirem)?                |     |
| Devemos avaliar riscos relacionados a usuários na lista negra de tokens específicos? |     |
| O código deve estar em conformidade com algum EIP específico?                        |     |
| Se sim para o anterior, por favor compartilhe os EIPs                                |     |

## Problemas Conhecidos

Os desenvolvedores do protocolo já estão cientes e trabalhando nos seguintes problemas e/ou os consideram riscos aceitáveis.

| Problema #1 |     |
| ----------- | --- |

## Auditorias e Relatórios Anteriores

Por favor, compartilhe relatórios de auditoria existentes.

| Quantas auditorias anteriores       | X   |
| ----------------------------------- | --- |
| Link para Relatório(s) de Auditoria |     |

## Recursos

Recursos que podem nos ajudar a entender melhor o protocolo.

### Fluxogramas / Documentos de Design

-

### Vídeos Explicativos

- ...

### Artigos / Blogs

- ...

## O Teste Rekt

1. Você tem todos os atores, papéis e privilégios documentados?
2. Você mantém documentação de todos os serviços externos, contratos e oráculos dos quais depende?
3. Você tem um plano de resposta a incidentes por escrito e testado?
4. Você documenta as melhores maneiras de atacar seu sistema?
5. Você realiza verificação de identidade e verificação de antecedentes em todos os funcionários?
6. Você tem um membro da equipe com segurança definida em sua função?
7. Você exige chaves de segurança física para sistemas de produção?
8. Seu sistema de gerenciamento de chaves requer múltiplos humanos e etapas físicas?
9. Você define invariantes principais para seu sistema e os testa em cada commit?
10. Você usa as melhores ferramentas automatizadas para descobrir problemas de segurança em seu código?
11. Você passa por auditorias externas e mantém um programa de divulgação de vulnerabilidades ou recompensa por bugs?
12. Você considerou e mitigou formas de abusar dos usuários do seu sistema?

## Planejamento Pós-Implantação

1. Você está planejando usar um programa de recompensa por bugs? Qual/onde?
2. Qual é sua solução de monitoramento? O que você está monitorando?
3. Quem é sua equipe de resposta a incidentes?
