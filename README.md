# Automacao-do-processamento-de-PDF-e-OCR-com-UiPath
Automação no UiPath para processar faturas em PDF (pesquisável ou imagem) e guardar os  dados relevantes em planilha excel usando RegEx.

Requisitos:
1. Baixar os pacotes do UiPath (se for o caso):
  - UiPath.UIAutomation.Activities (v22.4.5)
  - UiPath.Excel.Activities (v2.12.3)
  - UiPath.System.Activities (v22.4.1)
  - UiPath.PDF.Activities (v3.3.0)


Descrição:
A automação verifica cada fatura em PDF e guarda os dados relevantes em uma variável do tipo tabela: Nr Fatura, data da fatura, data de vencimento e o total. Caso seja um arquivo do tipo imagem, é acionada uma estutura de decisão para aplicar o motor OCR. Por fim, guarda as informações extraidas em uma base de dados .xlsx (excel).
