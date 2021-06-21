# flat-eptc 

## Dicionário de dados

|      Campo   |   Tipo  | Descrição |
|--------------|---------|-----------|
|       id     | String  | Identificador do tweet referente ao incidente. |
|      type    | Number  | Tipo de incidente, referenciado abaixo. |
|      date    | Date    | Data do tweet do incidente. |
|  hasAddress  | Boolean | Se o texto provido contém a tupla (Logradouro, Número). |
|  isLocalized | Boolean | Se a API do Nominatim conseguiu localizar o endereço. |

## Tipos de incidentes

| Tipo | Descrição |
|------|-----------|
|  0   | Atropelamento. |
|  1   | Acidente ou colisão. |
|  3   | Queda de moto. |
|  4   | Derramamento de líquidos na via. |
|  5   | Pane de veículo automotor na via. |
|  6   | Queda de árvore e galhos na via. |
|  7   | Queda de fios energizados na via. |
|  8   | Içamento do vão móvel da Ponte do Guaíba. |
|  9   | Animais soltos na via. |
