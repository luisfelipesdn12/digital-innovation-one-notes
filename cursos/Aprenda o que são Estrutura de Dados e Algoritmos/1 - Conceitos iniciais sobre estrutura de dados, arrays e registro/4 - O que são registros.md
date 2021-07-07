# O que são registros

---

## Defnição

Nos arrays, temos armazenados múltiplos dados do mesmo tipo. No caso de registros, podemos armazenar múltiplos dados de múltiplos tipos juntos.

Para especificar cada um dos dados armazenados, campos nomeados compõe um registro. Podemos pensar nisso como uma tabela.

### Exemplo

Um registro de cliente:

| CPF            | Nome              | Endereço | Contato         |
| -------------- | ----------------- | -------- | --------------- |
| 333.283.541-66 | Mariane Rodrigues | Rua G    | (79) 98520-6949 |

No registro, podemos acessar campo específico da segunte forma:

```typescript
console.log(cliente.nome)
// => Mariane Rodrigues
```

