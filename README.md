# Cucumber-JS Examples

There are so many ways you can use Cucumber-JS!

For example:

  * [a Node.js app with ESM](./examples/esm-node)
  * [a TypeScript Node.js app](./examples/typescript-node)
  * [a Command-line Node.js app](./examples/command-line)
  * [a GitHub Probot app](./examples/probot)

## Diagramas
```mermaid
sequenceDiagram
    accTitle: My title here
    accDescr: My description here
    title Diagrama de Flujo Create Wallet
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop HealthCheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

### Mermaid with custom title/desc
```mermaid
sequenceDiagram
    title Diagrama de Flujo Preparación de datos de tarjeta
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop HealthCheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```