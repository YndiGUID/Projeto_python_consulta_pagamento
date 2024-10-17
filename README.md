### Projeto_python_consulta_pagamento ###
'''
Import openpyxl

# 1. Entrar na planilha e extrair o CPF do cliente #

Planilha_Clientes = openpyxl.load_workbook('dados_clientes.xlsx')
pagina_clientes = Planilha_Clientes['Sheet1']


for linha in pagina_clientes.iter_rows(min_row=2,values_only=True):
   Nome, Valor,CPF,Vencimento = linha


# 2. entrar no site ________ e uso o CPF da planilha para pesquisar status de pagamento da aquele cliente #
# 3. Verificar se esta "em dia" ou "Atrasado" #
# 4. Se estiver "em dia", pegar a data de pagamento e o método de pagamento #
# 5. Caso estiver "Atrasado", colocar status como "pendente" #
# 6. Insserir essas novas Informaçoes (Nome,Valor,CPF,Vencimento,Status e caso esteja em dia, data pagamento, método de pagamento (crtão ou Boleto)) em uma nova planilha #
# 7. Repetir até chegar ao ultimo cliente. #

   '''
