# open-day

O projeto open-day é um script em Batch e PowerShell que permite abrir automaticamente os programas e sites que você acessa diariamente com apenas um comando.

## Pré-requisitos

Antes de executar o script, verifique se o seu sistema atende aos seguintes requisitos:

+ Windows (o script foi desenvolvido para ser executado no ambiente Windows)
+ Os caminhos dos programas no arquivo open-day.ps1 devem estar corretos e apontar para as localizações dos programas em seu sistema.

## Como instalar

Siga as etapas abaixo para configurar e instalar o script:

1. Faça o download ou clone o repositório para o seu computador.

2. Abra as Variáveis de Ambiente do Windows:

+ Pressione as teclas ```Windows + X``` e selecione ```Sistema```.
+ Na janela de configurações do sistema, clique em ```Configurações avançadas do sistema```.
+ Na nova janela, clique no botão Variáveis de Ambiente.
3. Na seção ```Variáveis do sistema```, encontre a variável Path e clique em ```Editar```.
4.Na janela ```Editar variável de ambiente```, clique em ```Novo``` e adicione o caminho completo para a pasta onde você salvou os arquivos ```open-day.bat e open-day.ps1```. Por exemplo:

```script
C:\caminho\para\os\arquivos
```

5. Clique em OK em todas as janelas para salvar as alterações nas variáveis de ambiente.

6. Agora você pode executar o script a partir de qualquer local no prompt de comando.

## Como usar

1. Abra um terminal ou prompt de comando.

2. Execute o seguinte comando para iniciar o script:

```
open-day
```

3. O script abrirá automaticamente os programas e sites configurados.

## Configuração

Antes de executar o script, você pode configurar quais programas e sites deseja abrir. Siga as etapas abaixo para configurar o script:

1. Abra o arquivo ```open-day.ps1``` em um editor de texto.

2. Localize as linhas no arquivo onde os programas e sites estão definidos.

3. Modifique as linhas de acordo com os programas e sites que você deseja abrir. Certifique-se de fornecer os caminhos corretos para os programas e os URLs corretos para os sites.

4. Salve o arquivo após fazer as alterações.

5. Agora você pode executar o script novamente para abrir os programas e sites configurados.

## Licença

Este projeto está licenciado sob a licença MIT.
