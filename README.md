<div align="center">

<h1>Albert Kooro</h1>

<p>Desenvolvedor Back-end · Go · Node.js · SQL</p>

<a href="https://www.linkedin.com/in/albert-kooro/"><img src="https://img.shields.io/badge/LinkedIn-1f6feb?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:albertkooro@icloud.com"><img src="https://img.shields.io/badge/Email-1f6feb?style=flat-square&logo=icloud&logoColor=white" /></a>
<a href="https://portifolio-linkedin-gamma.vercel.app"><img src="https://img.shields.io/badge/Portf%C3%B3lio-1f6feb?style=flat-square&logo=vercel&logoColor=white" /></a>

</div>

<br>

### Sobre

Desenvolvedor back-end com foco em APIs REST, hoje principalmente em **Go** e **Node.js**, com SQL Server na camada de dados.

Atuo na **Clicksign**, plataforma de assinatura eletrônica, em Customer Success, o que me dá contato diário com o produto e com os problemas reais de quem usa. Antes, desenvolvi APIs e regras de negócio em Node.js na **Krypta Solutions**.

<br>

### Stack

<p>
<img src="https://skillicons.dev/icons?i=go,nodejs,ts,js,python,git&theme=dark" />
</p>

| Área | Tecnologias |
|---|---|
| Linguagens | Go, JavaScript (Node.js), TypeScript, Python |
| Banco de dados | SQL Server: queries, procedures e modelagem |
| Ferramentas | Git, GitHub |

<br>

### Projeto em destaque

**[cpf-validator-api](https://github.com/AlbertKoor/cpf-validator-api)** · API REST em Go para validação de CPF

- `POST /api/v1/validate_cpf` recebe o CPF em JSON e responde se ele é válido
- Aceita CPF com ou sem máscara e rejeita letras, tamanho errado e dígitos todos iguais
- Calcula e confere os dois dígitos verificadores
- Responde `400 Bad Request` para JSON mal formado
- Rota `GET /status` para verificar se a API está no ar
- Regra de validação isolada em `internal/cpf`, coberta por testes unitários

```jsonc
// requisição
{ "cpf": "529.982.247-25" }

// resposta
{ "valid": true }
```

<br>

### Experiência

| Empresa | Função | Período |
|---|---|---|
| Clicksign | Customer Success | Atual |
| Krypta Solutions | Desenvolvimento back-end (Node.js) | Anterior |

<br>

### Formação

| Curso | Instituição | Status |
|---|---|---|
| Análise e Desenvolvimento de Sistemas | Universidade Cruzeiro do Sul | Em andamento |
