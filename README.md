# 🤖 Claude Code Integrado

Este repositorio está configurado con Claude Code para revisión automática de Pull Requests y respuestas inteligentes en Issues.

## 🚀 ¿Qué hace Claude?

- Revisa código automáticamente cuando se abre un Pull Request
- Responde menciones como @claude en Issues y comentarios
- Adapta sus respuestas según etiquetas como ug, yuda, o evisión

## 🧪 Cómo probarlo

1. Crea un Pull Request → Claude lo revisará automáticamente
2. Crea un Issue con una etiqueta (ug, yuda, evisión)
3. Menciona a Claude en el cuerpo del Issue:

\\\
@claude ¿puedes revisar este error?
\\\

## 🔐 Seguridad

Claude usa un token privado guardado como secreto en GitHub: CLAUDE_CODE_OAUTH_TOKEN
