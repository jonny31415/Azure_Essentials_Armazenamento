# Dominando o Armazenamento na Azure
Primeiramente, é necessário criar uma *storage account*. O nome deve ser único dentre todas as contas de armazenamento existentes no Azure e pode conter apenas números e letras minúsculas, com tamanho entre 3 e 24 caracteres. Na criação de conta é escolhido o modelo de redundância, que pode ser LRS, ZRS, GRS e GZRS.

## Opções de armazenamento
Pode-se criar blobs, compartilhamentos de arquivos SMB, filas e tabelas. É possível escolher a frequência com que os arquivos serão acessados e também o tempo de armazenamento, de modo a escolher as opções de maior custo-benefício, como quente ou frio.

## Azure Migrate
Com o Azure Migrate é possível migrar de servidores físicos para a nuvem. É possível realizar a transferência de bancos de dados e backups, por exemplo. Para grandes volumes de dados, é possível utilizar o Azure Data Box, que suporta até 80 TB de dados.

## Azcopy
Com o Azcopy é possível fazer upload de arquivos locais para a nuvem. O sincronismo se dá em uma via unidirecional.

## Gerenciador de armazenamento do Azure
Com o gerenciador de armazenamento do Azure, é possível ter uma comparação dos arquivos locais e na nuvem, fazendo um sincronismo bidirecional.
