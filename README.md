# Ec2-project-Proz

Este projeto configura uma instância EC2 na AWS com um volume EBS adicional. Aqui estão as etapas para configurar o ambiente:

## Configuração da Instância EC2

1. Acesse o Console da AWS e navegue até o serviço EC2.
2. Crie uma nova instância EC2 usando a imagem Amazon Linux 2.
3. Escolha o tipo de instância com base em suas necessidades de recursos.

## Conexão via SSH

1. Após a instância ser criada, use a chave privada para conectar via SSH.
2. Execute os comandos necessários para acessar o terminal da instância.

## Gerenciando o Armazenamento

1. Explore as opções de armazenamento oferecidas pelo Amazon EC2.
2. Crie um novo volume Elastic Block Store (EBS) com um tamanho de sua escolha.
3. Anexe o volume à sua instância EC2.

## Formatando e Montando o Volume

1. Formate o volume recém-criado usando um sistema de arquivos de sua escolha.
2. Monte o volume em um diretório específico em sua instância.

## Criação de Arquivos

1. Crie um arquivo de texto simples usando o editor de sua preferência.
2. Salve esse arquivo no volume montado.

## Explorando Recursos

1. Use comandos como ls, df -h, mount e cat para verificar o status do volume montado, o espaço em disco disponível e o conteúdo do arquivo criado.

## Encerramento

1. Interrompa ou encerre a instância criada para não gerar custos adicionais.
