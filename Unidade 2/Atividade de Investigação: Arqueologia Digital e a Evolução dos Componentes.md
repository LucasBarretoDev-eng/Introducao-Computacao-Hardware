# Atividade de Investigação: Arqueologia Digital e a Evolução dos Componentes

## 🏛️ O Supercomputador Cray-1

O **Cray-1**, projetado por Seymour Cray na empresa *Cray Research*, foi um marco na computação, utilizando uma **arquitetura vetorial** para alcançar alto desempenho para a sua época.

### 1. Processamento ⚙️
O sistema operava com **pipeline**, permitindo processar vetores de dados de forma contínua. Após o pipeline estar cheio, o computador gerava aproximadamente um resultado por ciclo. Ele era composto por unidades funcionais especializadas:

* **Unidade de soma**
* **Unidade de multiplicação**
* **Unidade lógica**
* **Unidade de deslocamento**
* **Unidade de ponto flutuante**

**Funções principais:**
- Buscar e decodificar instruções.
- Enviar cada operação para a unidade funcional correta.
- Controlar dependências entre instruções para permitir execução paralela eficiente.

---

### 2. Armazenamento 💾
O sistema de armazenamento foi projetado para suportar a velocidade do processamento vetorial.

* **Memória Principal:**
    * Tipo: SRAM bipolar.
    * Capacidade: ~1 milhão de palavras de 64 bits (Aproximadamente **8 MB**).
* **Registradores:**
    * 8 registradores escalares (64 bits).
    * 8 registradores de endereço (24 bits).
    * 8 registradores vetoriais (cada um com 64 elementos de 64 bits).

---

### 3. Interface (Entrada e Saída) 🔌
O Cray-1 não operava sozinho; ele era conectado a sistemas *front-end* que gerenciavam os dados.

| Tipo | Dispositivos |
| :--- | :--- |
| **Entrada** | Leitor de cartões perfurados, Unidades de fita magnética, Terminais (teclado). |
| **Saída** | Impressoras de alta velocidade, Unidades de fita, Monitores (logs), Plotters (gráficos). |

---

### 4. Comparação Histórica: Cray-1 vs. iPhone 15 Pro 📱

Esta comparação demonstra o salto tecnológico em quase 50 anos:

| Característica | Cray-1 (1976) | iPhone 15 Pro (Hoje) |
| :--- | :--- | :--- |
| **Desempenho** | 160 MFLOPS | ~35 TFLOPS (GPU) |
| **Memória RAM** | 8 MB | 8 GB |
| **Tamanho** | Quase uma sala inteira | Bolso da calça |
| **Público** | Cientistas e Centros de Pesquisa | Uso Pessoal/Global |

---

## 🏁 Conclusão

O Cray-1 representa o ápice da engenharia dos anos 70. A transição de uma máquina que ocupava salas e processava megabytes para dispositivos de bolso que processam terabytes de operações por segundo evidencia a velocidade da **Lei de Moore** e a evolução da arquitetura de computadores.

---
*Documento gerado para fins de estudo em Arqueologia Digital.*
