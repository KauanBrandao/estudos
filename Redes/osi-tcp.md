# Os Modelos OSI e TCP/IP

Os protocolos TCP, UDP e IP são a base da comunicação entre máquinas na internet. Para organizar a forma como esses dados viajam, existem dois modelos de referência:
* **Modelo OSI:** Possui 7 camadas. É muito usado para fins teóricos, didáticos e para encontrar erros (troubleshooting) na infraestrutura.
* **Modelo TCP/IP:** É o modelo prático que a internet realmente usa por ser mais compacto, possuindo apenas 4 camadas.



Independentemente do modelo, o fluxo da informação passa pelas seguintes etapas lógicas fundamentais:

### 1. Camada de Aplicação
É a interface do usuário e o local onde o seu código é executado. É nesta camada que os dados nascem e onde operam os sites, APIs e protocolos voltados para o usuário (como HTTP, FTP, SMTP, etc.).

### 2. Camada de Transporte
Como o próprio nome já diz, é a camada que recebe os dados da aplicação e decide a forma de envio. É aqui também que são definidas as **Portas** lógicas de comunicação. Ela opera principalmente com dois protocolos:
* **TCP:** Focado em confiabilidade. Garante a conexão estabelecida entre as máquinas e confirma que os dados chegaram íntegros.
* **UDP:** Focado em velocidade. Apenas dispara (joga) os dados sem esperar resposta, confirmação de recebimento ou garantia de entrega.

### 3. Camada de Rede (Internet)
É onde acontece o gerenciamento de rota dos dados. Aqui atuam o **protocolo IP (Internet Protocol)** e os **Roteadores**. O intuito exclusivo dessa camada é encontrar a melhor rota para a informação viajar do IP de origem até o IP de destino.

### 4. Camada de Enlace de Dados (e Física)
Por fim, é onde acontece a entrega local. É nesta camada que atuam o **MAC Address** e os **Switches**, definindo fisicamente em qual equipamento ou placa de rede a entrega dos pacotes será feita.