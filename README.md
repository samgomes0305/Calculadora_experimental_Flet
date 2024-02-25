# Calculadora

Esta é uma calculadora simples implementada em Python usando a biblioteca `flet` para a construção de interfaces gráficas. A calculadora fornece operações aritméticas básicas, como adição, subtração, multiplicação e divisão. Também inclui recursos como cálculo de porcentagem e a capacidade de inverter o sinal do número exibido.

## Utilização

Para executar a calculadora, execute o script fornecido. A interface gráfica do usuário será exibida, permitindo a realização de cálculos.

## Componentes da Interface

A calculadora consiste nos seguintes componentes de interface:

- **Display**: A linha superior exibe o resultado atual e pode ser usada para mostrar a entrada e saída de cálculos.

- **Botões Numéricos**: A calculadora inclui botões para os dígitos de 0 a 9, bem como um ponto decimal. Clicar nesses botões anexa o dígito correspondente à entrada atual.

- **Botões de Operações Aritméticas**: Botões para adição (+), subtração (-), multiplicação (*) e divisão (/) estão disponíveis. Clicar nesses botões realiza a operação especificada com a entrada atual e atualiza o display.

- **Botões Especiais**: 
    - **AC (Limpar Tudo)**: Reinicia a calculadora para seu estado inicial.
    - **+/- (Inverter Sinal)**: Altera o sinal do número atualmente exibido.
    - **% (Porcentagem)**: Converte a entrada atual em porcentagem.

- **Botão Igual (=)**: Calcula o resultado da expressão inserida até o momento e atualiza o display.

## Operação

- Insira valores numéricos e realize operações aritméticas clicando nos botões correspondentes.
- Use o botão AC para limpar a entrada e iniciar um novo cálculo.
- Inverta o sinal do número exibido usando o botão +/-.
- Use o botão % para converter a entrada atual em porcentagem.
- Clique no botão igual (=) para calcular o resultado da expressão inserida.

## Tratamento de Erros

A calculadora trata a divisão por zero de maneira adequada e exibe "Erro" quando encontrada. O botão AC reinicia a calculadora em caso de erro.

## Informações para Desenvolvedores

O aplicativo é construído usando a biblioteca `flet`, e os componentes da interface estão organizados em uma estrutura definida na classe `CalculatorApp`. A função principal do aplicativo, `main`, cria uma instância de `CalculatorApp` e a adiciona à página.

## Dependências

Certifique-se de que a biblioteca `flet` esteja instalada antes de executar o aplicativo. Você pode instalá-la usando o seguinte comando:

```bash
pip install flet
```

Sinta-se à vontade para explorar e aprimorar a funcionalidade da calculadora com base em suas necessidades.
