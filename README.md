# Projeto-Aplicado-III

# 🎹 Conjunto de Dados de Faixas do Spotify 
Um conjunto de dados de músicas do Spotify com diferentes gêneros e suas características de áudio

# Conteúdo 

Este é um conjunto de dados de faixas do Spotify em uma variedade de 125 gêneros diferentes. Cada faixa tem algumas características de áudio associadas a ela. Os dados estão no formato CSV, que é tabular e pode ser carregado rapidamente.

# Descrição da Coluna 

- track_id: O ID do Spotify para a faixa artists: Os nomes dos artistas que executaram a faixa. Se houver mais de um artista, eles são separados por um ;
- album_name: O nome do álbum em que a faixa aparece
- track_name: Nome da faixa
- popularity: A popularidade de uma faixa é um valor entre 0 e 100, sendo 100 o mais popular. A popularidade é calculada por algoritmo e baseia-se, na maior parte, no número total de reproduções que a faixa teve e quão recentes foram essas reproduções. Em geral, as músicas que estão sendo tocadas muito agora terão uma popularidade maior do que as músicas que foram tocadas muito no passado. Faixas duplicadas (por exemplo, a mesma faixa de um single e um álbum) são classificadas independentemente. A popularidade do artista e do álbum é derivada matematicamente da popularidade da faixa.
- duration_ms: O comprimento da faixa em milissegundos
- explicit: Se a faixa tem ou não letras explícitas (verdadeiro = sim, tem; falso = não tem OU desconhecido)
- danceability: A dançabilidade descreve quão adequada uma faixa é para dançar com base em uma combinação de elementos musicais, incluindo tempo, estabilidade do ritmo, força da batida e regularidade geral. Um valor de 0.0 é menos dançável e 1.0 é mais dançável
- energy: A energia é uma medida de 0.0 a 1.0 e representa uma medida perceptual de intensidade e atividade. Normalmente, faixas energéticas parecem rápidas, altas e barulhentas. Por exemplo, o death metal tem alta energia, enquanto um prelúdio de Bach tem baixa pontuação na escala
- key: A chave em que a faixa está. Os inteiros mapeiam para tons usando a notação padrão de Classe de Tom. Por exemplo, 0 = C, 1 = C♯/D♭, 2 = D, e assim por diante. Se nenhuma chave foi detectada, o valor é -1
- loudness: O volume geral de uma faixa em decibéis (dB)
- mode: O modo indica a modalidade (maior ou menor) de uma faixa, o tipo de escala de onde seu conteúdo melódico é derivado. Maior é representado por 1 e menor é 0
- speechiness: A fala detecta a presença de palavras faladas em uma faixa. Quanto mais exclusivamente falada a gravação (por exemplo, talk show, audiolivro, poesia), mais próximo de 1.0 o valor do atributo. Valores acima de 0.66 descrevem faixas que provavelmente são feitas inteiramente de palavras faladas. Valores entre 0.33 e 0.66 descrevem faixas que podem conter música e fala, seja em seções ou em camadas, incluindo casos como música rap. Valores abaixo de 0.33 provavelmente representam música e outras faixas não semelhantes à fala
- acousticness: Uma medida de confiança de 0.0 a 1.0 de se a faixa é acústica. 1.0 representa alta confiança de que a faixa é acústica
- instrumentalness: Prevê se uma faixa não contém vocais. Sons de “Ooh” e “aah” são tratados como instrumentais neste contexto. Faixas de rap ou palavra falada são claramente “vocais”. Quanto mais próximo o valor da instrumentalidade estiver de 1.0, maior a probabilidade de a faixa não conter conteúdo vocal
- liveness: Detecta a presença de uma audiência na gravação. Valores mais altos de vivacidade representam uma probabilidade aumentada de que a faixa foi executada ao vivo. Um valor acima de 0.8 fornece forte probabilidade de que a faixa é ao vivo
- valence: Uma medida de 0.0 a 1.0 descrevendo a positividade musical transmitida por uma faixa. Faixas com alta valência soam mais positivas (por exemplo, felizes, alegres, eufóricas), enquanto faixas com baixa valência soam mais negativas (por exemplo, tristes, deprimidas, zangadas)
- tempo: O ritmo geral estimado de uma faixa em batidas por minuto (BPM). Em terminologia musical, ritmo é a velocidade ou ritmo de uma determinada peça e deriva diretamente da duração média da batida
- time_signature: Uma assinatura de tempo estimada. A assinatura de tempo (medida) é uma convenção notacional para especificar quantas batidas estão em cada compasso (ou medida). A assinatura do tempo varia de 3 a 7, indicando assinaturas de tempo de 3/4 a 7/4.
- track_genre: O gênero ao qual a faixa pertence


# Sobre o projeto:

Com a popularização dos meios digitais para músicas, uma infinidade de serviços de reprodução musicais disseminou-se e consequentemente, os ouvintes de música de repente se deparam com uma quantidade enorme de conteúdo musical prontamente disponível. Em resposta a essa questão, os sistemas de recomendação musical surgem cada vez mais como uma ferramenta auxiliar que oferece suporte aos usuários que exploram vastas coleções de itens musicais e conteúdo relacionado (SCHEDL et al., 2022). Os itens musicais mais frequentemente recomendados incluem artistas, álbuns, faixas e listas de reprodução personalizada. Este trabalho se propõe a explorar o uso do aprendizado de máquina para desenvolver um modelo de sistema de recomendação de músicas que vai além do gênero musical, considerando uma variedade de atributos intrínsecos à composição e performance das músicas.
O objetivo é criar um sistema que possa entender e aprender com os padrões e preferências do usuário, proporcionando recomendações personalizadas e melhorando sua experiência.
Este estudo representa uma tentativa de contribuição significativa para a área de sistemas de recomendação de música, com potencial para impactar a maneira como os ouvintes descobrem novas músicas e artistas. Esperamos que nossas descobertas possam abrir caminho para futuras pesquisas e aplicações nesta área fascinante e em constante evolução.
A aplicação do aprendizado de máquina no contexto de sistemas de recomendação de música, permitirá analisar e aprender a partir de padrões de comportamento do usuário, bem como características intrínsecas das músicas. Isso permite que o sistema faça previsões precisas sobre quais músicas um usuário pode gostar com base em suas interações passadas e preferências musicais.
Hoje, existem excelentes Sistemas de Recomendação como os vistos em grandes empresas como a Amazon (recomendação de livros e produtos em geral), Netflix (recomendação de filmes e séries), Spotify (recomendação de músicas) e diversos outros, que nada mais são consequências do avanço do uso de tecnologia de Inteligência Artificial com técnicas de Machine Learning. Hoje as recomendações fornecidas por esses sistemas estão de acordo com as preferências dos usuários (LUDERMIR, 2021).
O aprendizado de máquina oferece várias técnicas, como aprendizado supervisionado, não supervisionado e aprendizado por reforço, cada uma com suas próprias forças e aplicações. Neste trabalho, exploraremos técnicas que permitam a aplicação de modelos de sistema recomendação baseados em conteúdo.
O uso do aprendizado de máquina em sistemas de recomendação de música representa uma área de pesquisa empolgante e desafiadora com o potencial para transformar a maneira como interagimos com a música. Este trabalho visa contribuir para essa área, explorando novas abordagens e técnicas para melhorar a precisão e a personalização das recomendações de música, no qual resultaria em uma experiência de audição mais personalizada e satisfatória, e, enquanto para as plataformas, pode resultar em maior engajamento do usuário, retenção e fidelização, e, consequentemente, aumentando a lucratividade e o nível de competividade.

# 1.1.	MOTIVAÇÃO E JUSTIFICATIVA

Não é recente o fato de que com a expansão do uso da internet as pessoas têm acesso a uma vasta gama de informações, produtos e serviços e que isso tem alterado significativamente os comportamentos e expectativas da sociedade. Nesse cenário, surgem cada vez mais a necessidade de encontrar itens que atendam às suas preferências e individualidades, muitas vezes exigindo a previsão das necessidades dos usuários com base em informações contextuais, como localização, horário e perfil do usuário. Os sistemas de recomendação surgem como uma resposta a essa demanda, oferecendo sugestões personalizadas para facilitar a escolha dos usuários.
Esses sistemas têm experimentado um progresso notável em aplicações comerciais, visando a recomendação de itens que satisfaçam ou superem as expectativas dos consumidores. Em diferentes contextos, como recomendação de filmes, livros ou músicas, é fundamental compreender as particularidades de cada categoria e as preferências dos usuários, adaptando as estratégias de recomendação conforme necessário.
No caso específico da recomendação de músicas, os desafios são amplificados devido à dinâmica do comportamento dos usuários e à influência do contexto de consumo, como nos serviços de streaming de música. Aqui, a personalização das recomendações torna-se crucial, uma vez que os usuários têm preferências únicas e consomem música em uma variedade de situações, exigindo recomendações adaptativas.
Um dos principais desafios enfrentados pelos sistemas de recomendação é a volatilidade das preferências dos usuários, que podem mudar ao longo do tempo e serem influenciadas por diversos fatores. Diante desse contexto, o presente estudo tem como objetivo principal explorar e analisar algoritmos de aprendizado de máquina que possam através de ferramentas de seleções especificas possibilitar a construção de um sistema de recomendação personalizada de ouvintes de músicas on-line. Especificamente, pretende-se investigar a eficácia e a precisão desses métodos, como filtragem colaborativa, redes neurais, e recomendações baseados em conteúdo.

# 1.2.	OBJETIVO GERAL

O trabalho vigente visa explorar e comparar os algoritmos utilizados em sistemas de recomendação de músicas, verificando suas aplicações e seus respectivos funcionamentos. Para tal finalidade, foi definido analisar a base de dados da plataforma Spotify, sendo assim, será feita a exploração desses dados e, ainda, modelos de aprendizado de máquina serão aplicados. Por fim, para atingir tal propósito, será calculada sua acuracidade. 

# 1.3.	OBJETIVOS ESPECÍFICOS

•	Coleta, pré-processamento e exploração dos dados.
•	Seleção das features adequadas para o modelo de aprendizado de máquina.
•	Desenvolver um modelo de aprendizado de máquina, treinando e validando o sistema de recomendação relacionado à plataforma. 
•	Aplicação de algoritmos de recomendação de músicas, como filtragem baseada em conteúdo. 
•	Reavaliação do modelo final. 
•	Publicação e apresentação dos resultados do modelo.
