# Meu Repositório de Estudo - Git e Github

## Objetivos da Aula:

# Inicializar um repositório Git
Se você ainda não tem um repositório Git, inicie um novo ou clone um existente:

# Iniciar um novo repositório
*git init* inicia 

# OU

# Clonar um repositório existente
*git clone* https://github.com/seu-usuario/seu-repositorio.git
Adicionar arquivos ao repositório
Adicione os arquivos que você deseja enviar para o repositório:

Copy
# Adicionar todos os arquivos no diretório
*git add .*

# OU

# Adicionar um arquivo específico
*git add nome-do-arquivo*
Commitar as mudanças
Comite as mudanças adicionadas, fornecendo uma mensagem descritiva:

# A mensagem do commit deve ser clara e concisa, explicando o que foi alterado.
*git commit -m "Mensagem do commit aqui"*
Enviar para o GitHub
Se ainda não vinculou seu repositório local a um repositório remoto no GitHub, faça isso:

*git remote add origin https://github.com/seu-usuario/seu-repositorio.git*
Agora, envie as alterações para o GitHub:


*git push -u origin branch-name*
Substitua branch-name pelo nome da sua branch atual (geralmente é main ou master).