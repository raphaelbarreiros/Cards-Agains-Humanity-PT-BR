Programa em Python que gera cartas do Cards Agains Humanity, traduzido e em alta qualidade para imprimir.

-------------
Imprimir direto:
-------------
- Basta ir em [Releases](https://github.com/raphaelbarreiros/Cards-Agains-Humanity-PT-BR/releases/tag/PT-BR) e baixar a última versão em ZIP.

-------------
Dependencias:
-------------
- ImageMagick e Python (developed with python v2.* in mind).

---------------
Exemplos de uso:
---------------
- ./genCard.py -h
- ./genCard.py -i icon/icon-tabletop.png -b background/front-white.png -f fonts/HelveticaNeue-Bold.ttf -t "This is the card text" -n "1 / 44" -o custom001.png
- ./genCard.py -b background/front-white-sloth.png -o slothCard.png
- ./genCards.py -h
- ./genCards.py -i
- ./genCards.py -f sample/house-of-cards.csv.csv -p "HoC-" -s 1 -v -o generated/HOC/

Gerar expansões do CAH automaticamente:
- ./extras.py
- ./house-of-cards.py
- ./pax.py
- ./reject.py
- ./retail.py
- ./tabletop.py

GenCard gera uma única carta, enquanto GenCards gera várias cards usando as intruções do arquivo CSV de entrada.
Verifique os arquivos no diretório sample/ para obter inspiração sobre como criar um arquivo de entrada para GenCards.
 
-----
Pendências:
-----
- Ícones para expansões oficiais 1-6, expansão de caixa, várias expansões de férias e expansão científica. Essa é uma prioridade baixa, pois essas expansões estão prontamente à venda. Pesquise se as versões AU ou CA têm ícones.
- Melhorias nos fundos do cartão rejeitado e no cartão ladel. Além disso, melhorias nos ícones de expansão e garantia de posicionamento do texto são precisas. Este programa tenta fazer cartões o mais parecidos possível com os originais, mas isso não é possível em alguns lugares (como o pacote rejeitado).

-----
Notas:
-----
- Se você adicionar planos de fundo, adicione um plano de fundo de 3300 x 4500 pixels para garantir a qualidade do cartão e permitir sangramento.
- Os ícones devem ter 140 x 140. O software gira automaticamente os ícones para caber na caixa mais à direita do logotipo inferior esquerdo.
