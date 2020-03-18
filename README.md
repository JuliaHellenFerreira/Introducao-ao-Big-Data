# Introducao ao Big Data

Anotações do curso de Introdução ao Big Data ( Coursera )

## Aula 01 - Contextualização do Big Data

Podemos definir como: "Um conjunto de metodologias utilizadas para capturar, armazenar e processar um volume imenso de informações de várias fontes ( dados estruturados e não estruturados ) com o objetivo de acelerar a tomada de decisão e trazer vantagem competitiva.

- Tipos de dados:

Dado estruturado: Em tabelas, por exemplo.
Dado Semiestruturado: XML ( dados irregulares, facilidade de compartilhamento de informações pela internet), Json ( formato leve, útil para traficar milhares de informações)
Dado não estruturado: Sem estrutura pré definida - Textos, por exemplo (livros, emials, twitter, imagens, vídeos, voz)

- Necessidade de trabalhar com o Big Data:

Atualmente tudo vivemos no mundo das informações. Tudo gera dados e em grande números. Com isso, temos vários caminhos para tomada de decisão. E saber Big Data é fundamental para realizar análise de dados. É importante saber que a maioria dos dados são não estruturados. As informações geradas em redes sociais ajuda a aprimorar modelos, traçar perfis, criação de novos aplicativos e muito mais.

- 7 V's do Big Data

Volume: número dados gerados ( Bits, Byte, Kilobyte, Megabyte, Gigabyte, TeraByte, PetaByte, Exabyte, Zettabyte, Yottabyte ).

Velocidade: Velocidade na tomada de decisão ( Venda de produtos online, check up de doenças, fraudes, detectar criminosos, transito ).

Variedade: Hoje 70% dos dados não são estruturados.

Veracidade: Ter certeza que os dados são confiavéis e a fonte segura.

Visualização: fazer uma análise gráfica ( Power BI ).

Vunerabilidade: Investir em segurança para não roubarem dados.

Valor: Os projetos de Big Data devem gerar valor para as organizações.

- Cientista de Dados

O profissional cientista de dados toma decisões com base em todas as informações que ele tem em mão. Pode ser em mensagens, rede sociais, vídeos e outros. Ele precisa ter conheciemnto nas seguintes áreas programação, banco de dados, segunraça de informação, tecnologias de big data e modelagem. Em trabalhos em equipe os profissionais que trabalham com ele são especalista em tecnologia, especialista em modelagem e especialista em negócios. 

- Definir, preparar e armazenar 

Podemos dizer que as etapas de um projeto de Big Data são:

Definição do Objetivo: Boa pergunta, propósito, objetivo viável, perguntas frequentes para a equipe de Big Data, valor agregado ao negócio, custo de implatanção do projeto, retorno financeiro e qual o aumento esperado de mercado.

Preparar o Ambiente e Armazenar: Relação a escalabilidade (a quantiade de usuários que acessam o banco de dados) , alta disponibilidade ( acesso a informaççao deve estar sempre disponível e flexibilidade (a forma de armazenamento da informação deve ser flexível para que se possa armazenar dados estruturados e não estruturados que serão processados com a utilização de diversas tecnologias). Além disso, devemos levar em conta: A estrutura de Banco de dados, custo dos equipamentos, custo da equipe de big data, aspectos de segurança da informação, como as informações serão processadas, quais software e aplicativos envolvidos, como os dados serão gerenciados. O ideal é que todas as informações estejam em um único lugar, chamamos de Data Lake. Lá são amezenadas dados brutos. Para criação deste banco de dados devemos ter a equipe de TI, área de modelagem, área de negócios e diretores envolvidos. As formas que os dados podem ser armazenados são: orientada a chave-valor, orientado a colunas, orientado a documentos, orientado a grafos.

Cloud Computing:é modelo que permite acesso sob demanda, via redes de computadores a conjunto compartilhado de recursos computacionais que podem ser rapidamente provisionado e liberado, com o mínimo de esforço administrativo ou interação com o provedor dos serviços. Pública, privada e híbrida 

- Capturar, Processar, Modelar e Visualizar

Capturar a Informação: Precisamos ddefinir o objetivo de estudo e os dados que precisam ser amazenados. Tais informações podem seer extraídas da internet, das redes sociais e de sensores. Tudo irá para o Data Lake. A melhor forma de capturar os dados é através de API e algumas empresas de midias sociais disponibilização APIs.

Processar, Modelar e Visualizar: Podemos dividir em três pilares, tecnologia de big data, ferramentas de analytics e ferramentas de BI.

Capturar a Informação: Tecnologias > Algumas tecnologias como disco, memória e velocidade tem as seguintes desvangatens como custo de atualização dos equipamentos, escalabilidade limitada. O Hadoop trouxe inovação ao processamento de dados. Ele é um projeto open source da Apache Software Foudation. Ele permite processamento de dados em várias unidades de fisco de forma distribuída, com toleraância a falhas. 

Processar, Modelar e Visualizar: Ferramentas de Analytics e de BI > Sas, R, IBM, Python. Podemos usar Power BI.

Tomar a decisão.

## Aula 2: Aplicações

- Técnicas de Previções

Os modelos de previsão de vendas podem ser feitas utilizadas com ferrementas Business Intelligence ( BI ). Assim conseguimos, ter uma noção por região, ano e produto. Através do BI, podemos detectar sazonalidades, tendências, e comportamento do padrão do consumidor. Podemos gerar gráficos, dashbords e relátorios. Com essas ferramentas teremos uma ideia do passado e do futuro de uma empresa, por exemplo. O objetivo de técncas de projeção é projetar uma váriavel de interesse em funçaõ de várias variavéis auxiliares. Os dados utilizados podem ser estruturados ou não esruturados. Dados fora do padrão recebem o nome de outlier.

- Fidelização de Cliente

A segmentação de cliente é quando cada grupo dentro dde uma empresa é responsável por realizar uma ação. Podemos fazer por meio do comportamento de compras ou da utilização de produtos e serviços. As informações podem ser obtidas através das redes sociais, fotos do facebook e etc. Com base nisso saberemos o perfil do cliente ( classe social, gostos e hábitos de consumo ). Com base em tudo isso, podemos sugririr produtos ou servições para o cliente. 

Previsão de Churn: objetivo de detectar os clientes com alta protensão a deixar de consumir produtos ou cancelar serviços. Deve identificqar tais clientes e evitar isto.

Scoragem de Cliente: Mapear melhores clientes para convencer o lvliente a ter fidelidade. Assim, não perdemos clientes e tornamos fiel a empresa.

Cross-Selling: Venda casada e um método para conseguir mais vendas. Tudo isto pode ser feito através de uma análise de cesto de compras.
