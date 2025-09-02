<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&center=true&width=800&lines=🤖+Raspberry+Pi+RP2040+—+Projeto+Braço+Robótico;Aprendizado+Real+com+Hardware+Real+em+Ada!+💡" alt="🧬 PROJETO BRAÇO ROBÓTICO ADA" /> <br>
</h1>

<img width="75" height="307" alt="image" src="https://github.com/user-attachments/assets/a9275006-bef7-4d56-bfa1-877e5bc54f20" />

<p align="center">
  <img src="https://img.shields.io/badge/Raspberry%20Pi⚡-Hardware-green?style=for-the-badge&logo=raspberry-pi" />
  <img src="https://img.shields.io/badge/Ada🧬-Embarcado-blue?style=for-the-badge&logo=ada" />
  <img src="https://img.shields.io/badge/Autodidata📚-Em%20progresso-brightgreen?style=for-the-badge" />
</p>

<img width="700" height="750" alt="image" src="https://github.com/user-attachments/assets/79e7332b-fc66-439e-ad1b-e0ab91b236bb"/>

---

## 🔧 Sobre o Projeto

Este repositório documenta o desenvolvimento completo de um **braço robótico**, utilizando a placa **Raspberry Pi RP2040** com **Ada**.  
O projeto inclui controle de servomotores, alimentação estável e integração com sensores para movimentos precisos e confiáveis.

O diferencial deste projeto é que todo o firmware será desenvolvido **em Ada**, explorando os recursos de segurança e confiabilidade da linguagem para sistemas embarcados.

---

## 🎯 Objetivos

- Aprender programação embarcada com **Ada** em RP2040  
- Controlar múltiplos servomotores de forma precisa e segura  
- Projetar e montar o próprio circuito de alimentação e controle  
- Integrar Ada com **periféricos RP2040** (GPIO, PWM, I2C)  
- Criar um projeto modular e escalável para automação  
- Documentar todo o processo para aprendizado e referência futura

---

## 🛠️ Ferramentas e Bibliotecas

> Ferramentas utilizadas ao longo do projeto com foco em Ada embarcado:

- `GNAT` – Compilador Ada  
- `Ada.Text_IO` e `Ada.Integer_Text_IO` – Entrada e saída de dados  
- `RP2040 HAL` *(planejado)* – Integração com periféricos da placa  
- `Makefile` – Para automatizar builds e deploy  

---

## 🧩 Componentes Utilizados

| Componente | Descrição |
|-----------|-----------|
| 🔌 **Placa** | Raspberry Pi RP2040 |
| ⚙️ **Estrutura** | Braço robótico com múltiplas articulações |
| 🧠 **MCU** | RP2040 dual-core a 133 MHz |
| ⚡ **Fonte de alimentação** | Fonte regulada 5V |
| 🛠 **Circuito** | PCB customizada para distribuição de energia e controle |
| 🎯 **Servos** | Servomotores padrão e de alto torque |
| 🔋 **Alimentação** | Circuito regulado a partir da fonte chaveada |

---

## 📦 Estrutura do Projeto

```bash
braco-robotico-ada/
├── src/
│   ├── main.adb        <- ponto de entrada do braço robótico
│   ├── servo.adb       <- controle dos servos
│   ├── control.adb     <- lógica de controle do braço
│   ├── power.adb       <- gerenciamento de alimentação
├── hardware/
│   ├── rp2040.jpg
│   ├── fonte-chaveada.jpg
│   ├── circuito-pcb.jpg
├── assets/
│   ├── braco-robotico-360.mp4
│   ├── braco-robotico-fotos/
├── build/             <- scripts de compilação e Makefiles
└── README.md          <- documentação do projeto
