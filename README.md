# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

Developed by: Sifiz.A
RegisterNumber: 25010152

<img width="694" height="607" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/ff2a68df-2e28-4bf6-b8db-3a62300ee305" />


**RTL LOGIC FOR FLIPFLOPS**

<img width="1114" height="777" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/0be9bb7c-cc48-478d-96ae-bd3d4247a586" />


**TIMING DIGRAMS FOR FLIP FLOPS**
<img width="1101" height="339" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/d0e1c9be-2146-4397-924b-6fd33f122fcc" />

**RESULTS**
Thus, the given logic functions are implemented using and their operations are verified using Verilog programming.

