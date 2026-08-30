# 🎂 Calculadora de Idade com Interface Gráfica

Uma calculadora de idade visual e interativa desenvolvida em Python com Tkinter e bibliotecas auxiliares para manipulação de datas. Permite calcular a diferença entre duas datas (por exemplo, data atual e data de nascimento) e exibe o resultado em anos, meses e dias.

![Tela da calculadora](screenshot.png)
*(Adicione um print da aplicação como "screenshot.png" na pasta do projeto.)*

---

## 🖥️ Sobre o projeto

Esta aplicação gráfica (GUI) foi criada para facilitar o cálculo de idade ou intervalo de tempo entre duas datas. Diferente de uma calculadora comum, ela oferece:

- **Seleção de datas** através de um calendário visual (widget `DateEntry` do `tkcalendar`).
- **Cálculo preciso** da diferença em anos, meses e dias usando a biblioteca `dateutil.relativedelta`.
- **Interface limpa e colorida**, com destaque para o resultado principal.
- **Botão "Calcular"** que atualiza instantaneamente os valores na tela.

---

## ✨ Funcionalidades

- **Data inicial**: permite escolher uma data de referência (ex.: data atual, data de um evento).
- **Data de nascimento**: data a ser comparada com a data inicial.
- **Exibição do resultado**: mostra separadamente a diferença em:
  - Anos
  - Meses
  - Dias
- **Cálculo instantâneo**: ao clicar no botão "Calcular", os valores são atualizados automaticamente.
- **Calendário embutido**: facilita a seleção de datas sem digitar manualmente.

---

## 🛠️ Tecnologias utilizadas

- **Python 3** – Linguagem principal.
- **Tkinter** – Biblioteca padrão para criação da interface gráfica.
- **tkcalendar** – Fornece o widget `DateEntry` para seleção de datas (calendário).
- **dateutil.relativedelta** – Calcula a diferença entre datas em anos, meses e dias de forma precisa.
- **datetime** – Manipulação básica de datas.
