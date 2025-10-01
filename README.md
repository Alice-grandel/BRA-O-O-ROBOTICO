<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&center=true&width=800&lines=🤖+Raspberry+Pi+RP2040+—+Projeto+Braço+Robótico;Aprendizado+Real+com+Hardware+Real+em+Rust!+💡" alt="🧬 PROJETO BRAÇO ROBÓTICO RUST" /> <br>
</h1>


<p align="center">
  <img src="https://img.shields.io/badge/Raspberry%20Pi⚡-Hardware-green?style=for-the-badge&logo=raspberry-pi" />
  <img src="https://img.shields.io/badge/Rust-Embarcado-orange?style=for-the-badge&logo=rust" />
  <img src="https://img.shields.io/badge/Autodidata📚-Em%20progresso-brightgreen?style=for-the-badge" />
</p>

<img width="700" height="750" alt="image" src="https://github.com/user-attachments/assets/79e7332b-fc66-439e-ad1b-e0ab91b236bb"/>

---

## 🔧 Sobre o Projeto

Este repositório documenta o desenvolvimento completo de um **braço robótico**, utilizando a placa **Raspberry Pi RP2040** com **Rust**.  
O projeto inclui controle de servomotores, alimentação estável e integração com sensores para movimentos precisos e confiáveis.

O diferencial deste projeto é que todo o firmware será desenvolvido **em Rust**, explorando os recursos de segurança de memória, modularidade, performance e controle de baixo nível para sistemas embarcados.

---

## 🎯 Objetivos

- Aprender programação embarcada com **Rust** no RP2040  
- Controlar múltiplos servomotores de forma precisa e segura  
- Projetar e montar o próprio circuito de alimentação e controle  
- Integrar **Rust** com periféricos do RP2040 (GPIO, PWM, I2C, UART)  
- Criar um projeto modular e escalável para automação  
- Documentar todo o processo para aprendizado e referência futura  

---

## 🛠️ Ferramentas e Bibliotecas

> Ferramentas utilizadas ao longo do projeto com foco em **Rust embarcado**:

- `cargo` – Gerenciador de pacotes e build system do Rust  
- `probe-rs` – Debug e flash direto em microcontroladores  
- `defmt` – Logging otimizado para sistemas embarcados  
- `rp-hal` – Hardware Abstraction Layer (HAL) para RP2040 em Rust  
- `embedded-hal` – Interface padronizada para drivers embarcados  
- `cross` *(opcional)* – Compilação cruzada simplificada  

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
braco-robotico-rust/
├── src/
│   ├── main.rs        <- ponto de entrada do braço robótico
│   ├── servo.rs       <- controle dos servos (PWM)
│   ├── control.rs     <- lógica de controle do braço
│   ├── power.rs       <- gerenciamento de alimentação
│   ├── utils.rs       <- funções auxiliares (logging, delays)
│   └── config.rs      <- configurações globais do sistema
│
├── hardware/
│   ├── rp2040.jpg
│   ├── fonte-chaveada.jpg
│   ├── circuito-pcb.jpg
│
├── assets/
│   ├── braco-robotico-360.mp4
│   ├── braco-robotico-fotos/
│
├── build/
│   ├── Makefile        <- comandos úteis (cargo build/run flash)
│   └── cross.toml      <- config de compilação cruzada (se usar `cross`)
│
├── docs/
│   ├── architecture.md
│   ├── setup_rp2040.md
│   └── drivers.md
│
├── Cargo.toml          <- manifesto do Rust (deps, metadata do projeto)
└── README.md           <- documentação do projeto

