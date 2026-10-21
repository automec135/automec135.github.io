# Histórico do veículo — Auto Mecânica Itabaiana

Página aberta pelo QR Code das etiquetas de troca de óleo.

- `index.html` lê o código do carro no link (`?c=CODIGO`), transforma o código num
  identificador (SHA-256) e procura esse identificador na aba **Público** da planilha
  da oficina, publicada na Web como CSV.
- A aba Público é gerada pelo Apps Script da planilha e só tem: identificador, modelo,
  ano e os serviços. Sem placa, código, nome ou telefone. A observação interna não sai
  da planilha.
- `?c=DEMO` mostra um exemplo com dados fictícios.

Não renomeie este repositório nem a conta do GitHub: os QR Codes já impressos
apontam para `https://automec135.github.io/`.
