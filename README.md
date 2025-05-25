
# Análise de Dados do Google Sheets com Pandas

Script para ler dados públicos de uma planilha Google Sheets, limpar e processar informações sobre afiliações, regiões, países, autores e referências.

## Requisitos

- Python 3.x
- pandas

Instalação do pandas:

```bash
pip install pandas
```

## Como usar

1. Altere o `sheet_id` para o ID da sua planilha pública do Google Sheets. 
2. Execute o script.

## Funções principais

- `limpar_texto(texto)`: limpa e normaliza texto.
- `separar_afiliacoes(texto)`: separa afiliações e países.
- `separar_paises(campo)`: separa múltiplos países.
- `separar_autores(campo)`: separa múltiplos autores.
- `extrair_autor_ano(texto)`: extrai autor(es) e ano de referências.

## Colunas esperadas

- `Afiliation`
- `Region`
- `country`
- `Autores`
- `Ref`

## Saída no console

- Colunas da planilha
- Afiliações únicas e contagem
- Contagem por região
- Contagem por país
- Contagem por autor
- Referências limpas com autor(es) e ano

---

## Exemplo mínimo de uso


---

Feito para facilitar análises rápidas em bases públicas do Google Sheets.

---

*Ivan Moriá — 2025*
