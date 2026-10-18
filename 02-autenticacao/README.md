# 🔑 AuthLab — Autenticação e Controle de Acesso

Laboratório prático do curso de **Cibersegurança do OxeTech Lab**, baseado no cenário fictício **AccessLab Systems**.

## 🎯 Objetivos

Ao concluir as atividades, o estudante deverá ser capaz de:

- Diferenciar autenticação (AuthN) e autorização (AuthZ), incluindo respostas HTTP 401, 403, 404 e 429.
- Entender o armazenamento seguro de senhas com salt individual e PBKDF2-HMAC-SHA256.
- Simular limites de tentativas e bloqueio temporário.
- Explicar MFA/TOTP, janela temporal, expiração e prevenção de replay.
- Comparar sessões stateful e tokens JWT, validando assinatura e claims.
- Aplicar RBAC, escopo e propriedade do recurso para evitar falhas de controle de acesso, incluindo IDOR.
- Integrar os controles em um fluxo didático e examinar logs sem credenciais.

## 🧪 Material

- [AuthLab — versão do aluno](./AuthLab-Aluno.ipynb)

O notebook inclui conceitos, demonstrações, testes, desafios e perguntas para análise Blue Team. Os exercícios usam somente dados fictícios e estruturas locais em memória.

## ⚙️ Ambiente

Compatível com:

- Google Colab
- Jupyter Notebook
- VS Code com extensão Jupyter

Requisitos recomendados: **Python 3.10 ou superior**.

Para instalar as dependências manualmente:

```bash
python -m pip install -r requirements.txt
```

O notebook também verifica e instala as dependências fixadas quando necessário. A instalação inicial exige acesso ao PyPI, salvo se os pacotes já estiverem instalados. O QR Code TOTP é opcional e fica desativado por padrão.

## ⏱️ Tempo sugerido

**220 minutos (3h40)**, que podem ser divididos em duas aulas.

## ⚠️ Uso responsável

Material exclusivamente educacional. Todos os usuários, relatórios, senhas, tokens e segredos são fictícios. Não use credenciais pessoais nem conecte o notebook a sistemas reais.

**SecureAccess é uma simulação didática, não um sistema de produção.** Persistência, concorrência, transporte HTTP/TLS, recuperação de conta e gestão operacional de segredos não são implementados.

---

**Docente:** Fernando dos Santos Alves  
**OxeTech Lab — Cibersegurança**
