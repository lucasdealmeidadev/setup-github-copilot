---
applyTo: '**/*.ts,**./*.tsx'
---

# Padrões de codificação de projetos para TypeScript e React

Aplique as [diretrizes gerais de codificação](./general-coding.instructions.md) a todo o código

## Diretrizes de TypeScript

- Use TypeScript para todo o código novo
- Siga os princípios de programação funcional sempre que possível
- Use interfaces para estruturas de dados e definições de tipo
- Prefira dados imutáveis (const, somente leitura)
- Use operadores opcionais de encadeamento (?.) e coalescência nula (??)

## Diretrizes do React

- Use componentes funcionais com ganchos
- Siga as regras de ganchos do React (sem ganchos condicionais)
- Use o tipo React.FC para componentes filhos
- Mantenha os componentes pequenos e focados
- Use módulos CSS para estilização de componentes