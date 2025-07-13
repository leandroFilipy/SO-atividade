# 🖥️ Sistemas Operacionais – Questionário Teórico

Este repositório contém um trabalho teórico desenvolvido por **Leandro Filipy de Lima**, com foco nos conceitos fundamentais de **sistemas operacionais**, incluindo temas como monoprogramação, multiprogramação, sistemas em tempo real, multiprocessamento e sistemas distribuídos.

> 📅 Data: 19/03/2025  
> 🏫 Curso: Técnico em Desenvolvimento de Sistemas – SENAI Jaraguá do Sul

---

## ✍️ Parte 1 – Questões Objetivas

1. **Qual das alternativas abaixo descreve corretamente um sistema monoprogramável/monotarefa?**  
   ✅ **b) Executa apenas uma tarefa por vez, dedicando todos os recursos do sistema a ela.**

2. **Qual é a principal desvantagem dos sistemas monoprogramáveis?**  
   ✅ **b) Subutilização dos recursos computacionais.**

3. **Os sistemas multiprogramáveis/multitarefa têm como principal vantagem:**  
   ✅ **a) Redução de custos devido ao compartilhamento de recursos.**

4. **Qual das características abaixo NÃO se aplica a sistemas operacionais em lote (batch)?**  
   ✅ **c) É ideal para aplicações que exigem respostas em tempo real.**

5. **No modelo de tempo compartilhado (time sharing), o que define a distribuição de tempo entre os processos?**  
   ✅ **c) Fatiamento do tempo do processador em pequenas porções (time-slice).**

6. **Qual dos seguintes sistemas é considerado tempo real crítico (Hard Real-Time)?**  
   ✅ **a) Controle de tráfego aéreo.**

7. **A principal diferença entre sistemas multiprocessados fortemente acoplados e fracamente acoplados é:**  
   ✅ **a) Os fortemente acoplados compartilham memória e recursos, enquanto os fracamente acoplados são independentes.**

8. **Um sistema operacional distribuído permite:**  
   ✅ **a) Executar um mesmo programa em vários processadores simultaneamente.**

9. **O que caracteriza um sistema NUMA (Non-Uniform Memory Access)?**  
   ✅ **b) A memória é distribuída e o tempo de acesso varia conforme a localização física.**

10. **Qual das seguintes vantagens NÃO é um benefício dos sistemas operacionais distribuídos?**  
   ✅ **d) Maior custo operacional.**

---

## 🧠 Parte 2 – Questões Discursivas

### 🟢 Diferença entre sistemas monoprogramáveis e multiprogramáveis

Sistemas **monoprogramáveis** dedicam todos os recursos para **executar uma única função**, enquanto sistemas **multiprogramáveis** permitem que **vários usuários acessem simultaneamente**, compartilhando os recursos entre diversas aplicações.

---

### 🟢 Tipos de sistemas de tempo real e exemplos

- **Soft Real-Time**: falhas são toleradas.  
  _Exemplo:_ Reconhecimento de digital em celular.

- **Firm Real-Time**: falhas afetam o desempenho, mas não causam danos críticos.  
  _Exemplo:_ Sistema automatizado de pizzaria.

- **Hard Real-Time**: falhas são inaceitáveis e podem causar tragédias.  
  _Exemplo:_ Sistema de controle de semáforos.

---

### 🟢 Sistemas multiprocessados: fortemente vs fracamente acoplados

| Tipo                      | Descrição                                                                 | Vantagem                        | Desvantagem                              |
|---------------------------|--------------------------------------------------------------------------|----------------------------------|------------------------------------------|
| Fortemente Acoplado       | Múltiplos processadores compartilham a mesma memória                    | Alta velocidade e desempenho     | Dificuldade de reaproveitamento de módulos |
| Fracamente Acoplado       | Sistemas independentes conectados por rede                             | Escalabilidade e flexibilidade   | Maior sobrecarga de rede                  |

---

### 🟢 Sistema operacional de rede vs. distribuído

- **Sistema Operacional de Rede**: Compartilha recursos como impressoras ou arquivos.  
  _Exemplo:_ Impressora compartilhada em uma rede local.

- **Sistema Operacional Distribuído**: Divide tarefas entre múltiplos hosts.  
  _Exemplo:_ Banco de dados distribuído que espalha consultas entre servidores.

---

### 🟢 Melhor sistema para laboratório de testes

O estudante deve optar por um **Sistema Operacional de Múltiplos Processadores**, pois ele deseja executar **múltiplas aplicações ao mesmo tempo** com **eficiência no compartilhamento de recursos**, e esse tipo de sistema é ideal por **suportar várias UCPs simultaneamente**.

---

## 👨‍💻 Autor

- **Leandro Filipy de Lima**

---

## 📝 Licença

Este material é de uso educacional, podendo ser utilizado como referência em estudos sobre sistemas operacionais, desde que sejam mantidos os devidos créditos ao autor.

> *"Conhecimento em sistemas operacionais é a base para compreender a lógica por trás de toda execução digital."* 🚀
