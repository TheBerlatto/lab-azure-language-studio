# Análise de Sentimentos com Language Studio no Azure IA

Olá a todos! O objetivo desse repositório é descrever o passo a passo sobre o Language Studio, para entender se algumas avaliações são majoritariamente positivas ou negativas.

Isso faz parte do Desafio de Projeto do curso "Microsoft Azure AI Fundamentals" em parceria com a [DIO](https://dio.me)!

## 👣 Passo a Passo para criar um recurso de idioma
1. Em outra guia do navegador, abra o [Portal do Azure](https://portal.azure.com), entrando com a conta da Microsoft associada à sua assinatura do Azure.
2. Clique no botão **+Criar um recurso** e procure *Serviço de Idioma*. Selecione criar um plano de **serviço de idioma**. Você será direcionado para uma página para **Selecionar recursos adicionais.** Mantenha a seleção padrão e clique em **Continuar para criar seu recurso.** 
3. Na página **Criar Idioma**, configure-o com as seguintes configurações:
- Assinatura: sua assinatura do Azure.
- Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
- Região: Leste dos EUA.
- Nome: insira um nome exclusivo.
- Nível de preços: F0 ou S grátis se F0 gratuito não estiver disponível
- **Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo:** Selecionado.
4. Selecione Revisar + criar e, em seguida, Criar e aguarde a conclusão da implantação.

## 👣 Passo a Passo para configurar seu recurso no Estúdio de Idiomas de IA do Azure
1. Em outra guia do navegador, abra o [Language Studio](https://language.cognitive.azure.com).
2. Quando solicitado com **Selecionar um recurso do Azure**, faça as seguintes configurações:
- Diretório do Azure: Diretório padrão, o diretório que você está usando
- Assinatura do Azure: selecione a assinatura que você está usando
- Tipo de recurso: Idioma
- Nome do recurso: selecione o recurso Serviço de idioma que você acabou de criar

Em seguida, selecione **Concluído**.

## 👣 Passo a Passo para analisar avaliações no Language Studio
1. Em outra guia do navegador, abra o [Language Studio](https://language.cognitive.azure.com).
2. Na página inicial **Bem-vindo ao Language Studio**, selecione a guia **Classificar texto** e selecione o bloco **Analisar sentimento e minerar opiniões.**
3. Em *Selecionar idioma do texto*, selecione **Inglês**.
4. Em **Selecione seu recurso do Azure**, *selecione seu recurso*.
5. Em **Digite seu próprio texto**, carregue um arquivo.
6. Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá incorrer em custos e, em seguida, selecione **Executar**.
7. **Revise a saída**. Observe que o documento é analisado quanto ao sentimento, assim como cada frase. Selecione Frase 1 para mostrar a análise de sentimento dessa frase.