# Histórico do veículo — Auto Mecânica Itabaiana

Página aberta pelo QR Code das etiquetas de troca de óleo.

- `index.html` lê o código do carro no link (`?c=CODIGO`) e busca o histórico na
  planilha do Google da oficina (Apps Script publicado como App da Web).
- A planilha fica privada: a página só recebe modelo, ano, parte da placa e os
  serviços daquele carro. Observações internas e dados do cliente não saem de lá.
- `?c=DEMO` mostra um exemplo com dados fictícios.

Não renomeie este repositório nem a conta do GitHub: os QR Codes já impressos
apontam para `https://automec135.github.io/`.
