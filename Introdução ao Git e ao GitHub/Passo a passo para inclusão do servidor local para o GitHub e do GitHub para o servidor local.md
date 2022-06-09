# Passo a passo para inclusão do servidor local para o GitHub

Para incluir arquivos/pastas do servidor local para o remoto do GitHub.

- Utilizar o comando **git status** para confirmar que foram feitas modificações locais
- Para incluir usar **git add .** ou **git add -a**
- Usar **git commit -m "comentário sobre o envio feito"**
- Enviar para o GitHub através do **git push origin main**
- Atualizar o GitHub e confirmar que as inclusões foram feitas.



# Passo a passo para inclusão do GitHub para o servidor local

Para incluir arquivos/pastas criados diretamente no GitHub para o servidor local.

- Após criar/incluir arquivos e/ou pastas no GitHub ir na página do repositório na opção **Code**, sinalizado em verde, e copiar o link HTTPS ou SSH (se tiver chave SSH ativada para não ficar colocando as credenciais sempre).
- Com o **Git Bash** aberto na pasta onde se deseja clonar do GitHub, utilizar o seguinte comando **git clone *<u>colar link copiado</u>***