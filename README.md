# tcc-puc-melanoma-detection
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Diagnóstico Automático de Melanoma utilizando Redes Neurais</h1>

<p>
    Este projeto faz parte do Trabalho de Conclusão de Curso (TCC) de pós-graduação em Ciência de Dados e Big Data e 
    tem como objetivo desenvolver uma solução automatizada para o diagnóstico de melanoma em imagens utilizando 
    redes neurais convolucionais (CNNs).
</p>

<h2>Descrição do Projeto</h2>

<p>
    O melanoma é um tipo agressivo de câncer de pele, e seu diagnóstico precoce é crucial para aumentar as chances 
    de sucesso no tratamento. Este projeto utiliza aprendizado profundo para criar um modelo de machine learning que 
    auxilia na classificação de imagens de pele entre melanoma e não melanoma.
</p>

<h3>Características do Projeto</h3>
<ul>
    <li>Base de dados utilizada: Kaggle e ISIC (International Skin Imaging Collaboration).</li>
    <li>Modelos treinados: MobileNetV2, ResNet-50 e DenseNet-121.</li>
    <li>Pré-processamento de dados: Redimensionamento de imagens para 224x224 pixels, normalização de valores de pixels, 
        e unificação de datasets de diferentes fontes.</li>
    <li>Métricas de avaliação: Acurácia e F1-Score.</li>
</ul>

<h2>Arquitetura dos Modelos</h2>

<p>
    Foram utilizados três modelos de redes neurais convolucionais, com as seguintes configurações:
</p>

<ul>
    <li><strong>MobileNetV2</strong>: Modelo leve e eficiente, alcançou a maior acurácia (92.73%) e F1-Score (89.56%).</li>
    <li><strong>ResNet-50</strong>: Modelo profundo, com uma acurácia de 92.00% e F1-Score de 88.52%.</li>
    <li><strong>DenseNet-121</strong>: Obteve uma acurácia de 91.64% e F1-Score de 88.93%, destacando-se pela reutilização 
        de características entre camadas.</li>
</ul>

<h2>Resultados</h2>

<p>
    Os três modelos apresentaram desempenhos competitivos, com o MobileNetV2 se destacando em termos de eficiência e 
    precisão. Testes adicionais foram realizados em imagens reais, com resultados variando entre os modelos.
</p>

<h3>Métricas de Desempenho</h3>
<table>
    <tr>
        <th>Modelo</th>
        <th>Acurácia</th>
        <th>F1-Score</th>
    </tr>
    <tr>
        <td>MobileNetV2</td>
        <td>92.73%</td>
        <td>89.56%</td>
    </tr>
    <tr>
        <td>ResNet-50</td>
        <td>92.00%</td>
        <td>88.52%</td>
    </tr>
    <tr>
        <td>DenseNet-121</td>
        <td>91.64%</td>
        <td>88.93%</td>
    </tr>
</table>

<h2>Requisitos</h2>

<p>
    Para rodar este projeto localmente, certifique-se de ter o seguinte ambiente configurado:
</p>

<ul>
    <li>Python 3.9</li>
    <li>Bibliotecas: Torch, torchvision, numpy e pandas</li>
    <li>GPU NVIDIA para aceleração do treinamento</li>
</ul>

<h2>Como Executar</h2>

<ol>
    <li>Clone este repositório.</li>
    <li>Instale as dependências utilizando <code>pip install nome_biblioteca</code>.</li>
    <li>Prepare os datasets (Kaggle e ISIC).</li>
    <li>Execute os scripts de treinamento disponíveis.</li>
</ol>

</body>
</html>
