<div align="center">

# Lucas Velôso

**Automation Engineer** · Backend · AWS

<a href="https://github.com/oveloso">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=680&lines=Entendo+o+problema+antes+de+abrir+o+editor;Backend+serverless+%E2%80%94+rumo+%C3%A0+arquitetura;Penso+em+evento%2C+fila%2C+retry%2C+o+que+quebra+%C3%A0s+3h" alt="quem sou"/>
</a>

</div>

Tenho 24 anos e 2 na área. Entrei pela porta da **operação** — mapeando processo, entendendo o que estava quebrado antes de escrever qualquer linha — e fui parar na engenharia. Hoje construo backend serverless e estou indo fundo em Python, mirando arquitetura de software.

O que me move não é a ferramenta, é o **problema**. Antes do editor, eu quero saber o que falha no processo e por quê. Foi assim que aprendi AWS: não como uma lista de serviços, mas como o jeito de fazer um sistema aguentar o mundo real.

### Como eu penso um sistema

```
evento entra        →  API Gateway
processa            →  Lambda  (x86 ou Graviton/ARM pra cortar custo)
guarda estado       →  DynamoDB / S3
o que falha         →  DLQ + retry  (nada se perde calado)
fica observável     →  CloudWatch + alarmes  (eu descubro antes do cliente)
chega rápido        →  CloudFront na borda
não precisa de código?  →  n8n
```

Quando o problema pede, troco de nuvem (GCP) ou subo uma automação no lugar de um serviço. A decisão é do problema, não da ferramenta favorita.

### No que estou trabalhando

- **[serverless-crm-integration](https://github.com/oveloso/serverless-crm-integration)** — pipeline serverless orientado a eventos (Lambda · SQS · DynamoDB). Circuit breaker, rate limiter global e idempotência, com 400+ testes passando. *Código real, em TypeScript.*
- **[pipeline-traducao-juramentada](https://github.com/oveloso/pipeline-traducao-juramentada)** — um documento sai do CRM e volta assinado, sem ninguém no meio. Cada etapa pensada em torno de "o que acontece quando falha".
- **[analise-cidadania-italiana](https://github.com/oveloso/analise-cidadania-italiana)** — IA que faz a triagem de uma pasta de cidadania: horas de conferência viram minutos.

### Onde estou indo

Backend forte agora, arquitetura de software depois. Estudando Python a fundo e sistemas distribuídos — quero ser o dev que entende o sistema linha por linha, não o que só faz funcionar.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oveloso/oveloso/output/github-snake-dark.svg">
  <img alt="snake comendo o contribution graph" src="https://raw.githubusercontent.com/oveloso/oveloso/output/github-snake.svg">
</picture>

</div>

---

<div align="center">

[![CV](https://img.shields.io/badge/CV-1F6FEB?style=flat-square&logo=readme&logoColor=white)](https://github.com/oveloso/cv)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-veloso-pergentino)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lucasvelosopergentino@gmail.com)

</div>
