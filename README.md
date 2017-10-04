Para utilizar deve estar declarado no AfterGlobalIncludes dentro do GlobalEmbeds

    INCLUDE('ClaRunExt.INC'),ONCE
    INCLUDE('JSON.INC'),ONCE

Para utilizar o source basta fazer a chamada com a seguinte

ConsultaCEPWeb(CEP,LOGRADOURO,COMPLEMENTO,BAIRRO,LOCALIDADE,UF,IBGE)

e irá retornar com os dados preenchido.
