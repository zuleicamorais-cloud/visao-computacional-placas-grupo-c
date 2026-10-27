## Etapa 01 — Conexão com o Google Drive

**Objetivo:** Permitir o acesso ao conjunto de imagens armazenado no Google Drive.

**Implementação:** O módulo `drive`, disponibilizado por `google.colab`, permite montar o armazenamento no ambiente de execução do notebook.

```python
from google.colab import drive
drive.mount('/content/drive')
```

**Resultado:** A mensagem `Mounted at /content/drive` confirmou a montagem bem-sucedida.

**Observação técnica:** A conexão pode precisar ser refeita após o encerramento da sessão do Colab.

**Documentação:** Zuleica Morais Firmino.
