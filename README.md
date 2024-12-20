
# Organização e Explicação

01_data_analysis.ipynb -> Análise inicial do conjunto de dados
02_data_preprocessing.ipynb -> Testes de técnicas de préprocessamento
03_quad_tree.ipynb -> Testes com Snakes utilizando QuadTree para inicialização das snakes
03_snakes_segmentation.ipynb -> Testes com Snakes utilizando quadro de xadrez como inicialização das snakes
03_thresholding.ipynb -> Testes com Thresholding
04_model_evaluation.ipynb -> Script para comparação entre predito e esperado, assim como comparação das técnicas

Falta:

Organizar todos os scripts e botar pra rodar
Apresentar os preprocessamentos
Salvar os resultados e depois carregar para fazer comparação com DSC

(a) Variação dos parâmetros
    - Selecionar alguns parâmetros para variar
        - Nas snakes, o level set e threshold
        - No filtro gaussiano o tamanho do filtro
        - Na erosão o elemento estruturante

(b) Mudança de resolucão espacial das imagens
    - Implementar scripts para automatizar isso depois da seleção dos parâmetros

(c) Outro
    - Comparação entre o modelo das snaskes e o modelo com threshold
