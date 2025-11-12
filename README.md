## ⚙️ HALF ADDER (Meio Somador)

- Soma dois bits (A e B).  
- Gera duas saídas:
  - **S (Soma)** — resultado da soma binária.  
  - **C (Carry)** — transporte para o próximo bit quando A e B são 1.  
- Implementado com portas **XOR** e **AND**.  
## ⚙️ FULL ADDER (Somador Completo)

- Soma três bits: A, B e **Carry In** (vai-um anterior).  
- Saídas:
  - **S (Soma)** — resultado da soma.  
  - **Cout (Carry Out)** — transporte para o próximo bit.  
- Pode ser construído com **dois Half Adders + uma porta OR**.  
## 💻 4-BIT ADDER

- Formado por **quatro Full Adders** conectados em sequência.  
- Cada Full Adder soma um par de bits (A[i], B[i]) e o carry da etapa anterior.  
- O primeiro somador recebe **Carry In = 0**.  
- O último gera o **Carry final (Cout)**.  


---

## 👨‍💻 Autor

**Kayky Jesus**  
💼 Estudante de Engenharia e entusiasta de sistemas digitais.  
📧 [kayky@edu.unifil.br](mailto:kayky@edu.unifil.br)
