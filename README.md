<div align="center">

# 🧩 PONYTAIL

**Regras, skills e plugins para simplificar o desenvolvimento assistido por IA**

![Idioma](https://img.shields.io/badge/IDIOMA-PT--BR-65c600?style=for-the-badge)
![Codex](https://img.shields.io/badge/OPENAI_CODEX-COMPAT%C3%8DVEL-0078d4?style=for-the-badge)
![Claude](https://img.shields.io/badge/CLAUDE_CODE-COMPAT%C3%8DVEL-111827?style=for-the-badge)
![Origem](https://img.shields.io/badge/ORIGEM-DietrichGebert-f0b400?style=for-the-badge)

</div>

---

## ⭐ Apoie o projeto — deixe uma ⭐

Se este guia ajudar, considere deixar uma estrela e compartilhar melhorias. Apoie também o [projeto original](https://github.com/DietrichGebert/ponytail).

---

## 📌 Visão geral

O **Ponytail** reúne instruções, skills e plugins para agentes de programação, incentivando soluções mais simples, menos complexidade desnecessária e revisões de código criteriosas.

**Projeto original:** [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)  
**Documentação em português:** [thuf86](https://github.com/thuf86)

> **Importante:** este repositório disponibiliza um guia comunitário em português. Não é, atualmente, um espelho completo do código original. Os comandos abaixo instalam a distribuição oficial.

---

## ✨ Principais recursos

| Recurso | Finalidade |
|---|---|
| Regras de desenvolvimento | Incentivar implementações diretas e evitar complexidade desnecessária |
| Skills | Orientar tarefas de desenvolvimento e revisão |
| Integração Codex | Instalação por marketplace e hooks |
| Integração Claude Code | Instalação como plugin do Claude |
| Configuração assistida | Prompt pronto para executar no agente |
| Documentação PT-BR | Guia de instalação e referências oficiais |

---

## 🚀 Instalação rápida

**Requisito:** Node.js disponível no PATH para os hooks de ciclo de vida.

### OpenAI Codex

Execute no terminal:

```bash
codex plugin marketplace add DietrichGebert/ponytail
codex plugin add ponytail@ponytail
```

Inicie o Codex, abra `/hooks`, **revise e autorize** os dois hooks e comece uma nova conversa. Reinicie o aplicativo desktop, se necessário.

### Claude Code

Execute **separadamente**, dentro do Claude Code:

```text
/plugin marketplace add DietrichGebert/ponytail
```

```text
/plugin install ponytail@ponytail
```

---

## 🤖 Prompt universal — instalação com Codex ou Claude Code

Copie e cole este prompt no agente desejado:

```text
Instale e configure globalmente o Ponytail para meu agente de programação.
Fonte oficial: https://github.com/DietrichGebert/ponytail
Guia PT-BR: https://github.com/thuf86/ponytail

1. Identifique o sistema operacional e o agente atual (Codex ou Claude Code).
2. Leia o README.md e INSTALL.md oficiais e confirme os requisitos atuais.
3. Verifique Node.js, instalações anteriores, plugins, hooks e permissões.
4. Instale pelo marketplace oficial usando o método específico do agente.
5. No Codex, apresente os hooks para minha revisão antes de habilitá-los.
6. No Claude Code, envie os dois comandos /plugin separadamente.
7. Configure no escopo global do usuário, quando suportado.
8. Preserve minhas configurações, plugins e skills existentes.
9. Reinicie a sessão quando necessário e valide o carregamento do plugin.
10. Explique como atualizar, desativar e desinstalar.
11. Não execute scripts remotos não revisados nem modifique configurações
    sensíveis sem minha autorização.

Entregue relatório em português com ambiente, origem, versão,
comandos executados, validações e pendências.
```

---

## 📂 Estrutura do repositório

```text
ponytail/
└── README.md     # Guia PT-BR e prompt universal
```

O código executável, skills e hooks estão no [repositório oficial](https://github.com/DietrichGebert/ponytail).

---

## 📚 Documentação

- [README oficial](https://github.com/DietrichGebert/ponytail/blob/main/README.md)
- [Manual oficial de instalação](https://github.com/DietrichGebert/ponytail/blob/main/INSTALL.md)
- [Código-fonte e atualizações](https://github.com/DietrichGebert/ponytail)

---

## 🔐 Segurança e boas práticas

Revise os hooks antes de autorizá-los, preserve as configurações existentes e não compartilhe credenciais ou tokens. Confirme sempre os comandos na documentação oficial antes de executá-los.

---

## ⚖️ Créditos e licença

**Autor do projeto original:** [DietrichGebert](https://github.com/DietrichGebert/ponytail) e colaboradores.  
**Guia comunitário em português:** [thuf86](https://github.com/thuf86).

A licença e os direitos autorais do código original pertencem aos respectivos titulares. Consulte o [arquivo LICENSE oficial](https://github.com/DietrichGebert/ponytail/blob/main/LICENSE).
