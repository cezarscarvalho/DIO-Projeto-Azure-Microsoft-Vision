# Reconhecimento Facial e Transformação de Imagens em Dados
## Descubra o passo a passo e Mergulhe fundo num Mundo de Oportunidades Infinitas com a Inteligência Artificial

Iniciaremos acessando o [portal do Azure](https://www.portal.azure.com).

Criaremos um Recurso (+Create a resource).

 Opção no Menu (Três traços Verticais) ao lado esquerdo que poderá não estar visível.

![Vision](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/b98f4bf9-cc26-4728-b679-424a127d71f3)

Clique para que ele expanda

![+Create a resource](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/c82615bb-682b-4819-b22a-6081298d31a3)


Ou ainda na parte inferior da página você encontrará um Menu com a opção "+ Create a resource"

![Serviços Azure - Create a resource](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/2e8a7742-573b-4543-b8d2-1025e3075176)

Busque em Categorias "AI + Aprendizado de Máquina (Machine Learning) ou procure pela lupa.

![Categorias IA + Machine Learning](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/991e0620-92a4-494f-a978-4ad594d1803d)

Clique para abrir as opções. Selecione "Criar" em Seriços de IA do Azure (Azure AI Service)

![Seriços Azure IA Criar](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/5e330188-5755-4289-b4fb-dd29f2fcaced)

Preencha os dados do seu Projeto

![Detalhes do Projeto](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/a14afd70-7ee2-428d-bc0d-be25504d18ff)

Preencha Nível de Preços : SO.

Marque a Caixa li e compreendi todos os termos abaixo.
Clique em "Revise + crie (Review +create)

![Detalhes do Projeto](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/a14afd70-7ee2-428d-bc0d-be25504d18ff)
![Detalhes do Projeto 2](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/5a449fd6-6953-41f6-96b6-06e6eb80a770)

Aguarde a finalização e clique em "Create (Criar)"

![Criar Serviço Azure](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/f7162ed4-508b-40fe-838b-40f3b7c977f5)

Serviço criado com sucesso
![Serviço criado com sucesso](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/36e80562-6181-40ce-9637-59f28b412247)


...

# Nosso próximo passo será conectar o Serviço que acabamos de criar ao Vision Studio

Acesse o [Vision Studio](https://portal.vision.cognitive.azure.com/?azure-portal=true) .

![Portal Azure Visão](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/aa4d1dbe-3744-4dbb-b5ec-5998a54e3582)

Clique em "Ver todos os recursos (View all resources)

![Ver todos os recursos](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/dcff46ef-45cd-49a1-9e15-f77114dc63e3)

Selecione o seu recurso criado e clique em "Selecione como recurso padrão (Select as default resource)"

![Selecione o seu Recurso criado](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/5107a693-1180-462b-bfcc-8e6f4b7d9cc9)

Clique no "x" no canto superior direito

![Clique no X](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/d7ad4975-d151-4dac-b2d5-a08107d15135)


## Agora iremos para melhor parte. A funcionalidade do Vision Studio

# Detectar Rostos no Vision Studio

- Clicar na aba face.
- Clicar em detectar rostos em uma imagem.




![Aba Face](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/0c2d8fc5-bcf3-413f-aa5c-56ed67189998)

![Detectar Rostos em uma imagem](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/fd264e70-4e6c-4395-a8ea-737462bbc12a)

- Marque a caixa "Experimente".
- Você pode Inserir uma foto, Tirar uma foto ou utilizar uma das fotos ao lado.

![Marque Experimente](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/11d7526e-0df3-47a0-ae7a-8d3a532fe026)

## Teste

Como teste utilizei uma foto de arquivo pessoal, em que estava utilizando óculos propositalmente para testar se o reconhecimento seria possível

![Teste Foto 01](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/3a964e17-bc62-4a77-91ec-c4351e9f47bf)



# Resultado

Como observado, a informação de detecção de apenas um rosto foi efetuada.

## Reconhecimento Óptico de Caracteres

Um serviço em que consiste extrair textos nos mais diversos contextos como em fotos, documentos, notas fiscais. Sendo um serviço interessante para utilização em projetos para scanear documentos no geral, otimizando espaço físico e gerando maior agilidade na localização destes arquivos.

![Aba Reconhecimento Óptico de Caracteres](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/004bf12d-8ec1-4db3-a920-ed06bf75c694)

- Clicar na aba Reconhecimento Óptico de Caracteres.
- Clicar em Extraia texto de imagens.
- Marque a caixa "Experimente".
- Você pode Inserir uma foto, Tirar uma foto ou utilizar uma das fotos ao lado.

![Experimente Extração de Textos](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/5b72e4df-1055-4c60-af4d-c55e599f3468)

## Teste


O Serviço extrai muito bem o texto de livros como no Livro de Júlio Verne, neste teste.


![Teste Foto 04](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/e50a4f56-0074-4d7c-87a2-d41aa649d34a)

Neste último teste, O texto foi extraido do livro de Júlio Verne.

![Terste Imagem 05](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/2e025579-a224-455b-b97a-0d91786b5de7)

Serviço facilitador para armazenamento de dados em grande escala, otimizando espaço de armazenamento físico.

## Adicione Legendas às imagens

- Clicar na análise de imagem.
- Clicar em adicione legendas às imagens.

![Aba Análise de Imagem](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/becc30ef-7509-4653-ac9d-5e3893cc2e08)

![Adicione Legenda as imagens](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/15e46979-7bdc-4abc-9431-691caa7c02f4)

# Teste

Nesta foto, o serviço detecta um cachorro sentado em uma cadeira como observado abaixo.

![Teste Foto 06](https://github.com/cezarscarvalho/DIO-Projeto-Azure-Microsoft-Machine-Learning/assets/158849910/9cd59a5e-ec8d-4f97-b909-46733fbb7c42)

# Considerações Finais

Os serviços nos mostram várias formas inclusivas nas quais poderemos inserir em projetos que facilitem a vida de todos. Lembrando sempre da correta utilização dos dados de acordo com normas éticas da utilização da IA.










