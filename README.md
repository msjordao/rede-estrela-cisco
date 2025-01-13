# Rede Estrela no Cisco Packet Tracer

Este repositório contém a configuração de uma rede em topologia estrela, criada para o show da banda de Miguel. A configuração foi feita no Cisco Packet Tracer para permitir a comunicação eficiente entre os membros da equipe de produção.

## **Descrição do Projeto**
O projeto simula uma rede de computadores onde os dispositivos (PCs) estão conectados a um switch central, formando uma topologia em estrela. Cada computador representa um membro da equipe de produção, como iluminação, som, produção geral e coordenação.

### **Configuração da Rede**
- **Topologia:** Estrela
- **Dispositivos:**
  - 1 Switch central (modelo usado: 2960 Switch)
  - 4 PCs conectados ao switch com cabos ethernet
- **Endereços IP dos PCs:**
  - PC1 (Iluminação): `192.168.1.1`
  - PC2 (Som): `192.168.1.2`
  - PC3 (Produção): `192.168.1.3`
  - PC4 (Coordenação): `192.168.1.4`

### **Testes de Conectividade**
Para garantir que todos os PCs estão configurados corretamente e podem se comunicar:
- Teste de ping realizado entre os PCs, confirmando a comunicação bem-sucedida.

### **Conteúdo do Repositório**
- **Arquivo `.pkt`:** Configuração do projeto no Cisco Packet Tracer.
- **Capturas de tela:** 
  - Topologia montada.
  - Resultados dos testes de conectividade usando o comando `ping`.

---

## **Como usar este repositório**
1. Abra o arquivo `.pkt` no Cisco Packet Tracer.
2. Verifique a topologia e os endereços IP configurados.
3. Execute seus próprios testes de conectividade, se necessário.
