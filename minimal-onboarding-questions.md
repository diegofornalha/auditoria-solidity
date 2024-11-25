# Revisão de Segurança Mínima de Contratos Inteligentes

# Índice

- [Revisão de Segurança Mínima de Contratos Inteligentes](#revisão-de-segurança-mínima-de-contratos-inteligentes)
- [Índice](#índice)
- [Sobre o projeto / Documentação](#sobre-o-projeto--documentação)
- [Estatísticas](#estatísticas)
- [Configuração](#configuração)
  - [Requisitos](#requisitos)
  - [Testes](#testes)
- [Escopo da Revisão de Segurança](#escopo-da-revisão-de-segurança)
  - [Hash do Commit](#hash-do-commit)
  - [URL do Repositório](#url-do-repositório)
  - [Contratos dentro vs fora do escopo](#contratos-dentro-vs-fora-do-escopo)
  - [Compatibilidades](#compatibilidades)
- [Funções](#funções)
- [Problemas Conhecidos](#problemas-conhecidos)

# Sobre o projeto / Documentação

_Resumo do projeto. Quanto mais documentação, melhor._

# Estatísticas

_Use algo como métricas do solidity ou cloc para obter estes dados._

- nSLOC: XX
- Pontuação de Complexidade: XX
- Cronograma da Revisão de Segurança: Data -> Data

# Configuração

## Requisitos

_Quais ferramentas são necessárias para configurar a base de código e o conjunto de testes?_

Exemplo:

```bash
forge init
forge install OpenZeppelin/openzeppelin-contracts --no-commit
forge install vectorized/solady --no-commit
forge build
```

## Testes

_Como executar os testes. Como ver a cobertura dos testes._

Example:

```bash
forge test
```

# Escopo da Revisão de Segurança

_Os detalhes específicos da revisão de segurança. Defina exatamente o que o protocolo está planejando implantar e como planeja implantá-lo._

## Hash do Commit

## URL do Repositório

## Contratos dentro vs fora do escopo

## Compatibilidades

- Versão do Solc: XXX
- Redes para implantação do contrato:
  - XXX (ex: ETH)
  - XXX (ex: Arbitrum)
- Tokens:
  - XXX (ex: ERC20s)
    - XXX (ex: LINK: <endereço>)
    - XXX (ex: USDC: <endereço>)
  - XXX (ex: ERC721s)
    - XXX (ex: CryptoKitties: <endereço>)
  - _Liste os ERC20s esperados e outros tokens específicos. Se um protocolo deve funcionar com múltiplos ou quaisquer tokens de um determinado padrão, você pode fazer algo como "Todos os ERC20s". Ou uma lista ordenada como "USDC: <Endereço USDC>" etc_

# Funções

_Quais são os diferentes atores do sistema? Quais são seus poderes? O que eles devem/não devem fazer?_

Exemplo:

```
Atores:
    Comprador: O comprador dos serviços, neste cenário, um projeto comprando uma auditoria.
    Vendedor: O vendedor dos serviços, neste cenário, um auditor disposto a auditar um projeto.
    Árbitro: Um ator imparcial e confiável que pode resolver disputas entre o Comprador e o Vendedor.
    O Árbitro só é compensado com o valor da taxa de arbitragem se ocorrer uma disputa.
```

# Problemas Conhecidos

_Liste quaisquer problemas que a equipe do protocolo está ciente e não irá reconhecer/corrigir._
