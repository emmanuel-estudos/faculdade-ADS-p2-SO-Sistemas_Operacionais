<style>
    /* Reiniciando a Contagem Geral */
    body {
        counter-reset: contadorh1 1 contadorLegenda 0;
    }

    /* Aplica o estilo para H1 e informa que a contagem de H2 deve começar do 0 sempre que um H1 aparecer */
    h1 {
        counter-reset: contadorh2;
        text-align: center;
    }

    h1::before {
        counter-increment: contadorh1;
    }

    /* Aplica o estilo para H2 e informa que a contagem de H3 deve começar do 0 sempre que um H2 aparecer */
    h2 {
        counter-reset: contadorh3;
    }

    h2::before {
        counter-increment: contadorh2;
        content: counter(contadorh2) ". ";
    }

    /* Aplica estilo para H3 */
    h3::before {
        counter-increment: contadorh3;
        content: counter(contadorh2) "." counter(contadorh3) ". ";
    }

    /* Legendas */
    .legenda::before {
    /* Incrementa o contador toda vez que a classe aparece */
    counter-increment: contadorLegenda;
    /* Define o texto automático */
    content: "Figura " counter(contadorLegenda) ": ";
    font-weight: bold;
}
</style>

# Sistemas Operacionais

> **Última sincronização:** 26/03/2026 22:46:04

## Sumário de Aulas

- Aula 00 - [Informações Gerais sobre Sistemas Operacionais](#informações-gerais-sobre-sistemas-operacionais)
- Aula 01 - [Introdução aos Sistemas Operacionais](#introdução-aos-sistemas-operacionais)

---

## Informações Gerais sobre Sistemas Operacionais

### Assuntos para a Primeira Prova

- [Aula 01 - Introdução aos Sistemas Operacionais](./aula_01-Introducao_aos_SOs.md)

---

## Introdução aos Sistemas Operacionais

### Tópicos

- [Introdução aos Sistemas Operacionais](#introdução-aos-sistemas-operacionais)
  - [Tópicos](#tópicos)
  - [Sistema Computacional](#sistema-computacional)
    - [Hardware vs Software](#hardware-vs-software)
    - [Etapas Funcionais](#etapas-funcionais)
    - [Entrada de Dados](#entrada-de-dados)
    - [Saída de Dados](#saída-de-dados)
    - [Entrada de Saída de Dados](#entrada-de-saída-de-dados)

### Sistema Computacional

#### Hardware vs Software

&emsp; **Hardware** é qualquer maquinário que dá suporte à entrada, ao processamento, ao armazenamento e às atividades de saída de um sistema informatizado.

&emsp; **Software** é a parte lógica usada no computador. São programas, você não consegue tocar neles, mas eles existem.

#### Etapas Funcionais

&emsp; Um computador trabalha obedecendo a um fluxo básico de procedimentos:

1. **Entrada de Dados**: Introduzem informações para o processamento
2. **Processamento de Dados**: Executa as instruções dos programas (softwares), que são formadas por ações (mover, somar, multiplicar, verificar, etc) e pelos dados (datas, valores, nomes, etc)
3. **Saída de Dados**: Apresenta ou armazena o resultado do processamento

#### Entrada de Dados

- Teclado
- Mouse
- Touchpad
- Webcam
- Microfone
- Leitor de Código de Barras
- Leitores Biométricas
- Scanner / Máquina Digitalizadora

#### Saída de Dados

- Monitor de Vídeo
- Impressora
- Caixa de Som

#### Entrada de Saída de Dados

&emsp; Alguns periféricos podem ser considerados de _entrada_ e _saída_ ao mesmo tempo. Por exemplo:

- Impressora Multifuncional
- Fones de ouvido com microfone
- Monitor Touchscreen

---

