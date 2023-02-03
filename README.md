# testando_pyarrow

Fiz alguns testes com o pyarrow, no intuito de demonstrar suas vantagens em relação ao python quando precisamos submeter python dentro do spark, mostrando que pode ser uma ferramenta muito boa para evitarmos de perder muito desempenho e não ter que utilizar de recursos do scala para tal, os resultados foram satisfatórios nos testes que fiz imaginando um consumo de uma api pelo python requests, e por uma medida paliativa que realizei em um trabalho essa semana.

# Definições:

Apache Arrow é uma biblioteca de código aberto para colaboração em colunas, que oferece uma forma eficiente e padronizada de troca de dados entre sistemas. É projetado para ser usado com várias linguagens de programação, como Java, C ++, Python, JavaScript e R, e permite a transferência de dados de alta velocidade entre aplicativos e bancos de dados. Arrow também fornece uma estrutura para comprimir, filtrar e processar grandes conjuntos de dados de forma rápida e eficiente em termos de recursos.

O pyarrow pode ser utilizado para usar codigos python dentro da memória, e de formato colunar, provando ser muito util em analytics
