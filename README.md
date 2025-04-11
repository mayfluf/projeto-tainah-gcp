# Processamento e Upload de Dados no Google Cloud

Pipeline de ETL para tratamento de dados inconsistentes e upload automatizado para Google Cloud Storage.

## Funcionalidades
- **Carregamento inteligente** de dados de URL externa
- **Conversão estruturada** para dicionários
- **Limpeza avançada** de dados inválidos (NaN, strings vazias)
- **Conversão de tipos** automática (float para salários, int para idades)
- **Upload seguro** para bucket GCS com autenticação OAuth2

## Tecnologias
- Python 3.8+
- Pandas (manipulação de dados)
- Google Cloud Storage Client (integração com GCP)

Esta estrutura oferece:
- Documentação clara e profissional
- Fluxo de trabalho reproduzível
- Segurança no manuseio de credenciais
- Organização de código escalável
- Compatibilidade com boas práticas de engenharia de dados

Para usar basta:
1. Substituir as informações do bucket GCS
2. Adicionar seu arquivo de credenciais na pasta config
3. Ajustar os paths conforme necessidade

Sugiro também adicionar:
- Testes unitários para as funções
- Logging detalhado
- Tratamento de exceções
- Pipeline de CI/CD básico
