[![Português](https://img.shields.io/badge/Portugu%C3%AAs-green?style=plastic&logo=openbadges&logoColor=white)](README-pt-BR.md) [![English](https://img.shields.io/badge/English-blue?style=plastic&logo=openbadges&logoColor=white)](README.md)

<div align="center">
  <a href="https://vitalets.github.io/playwright-bdd">
    <img width="128" alt="playwright-bdd" src="./docs/logo.svg">
  </a>
</div>

<h2 align="center">Playwright-BDD</h2>
<div align="center">

Execute testes BDD com o runner do Playwright

</div>

<div align="center">

[![lint](https://github.com/vitalets/playwright-bdd/actions/workflows/lint.yaml/badge.svg)](https://github.com/vitalets/playwright-bdd/actions/workflows/lint.yaml)
[![test](https://github.com/vitalets/playwright-bdd/actions/workflows/test.yaml/badge.svg)](https://github.com/vitalets/playwright-bdd/actions/workflows/test.yaml)
[![npm version](https://img.shields.io/npm/v/playwright-bdd)](https://www.npmjs.com/package/playwright-bdd)
[![npm downloads](https://img.shields.io/npm/dw/playwright-bdd)](https://www.npmjs.com/package/playwright-bdd)
[![license](https://img.shields.io/npm/l/playwright-bdd)](https://github.com/vitalets/playwright-bdd/blob/main/LICENSE)

</div>

<p align="center">
  🚀 <a href="https://vitalets.github.io/playwright-bdd/#/getting-started/index">Começando</a>&nbsp;
  📚 <a href="https://vitalets.github.io/playwright-bdd/">Documentação</a>&nbsp;
  ▶️ <a href="https://github.com/vitalets/playwright-bdd-example">Exemplo</a>&nbsp;
  📝 <a href="https://github.com/vitalets/playwright-bdd/blob/main/CHANGELOG.md">Changelog</a>
</p>

## BDD na Era da IA

O [Desenvolvimento Guiado por Comportamento (BDD)](https://cucumber.io/docs/bdd/) descreve os requisitos do produto como cenários `Given / When / Then` escritos em arquivos `.feature`. Esses cenários são artefatos valiosos para agentes de IA porque são ao mesmo tempo:

* **legíveis**: você pode refiná-los facilmente durante o planejamento para dar ao agente um objetivo claro.
* **executáveis**: uma vez que o código é escrito, o agente executa os mesmos cenários como testes para verificar a implementação.

Diferentemente de especificações em markdown puro, o BDD não apenas descreve o recurso; ele torna a especificação viva e a mantém alinhada com a base de código.

Instale a [skill playwright-bdd](https://vitalets.github.io/playwright-bdd/#/getting-started/agent-skill) e confira o [artigo de blog](https://vitalets.github.io/posts/bdd-agentic-workflow/) sobre o uso de BDD em fluxos de trabalho agenticos.

```diff
Feature: Agentic development

  Scenario: Implement a new feature
    Given business requirements
    When a human defines the behavior as BDD steps
-   Then the human implements the feature and verifies it with tests
+   Then the agent implements the feature and verifies it with tests
```

## Por que o Playwright Runner?

O [Playwright](https://playwright.dev/) fornece tanto APIs de automação de navegador quanto um poderoso runner de testes. O Playwright-BDD converte arquivos `.feature` em testes nativos do Playwright, para que você possa usar todos os recursos do runner do Playwright:

- Configuração e limpeza automáticas do navegador
- Espera automática pelos elementos da página
- Captura automática de screenshots, vídeos e traces
- Execução paralela e sharding
- Relatórios integrados e testes de comparação visual
- Fixtures do Playwright
- [...e muito mais](https://playwright.dev/docs/library#key-differences)

## Como Funciona

<img align="center" src="https://raw.githubusercontent.com/vitalets/playwright-bdd/refs/heads/main/docs/_media/schema.png"/>

## Extras
O Playwright-BDD possui vários recursos exclusivos:

- 🔥 Tags avançadas [por caminho](https://vitalets.github.io/playwright-bdd/#/writing-features/tags-from-path) e [tags especiais](https://vitalets.github.io/playwright-bdd/#/writing-features/special-tags)
- 🎩 [Decoradores de steps](https://vitalets.github.io/playwright-bdd/#/writing-steps/decorators) para métodos de classe  
- 🎯 [Definições de steps com escopo](https://vitalets.github.io/playwright-bdd/#/writing-steps/scoped)  
- ✨ [Exportação de steps](https://vitalets.github.io/playwright-bdd/#/writing-features/chatgpt) para IA  
- ♻️ [Funções de step reutilizáveis](https://vitalets.github.io/playwright-bdd/#/writing-steps/reusing-step-fn)  

## Documentação
Confira o [site de documentação](https://vitalets.github.io/playwright-bdd/#/).

## Demos

- Confira a pasta [`examples`](/examples)
- Clone o repositório totalmente funcional: [playwright-bdd-example](https://github.com/vitalets/playwright-bdd-example)

## Suporte a Versões do Playwright

O `playwright-bdd` suporta todas as versões **não descontinuadas** do Playwright. Para verificar quais versões do Playwright estão atualmente descontinuadas, execute:
```bash
npm show @playwright/test@1 deprecated
```

## Changelog
Confira as últimas alterações no [CHANGELOG.md](https://github.com/vitalets/playwright-bdd/blob/main/CHANGELOG.md).

## 💖 Patrocinadores

Um enorme agradecimento às **pessoas e empresas incríveis** que já apoiam o Playwright-BDD! Sua ajuda mantém o projeto vivo e em crescimento:

<p align="center">
  <a href="https://currents.dev/" target="_blank">
    <img src="./docs/_media/sponsors/currents.svg" alt="Currents" width="300" />
  </a>
</p>

<p align="center">
<a href="https://www.testmuai.com/?utm_medium=sponsor&utm_source=playwright-bdd" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./docs/_media/sponsors/testmu-ai-white.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./docs/_media/sponsors/testmu-ai-black.svg" />
      <img src="./docs/_media/sponsors/testmu-ai-black.svg" alt="TestMu AI" width="300">
    </picture>
  </a>
</p>

<p align="center">

<!-- sponsors --><a href="https://github.com/alescinskis"><img src="https:&#x2F;&#x2F;github.com&#x2F;alescinskis.png" width="60px" alt="User avatar: Arturs Leščinskis" /></a><a href="https://github.com/alexhvastovich"><img src="https:&#x2F;&#x2F;github.com&#x2F;alexhvastovich.png" width="60px" alt="User avatar: " /></a><a href="https://github.com/FrancescoBorzi"><img src="https:&#x2F;&#x2F;github.com&#x2F;FrancescoBorzi.png" width="60px" alt="User avatar: Francesco Borzì" /></a><!-- sponsors -->

</p>

Se você acha o Playwright-BDD útil em seus projetos pessoais ou de trabalho, considere [tornar-se um patrocinador](https://github.com/sponsors/vitalets). Mesmo pequenas contribuições ajudam a dedicar mais tempo à manutenção, a novos recursos e ao suporte à comunidade.

## Feedback & Comunidade

Sinta-se à vontade para reportar um bug, propor um recurso ou compartilhar sua experiência:

* [GitHub issues](https://github.com/vitalets/playwright-bdd/issues)
* [Discord do Playwright-BDD](https://discord.gg/5rwa7TAGUr)

## Contribuindo
Suas contribuições são bem-vindas! Por favor, revise o [CONTRIBUTING.md](https://github.com/vitalets/playwright-bdd/blob/main/.github/CONTRIBUTING.md) para os detalhes.

## Outras ferramentas Playwright que criei

* [playwright-timeline-reporter](https://github.com/vitalets/playwright-timeline-reporter) - Relatório de timeline interativo para execuções de testes do Playwright.
* [@global-cache/playwright](https://github.com/vitalets/global-cache) - Cache chave-valor para compartilhar dados entre workers paralelos.
* [request-mocking-protocol](https://github.com/vitalets/request-mocking-protocol) - Mock de chamadas de API no servidor no Playwright.
* [playwright-network-cache](https://github.com/vitalets/playwright-network-cache) - Acelere testes do Playwright armazenando requisições de rede em cache no filesystem.
* [playwright-magic-steps](https://github.com/vitalets/playwright-magic-steps) - Transforme automaticamente comentários JavaScript em steps do Playwright.

## Licença
Este projeto é licenciado sob a [Licença MIT](https://github.com/vitalets/playwright-bdd/blob/main/LICENSE), permitindo que você use, modifique e compartilhe o código livremente, até mesmo para fins comerciais. Aproveite para construir algo incrível! 🎉