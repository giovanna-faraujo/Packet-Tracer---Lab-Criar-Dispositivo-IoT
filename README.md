# Criação, Conexão Sem Fio e Padronização de Dispositivo IoT no Cisco Packet Tracer

**Resumo Rápido:** Construção e integração prática de uma câmera de segurança sem fio customizada em ambiente simulado, com foco no mapeamento seguro de ativos IoT e padronização como template reutilizável.

---

## 1. O que é este projeto?
Imagine que você comprou componentes eletrônicos avulsos para montar um sensor ou alarme de segurança. Ao tirar as peças da caixa, ele ainda não funciona: você precisa colocar tudo em um invólucro identificado, instalar uma placa com antena sem fio para conectar ao roteador da casa e garantir que ele receba um endereço de identificação exclusivo (o IP). 

Depois de testar a resposta do aparelho por um tablet, você salva essa receita completa em um catálogo técnico para não precisar refazer o trabalho manual do zero nas próximas instalações. 

Este projeto replica exatamente esse processo no Cisco Packet Tracer: convertemos um componente base (`Thing`) em uma Câmera de Segurança inteligente com placa Wi-Fi, validamos a resposta na rede corporativa e exportamos o ativo para o catálogo permanente de modelos da ferramenta.

---

## 2. Objetivo e Valor para o Negócio
- **Problema Enfrentado:** Dispositivos inteligentes (CFTV, sensores, controladores) costumam ser adicionados a redes corporativas sem padronização ou controle de inventário, gerando pontos cegos de cibersegurança e demandando tempo excessivo de configuração manual.
- **Solução Aplicada:** Construção modular do dispositivo inteligente com placa sem fio compatível (`PT-IOT-NM-1W-AC`), validação de alocação de endereço na sub-rede autorizada (`192.168.25.0/24`) e exportação como modelo padrão no *Device Template Manager*.
- **Impacto Prático:** Redução do tempo de implantação em novos projetos, prevenção de erros humanos de configuração e garantia de visibilidade total de inventário de ativos conectados na rede.

---

## 3. Tecnologias e Competências Praticadas
- **Ambiente e Ferramentas:** Cisco Packet Tracer, Módulo Genérico IoT (`Thing`), Placa de Rede Wi-Fi `PT-IOT-NM-1W-AC`, Tablet de Controle e Gerenciador de Gabaritos (*Device Template Manager*).
- **Técnicas e Metodologias:** Customização de Ativos IoT, Conectividade Sem Fio 802.11 (Wi-Fi), Gestão de Ativos (*Asset Management*), Endereçamento IPv4 e Validação de Conectividade Base via Protocolo ICMP (*Ping*).
- **Competências Profissionais Evidenciadas:** Governança e higiene de rede, homologação de equipamentos inteligentes, padronização de configurações e testes sistemáticos de conectividade.

---

### Evidências do Laboratório

<img width="457" height="355" alt="image" src="https://github.com/user-attachments/assets/425b7076-977d-4ec4-a4c0-c78d0a9d9ad1" />

---

### Direitos Autorais e Créditos
*Este laboratório foi realizado com base no material e instruções do curso **Cisco Networking Academy (NetAcad) / Packet Tracer**. Todos os direitos autorais dos cenários e materiais originais pertencem à **Cisco Systems, Inc.***
