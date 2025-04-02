# Projeto-Cloud

1. Configuração do Ambiente de Desenvolvimento
Azure:

Criar uma conta no Azure e configurar o Azure App Service para hospedar o bot.

Criar um banco de dados SQL no Azure SQL Database para armazenar as transações e relatórios.

API da Binance:

Configurar a conexão com a API da Binance para consultar preços e executar ordens de compra e venda.

2. Desenvolvimento do Bot
Sinais de Trading:

Implementar a lógica para identificar os sinais de trading: Engolfo (padrão de vela que indica reversão) e Inside Bar (padrão de vela que sugere continuação ou indecisão do mercado).

Execução de Ordens:

Implementar a lógica para compra e venda de criptomoedas com ordens de mercado ou limitadas, incluindo configurações de Stop Loss (para limitar perdas) e Take Profit (para garantir lucro).

Armazenamento de Dados:

Implementar a gravação das transações e relatórios de ganhos e perdas no Azure SQL Database.

3. Teste e Validação
Teste Local:

Realizar testes locais para validar a execução das operações, incluindo a verificação da lógica de sinais de trading, execução de ordens, e cálculos de ganhos e perdas.

Teste na Nuvem:

Realizar testes no ambiente da Azure para garantir que o bot esteja funcionando corretamente, validando a execução das ordens e o armazenamento dos dados.

4. Deploy para o Azure
Deploy no Azure App Service:

Fazer o deploy do código do bot no Azure App Service.

Configurar Azure Monitor para rastrear erros e métricas de desempenho, garantindo a operação eficiente e sem falhas.

5. Documentação e Apresentação
Documentação:

Documentar as funcionalidades do bot, como configurar o bot, realizar ordens de compra e venda, e analisar os relatórios de desempenho.

Explicar como configurar o monitoramento no Azure e como interpretar os alertas do Azure Monitor.

Apresentação:

Preparar uma apresentação para demonstrar o funcionamento do bot, os relatórios de desempenho gerados e a operação na nuvem.

Critérios de Avaliação
Funcionalidade: O bot deve realizar operações corretamente com base nos sinais de trading e ordens configuradas.

Usabilidade: O sistema deve ser fácil de configurar e usar.

Desempenho: O bot deve ser eficiente e não apresentar falhas frequentes ou perda de dados.

Escalabilidade: O sistema deve ser capaz de operar de maneira escalável na nuvem.

Documentação: A documentação deve ser clara e explicar todas as funcionalidades e processos de configuração.
