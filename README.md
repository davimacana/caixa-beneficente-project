# caixa-beneficente-project
Repositório criado para gerenciar o desenvolvimento da caixa beneficiária


https://caixa-beneficente-frontend.herokuapp.com/

Obs.: Heroku tem um limite de conexões com o banco (20). Então, quando atinge esse limite tem que restaurar o banco
Se quiser entrar como colaborador do projeto no heroku, deixa o email aqui que eu add.


Dúvidas e questionamentos:
- PREÇO E PLANO PRECISAM MESMO TER UM PERÍODO ? DATA INÍCIO E DATA FIM
- Depois de criado um preço ele pode ser alterado ? ou deve ser inativado e um novo é criado (Caso possa alterar, poderá ter recibos com mesmo plano e faixa de idade com preços diferentes)

Correções:
- Correções gerais do layout
- Acertar o layout com o span em baixo da data


Bugs:



Melhorias:



Falta implementar: 

- Criar a funcionalidade de carteirinhas
- Criar a funcionalidade Relatórios (Já tem implementado, falta inserir mais relatórios)
- Criar a funcionalidade dashboards (Já tem implementado, falta inserir mais gráficos)
- Configurar o log externo da applicação


Observações ao testar:
- Não pode gerar novo recibo se o preco do plano ou o plano tiver inativo
- Recibo deve ter o id do preço
- Todo associado deve estar associado a um plano e esse plano a um preço
- Um plano pode ter N preços associados 
- Um plano só pode ter um preço ativo por faixa de idade

