# Ponytail — Guia em Português Brasileiro

> Ferramenta original: https://github.com/DietrichGebert/ponytail

Ponytail é um conjunto de regras, skills e plugins para agentes de programação, projetado para incentivar soluções simples, reduzir complexidade desnecessária e melhorar revisões de código. Esta página documenta como instalar o projeto oficial no **Codex** e no **Claude Code**.

## Instalação no Codex

No terminal:

```bash
codex plugin marketplace add DietrichGebert/ponytail
codex plugin add ponytail@ponytail
```

Depois inicie o Codex, abra `/hooks`, revise e autorize os dois hooks e comece uma nova conversa. Reinicie o aplicativo desktop se necessário.

## Instalação no Claude Code

Envie **em duas mensagens separadas** dentro do Claude Code:

```text
/plugin marketplace add DietrichGebert/ponytail
```

```text
/plugin install ponytail@ponytail
```

**Requisito:** Node.js disponível no PATH para execução dos hooks de ciclo de vida.

## Prompt universal — copie para Codex ou Claude

```text
Instale e configure o Ponytail globalmente para meu agente de programação.
Fonte oficial: https://github.com/DietrichGebert/ponytail
Guia em português: https://github.com/thuf86/ponytail

1. Identifique o sistema operacional e se está executando no Codex ou Claude Code.
2. Leia o README.md e o INSTALL.md oficiais e identifique requisitos e comandos atuais.
3. Verifique Node.js, instalações anteriores, permissões e configurações existentes.
4. Instale pelo marketplace oficial, seguindo o método correspondente ao agente.
5. Para Codex, revise os hooks comigo antes de habilitá-los via /hooks.
6. Para Claude Code, execute separadamente os dois comandos /plugin.
7. Configure o plugin em escopo global de usuário quando suportado.
8. Preserve outras skills, plugins, arquivos e configurações já existentes.
9. Valide carregamento, comandos, skills e hooks em uma nova sessão.
10. Documente atualização, desativação e desinstalação.
11. Não execute scripts remotos não revisados nem altere configurações sensíveis sem autorização.

Ao concluir, apresente um relatório em português com versão, origem,
comandos utilizados, testes, resultados e eventuais pendências.
```

## Documentação e autoria

- [Repositório original](https://github.com/DietrichGebert/ponytail)
- [Manual de instalação](https://github.com/DietrichGebert/ponytail/blob/main/INSTALL.md)
- [Licença original](https://github.com/DietrichGebert/ponytail/blob/main/LICENSE)

**Créditos:** DietrichGebert e colaboradores. Guia em português mantido por thuf86.

**Nota de integridade:** este repositório contém, neste momento, documentação de instalação e não deve ser confundido com uma cópia integral do código-fonte original. Instale pelo projeto oficial nos comandos acima.
