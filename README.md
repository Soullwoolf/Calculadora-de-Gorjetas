# 🧮 Calculadora de Gorjetas

Uma aplicação web desenvolvida com **HTML5, CSS3 e JavaScript** para calcular o valor da gorjeta de acordo com a qualidade do serviço e dividir o valor entre as pessoas.

O projeto foi desenvolvido como parte da minha prática em **desenvolvimento web**, com foco na integração entre estrutura, estilização e lógica de programação.

---

## 📸 Preview

![Calculadora de Gorjetas].

---

## 🚀 Sobre o projeto

A **Calculadora de Gorjetas** é uma aplicação web simples e interativa que permite informar o valor de uma conta, selecionar a porcentagem de gorjeta de acordo com a avaliação do serviço e informar entre quantas pessoas o valor será dividido.

Após o preenchimento do formulário, a aplicação realiza o cálculo utilizando **JavaScript** e apresenta dinamicamente o valor da gorjeta por pessoa.

O principal objetivo do projeto foi colocar em prática conceitos fundamentais de desenvolvimento front-end, especialmente a comunicação entre **HTML, CSS e JavaScript**.

---

## ✨ Funcionalidades

* 💰 Inserção do valor da conta
* ⭐ Seleção da qualidade do serviço
* 📊 Diferentes porcentagens de gorjeta
* 👥 Divisão da gorjeta entre várias pessoas
* 🧮 Cálculo automático do valor
* ⚡ Atualização dinâmica do resultado
* 📝 Validação básica dos campos
* 📱 Estrutura preparada para diferentes tamanhos de tela

### Percentuais disponíveis

| Avaliação | Gorjeta |
| --------- | ------: |
| Incrível  |     30% |
| Bom       |     20% |
| Aceitável |     15% |
| Ruim      |     10% |
| Péssimo   |      5% |

---

## 🛠️ Tecnologias utilizadas

### HTML5

Utilizado para construir a estrutura da aplicação, incluindo:

* Formulários
* Inputs
* Selects
* Labels
* Botões
* Organização dos elementos da interface

### CSS3

Utilizado para desenvolver a identidade visual da aplicação, incluindo:

* Variáveis CSS
* Cores personalizadas
* Tipografia
* `border-radius`
* `box-shadow`
* Estados de foco
* Estilização de formulários
* Organização visual da interface

### JavaScript

Responsável pela lógica e interatividade da aplicação:

* Manipulação do DOM
* Eventos de formulário
* Funções
* Estruturas condicionais
* Conversão de valores
* Cálculos matemáticos
* Atualização dinâmica dos elementos
* Controle da exibição dos resultados

---

## 🧠 Conceitos praticados

Durante o desenvolvimento do projeto, foram colocados em prática conceitos fundamentais de desenvolvimento front-end:

* Estruturação de páginas com HTML5
* Estilização utilizando CSS3
* Variáveis CSS com `:root`
* Manipulação do DOM
* Seleção de elementos com `getElementById()`
* Eventos utilizando `addEventListener()`
* Funções em JavaScript
* `event.preventDefault()`
* Conversão de dados com `Number()`
* Estruturas condicionais `if / else`
* Operações matemáticas
* Manipulação de propriedades CSS através do JavaScript
* Atualização de conteúdo utilizando `innerHTML`
* Organização do projeto em arquivos separados

---

## ⚙️ Como funciona

O funcionamento da aplicação segue basicamente quatro etapas:

```text
Valor da conta
      ↓
Qualidade do serviço
      ↓
Quantidade de pessoas
      ↓
Cálculo da gorjeta
      ↓
Resultado por pessoa
```

A lógica utilizada para calcular o valor individual da gorjeta é baseada na seguinte operação:

```text
(valor da conta × percentual da gorjeta) ÷ quantidade de pessoas
```

### Exemplo

Para uma conta de **R$ 100,00**, com gorjeta de **20%**, dividida entre **2 pessoas**:

```text
(100 × 20%) ÷ 2

20 ÷ 2

= R$ 10,00 por pessoa
```

---

## 📂 Estrutura do projeto

```text
Calculadora-de-Gorjetas/
│
├── index.html
├── styles.css
├── scripts.js
└── README.md
```

### `index.html`

Responsável pela estrutura da aplicação e pelo formulário de entrada dos dados.

### `styles.css`

Responsável pela aparência e estilização da interface.

### `scripts.js`

Contém a lógica responsável pelo processamento dos dados e pelo cálculo da gorjeta.

---

## 💻 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Soullwoolf/Calculadora-de-Gorjetas.git
```

### 2. Acesse a pasta

```bash
cd Calculadora-de-Gorjetas
```

### 3. Execute a aplicação

Abra o arquivo:

```text
index.html
```

em um navegador.

Não é necessário instalar dependências ou configurar um servidor para executar a aplicação.

---

## 🎯 Objetivo

O objetivo deste projeto foi transformar conhecimentos teóricos de **HTML, CSS e JavaScript** em uma aplicação funcional.

Além da construção da interface, o projeto permitiu praticar conceitos importantes relacionados à interação com o usuário e ao processamento de informações diretamente no navegador.

A aplicação também representa uma etapa da minha evolução no desenvolvimento web e serve como base para projetos futuros com maior complexidade.

---

## 🔎 O que este projeto demonstra

Este projeto demonstra minha capacidade de trabalhar com os fundamentos do desenvolvimento front-end, desde a construção da interface até a implementação da lógica necessária para tornar a aplicação interativa.

Entre os principais pontos praticados estão:

**Interface →** construção e estilização de uma aplicação web.

**Interação →** captura das informações fornecidas pelo usuário.

**Lógica →** processamento dos valores e cálculo da gorjeta.

**DOM →** atualização dos elementos da página de acordo com os dados informados.

**Organização →** separação da estrutura, estilo e lógica em arquivos distintos.

---

## 🔮 Possíveis melhorias

Algumas melhorias podem ser implementadas em versões futuras:

* [ ] Melhorar a validação dos campos
* [ ] Aprimorar a experiência em dispositivos móveis
* [ ] Adicionar formatação monetária aos valores
* [ ] Adicionar uma opção de tema claro/escuro
* [ ] Criar animações e microinterações
* [ ] Melhorar a acessibilidade da aplicação
* [ ] Adicionar uma opção para calcular também o valor total da conta por pessoa
* [ ] Publicar uma versão online da aplicação

---

## 📚 Aprendizado

Este projeto foi uma oportunidade para praticar o desenvolvimento de uma aplicação completa utilizando tecnologias fundamentais do front-end.

A construção da calculadora permitiu compreender melhor como **HTML, CSS e JavaScript trabalham em conjunto**, desde a criação da interface até o processamento dos dados e atualização das informações apresentadas ao usuário.

Projetos como este fazem parte do meu processo contínuo de aprendizado e evolução na área de desenvolvimento de software.

---

## 👨‍💻 Autor

**Soullwoolf**

Desenvolvedor em formação, estudando e desenvolvendo projetos práticos para aprimorar conhecimentos em programação e desenvolvimento de software.

---

⭐ **Se você gostou do projeto, considere deixar uma estrela no repositório!**

