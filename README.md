# Corretor de XML NF-e (Mercado Livre)

Ferramenta simples para **corrigir automaticamente o cabeçalho de arquivos XML de NF-e** exigido pelo Mercado Livre.

Resolve erros como:
> “Cabeçalho do XML é inválido ou não foi incluído. Atualize para a versão 1.0 e UTF-8.”

---

## O que este projeto faz

- Remove qualquer texto, espaço ou lixo **antes do início do XML**
- Garante que a **primeira linha do arquivo** seja exatamente:
  ```xml
  <?xml version="1.0" encoding="UTF-8"?>
