# Prompt de Segurança para Revisão de Código (IA)

Copie e cole o texto abaixo no seu LLM/IA de preferência para analisar vulnerabilidades.

> **Revisa este código atrás das 5 falhas mais comuns em app gerado por IA:**
> 
> **(1)** Tabelas de Supabase/Firebase sem RLS (Row Level Security);
> **(2)** Autorização decidida no frontend em vez do servidor;
> **(3)** Rotas que buscam por ID sem checar o dono (vulnerabilidade IDOR);
> **(4)** Segredos e chaves de API expostos no código ou enviados no bundle final;
> **(5)** Input do usuário sem validação/sanitização adequada e upload de arquivos sem checar o tipo.
> 
> *Lista cada achado identificando o arquivo, a linha exata e fornecendo as instruções passo a passo de como corrigir.*

---
**→ Dica:** Forneça os arquivos de código logo após enviar este prompt.
