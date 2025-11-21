# coreAI-edge
# 📊 Calculadora de Chance de Vaga — ESP32

Este projeto foi criado com o objetivo de ajudar estudantes e candidatos a entenderem suas chances médias de conseguir uma vaga de emprego ou estágio. A ideia surgiu da necessidade de visualizar, de forma simples, a relação entre o número de vagas disponíveis e o número de pessoas que já se candidataram.

---

## ⚙️ Como funciona

O sistema pede dois dados via Serial Monitor:
- Quantas vagas estão disponíveis
- Quantas pessoas já aplicaram

Com base nisso, ele calcula a chance média de sucesso usando a fórmula:


O resultado é exibido no Serial Monitor e limitado a no máximo 100%.

---

## 🧩 Componentes usados

- ESP32 (simulado no Wokwi)
- Serial Monitor para entrada e saída de dados
- Ambiente de simulação: [Wokwi](https://wokwi.com/projects/447875983340936193)

---

## 🛠️ Funções principais

- `setup()` → inicia a comunicação serial e exibe instruções
- `loop()` → recebe os dados do usuário, calcula a chance e mostra o resultado
- Validação simples para evitar divisão por zero

---

##Link Do Video
https://youtu.be/LPdclPwDDSA

---
<div align="center">

**Feito por:**

- Tomomé — RM: 562422  
- Leonardo Eiji Kina — RM: 562784  
- Nicholas Braga de Souza — RM: 561733  

</div>
