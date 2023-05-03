## Descrição Etiqueta: 110 x 30 Normal com precificacao
## Elaborada por: Emerson Zanotta
## Caracteres por linha: 70
## Formato da Etiqueta: ZPL - Zebra
## Modelo: Gondola


^XA
^LH0,0^FS
^LL240^FS
^PRA^FS
^FO010,010^A0,60,32^FD${etiqueta.descricao[0]}^FS
^FO360,80^BY2,2.5,100^BCN,30,Y,N^FD${etiqueta.barra}^FS
^FO010,140^A0,50,50^FDR$^FS
^FO060,80^A0,134,106^FD${etiqueta.preco}^FS
^FO320,155^A0,30,30^FD/${etiqueta.embalagemKey} ^FS
^FO455,160^A0,30,20^FD* Preco equivalente a R$ ${etiqueta.precoPorQuantidadeDaUnidadeDeMedida} / ${etiqueta.tipoUnidadeMedida}^FS
^PQ1,0,1,N^FS
^XZ