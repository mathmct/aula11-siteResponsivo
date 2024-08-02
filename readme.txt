Mudanças:


    • CSS foi dividido em 2 seções, uma quando a pagina tiver mais de 600px de tamanho, a outra quando tiver menos;
    • Adicionado alinhamento em flexbox para toda a pagina (header, nav, main, footer);
    • O alinhamento flexbox muda conforme o tamanho da página, sendo em row (horizontal) quando a pagina é maior que 600px, e em coluna (vertical) quando é menor, EXCETO no main, que é sempre em coluna/vertical para facilitar a organização da informação em listas e imagens. A visualização em coluna faz com que a página se adeque melhor aos dispositivos móveis, enquanto a visualização em linha aproveita melhor o espaço da tela dos computadores;
    • A largura da página foi configurada para ocupar 100% do viewwidth em ambos os casos, para preencher a tela em ambos os dispositivos;
    • A margem ajustada para 1vw em telas menores que 600px, e 0.5vw em telas maiores que 600px, ao invés de pixels, para que ela se adapte a visualização;
    • As imagens foram tratadas individualmente em cada pagina html, tendo seu tamanho adaptado conforme o tamanho da tela.
    • Na pagina pequena, texto alinhado ao centro para melhor ajuste as telas mobile. Na grande, o alinhamento do texto varia entre centro e justificado nas diferentes seções;
    • Imagens na pagina acima de 600px terão uma margem direita de 15% do width do viewport, e de 2% do height;
    • Na pagina menor de 600px, colocada uma margem a direita de 15vw nos seguintes elementos do main: h2, table, ul, ol, p, para que o texto não fique grudado no canto da tela, dessa forma deixando a visualização mais agradável;
    • Tabela estilizada para se ajustar melhor em ambas as visualizações.
