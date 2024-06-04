# Lista de comandos GitHub
## Configurando Git:
- **git config --global user.name "Nome"**
> Adiciona o nome informado (esse nome aparece nos commits)

- **git config --global user.email "email@dominio.com"**
> Adiciona o email informado (esse email aparece nos commits)

- **ssh-keygen -t rsa -C "email@dominio.com"**
> Gera uma chave SSH pública e uma privada a partir do seu email no diretório atual

- **ssh -T git@github.com**
> Após configurar no site, vincula a sua máquina a conta GitHub

## Configurando Repositório:
- **git init NomeDoRepositorio**
> Cria uma pasta com o nome indicado e abre um repositório nela, se não houver nome indicado considera o diretório atual o repositório

- **git remote add origin git@github.com:nome-do-usuario-no-github/nome-do-repositorio.git**
> Considera o HTML ou o SSH copiado do botão "code" (em verde no canto superior do repositório no site), como o diretório origem

## Mexendo no Repositório:
- **git status**
> Mostra o que foi alterado, e se precisa ser adicionado/commitado

- **git log**
> Mostra todas os commits realizados e as alterações feitas no repositório

- **git rm arquivo.extensao**
> Remove o arquivo nomeado

- **mate arquivo.extensao**
> Abre o arquivo indicado no editor configurado (Só funciona em Mec)

- **git add arquivo.extensao**
> Salva o arquivo indicado nos registros para o próximo commit

- **git add .**
> Salva todos os arquivos nos registros para o próximo commit

- **git commit -m "Commit text"**
> Commita o arquivo no registro de alteações do repositório (log)

- **git commit -am "Commit text"**
> NULL

- **mkdir NomeDaPasta**
> Cria uma pasta nova no diretório atual

- **git mv arquivo.extensao NomeDaPastaDestino**
> Move o arquivo indicado para a pasta indicada

## Repositório online:
- **git remote -v**
> Confere quais repositórios online estão sendo considerados como repositório de origem do repositório atual

- **git pull origin master**
> Se o diretório origem estiver configurado, copia os dados para o diretório atual

- **git push origin master**
> Se o diretório origem estiver configurado, copia os dados do diretório atual para o repositório origem

## Navegando no terminal:
- **pwd**
> Mostra o diretório atual

- **ls**
> Mostra os arquivos do diretório atual

- **ls -a**
> Mostra todos os arquivos do diretório atual (inclui ocultos)

- **clear**
> Limpa o terminal

- **cd NomeDaPasta**
> Abre a pasta nomeada como o diretério atual

- **cd ..**
> Fecha a pasta do diretório atual e volta uma pasta do PATH

## Recuperação de Versão:
- **git reset HEAD arquivo.extensao**
> Retorna o arquivo para a sua versão de 1 commit atrás

- **git checkout -- arquivo.extensao**
> Deleta o registro de commit da versão mais atual (previamente descartada)

## Comandos notáveis:
- **mate id_rsa.pub**
> Abre (se não existir cria) o arquivo de chave SSD (deve ser configurada no site do GitHub)

- **mate .gitignore**
> Abre (se não existir cria) o arquivo de lista de arquivos ignorados pela leitura do GitBash (As alterações desses arquivos não serão consideradas)

- **mkdir .ssh**
> Cria a pasta-padrão das chaves SSH pública/privada
