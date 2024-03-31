# [Conhecendo o Estudio de fala ](https://speech.microsoft.com/portal) :books: :pencil2::paperclip:

## O que é: :book: :eyes:

Um "Estúdio de Fala Azure" provavelmente se refere a uma solução ou serviço oferecido pela Microsoft Azure relacionado ao processamento de fala ou reconhecimento de voz. A Microsoft Azure é uma plataforma de computação em nuvem oferecida pela Microsoft, que fornece uma ampla gama de serviços para desenvolvedores e empresas.
 
No contexto de um "Estúdio de Fala Azure", é provável que seja uma plataforma ou conjunto de ferramentas para desenvolvimento de aplicativos que envolvam a entrada e processamento de fala. Isso pode incluir reconhecimento de fala em tempo real, conversão de fala em texto, análise de sentimento em áudio, entre outras funcionalidades relacionadas.

## Passo a passo 👨🏽‍🏫👨🏽‍💻
📕 Passo 1:

1.  abra [o Azure AI Speech Studio](https://speech.microsoft.com/) , entrando com sua conta da Microsoft.
    
2.  Selecione *Configurações* e depois *Crie um recurso.* Configure-o com as seguintes configurações:
    -   *Nome do novo recurso* : Insira um nome exclusivo .
    -   *Assinatura* : sua assinatura do Azure .
    -   *Região* : Selecione uma [região suportada](https://learn.microsoft.com/azure/ai-services/speech-service/regions) .
    -   *Nível de preços* : FO gratuito (se disponível, caso contrário, selecione Standard S0).
    -   *Grupo de recursos* : selecione ou crie um grupo de recursos com um nome exclusivo .

IMAGEM PASSO 1

3.  Selecione *Criar recurso.* Aguarde até que o recurso seja criado e selecione *Usar recurso* . A página Introdução à Fala é exibida.

IMAGEM PASSO 2

4. Preencha com o dados, na imagem a seguir segue sugestões. 

IMAGEM PASSO 3

5.  Selecione  *Criar um recurso*
6. Após, selecione o recurso criado 
7. Selecione *Usar o recurso*

IMAGEM PASSO 4

8. Selecione a opção *Conversão de fala em texto em tempo real*

IMAGEM PASSO 5

Essa funcionalidade será responsável por Trasncrever ao vivo, a partir de um áudio, sem escrever nenhum código.

9. Marque a opção *Reconheço que este usa o recurso do Laboratório3 e incorrerá em uso para minha conta*
10. Na opção *Escolher um idioma*. onde seleciona qual dos idiomas ossui no seu arguivo
11. Após, Em Escolher arquivos de áudio , selecione *Procurar arquivos* e navegue até a pasta onde você salvou o arquivo. Selecione e depois *Abrir*.

IMAGEM PASSO 6

Após realizado todos esses passos, a IA irá transcrever o audio enviado por você. No meu caso, foi uma música *"Unstoppable - Sia"*

IMAGEM PASSO 7

12.  O serviço Speech transcreve e exibe o texto em tempo real. Se você tiver áudio em seu computador, poderá ouvir a gravação enquanto o texto é transcrito.
13.  Revise a saída, que deve ter reconhecido e transcrito com êxito o áudio em texto.

⚠*Observação* Se você receber uma mensagem de erro, aguarde alguns minutos antes de tentar novamente. Demora um pouco para que o recurso Fala fique disponível para o primeiro uso. ⚠

## Limpar :paperclip::scissors:🚨

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

1.  Abra o [portal do Azure](https://portal.azure.com/) e selecione o grupo de recursos que contém o recurso que você criou.
2.  Selecione o recurso e selecione *Excluir* e depois *Sim* para confirmar. O recurso é então excluído.

# [Conhecendo o Language Studio](https://language.cognitive.azure.com/home) :books: :pencil2::paperclip:

Esta plataforma oferece uma série de ferramentas e recursos para ajudar os desenvolvedores a construir e implementar modelos de processamento de linguagem natural (NLP) de ponta. O Language Studio inclui modelos pré-treinados, APIs poderosas e uma série de funcionalidades para facilitar tarefas como análise de sentimentos, geração de texto, tradução automática, e muito mais. Essa plataforma é utilizada por empresas e pesquisadores para uma variedade de aplicações, desde chatbots até sistemas de análise de texto avançados.  

Language Studio é uma ferramenta poderosa para explorar e criar soluções de processamento de linguagem natural, tornando mais fácil integrar recursos de linguagem em seus aplicativos!

## Passo a passo 👨🏽‍🏫👨🏽‍💻

📕 Passo 1:
1.  Em outra guia do navegador, abra o portal do Azure em [https://portal.azure.com](https://portal.azure.com/?azure-portal=true) , entrando com a conta da Microsoft associada à sua assinatura do Azure.
2. Clique no botão *＋Criar um recurso* e pesquise Serviço de idioma . Selecione *criar* um plano *de serviço de idiomas* . Você será levado a uma página para *selecionar recursos adicionais* . Mantenha a seleção padrão e clique em *Continuar para criar seu recurso* .

IMAGEM PASSO2-1

IMAGEM PASSO2-2

3. Na página *Criar Idioma* , configure-o com as seguintes configurações:
    -   *Assinatura* : sua assinatura do Azure .
    -   *Grupo de recursos* : Selecione ou crie um grupo de recursos com um nome exclusivo .
    -   *Região* : Leste dos EUA.
    -   *Nome* : Insira um nome exclusivo .
    -   *Nível de preços* : F0 grátis ou S se F0 grátis não estiver disponível
    -   *Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo* : Selecionado .
4.  Selecione *Revisar + criar e* depois *Create* e aguarde a conclusão da implantação.

IMAGEM PASSO2-3

5. Após criado o recurso. Verificamos na seguinte opção se ele está ativo

IMAGEM PASSO2-4

6. Em outra guia do navegador, abra *o Language Studio* em [https://language.cognitive.azure.com](https://language.cognitive.azure.com/?azure-portal=true) e entre.

IMAGEM PASSO2-5

7. Na página inicial *Bem-vindo ao Language Studio , selecione a guia* *Classificar texto* e, em seguida, selecione o bloco *Analisar sentimento e extrair opiniões* .
    
 IMAGEM PASSO2-6
 
8.  Em Selecionar idioma do texto , selecione *Inglês* .
    
9.  Em Selecione seu recurso do Azure , selecione seu recurso.
    
10.  Em Digite seu próprio texto, carregue um arquivo ou use um de nossos textos de exemplo , copie e cole a seguinte revisão:

IMAGEM PASSO2-7

11.  Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá gerar custos e selecione *Executar* .

IMAGEM PASSO 2-8    
    
12.  Revise a saída. Observe que o documento é analisado quanto ao sentimento, assim como cada frase . Selecione *Frase 1* para mostrar a análise de sentimento dessa frase.,

⚠ Observe que há um sentimento geral seguido por pontuações próximas a três categorias: pontuação positiva , pontuação neutra e pontuação negativa . Em cada uma das categorias é atribuída uma pontuação entre 0 e 1. Essas pontuações de confiança indicam a probabilidade do texto fornecido ser um sentimento específico.⚠

Neste exercício você usou o Language Studio para criar um novo recurso de idioma ou usar um recurso de idioma existente. Você habilitou o recurso em Configurações antes de experimentar o serviço de mineração de sentimento e opinião. Em seguida, você testou o serviço com três trechos de texto.

## Limpar :paperclip::scissors:🚨

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

1.  Abra o *portal do Azure* em [https://portal.azure.com](https://portal.azure.com/) e selecione o grupo de recursos que contém o recurso que você criou.
2.  Selecione o recurso e selecione *Excluir* e depois *Sim* para confirmar. O recurso é então excluído.

## Comentário sobre a aplicação que foi utilizada:🌐📃✏

TEXTO AQUI

## 😄😁😆👾👻
Estruturado e organizado por Gustavo Henrique.