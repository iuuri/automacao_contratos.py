# Automação de Geração de Contratos para Fornecedores

Este projeto é uma automação desenvolvida para gerar arquivos `.docx` personalizados para cada fornecedor listado em uma planilha Excel. O objetivo é automatizar o processo de criação de contratos, inserindo dados específicos de cada fornecedor em um modelo de documento.

## Tecnologias Utilizadas
- **Python**
- **openpyxl**: Para leitura de planilhas Excel.
- **python-docx**: Para geração e manipulação de arquivos `.docx`.
- **Selenium**: Preparado para futuras expansões com automação web.
- **datetime**: Para adicionar a data de geração do contrato.

## Funcionalidades
1. Leitura dos dados dos fornecedores a partir de uma planilha Excel.
2. Geração automática de arquivos `.docx` contendo:
   - Nome da empresa
   - Endereço completo
   - Cidade, Estado, CEP
   - Telefone e E-mail
   - Setor
3. Criação dos arquivos `.docx` com nome personalizado, no formato `contrato_<nome_da_empresa>.docx`.

## Estrutura da Planilha
A planilha `fornecedores.xlsx` deve conter as seguintes colunas na aba `Sheet1`:
- Nome da Empresa
- Endereço
- Cidade
- Estado
- CEP
- Telefone
- E-mail
- Setor

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/automacao-contratos-fornecedores.git
