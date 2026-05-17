# Automação de Processos e Relatórios com Python (RPA & Data Analytics)

## 📝 Descrição do Projeto
Este projeto simula uma rotina diária real de um analista administrativo/financeiro. Ele automatiza de ponta a ponta o processo de download de relatórios de vendas numa plataforma em nuvem (Google Drive), realiza o tratamento e cálculo de indicadores-chave de performance (KPIs) e envia um relatório consolidado por e-mail para a diretoria.

O objetivo principal foi eliminar o trabalho manual repetitivo, mitigar o risco de erros de digitação e garantir agilidade na entrega de dados estratégicos logo nas primeiras horas do dia.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Python**: Linguagem base do projeto.
- **PyAutoGUI**: Automação Robótica de Processos (RPA) para controle e simulação dos periféricos (rato, teclado e navegação de interface).
- **Pandas**: Manipulação e análise de dados para carregamento e consolidação das planilhas Excel.
- **OpenPyXL**: Mecanismo integrado ao Pandas para leitura de arquivos `.xlsx`.
- **Pyperclip**: Manipulação segura da área de transferência para tratamento de caracteres especiais e acentuações no e-mail.
- **Time**: Sincronização e controle de tempo de execução entre as interações do sistema.

## 📊 Indicadores Calculados
O script faz a leitura automática de milhares de registros de vendas diárias e extrai:
1. **Faturamento Total**: Soma da receita final gerada no período.
2. **Volume de Vendas**: Quantidade total de produtos comercializados.

## 🚀 Como Executar o Projeto
1. Certifique-se de ter o Python instalado.
2. Instale as dependências necessárias via terminal:
   ```bash
   pip install pyautogui pandas openpyxl pyperclip
