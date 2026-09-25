# Estudo de Caso Cyclistic: Análise da Utilização das Bicicletas Partilhadas

## 📌 Visão Geral do Projeto
A **Cyclistic** é uma empresa fictícia de partilha de bicicletas em Chicago. O objetivo deste estudo de caso é compreender como os utilizadores **membros anuais** e os utilizadores **casuais**(passes de viagem única ou para o dia inteiro) utilizam o serviço de forma diferente. 

A partir destas descobertas, a equipa de marketing visa criar estratégias focadas em **converter utilizadores casuais em membros anuais**.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Visualização de Dados:** Matplotlib & Seaborn

---

## 📊 Principais Descobertas (*Key Insights*)

1. **Volume e Dias da Semana:**
   * **Membros Anuais (`member`):** Apresentam maior volume de viagens durante os dias úteis (segunda a sexta-feira), com pico às terças e quartas-feiras. O comportamento sugere o uso focado no **transporte diário para o trabalho/estudos**.
   * **Utilizadores Casuais (`casual`):** O volume de viagens cresce significativamente durante o fim de semana (sábado e domingo), caracterizando o uso voltado para **lazer e turismo**.

2. **Horários de Pico:**
   * **Membros:** Concentração nos horários de início e fim do expediente comercial (7h/8h e 16h/17h).
   * **Casuais:** Distribuição constante ao longo da tarde, com pico no meio do dia nos fins de semana (entre 13h até 17h).

3. **Locais Mais Populares:**
   * As estações mais frequentadas pelos utilizadores casuais situam-se em zonas turísticas e parques da cidade.

---

## 💡 Recomendações de Negócio

* **Campanhas de Marketing de Fim de Semana:** Focar os anúncios e promoções do plano anual nas estações turísticas durante o sábado e o domingo.
* **Planos Flexíveis / Promoções de Transição:** Oferecer descontos na conversão para o plano anual direcionados a quem faz corridas frequentes ao fim de semana.
* **Comunicação Direcionada no App:** Enviar notificações nos horários de maior pico casual (tarde de sábado/domingo) destacando as vantagens financeiras do plano anual.
