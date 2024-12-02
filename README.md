# Pokémon Battle Simulator

Este é um simulador simples de batalhas Pokémon desenvolvido em TypeScript. O projeto inclui dois tipos de Pokémon: Selvagem e Doméstico, com funcionalidades de treinamento, batalha, descanso e mais.

## Funcionalidades

- **Treinar ataque**: Melhora os atributos de ataque do Pokémon.
- **Treinar defesa**: Melhora os atributos de defesa do Pokémon.
- **Imprimir atributos**: Exibe o status atual do Pokémon.
- **Batalhar**: Simula uma batalha, reduzindo a energia do Pokémon.
- **Descansar**: Recupera a energia do Pokémon.

## Estrutura do Projeto

- **Pokemon**: Classe abstrata base para definir as propriedades e métodos comuns.
- **Selvagem**: Classe que estende `Pokemon` com características específicas de um Pokémon selvagem.
- **Domestico**: Classe que estende `Pokemon` com características específicas de um Pokémon domesticado.

## Pré-requisitos

- Node.js instalado
- Gerenciador de pacotes npm

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Instale as definições de tipo para prompt-sync:
    ```bash
    npm i @types/prompt-sync -D
    ```

## Uso

1. Compile o TypeScript para JavaScript:
    ```bash
    npx tsc
    ```
2. Execute o programa:
    ```bash
    node dist/index.js
    ```
3. Interaja com o menu no terminal para treinar, batalhar ou descansar com seu Pokémon.

## Estrutura de Código

- **Pokemon.ts**: Classe abstrata que define os métodos e propriedades básicas.
- **Selvagem.ts**: Classe que implementa as ações de um Pokémon selvagem.
- **Domestico.ts**: Classe que implementa as ações de um Pokémon doméstico.
- **index.ts**: Arquivo principal que executa o jogo com interação via terminal.

## Contribuindo

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do projeto.
2. Crie uma branch com sua feature: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Minha nova feature'`.
4. Envie suas alterações: `git push origin minha-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a MIT License.