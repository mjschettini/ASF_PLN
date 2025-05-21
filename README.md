# Recomendação de Requisitos de Cibersegurança em Histórias de Usuário Utilizando Processamento de Linguagem Natural


# Descrição dos Arquivos

## `all_user_stories.txt`

Contém o conjunto completo de histórias de usuário obtidas em [zenodo.org/records/13880060](https://zenodo.org/records/13880060). Desse total, 80% foram utilizadas na construção da base de palavras e os 20% restantes reservados para testes dos métodos aplicados.

## `extracao_palavras_historias_usuario.ipynb`

Notebook com o código-fonte responsável pela extração e tratamento das palavras presentes nas histórias de usuário.

## `saida_palavras_agrupadas_questoes_especificas.csv`

Arquivo resultante da extração de palavras realizada pelo notebook anterior, contendo a classificação de cada palavra segundo as questões específicas propostas no trabalho:

> Gabriella Costa, Victor de Paula, Marcelo Belisário, Maria Júlia Schettini, José Eduardo Fernandes, and Tiago Pedrosa. 2025. *Incorporating Cybersecurity Requirements in Agile Development Processes*. In *Proceedings of the 28th Workshop on Requirements Engineering (WER 2025)*. Recife, Brazil.

## `historias_nao_utilizadas.txt`

Reúne as histórias de usuário correspondentes aos 20% que não foram empregados na construção da base de palavras.

## `busca_completa.ipynb`

Notebook que implementa os métodos de busca direta e com lematização, aplicados sobre as histórias presentes no arquivo `historias_nao_utilizadas.txt`.
