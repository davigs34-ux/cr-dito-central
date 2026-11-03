# Receber instruções do ChatGPT via GitHub

## Como vai funcionar
1. **Você conecta o GitHub** (só você pode fazer isso): Configurações do projeto → Git → Conectar GitHub. Isso cria um repositório novo, sincronizado nos dois sentidos.
2. **O ChatGPT trabalha no repositório**: pode alterar o código direto (as mudanças aparecem aqui automaticamente) ou escrever pedidos num arquivo `INSTRUCOES.md` na branch principal.
3. **Eu executo**: eu não leio o GitHub sozinho. Quando o ChatGPT atualizar o `INSTRUCOES.md`, você me escreve "siga as instruções" e eu faço as tarefas e marco cada uma como feita.

## O que eu preparo agora
- Criar o `INSTRUCOES.md` com um modelo simples (lista de tarefas, status: pendente/feito, observações).
- Escrever no `AGENTS.md` a regra de ler o `INSTRUCOES.md` sempre que você pedir, e as regras do projeto que o ChatGPT deve seguir (sistema de páginas fixo, estilos, sem alterar arquivos gerados).

## Cuidados
- Peça para o ChatGPT enviar as mudanças na branch principal; outras branches não chegam aqui.
- Se os dois mexerem ao mesmo tempo, pode dar conflito; trabalhe com um de cada vez.
