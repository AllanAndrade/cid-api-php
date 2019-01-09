## CID API

A Classificação Internacional de Doenças e Problemas Relacionados à Saúde (também conhecida como Classificação Internacional de Doenças – CID 10) é publicada pela Organização Mundial de Saúde (OMS) e visa padronizar a codificação de doenças e outros problemas relacionados à saúde. A CID 10 fornece códigos relativos à classificação de doenças e de uma grande variedade de sinais, sintomas, aspectos anormais, queixas, circunstâncias sociais e causas externas para ferimentos ou doenças. A cada estado de saúde é atribuída uma categoria única à qual corresponde um código CID 10

###### Cada doença pode ser dada a uma categoria e receber um código de até seis caracteres de longitude (em formato de X00.000). Cada uma das tais categorias pode incluir um grupo de doenças similares.



### End-Points

## Lista Todas
`http://cidapi.com/cid10`
##### GET:

`
{
  "data":
    [
      {
        "codigo":"A00.9",
        "nome":"Cólera Não Especificada"
      },
              ...
      {
        "codigo":"A02",
        "nome":"Outras Infecções Por Salmonella"
      }
    ]
}   
`

## Obtém pelo código

`http://cidapi.com/cid10/{codigo-cid`

##### GET: 

`
{
  "data":
    [
      {
        "codigo":"A00",
        "nome":"Cólera"
      }
    ]
}     
`
### CC 3.0

API-CID foi criado por Atila Silva desenvolvedor de aplicações WEB e está sob a licença Creative Commons Attribution 3.0 License (CC BY 3.0)

Se você quiser copiar esse projeto sinta-se livre para fazer um fork no GitHub. Você pode !