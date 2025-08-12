<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&center=true&width=800&lines=🤖+STM32F303RE+com+Rust+—+Projeto+Braço+Robótico;Aprendizado+Real+com+Hardware+Real!+💡" alt="🧬 PROJETO BRAÇO ROBÓTICO " /> <br>
</h1>

<img width="75" height="307" alt="rustacean-orig-noshadow" src="https://github.com/user-attachments/assets/983e4913-db56-482a-8daa-5559680ecda8" />

<p align="center">
 <img src="https://img.shields.io/badge/STM32⚡-Hardware-blue?style=for-the-badge&logo=stmicroelectronics" />
  <img src="https://img.shields.io/badge/Rust🦀-Embarcado-orange?style=for-the-badge&logo=rust" />
  <img src="https://img.shields.io/badge/Autodidata📚-Em%20progresso-brightgreen?style=for-the-badge" />
</p>


<img width="700" height="750" alt="image" src="https://github.com/user-attachments/assets/79e7332b-fc66-439e-ad1b-e0ab91b236bb"/>

---

## 🔧 Sobre o Projeto

Este repositório documenta o desenvolvimento completo de um **braço robótico**, utilizando a placa **STM32F303RE**, uma **fonte chaveada** para alimentação estável e um circuito dedicado para controle dos servomotores.

O diferencial deste projeto é que todo o firmware será desenvolvido **em Rust**, explorando ao máximo os recursos de baixo nível e segurança da linguagem, além de integrar com a HAL (Hardware Abstraction Layer) para ARM.

---

## 🎯 Objetivos

- Aprender programação embarcada com **Rust** em ARM Cortex-M4
- Controlar múltiplos servomotores de forma precisa e segura
- Projetar e montar o próprio circuito de alimentação e controle
- Integrar Rust com **periféricos STM32** (PWM, GPIO, timers)
- Criar um projeto modular e escalável para automação
- Documentar todo o processo para aprendizado e referência futura

---

## 🛠️ Ferramentas e Bibliotecas

> Ferramentas utilizadas ao longo do projeto com foco em Rust embarcado:

- `rustup` – Gerenciador de toolchains Rust
- `cargo` – Build system e gerenciador de pacotes Rust
- `probe-rs` – Ferramenta para flash e debug direto no MCU
- `cortex-m` / `cortex-m-rt` – Suporte para ARM Cortex-M
- `stm32f3xx-hal` – HAL para STM32F303
- `RTIC` *(planejado)* – Framework para sistemas embarcados concorrentes

---

## 🧩 Componentes Utilizados

| Componente | Descrição |
|-----------|-----------|
| 🔌 **Placa** | STM32F303RE (ARM Cortex-M4) |
| ⚙️ **Estrutura** | Braço robótico com múltiplas articulações |
| 🧠 **MCU** | ARM Cortex-M4 a 72 MHz |
| ⚡ **Fonte de alimentação** | Fonte chaveada 5V/10A |
| 🛠 **Circuito** | PCB customizada para distribuição de energia e controle |
| 🎯 **Servos** | Servomotores padrão e de alto torque |
| 🔋 **Alimentação** | Circuito regulado a partir da fonte chaveada |

---
# placa: STM32F303RE
<img width="500" height="550" alt="image" src="https://github.com/user-attachments/assets/1cb1ef4e-c55c-4a92-b427-2e2799f0c44d" />


## 📦 Estrutura do Projeto

```bash
braco-robotico-rust/
├── firmware/
│   ├── src/
│   │   ├── main.rs
│   │   ├── servo.rs
│   │   ├── control.rs
│   │   ├── power.rs
│   ├── Cargo.toml
├── hardware/
│   ├── stm32f303re.jpg
│   ├── fonte-chaveada.jpg
│   ├── circuito-pcb.jpg
├── assets/
│   ├── braco-robotico-360.mp4
│   ├── braco-robotico-fotos/
├── README.md
