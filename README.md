# 🧮 Calculadora de IMC (Índice de Massa Corporal)

Este projeto é uma **Calculadora de IMC** desenvolvida com o objetivo de praticar conceitos fundamentais de **HTML**, **TAILWIND** e **JavaScript**.  
A aplicação permite que o usuário informe sua altura e peso, e receba automaticamente seu IMC e sua classificação de acordo com a tabela oficial da OMS.

---

## 🎯 Objetivo do Projeto

Este projeto foi criado para fins **educacionais**, aplicando:
- Manipulação da DOM com JavaScript  
- Estruturação de páginas com HTML  
- Estilização com TAILWIND  
- Lógica básica de cálculo e validação  

É ideal para iniciantes que desejam reforçar conceitos de frontend e cálculos simples.

---

## 🚀 Funcionalidades

- Entrada de **peso** (kg)  
- Entrada de **altura** (m ou cm, dependendo da implementação)  
- Cálculo automático do IMC  
- Exibição da **classificação** do usuário:  
  - Abaixo do peso  
  - Peso normal  
  - Sobrepeso  
  - Obesidade  
- Interface simples e intuitiva  

---

## 🧠 Tecnologias Utilizadas

- **HTML5** – estrutura da página  
- **TAILWIND** – layout e estilos  
- **JavaScript** – lógica do cálculo e interação  

---

## 📂 Estrutura de Pastas

```plaintext
📦 calculadora-imc
 ┣ 📁 images
 ┃ ┗ fitness-tracker-animate.svg
 ┣ 📄 script.js
 ┣ 📄 index.html
 ┗ 📄 README.md
```

---

## 🔧 Como Usar o Projeto

1. Clone ou baixe o repositório
````
git clone https://github.com/jorgerenan94-web/calculadora-imc.git
````
2. Acesse a pasta
````
cd calculadora-imc
````
3. Execute a aplicação
   Abra o arquivo index.html diretamente no navegador
   ou use extensões como Live Server no VS Code.

4. Utilize a calculadora
- Digite seu peso em kg

- Digite sua altura

- Clique em Calcular

- Veja instantaneamente seu IMC e classificação

---

## 🔢 Fórmula Utilizada

A fórmula oficial para o cálculo do IMC é:
````
IMC = peso (kg) / altura² (m)
````
Exemplo:
uma pessoa de 70 kg e 1.75 m:
IMC = 70 / (1.75 * 1.75) = 22.86

---

## 📊 Tabela de Classificação (OMS)

| IMC            | Classificação      |
| -------------- | ------------------ |
| Menor que 18.5 | Abaixo do peso     |
| 18.5 — 24.9    | Peso normal        |
| 25.0 — 29.9    | Sobrepeso          |
| Acima de 30.0  | Obesidade          |

---

## 🧑‍💻 Autor

Jorge Renan

Estudante de Desenvolvimento Full Stack

Projeto simples para estudo de lógica e frontend.

## 🪪 Licença

Este projeto é livre para uso acadêmico e estudos.
Sinta-se à vontade para modificar, melhorar e utilizar em seu portfólio!
