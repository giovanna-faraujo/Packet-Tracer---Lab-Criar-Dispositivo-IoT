# Criação e Integração de Câmera de Segurança

---

### Sobre o Projeto

Este repositório contém o arquivo e a documentação do laboratório prático de **Internet das Coisas (IoT)** realizado no **Cisco Packet Tracer**. 

O objetivo do projeto é demonstrar, de forma simples e visual, como um novo dispositivo inteligente (neste caso, uma **Câmera de Segurança**) é criado do zero, configurado com uma interface de rede sem fio (Wi-Fi), integrado à rede local e salvo como uma template reutilizável para topologias futuras.

---

### Por que este projeto é relevante para Cibersegurança?

Em ambientes corporativos e residenciais, os dispositivos **IoT (Internet das Coisas)** representam um dos maiores vetores de ataque se não forem devidamente mapeados e protegidos:
* **Mapeamento de Ativos (Asset Management):** Identificar todos os dispositivos conectados à rede (como câmeras Wi-Fi) é o primeiro passo para a gestão de vulnerabilidades.
* **Segmentação e Alocação de IP:** Verificar se o dispositivo recebeu o IP correto na subnet (ex: `192.168.25.0/24`) permite criar regras de firewall adequadas para isolar tráfego sensível.
* **Testes de Conectividade Base:** Utilizar o protocolo **ICMP (Ping)** para validar a alcançabilidade e comunicação segura entre os ativos da rede.

---

### Como o Laboratório foi Construído

#### **Parte 1: Construindo e Conectando a Câmera de Segurança**
1. **Criação do Dispositivo Genérico:** Um componente genérico de IoT (`Thing`) foi adicionado à área de trabalho.
2. **Personalização e Identificação:** O dispositivo foi renomeado para `Security Camera` e customizado visualmente com um ícone personalizado através do *Thing Editor*.
3. **Configuração da Interfase Digital:** Definida a interface digital no `Slot 1` para simular o comportamento de captura e transmissão do equipamento.
4. **Adição do Adaptador Wi-Fi:** Foi alterado o adaptador de rede interno do dispositivo para o modelo `PT-IOT-NM-1W-AC`, permitindo a conexão sem fio com a rede local.
5. **Endereçamento IP e Teste de Rede:** 
   * A câmera recebeu automaticamente um endereço IPv4 na rede `192.168.25.0/24`.
   * A partir de um **Tablet** conectado à rede, foi executado o comando `ping [IP_da_Câmera]`, confirmando que a câmera está visível e pronta para operar.

---

#### **Parte 2: Padronização e Exportação como Template**
1. **Criação de Gabarito (Template):** Através do *Device Template Manager*, a câmera configurada foi salva na categoria `Home`.
2. **Validação:** Ao abrir um novo arquivo limpo no Packet Tracer, o novo dispositivo customizado já fica disponível no menu de seleção rápida, otimizando o tempo de implantação de redes futuras.

---

### Tecnologias e Ferramentas Utilizadas

* **Simulador:** Cisco Packet Tracer
* **Protocolos e Conceitos:** Wi-Fi (802.11), IPv4 (DHCP/Estático), ICMP (Ping), IoT Device Customization, Asset Management.

---

### Evidências do Laboratório

<img width="1911" height="970" alt="image" src="https://github.com/user-attachments/assets/6866d5c3-81c2-42ba-adc7-b2ba232cd9a3" />

---

### Direitos Autorais e Créditos
*Este laboratório foi realizado com base no material e instruções do curso **Cisco Networking Academy (NetAcad) / Packet Tracer**. Todos os direitos autorais dos cenários e materiais originais pertencem à **Cisco Systems, Inc.***
