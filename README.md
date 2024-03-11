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
