# Guia de Contribuições

Obrigado por querer contribuir para este projeto! Para garantir consistência e qualidade, por favor siga os passos abaixo ao adicionar uma nova técnica ou melhorar uma já existente.

## Passos a Seguir:

### 1. Explicação Inicial da Técnica
- Comece o notebook com uma explicação clara e simples da técnica de Machine Learning.
- **Inclua fórmulas simples** se necessário para melhorar a compreensão.
- Forneça o **raciocínio lógico** por trás da técnica (quando e por que usá-la).

### 2. Etapas Tradicionais do Machine Learning
Certifique-se de seguir as etapas tradicionais do ciclo de Machine Learning. Aqui está o fluxo típico:

1. **Carregar e Explorar os Dados**:
   - Utilize datasets armazenados na pasta `datasets/` dentro da subpasta apropriada.
   
2. **Pré-Processamento de Dados**:
   - Limpeza, transformação e tratamento de dados ausentes, conforme necessário.
   
3. **Divisão de Dados**:
   - Divida os dados em conjuntos de treino e teste (ou validação, se aplicável).

4. **Treinamento do Modelo**:
   - Execute o processo de treino com a técnica correspondente.

5. **Avaliação do Modelo**:
   - Avalie o desempenho do modelo utilizando métricas relevantes.

6. **Ajuste de Hiperparâmetros** (opcional):
   - Se apropriado, adicione um processo de ajuste de hiperparâmetros.

7. **Visualização de Resultados** (se necessário):
   - Inclua gráficos ou visualizações que ajudem a interpretar os resultados do modelo.

### 3. Footer com Autor
- Ao final do notebook, inclua um rodapé com:
  - Seu **nome**
  - Link para seu perfil do **GitHub** e/ou **Twitter**

  Exemplo:
  ```markdown
  ---
  **Autor:** [Seu Nome](https://github.com/seu-usuario)  
  **Twitter:** [@seu-usuario](https://twitter.com/seu-usuario)

## Armazenamento de Datasets

- Todos os datasets utilizados nos notebooks devem ser armazenados dentro da pasta `datasets/`, na subpasta correspondente ao tema:

   - `datasets/1-pre-processamento/`
   - `datasets/2-aprendizagem-supervisionada/`
   - `datasets/3-aprendizagem-nao-supervisionada/`

## Outras Instruções

- Certifique-se de que o código está bem documentado e segue uma estrutura organizada.
- Faça um _pull request_ para submeter sua contribuição. Ela será revista antes de ser incorporada ao repositório.

