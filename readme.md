# [Conhecendo o Estudio de fala ](https://speech.microsoft.com/portal) :books::pencil2::paperclip:

## O que é: :book: :eyes:

Um "Estúdio de Fala Azure" provavelmente se refere a uma solução ou serviço oferecido pela Microsoft Azure relacionado ao processamento de fala ou reconhecimento de voz. A Microsoft Azure é uma plataforma de computação em nuvem oferecida pela Microsoft, que fornece uma ampla gama de serviços para desenvolvedores e empresas.
 
No contexto de um "Estúdio de Fala Azure", é provável que seja uma plataforma ou conjunto de ferramentas para desenvolvimento de aplicativos que envolvam a entrada e processamento de fala. Isso pode incluir reconhecimento de fala em tempo real, conversão de fala em texto, análise de sentimento em áudio, entre outras funcionalidades relacionadas.

## Passo a passo 👨🏽‍🏫👨🏽‍💻
📕 Passo 1:

1.  abra [o Azure AI Speech Studio](https://speech.microsoft.com/) , entrando com sua conta da Microsoft.
    
2.  Selecione *Configurações* e depois *Crie um recurso.*
    

![Passo1](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/9e087c5a-0b80-4612-bf19-beb319ae2ce6)

3.  Selecione *Criar recurso.* Aguarde até que o recurso seja criado e selecione *Usar recurso* . A página Introdução à Fala é exibida.

![Passo2](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/27994832-7ffb-4fd4-be33-49dc6d743a59)
4. Preencha com o dados, na imagem a seguir segue sugestões. 

![Passo3](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/762bc822-103d-420a-a27b-81037a794d22)

5.  Selecione  *Criar um recurso*
6. Após, selecione o recurso criado 
7. Selecione *Usar o recurso*

![Passo4](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/1ca56f31-1ebd-4dd4-9e10-28567f757a3b)


8. Selecione a opção *Conversão de fala em texto em tempo real*

![Passo5](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/d43d7a73-e0b4-4765-8681-18a4610a3a66)

Essa funcionalidade será responsável por Trasncrever ao vivo, a partir de um áudio, sem escrever nenhum código.

9. Marque a opção *Reconheço que este usa o recurso do Laboratório3 e incorrerá em uso para minha conta*
10. Na opção *Escolher um idioma*. onde seleciona qual dos idiomas ossui no seu arguivo
11. Após, Em Escolher arquivos de áudio , selecione *Procurar arquivos* e navegue até a pasta onde você salvou o arquivo. Selecione e depois *Abrir*.

![Passo6](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/1efb24f7-8976-441e-bc1a-b35d78b1876c)

Após realizado todos esses passos, a IA irá transcrever o audio enviado por você. No meu caso, foi uma música *"Unstoppable - Sia"*

![ResultadodoEstudioDeFala](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/4fddef26-51e5-46c2-8dd2-ad8599ab782a)

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

![Passo2-1](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/4120dbba-3888-4b2b-b46c-f43c12c95e32)


![Passo2-2](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/08b5b74b-7b0e-4ed0-9557-5bb39fd13c8a)

3. Na página *Criar Idioma* , configure-o com as seguintes configurações:
    -   *Assinatura* : sua assinatura do Azure .
    -   *Grupo de recursos* : Selecione ou crie um grupo de recursos com um nome exclusivo .
    -   *Região* : Leste dos EUA.
    -   *Nome* : Insira um nome exclusivo .
    -   *Nível de preços* : F0 grátis ou S se F0 grátis não estiver disponível
    -   *Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo* : Selecionado .
4.  Selecione *Revisar + criar e* depois *Create* e aguarde a conclusão da implantação.

![Passo2-3](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/3e196ef7-fadd-4b51-95d9-5ce41e9a1236)

5. Após criado o recurso. Verificamos na seguinte opção se ele está ativo

![Passo2-4](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/0ef656c1-1872-4051-b61f-91cb085443d9)


6. Em outra guia do navegador, abra *o Language Studio* em [https://language.cognitive.azure.com](https://language.cognitive.azure.com/?azure-portal=true) e entre.

![Passo2-5](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/42bc4117-3e6f-48a6-a38a-6f7ebd782cc6)


7. Na página inicial *Bem-vindo ao Language Studio , selecione a guia* *Classificar texto* e, em seguida, selecione o bloco *Analisar sentimento e extrair opiniões* .
    
![Passo2-6](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/feff157f-c9a4-46d5-8b57-28895141374c)
 
8.  Em Selecionar idioma do texto , selecione *Inglês* .
    
9.  Em Selecione seu recurso do Azure , selecione seu recurso.
    
10.  Em Digite seu próprio texto, carregue um arquivo ou use um de nossos textos de exemplo , copie e cole a seguinte revisão:

![Passo2-7](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/06434d2e-a171-44c0-9537-db3529530c16)

11.  Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá gerar custos e selecione *Executar* .

![Passo2-8](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals3/assets/96626042/fdea0dd2-b3ff-4557-85aa-564a50f51926)
    
12.  Revise a saída. Observe que o documento é analisado quanto ao sentimento, assim como cada frase . Selecione *Frase 1* para mostrar a análise de sentimento dessa frase.,

⚠ Observe que há um sentimento geral seguido por pontuações próximas a três categorias: pontuação positiva , pontuação neutra e pontuação negativa . Em cada uma das categorias é atribuída uma pontuação entre 0 e 1. Essas pontuações de confiança indicam a probabilidade do texto fornecido ser um sentimento específico.⚠

Neste exercício você usou o Language Studio para criar um novo recurso de idioma ou usar um recurso de idioma existente. Você habilitou o recurso em Configurações antes de experimentar o serviço de mineração de sentimento e opinião. Em seguida, você testou o serviço com três trechos de texto.

## Limpar :paperclip::scissors:🚨

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

1.  Abra o *portal do Azure* em [https://portal.azure.com](https://portal.azure.com/) e selecione o grupo de recursos que contém o recurso que você criou.
2.  Selecione o recurso e selecione *Excluir* e depois *Sim* para confirmar. O recurso é então excluído.

## Comentário sobre a aplicação que foi utilizada:🌐📃✏

O Estúdio de Fala Azure e o Language Studio são ferramentas poderosas para processamento de linguagem natural e reconhecimento de fala. 

O Estúdio de Fala Azure oferece recursos avançados de transcrição de áudio em texto, reconhecimento de voz e tradução de fala em tempo real. Sua precisão e capacidade de lidar com diferentes idiomas tornam-no uma escolha popular para empresas que buscam integrar tecnologias de voz em seus produtos e serviços.

Por outro lado, o Language Studio fornece uma gama de funcionalidades de NLP, incluindo análise de sentimentos, extração de entidades e tradução de texto. Sua flexibilidade e facilidade de uso permitem que os desenvolvedores criem aplicativos sofisticados que entendam e respondam à linguagem humana de forma mais natural.

Em conjunto, essas ferramentas oferecem uma experiência abrangente para desenvolvedores e empresas que desejam criar aplicativos com recursos avançados de processamento de linguagem natural e voz. A integração dessas tecnologias pode melhorar significativamente a interação entre humanos e máquinas, abrindo novas possibilidades para automação e personalização de serviços.

Achei muito fácil utilizar essas plataformas e de muita utilidade. eles formam uma dupla imbatível para desenvolvedores e empresas que querem levar suas aplicações para o próximo nível. Com essas ferramentas, é como se desbloqueássemos uma nova dimensão de interação humano-máquina, tornando nossas experiências digitais mais inteligentes e naturais. É tipo ter o futuro nas pontas dos dedos - e é emocionante ver para onde isso pode nos levar! :paperclip:
## 😄😁😆👾👻
Estruturado e organizado por Gustavo Henrique.
