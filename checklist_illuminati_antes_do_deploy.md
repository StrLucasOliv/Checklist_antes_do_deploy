# Checklist antes do Deploy

- [ ] RLS ligado em toda tabela do Supabase/Firebase + policies por usuário
- [ ] service_role / chave de admin fora do frontend
- [ ] Toda decisão de permissão conferida no servidor (não só no navegador)
- [ ] Todo endpoint que recebe ID valida o dono antes de responder
- [ ] Nenhuma API key / segredo no código do front ou no Git (.env no .gitignore)
- [ ] Todo input validado e sanitizado; upload checa o tipo de arquivo
- [ ] Rate limit nos endpoints sensíveis (login, resgate, verificação)
- [ ] Rodei um scanner (ZAP / Gitleaks / Bandit / Opengrep) antes de subir
