# Data Cleaning Script

Este repositório contém um script em Python para tratamento de dados em arquivos CSV, JSON e XML. O script é projetado para preencher valores vazios ou nulos com o valor que mais se repete em cada coluna. Além disso, ele informa se há colunas com valores nulos antes de prosseguir com o tratamento.

## Funcionalidades

- **Leitura de arquivos**: Suporta arquivos nos formatos CSV, JSON e XML.
- **Detecção de valores nulos**: Informa se há colunas com valores nulos e a quantidade de valores nulos em cada coluna.
- **Tratamento de dados**: Preenche valores vazios ou nulos com o valor mais frequente na coluna.
- **Continuidade do programa**: Permite ao usuário tratar múltiplos arquivos em uma única execução.

## Como Usar

1. **Clone o repositório**

    ```bash
    git clone https://github.com/seu_usuario/nome_do_repositorio.git
    ```

2. **Instale as dependências**

    Certifique-se de ter o Python instalado e instale as bibliotecas necessárias:

    ```bash
    pip install pandas
    ```

3. **Execute o script**

    Navegue até o diretório do repositório e execute o script:

    ```bash
    python data_cleaning_script.py
    ```

4. **Forneça os arquivos**

    - Quando solicitado, informe o nome do arquivo de entrada (CSV, JSON ou XML).
    - Informe o nome do arquivo de saída.

    O script processará o arquivo e perguntará se você deseja prosseguir com o tratamento dos valores nulos. Ao final, ele salvará o arquivo tratado com o nome fornecido.

## Exemplo de Uso

```bash
Digite o nome do arquivo de entrada (CSV, JSON ou XML): input.csv
Digite o nome do arquivo de saída: output.csv
```

O script exibirá informações sobre colunas com valores nulos e perguntará se deseja prosseguir com o tratamento. Após o processamento, o arquivo tratado será salvo como `output.csv`.

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
