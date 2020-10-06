# GDRIVE-SCRIPTS
Cliente de terminal Python para Google Drive para fácil upload, exclusão, listagem, compartilhamento de arquivos ou pastas. (Veja o uso no comentário)
Mantenha GDrive.py e client_secret.json no mesmo diretório.
Uso de execução:
python GDrive.py list (lista todos os arquivos com seus IDs)
python GDrive.py upload path (se o caminho for o arquivo, carregue-o. Se o caminho for dir, carregue o diretório vazio)
python GDrive.py upload path R (o caminho deve be dir. dir é carregado recursivamente. todos os arquivos e sub dirs são carregados)
python GDrive.py delete id (deletar arquivo ou dir com dado id)
python GDrive.py download id (download dir ou arquivo com determinado id para o diretório atual)
python GDrive.py download id caminho (download dir ou arquivo com determinado id para determinado caminho na máquina local)
python GDrive.py compartilhar e-mail de id (compartilhar arquivo ou dir com determinado id com e-mail)
