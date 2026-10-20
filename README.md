# triagem-hospitalar-e-hash-estados
projeto universitário com implementação de lista encadeada com prioridade para triagem hospitalar
# 🏥 Atividade Prática - Estrutura de Dados / Programação III
**UNINTER - 2026 | Prof. Me. Bruno Kostiuk**

## 👤 Aluno
**Giliard Gomes Martins - RU: 4410793**

---

### 📌 Questão 1 de 2 - Lista Encadeada com Prioridade
**Sistema de Triagem Hospitalar**

Regras implementadas:
- Pacientes com cartão **Amarelo (A)** têm prioridade sobre Verde (V)
- Numeração: **Verdes iniciam em 1** e **Amarelos em 201**
- Lista Encadeada Simples, não circular
- Funções exigidas:
    - `inserirSemPrioridade(nodo)` -> insere no final
    - `inserirComPrioridade(nodo)` -> insere após todos os "A" e antes dos "V"
    - `inserir()` -> cria o nodo automaticamente
    - `imprimirListaEspera()` 
    - `atenderPaciente()`
    - `menu()` -> opções 1-Adicionar, 2-Mostrar, 3-Chamar, 4-Sair

**Teste exigido:** Inserir 3x V, 2x A, 2x V, 3x A nessa ordem + imprimir lista + atender 2 pacientes.

### 📌 Questão 2 de 2 - Tabela Hash com Listas Encadeadas
**Cadastro de Estados Brasileiros**

Regras implementadas:
- Tabela Hash com **10 posições** (0 a 9)
- Cada posição é uma Lista Encadeada
- Função Hash: `(ASCII1 + ASCII2) MOD 10`
- **Exceção: DF retorna sempre 7**
- Inserção no **início** da lista
- Inserção dos 27 estados + **estado fictício GM - Giliard Martins**

**Teste exigido:**
1. Impressão da tabela vazia
2. Impressão com 27 estados
3. Impressão com estado fictício GM

---

## 🛠️ Tecnologias
- Python 3.x

## ▶️ Como executar
```bash
# Questão 1
python triagem_hospitalar.py

# Questão 2
python cadastro_estados.py
