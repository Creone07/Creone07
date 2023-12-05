  +-----------------+       +-----------------+
  |      Título     |       |     Exemplar    |
  +-----------------+       +-----------------+
  | ID do Título   |<----->| ID do Exemplar  |
  | Nome            |       | ID do Título   |
  | Descrição       |       | Status          |
  | Período Máx Empr|       +-----------------+
  +-----------------+

  +-----------------+       +-----------------+
  |     Cliente     |       |    Funcionário  |
  +-----------------+       +-----------------+
  | ID do Cliente  |       | ID do Funcionário|
  | Nome            |       | Nome            |
  | Endereço        |       | Cargo           |
  | Número de Tel   |       | Número Func     |
  | Endereço de E-mail |   | Info Contato    |
  +-----------------+       +-----------------+

  +-----------------+       +-----------------+
  |  Transação      |       |     Multa       |
  +-----------------+       +-----------------+
  | ID da Transação|       | ID da Multa     |
  | Data da Trans   |       | Valor Multa     |
  | Tipo Transação  |       | Data Registro   |
  | ID do Cliente  |       | ID da Trans Rel |
  | ID do Funcionário|      +-----------------+
  +-----------------+

                +-----------------+
                |   Promoção     |
                +-----------------+
                | ID da Promoção |
                | Nome Promoção  |
                | Descrição      |
                | Critérios Eleg.|
                +-----------------+
