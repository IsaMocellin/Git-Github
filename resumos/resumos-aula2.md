Comando                           | Descrição
--------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
git restore                       | Volta o arquivo para como ele foi salvo anteriormente (caso tenha sido deletado ou alterado erroneamente)
git commit --amend -m "texto"     | Altera a mensagem do último commit para "texto"
git commit --amend                | Abre o editor para editar a mensagem do último commit; para sair, pressione "ESC" e digite ":wq"
git log                           | Exibe o histórico de commits do Git
git reset                         | Desfaz alterações e volta para um commit anterior. Possui as opções: --soft (mantém as alterações no staged area), --mixed (mantém as alterações nos arquivos, mas não no staged area), --hard (descarta todas as alterações, tanto no staged quanto nos arquivos)
git reset --soft                  | Mantém as alterações no staged area, revertendo os arquivos modificados para staged. Se for feito um novo commit após isso, terá as mesmas mudanças do commit revertido.
git reset --mixed                 | Reverte os arquivos modificados para unstaged, permitindo que sejam adicionados novamente ao índice com o comando 'git add' antes de fazer um novo commit.
git reset --hard                  | Descarta todas as alterações, tanto no staged quanto nos arquivos, retornando ao estado do commit especificado. Cuidado ao usar este comando, pois todas as alterações serão perdidas permanentemente.
