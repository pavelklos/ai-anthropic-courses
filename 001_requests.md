# Building with the Claude API

## Making a request

**What is quantum computing? Answer in one sentence (answer in english and czech language)**

**English:** Quantum computing is a revolutionary computing paradigm that uses quantum mechanical phenomena like superposition and entanglement to process information in quantum bits (qubits), potentially solving certain complex problems exponentially faster than classical computers.

**Czech:** Kvantové počítačství je revoluční počítačový paradigma, které využívá kvantově mechanické jevy jako superpozici a provázanost k zpracování informací v kvantových bitech (qubitech), což může potenciálně řešit určité složité problémy exponenciálně rychleji než klasické počítače.



## Multi-Turn conversations

```json
[
  {
    "role": "user",
    "content": "Define quantum computing in one sentence"
  },
  {
    "role": "assistant",
    "content": "Quantum computing is a revolutionary computing paradigm that harnesses quantum mechanical phenomena like superposition and entanglement to process information in ways that can potentially solve certain complex problems exponentially faster than classical computers."
  },
  {
    "role": "user",
    "content": "Write another sentence"
  },
  {
    "role": "assistant",
    "content": "Quantum computers use quantum bits (qubits) that can exist in multiple states simultaneously, unlike classical bits that are either 0 or 1, enabling them to perform many calculations in parallel."
  }
]
```