# Geocolaboração utilizando a plataforma [Google My Maps](https://www.google.com/intl/pt-BR/maps/about/mymaps/)

O [Google My Maps](https://www.google.com/intl/pt-BR/maps/about/mymaps/) permite a criação e o compartilhamento de mapas personalizados de forma simples. Além disso permite a colaboração de diferente agentes.

Após a publicação do mapa o usuário decide com quem vai compartilhar(restrito aos colaboradores ou aberto ao público), assim como as pessoas que podem editar o mapa ou não.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/googlemps.png)

<br>

## Desenvolvimento

<br>
 
#### Preparação dos dados através do QGIS
Definir a base de dados para o local de interesse: os vetores do Municípo, dos Bairros e os pontos de descarte irregular.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/dadosqgis.png)

_______

#### Exportar camadas no formato KML
Com os dados prontos é necessário que sejam exportados no formato **.kml**. A plataforma do My Maps possibilita a importação de arquivos nos formatos: CSV, XLSX, KML ou GPX.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/exportKml.png)
_______

#### Criar um novo mapa na plataforma
Ao acessar o [endereço](https://www.google.com/intl/pt-BR/maps/about/mymaps/), clicar no botão criar um novo mapa e já é possível realizar as edições no mapa.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/criarmapa.png)
_______

#### Adicionar camadas e importar dados Kml
Neste momento são adicionadas as diferentes camadas existentes no projeto. Neste caso foram utilizadas 3: a do Município, a do Bairro e a dos pontos de descarte. Cada camada recebe os arquivos .Kml respectivos que foram exportados do Qgis.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/importarKml.png)
_______

#### Personalizar aparência dos elementos de camada
Existem algumas formas de modificação da aparência das camadas adicionadas. Para os pontos de descarte(RDC) foi utilizado o modo Estilizado por coluna de dados, o que permite a classificação pelos atributos de cada camada. Neste caso o tipo de resíduo foi o critério escolhido, dividos em (Construção) e (Construção e Doméstico).

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/estilizado.png)
_______

#### Conceder aos coladores acesso para edição do mapa
Ao finalizar as configurações de exibição dos dados é possível definir o acesso ao mapa. No botão compartilhar é possível adicionar usuários e as funções que cada um pode realizar no mapa.
<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/comp1.png)


<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/compartilhamento.png)

#### Adicionar pontos de interesse
Ao clicar no botão inserir marcador, ao escolher o tipo de resíduo o mapa já realiza sua classificação, sendo necessário o preenchimento dos dados do informante.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/inserirmarcador.png)

##### Aplicativo Google My Maps

O Google My Maps possui um aplicativo para manipulação dos mapas. Estas informações foram retiradas diretamente do site. Ainda não utilizei.

"Com o [Google My Maps](https://play.google.com/store/apps/details?id=com.google.android.apps.m4b&hl=pt_BR), você pode:

- Criar novos mapas e editar aqueles que foram criados na Web ou em outro dispositivo
- Procurar lugares e salvá-los no seu mapa
- Adicionar um ponto no seu local atual ou em qualquer lugar do mundo
- Ver rotas e navegar para qualquer lugar salvo no mapa."

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/app.png)
_______

#### Compartilhamento do mapa 
É possível compartilhar o site enviando um link de acesso ou até mesmo incorporando a um site existente, como foi o exemplo a seguir.

<br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/html.png)

_______

## Produto Final
Mapa finalizado e incorporado a um site simples desenvolvido em HTML. <br>

![](https://github.com/danielfbrg/rdc_MyGoogleMaps/blob/master/image/final.png)

<br>

**[DEMO]**(https://danielfbrg.github.io/rdcmap/)


<br>
<br>

## Fontes

**Google My Maps**
https://www.google.com/intl/pt-BR/maps/about/mymaps/

**Aplicativo para Android Google My Maps**
https://play.google.com/store/apps/details?id=com.google.android.apps.m4b&hl=pt_BR

**Qgis**
https://qgis.org/en/site/


