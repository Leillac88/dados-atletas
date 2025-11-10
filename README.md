# 🏅 Projeto DEVStart – Cálculo de Categoria, IMC e Média de Atletas

> **Continuação do projeto anterior (“Notas dos Atletas”)**, agora utilizando o poder da **Programação Orientada a Objetos (POO)** com **JavaScript**.  
> Este projeto faz parte da trilha **DEVStart – Certificação de Lógica de Programação**.

---

## 🧠 **Resumo do Projeto**

O desafio consiste em criar uma aplicação capaz de **receber informações de um atleta**, **calcular parâmetros importantes** (como categoria, IMC e média de notas) e **exibir os resultados** para o usuário de forma clara e estruturada.

Essa aplicação dá continuidade à avaliação da competição de ginástica artística, agora com um **modelo orientado a objetos**, aprimorando a legibilidade, a reutilização e a manutenção do código.

---

## 🏋️‍♂️ **Introdução**

Os organizadores da competição realizada no projeto anterior gostaram tanto da sua solução que resolveram expandi-la!  
Agora, o objetivo é desenvolver um **software completo** em JavaScript, utilizando **classes e métodos**, para processar dados dos atletas de forma dinâmica.

O sistema deve receber:

- Nome do atleta  
- Idade  
- Peso  
- Altura  
- Notas (cinco notas dos jurados)

E retornar:

- Categoria do atleta  
- IMC  
- Média válida (desconsiderando a maior e menor nota)

---

## ⚙️ **Especificações Técnicas**

### 🧩 Classe `Atleta`

A classe `Atleta` concentra os **atributos** e **métodos** relacionados a cada participante.

#### **Atributos**
- `nome`
- `idade`
- `peso`
- `altura`
- `notas`

#### **Métodos**
| Método | Descrição |
|--------|------------|
| `calculaCategoria()` | Retorna a categoria do atleta de acordo com a idade |
| `calculaIMC()` | Calcula o IMC usando a fórmula `peso / (altura²)` |
| `calculaMediaValida()` | Calcula a média das notas, desconsiderando a maior e menor |
| `obtemNomeAtleta()` | Retorna o nome do atleta |
| `obtemIdadeAtleta()` | Retorna a idade do atleta |
| `obtemPesoAtleta()` | Retorna o peso do atleta |
| `obtemAlturaAtleta()` | Retorna a altura do atleta |
| `obtemNotasAtleta()` | Retorna as notas do atleta |
| `obtemCategoria()` | Retorna a categoria (com base em `calculaCategoria()`) |
| `obtemIMC()` | Retorna o IMC calculado |
| `obtemMediaValida()` | Retorna a média calculada |

---

## 🧮 **Regras de Cálculo**

### 🏆 Categoria
| Faixa Etária | Categoria |
|---------------|------------|
| 9 a 11 anos | Infantil |
| 12 a 13 anos | Juvenil |
| 14 a 15 anos | Intermediário |
| 16 a 30 anos | Adulto |
| Demais idades | Sem categoria |

### ⚖️ IMC
> Fórmula:  
> `IMC = peso / (altura * altura)`

### 🧾 Média Válida
> Desconsidera a **maior** e a **menor** nota, calculando a média das **três notas centrais**.

---

## 🧰 **Tecnologias Utilizadas**

- JavaScript (ES6+)
- Node.js (para execução local, se desejar)
- Console do navegador ou terminal

---

## 🌟 **Aprendizados**

- Estruturação de classes e métodos em JavaScript
- Encapsulamento e reutilização de lógica
- Manipulação de arrays e métodos (sort, slice, reduce)
- Cálculos matemáticos aplicados ao contexto real

---

## 💬 **Autora**

- Leilla Carvalho<br>
- 💻 Estudante Full Stack | 🚀 DEVStart<br>
- 📚 Em constante aprendizado e evolução no mundo da tecnologia!