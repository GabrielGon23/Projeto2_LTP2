Aluno: Gabriel Gonçalves Sá
Matrícula: 22352853

Descrição:
Este programa é um sistema básico de estoque feito em Python usando a interface gráfica Tkinter e banco de dados SQLite. 
Ele permite cadastrar categorias e produtos, editar, excluir e listar todos os dados. 
O usuário pode associar produtos a categorias para organizar melhor o estoque.

Requisitos:
- Python 3 instalado no computador
- Biblioteca Tkinter 
- Biblioteca sqlite3 

Como rodar:
1. Salve o arquivo do programa (por exemplo, estoque.py) em uma pasta qualquer do seu computador.
2. Abra o terminal ou prompt de comando.
3. Navegue até a pasta onde salvou o arquivo, usando o comando cd.
   Exemplo: cd C:\Users\SeuUsuario\Documentos\ProjetoEstoque
4. Execute o programa com o comando:
   python estoque.py
5. A janela do sistema de estoque vai abrir.

Como usar/testar:
- Na aba "Categorias", você pode adicionar novas categorias, editar ou excluir as já existentes.
- Na aba "Produtos", você pode cadastrar produtos, definir a quantidade, preço e escolher a categoria a qual pertencem.
- Para editar um produto, selecione ele na lista e clique em "Editar Produto".
- Para excluir, selecione o produto ou categoria e clique em "Excluir".
- Também pode listar todos os produtos que pertencem a uma categoria clicando no botão "Listar Produtos da Categoria Selecionada".

Observações:
- O sistema não aceita valores negativos ou zero para quantidade e preço.
- A quantidade deve ser número inteiro.
- O preço aceita números com vírgula ou ponto decimal.
- Se algum dado estiver errado ou faltar, o sistema vai mostrar uma mensagem de erro.
- O banco de dados (arquivo estoque.db) é criado automaticamente na mesma pasta do programa, na primeira vez que rodar.


---
