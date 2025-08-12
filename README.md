<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&center=true&width=800&lines=🤖+STM32F303RE+com+Rust+—+Projeto+Braço+Robótico;Aprendizado+Real+com+Hardware+Real!+💡" alt="PROJETO BRAÇO ROBÓTICO" /> <br>
</h1>

<img width="45" height="2051" alt="Rust Logo" src="https://github.com/user-attachments/assets/fce28b01-dcc8-4f22-acb8-8cdffb4b9799" />

<p align="center">
  <img src="https://img.shields.io/badge/STM32⚡-Hardware-blue?style=for-the-badge&logo=stmicroelectronics" />
  <img src="https://img.shields.io/badge/Rust🦀-Embarcado-orange?style=for-the-badge&logo=rust" />
  <img src="https://img.shields.io/badge/Autodidata📚-Em%20progresso-brightgreen?style=for-the-badge" />
</p>


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
![braço robotico, placa stm32f303re e fonte chaveada 12w](link_da_foto_360)
<img width="700" height="800" alt="image" src="https://github.com/user-attachments/assets/ffd503f8-5859-45bb-b4af-83e7d589e5a3" />


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
