💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻
# Calculadora de Consumo Elétrico

# ⚡ Calculadora de Consumo Elétrico

👩‍💻Oiêê! Este projeto é uma calculadora simples que estima o **consumo mensal de energia elétrica** de um aparelho, usando sua potência em watts e o tempo médio de uso diário.

---

## ✅ Objetivo
Ajudar o usuário a descobrir:
- Quanto um aparelho gasta por mês (em kWh)
- Quanto esse consumo custa por mês (estimando R$ 0,75 por kWh)

---

## ✅ Fórmula utilizada

O consumo mensal é calculado assim:
consumo_mensal = (potência * horas_por_dia * 30) / 1000

---

## ▶️ Como executar o programa

1. Abra a pasta do projeto no terminal.
2. Execute
3. Informe:
- Nome do aparelho  
- Potência em watts (W)  
- Horas de uso por dia  

---

## ✅ Código do Projeto

```python
print("=== Calculadora de Consumo Elétrico ===")

aparelho = input("Nome do aparelho: ")
potencia = float(input("Potência do aparelho (em watts): "))
horas_dia = float(input("Horas de uso diário: "))

consumo_mensal = (potencia * horas_dia * 30) / 1000  # kWh/mês
custo_kwh = 0.75
custo_estimado = consumo_mensal * custo_kwh

print("\n--- Resultado ---")
print(f"Aparelho: {aparelho}")
print(f"Consumo estimado: {consumo_mensal:.2f} kWh/mês")
print(f"Custo estimado: R$ {custo_estimado:.2f}/mês")


Obrigada por ler até aqui! Até a próxima!
💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻💻
