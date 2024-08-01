# Data Cleaning Script

Este repositório contém um script em Python para tratamento de dados em arquivos CSV, JSON e XML. O script é projetado para preencher valores vazios ou nulos com o valor que mais se repete em cada coluna, além de permitir que o usuário selecione colunas que não devem ser preenchidas. O script também informa se há colunas com valores nulos antes de prosseguir com o tratamento.

## Funcionalidades

- **Leitura de arquivos**: Suporta arquivos nos formatos CSV, JSON e XML.
- **Detecção de valores nulos**: Informa se há colunas com valores nulos e a quantidade de valores nulos em cada coluna.
- **Tratamento de dados**: Preenche valores vazios ou nulos com o valor mais frequente na coluna, exceto para colunas que o usuário escolher não preencher.
- **Seleção de colunas a excluir**: Permite ao usuário selecionar colunas que não devem ser preenchidas com valores mais frequentes.
- **Continuidade do programa**: Permite ao usuário tratar múltiplos arquivos em uma única execução e decide se deseja tratar novos arquivos ou encerrar o programa.

## Como Usar

1. **Clone o repositório**

    ```bash
    git clone https://github.com/DerekWillyan/Data-Cleaning-Script.git
    ```

2. **Instale as dependências**

    Certifique-se de ter o Python instalado e instale as bibliotecas necessárias:

    ```bash
    pip install pandas
    ```

3. **Execute o script**

    Navegue até o diretório do repositório e execute o script:

    ```bash
    python ETL2024.py
    ```

4. **Forneça os arquivos**

    - Quando solicitado, informe o nome do arquivo de entrada (CSV, JSON ou XML).
    - Informe o nome do arquivo de saída.
    - O script exibirá informações sobre colunas com valores nulos e perguntará se deseja prosseguir com o tratamento.
    - Se houver colunas com valores nulos, o script permitirá que você selecione quais colunas não devem ser preenchidas.
    - Após o processamento, o arquivo tratado será salvo com o nome fornecido.

## Exemplo de Uso

```bash
Digite o nome do arquivo de entrada (CSV, JSON ou XML): input.csv
Digite o nome do arquivo de saída: output.csv
```

O script exibirá informações sobre colunas com valores nulos e perguntará se deseja prosseguir com o tratamento. Se houver colunas que você não deseja preencher, você poderá selecioná-las. Após o processamento, o arquivo tratado será salvo como `output.csv`.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou correções, por favor, abra uma issue ou envie um pull request.

1. **Fork o repositório**
2. **Crie uma branch para sua feature ou correção**
3. **Faça commit das suas mudanças**
4. **Envie um pull request**

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

Feito por Derek Willyan
