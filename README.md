# 🦾 Controle de Servo Motor com Potenciômetro  

Este projeto controla um **servo motor** usando um **potenciômetro** com um **Arduino**.  
Ao girar o potenciômetro, o servo motor muda de ângulo proporcionalmente.

## 📜 Como Funciona?  
1. O código inicializa e posiciona o **servo motor** em um ângulo inicial.  
2. Ele faz um **teste**, lendo o valor do **potenciômetro** e convertendo-o para um **ângulo**.  
3. O servo entra no ciclo normal:
   - 🎛 **Potenciômetro no mínimo (0)** → Servo na posição **0°**.  
   - 🔄 **Meio do potenciômetro (~512)** → Servo na posição **90°**.  
   - 🎚 **Potenciômetro no máximo (1023)** → Servo na posição **179°**.  
   - O ciclo se repete continuamente.

![image](https://github.com/user-attachments/assets/1d707639-a07d-46b8-9213-5cc49c7e1c5e)


## 🔌 Esquema de Ligações  

| Componente       | Pino no Arduino |
|-----------------|----------------|
| Potenciômetro (VCC) | 5V |
| Potenciômetro (GND) | GND |
| Potenciômetro (Sinal) | A0 |
| Servo Motor (VCC) | 5V |
| Servo Motor (GND) | GND |
| Servo Motor (Sinal) | 9 |

---

## 🔗 Simulação no Tinkercad
[Acesse aqui a simulação do semáforo no Tinkercad](https://www.tinkercad.com/things/fcJlY2aZ3b1-servo-com-potencometro)
