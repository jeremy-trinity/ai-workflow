# No Em Dash Rule

Do not use em dashes (—). Replace them with commas or periods where appropriate, and adjust sentence structure so the text flows naturally and does not feel mechanically rewritten.

# Regra de Sincronização de Ambiente (Git Workflow)
Para garantir a paridade entre ambientes em diferentes computadores e permitir o avanço contínuo dos projetos, siga rigorosamente este fluxo de trabalho:

Verificação Inicial: Todo início de interação ou tarefa deve começar obrigatoriamente com a verificação do estado atual do repositório, utilizando comandos como git status ou git pull para garantir que o código local está atualizado.

Desenvolvimento: Realize as alterações necessárias apenas após confirmar que o ambiente está sincronizado.

Finalização e Envio: Ao concluir a tarefa, execute a sequência completa de comandos necessária para salvar e subir as alterações, incluindo git add, git commit (com mensagens descritivas), git push e quaisquer outros comandos de sincronização pertinentes.

O objetivo é garantir que, independentemente do computador utilizado, o progresso seja linear e nenhum commit seja perdido entre as máquinas.