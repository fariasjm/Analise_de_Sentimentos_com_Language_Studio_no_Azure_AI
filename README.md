# Desafio: Análise de Sentimentos com Language Studio no Azure AI
 
## Analisar texto com o Estúdio de Idiomas
O Serviço de Linguagem de IA do Azure inclui funcionalidades de análise de texto e PNL. Isso inclui a identificação de frases-chave no texto e a classificação do texto com base no sentimento.

### Criar um recurso de Linguagem
1. Abra o portal do Azure em https://portal.azure.com, entrando com a conta Microsoft associada à sua assinatura do Azure
2. Clique no botão ＋Criar um recurso e pesquise Serviço de linguagem. Selecione criar um plano Serviço de linguagem. Você será levado a uma página para Selecionar recursos adicionais. Mantenha a seleção padrão e clique em Continuar para criar seu recurso
3. Na página Criar idioma, configure-o com as seguintes definições:
- Assinatura: sua assinatura do Azure
- Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo
- Região: Selecione a região geográfica mais próxima. Se estiver no leste dos EUA, use “Leste dos EUA 2”
- Nome: insira um nome exclusivo
- Tipo de preço: F0 Gratuito ou S se o F0 Gratuito não estiver disponível
- Marcar a caixa reconheço que li e compreendi todos os termos abaixo
- Selecione Revisar + criar e
- Criar e aguarde a conclusão da implantação.

### Configure seu recurso no Estúdio de Linguagem de IA do Azure
1. Em outra guia do navegador, abra o Estúdio de Idiomas em https://language.cognitive.azure.com
2. Selecionar o recurso de Linguagem do Azure criado
3. Faça as seguintes configurações:
   - Diretório do Azure: diretório que você está usando
   - Assinatura do Azure: Selecione a assinatura que está usando
   - Tipo de recurso: linguagem
   - Nome do recurso: selecione o recurso de Serviço de Linguagem que você acabou de criar
4. Selecione Concluído.

### Analisar as avaliações no Estúdio de Idiomas
1. Em um navegador da Web, navegue até Estúdio de Idiomas em https://language.cognitive.azure.com
2. Na página Bem-vindo(a) ao Estúdio de Idiomas, selecione a guia Classificar texto e, em seguida, selecione o bloco Analisar sentimentos e extrair opiniões
3. Em Selecionar o idioma do texto, selecione Inglês
4. Em Selecione seu recurso do Azure, selecione seu recurso
5. Em Insira seu próprio texto, carregue um arquivo ou use um de nossos exemplos de texto, copie e cole a seguinte avaliação:
   ![image](https://github.com/user-attachments/assets/fa0a5473-1e75-4c87-83c3-82d1f65d1a73)

     




