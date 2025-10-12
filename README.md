<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&center=true&width=800&lines=🤖+Raspberry+Pi+RP2040+—+Projeto+Braço+Robótico;Aprendizado+Real+com+Hardware+em+C+Bare-Metal+💡" alt="🧬 PROJETO BRAÇO ROBÓTICO C BARE-METAL" /> <br>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Raspberry%20Pi⚡-Hardware-green?style=for-the-badge&logo=raspberry-pi" />
  <img src="https://img.shields.io/badge/C-Embarcado-orange?style=for-the-badge&logo=c" />
  <img src="https://img.shields.io/badge/Autodidata📚-Em%20progresso-brightgreen?style=for-the-badge" />
</p>

<img width="700" height="750" alt="image" src="https://github.com/user-attachments/assets/79e7332b-fc66-439e-ad1b-e0ab91b236bb"/>

---

## 🔧 Sobre o Projeto

Este repositório documenta o desenvolvimento completo de um **braço robótico**, utilizando a placa **Raspberry Pi RP2040** (ou STM32/Arduino em outros exemplos) com **C bare-metal**.  
O projeto inclui controle direto de servomotores, alimentação estável e integração com sensores para movimentos precisos e confiáveis, **sem usar HALs ou frameworks de alto nível**.  

O diferencial deste projeto é que todo o firmware será desenvolvido **diretamente em C**, manipulando registradores e periféricos, para ter **controle total do hardware**.

---

## 🎯 Objetivos

- Aprender programação embarcada **bare-metal em C** no RP2040  
- Controlar múltiplos servomotores de forma precisa e direta  
- Projetar e montar o próprio circuito de alimentação e controle  
- Manipular GPIO, PWM, I2C, UART e timers diretamente via registradores  
- Criar um projeto modular e escalável para automação  
- Documentar todo o processo para aprendizado e referência futura  

---

## 🛠️ Ferramentas e Bibliotecas

> Ferramentas utilizadas ao longo do projeto com foco em **C bare-metal**:

- `gcc-arm-none-eabi` – Compilador C para ARM Cortex-M  
- `make` / `CMake` – Sistema de build  
- `openocd` ou `probe-rs` – Debug e flash direto no microcontrolador  
- `st-flash` / `picotool` – Programação e teste em hardware  
- `stdint.h`, `stdbool.h` – Tipos padrão para C embarcado  
- `CMSIS` (opcional) – Cabeçalhos e definições para ARM Cortex  

---

## 🧩 Componentes Utilizados

| Componente | Descrição |
|-----------|-----------|
| 🔌 **Placa** | Raspberry Pi RP2040 / STM32 / Arduino (bare-metal) |
| ⚙️ **Estrutura** | Braço robótico com múltiplas articulações |
| 🧠 **MCU** | RP2040 dual-core a 133 MHz ou STM32F103 / STM32F303 |
| ⚡ **Fonte de alimentação** | Fonte regulada 5V |
| 🛠 **Circuito** | PCB customizada para distribuição de energia e controle |
| 🎯 **Servos** | Servomotores padrão e de alto torque |
| 🔋 **Alimentação** | Circuito regulado a partir da fonte chaveada |

---

## 📦 Estrutura do Projeto

```bash
