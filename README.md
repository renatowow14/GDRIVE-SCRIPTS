# GDRIVE-SCRIPTS
Cliente de terminal Python para Google Drive para fácil upload, exclusão, listagem, compartilhamento de arquivos ou pastas. (Veja o uso no comentário)

Conclua as etapas descritas no restante desta página para criar um aplicativo de linha de comando Python simples que faz solicitações à API Drive.

-> https://developers.google.com/drive/api/v3/quickstart/python

# Pré-requisitos
Para executar este início rápido, você precisará de:

Python 2.6 ou superior

A ferramenta de gerenciamento de pacotes pip e Uma conta do Google com o Google Drive ativado

# Etapa 1: ativar a API do Drive
Acesse : https://developers.google.com/drive/api/v3/quickstart/python

Criar um novo projeto do Cloud Platform e ativar automaticamente a API Drive:

Ative a API do Drive

Na caixa de diálogo resultante, clique em BAIXAR CONFIGURAÇÃO DO CLIENTE e salve o arquivo credentials.jsonem seu diretório de trabalho.

# Etapa 2: Instale a biblioteca cliente do Google
Execute o seguinte comando para instalar a biblioteca usando pip:

pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib

#QuickStart:https://developers.google.com/drive/api/v3/quickstart/python

#Step By Step:https://www.youtube.com/watch?v=LSP9PUx7n04
# Etapa 3: Guia de Execução:

# Uso de execução:
python GDrive.py list (lista todos os arquivos com seus IDs)

python GDrive.py upload path (se o caminho for o arquivo, carregue-o. Se o caminho for dir, carregue o diretório vazio)

python GDrive.py upload path R (o caminho deve be dir. dir é carregado recursivamente. todos os arquivos e sub dirs são carregados)

python GDrive.py delete id (deletar arquivo ou dir com dado id)

python GDrive.py download id (download dir ou arquivo com determinado id para o diretório atual)

python GDrive.py download id caminho (download dir ou arquivo com determinado id para determinado caminho na máquina local)

python GDrive.py compartilhar e-mail de id (compartilhar arquivo ou dir com determinado id com e-mail)
