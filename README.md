<div style="border: 2px solid #85182A; padding: 15px; background-color: #ffffff;">



### <span style="color: #85182A;">Objetivos do Projeto</span>



O objetivo deste projeto é avaliar modelos de aprendizado de máquina supervisionado capazes de classificar a qualidade de vinhos tintos com base em suas características físico-químicas. Utilizando o dataset Wine Quality (Red Wine), serão aplicadas técnicas de pré-processamento de dados, redução de dimensionalidade por meio de PCA, validação cruzada e ajuste de hiperparâmetros, visando identificar o modelo com melhor capacidade de predição.
Neste projeto, será avaliado a eficácia de diversos algoritmos de aprendizado de máquina, categorizados da seguinte forma:

1. **Linear Models**: Logistic Regression   

2. **Tree-Based Models**: Random Forests

3. **Support Vector Classifier**: SVC


### <span style="color: #85182A;">Resumo do dataset Wine Quality </span>



O dataset inclui informações sobre vinhos portugueses "Vinho Verde" (tintos e brancos), com variáveis ​​baseadas em propriedades físico-químicas e pontuações de qualidade sensorial. Esse conjunto de dados pode ser utilizado para tarefas de classificação ou regressão, embora as classes estejam desbalanceadas.

- **INPUT**: Diversas propriedades físico-químicas do vinho (por exemplo, acidez, teor de açúcar, densidade).

- **OUTPUT**: Pontuação de qualidade (0-10) com base em dados sensoriais.



### <span style="color: #85182A;">Features</span>



<table style="width:100%; border-collapse: collapse; font-family: Arial, sans-serif;">
    <thead>
        <tr style="background-color: #fdfdfd;">
            <th style="border: 1px solid #dddddd; padding: 8px; text-align: left;"><b>Feature No.</b></th>
            <th style="border: 1px solid #dddddd; padding: 8px; text-align: left;"><b>Feature Name</b></th>
            <th style="border: 1px solid #dddddd; padding: 8px; text-align: left;"><b>Description</b></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">1</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Fixed Acidity</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Nível de acidez que permanece após a fermentação</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">2</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Volatile Acidity</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Quantidade de ácido acético que afeta o sabor</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">3</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Citric Acid</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Realça o sabor, acrescenta frescor</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">4</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Residual Sugar</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Açúcar residual após a fermentação</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">5</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Chlorides</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Teor de sal</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">6</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Free Sulfur Dioxide</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">O SO₂ não está ligado e atua como antimicrobiano.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">7</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Total Sulfur Dioxide</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Quantidade total de SO₂ (ligado + livre)</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">8</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Density</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Densidade do vinho, relacionada ao teor de álcool e açúcar</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">9</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">pH</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Nível de acidez</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">10</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Sulphates</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Contribui para a estabilidade microbiana</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">11</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Alcohol</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Teor alcoólico</td>
        </tr>
        <tr>
            <td style="border: 1px solid #dddddd; padding: 8px;">12</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Quality</td>
            <td style="border: 1px solid #dddddd; padding: 8px;">Pontuação de qualidade sensorial (0 a 10)</td>
        </tr>
    </tbody>
</table>
