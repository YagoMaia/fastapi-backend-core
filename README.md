# 🚀 FastAPI & SQLModel: Backend Reference Implementation

Este repositório serve como base técnica e laboratório de implementação para o desenvolvimento de APIs de alta performance no âmbito da Iniciação Científica (IC) na Universidade Estadual de Montes Claros (Unimontes).

O foco aqui não é apenas "fazer funcionar", mas aplicar padrões de engenharia como validação de dados, I/O assíncrono e mapeamento relacional de forma escalável.

## 🏗️ Arquitetura Core e Tecnologias

| Recurso               | Tecnologia  | Propósito                                                              |
| --------------------- | ----------- | ---------------------------------------------------------------------- |
| Framework             | FastAPI     | Framework web assíncrono de alta performance.                          |
| ORM / Camada de Dados | SQLModel    | Integração de SQLAlchemy e Pydantic para modelagem de dados intuitiva. |
| Validação             | Pydantic v2 | Verificação rigorosa de tipos e serialização de dados.                 |
| Ambiente              | Docker      | Desenvolvimento containerizado para paridade entre ambientes.          |

## 🔬 Contexto Científico (Unimontes)

Este projeto integra o esforço de pesquisa em [INSIRA AQUI O NOME DA SUA ÁREA DE PESQUISA, EX: SISTEMAS DISTRIBUÍDOS], visando criar uma camada de backend robusta para o processamento de [EX: DADOS GEOGRÁFICOS / MODELAGEM URBANA].

## 🛠️ Principais Recursos Técnicos Implementados

- **Endpoints Assíncronos**: Uso extensivo de `async/await` para evitar bloqueios de I/O.
- **Injeção de Dependência**: Implementação nativa do FastAPI para gerenciamento de sessões de banco de dados.
- **Auto-Documentação**: Swagger UI integrada para testes e validação de contratos de API.

## 🚦 Primeiros Passos

### Pré-requisitos

- Python 3.10+

### Instalação

```bash
# Clone o repositório
git clone https://github.com/yagomaia/fastapi-ic.git

# Navegue para o diretório da API
cd api

# Instale as dependências
pip install -e .

# Execute o servidor de desenvolvimento
fastapi dev main.py
```

## 📚 Documentação da API

Acesse a documentação interativa em `http://localhost:8000/docs` após iniciar o servidor.

## 📄 Licença

Este projeto está sob a licença MIT.
