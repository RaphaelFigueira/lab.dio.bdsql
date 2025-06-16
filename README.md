# lab.dio.bdsql
Laboratório de criação de BD SQL no Azure - DIO

Configuração de uma Instância Gerenciada de SQL no Azure

A Instância Gerenciada de SQL do Azure é uma opção PaaS (Plataforma como Serviço) que combina os recursos do SQL Server com a facilidade de gerenciamento da nuvem.
O processo de configuração envolve:

1. Acesso ao Portal do Azure
Acesse o portal.azure.com com sua conta.

2. Criar uma Instância Gerenciada
Vá em "Criar um recurso" > "Bancos de Dados" > "Instância Gerenciada de SQL".

Clique em "Criar".

3. Configurações Básicas
Assinatura e Grupo de Recursos.

Nome da instância (único na região).

Região e Zona de disponibilidade (opcional).

Camada de preço: General Purpose ou Business Critical.

4. Configurações de Rede
A Instância Gerenciada exige uma rede virtual (VNet) com sub-rede dedicada.

Crie ou selecione uma VNet conforme os requisitos do Azure.

Configure regras de segurança e acesso de IP se necessário.

5. Autenticação e Segurança
Defina as opções de autenticação: SQL Server Authentication ou Azure AD.

Crie um login de administrador.

6. Backup e Manutenção
O Azure realiza backups automáticos, mas você pode configurar a retenção (7 a 35 dias).

Atualizações automáticas são gerenciadas pela plataforma.

7. Revisar e Criar
Revise todas as configurações.

Clique em "Criar" para iniciar o provisionamento (pode levar até 30 minutos).

8. Conectar-se à Instância
Use ferramentas como SSMS ou Azure Data Studio.

Configure permissões na rede, regras de firewall e endpoints privados, se necessário.
