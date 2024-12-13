# 🌐 Endereçamento IPv4

O Internet Protocol (IPv4) é um dos principais protocolos da internet, responsável por identificar dispositivos em redes por meio de endereços numéricos. Aqui estão as informações organizadas com detalhes e emojis para facilitar a leitura. 👇

---

### 🏷️ Classes de IP

O IPv4 é dividido em 5 classes principais, mas apenas **A, B e C** são usadas para atribuição de endereços em redes convencionais.

#### 🟥 Classe A
- **Primeiro número:** 0 a 127  
- **Capacidade:** 16.777.216 endereços (16 milhões de hosts por rede).  
- **Uso:** Grandes provedores de internet e organizações governamentais.  
- **Exemplo:** Redes de ISPs (Internet Service Providers).

#### 🟧 Classe B
- **Primeiro número:** 128 a 191  
- **Capacidade:** 65.536 endereços por rede.  
- **Uso:** Redes médias, como universidades e empresas corporativas.  
- **Exemplo:** Redes de universidades e órgãos governamentais de médio porte.

#### 🟨 Classe C
- **Primeiro número:** 192 a 223  
- **Capacidade:** 256 endereços (ideal para redes menores).  
- **Uso:** Redes residenciais e pequenos escritórios.  
- **Exemplo:** Redes domésticas e roteadores de pequenas empresas.

#### 🟩 Classe D (Multicast)
- **Primeiro número:** 224 a 239  
- **Uso principal:** Multicast – enviar pacotes para múltiplos destinatários simultaneamente.  
- **Aplicações:** Videoconferências, streaming e jogos multiplayer.

#### 🟦 Classe E (Experimental)
- **Primeiro número:** 240 a 255  
- **Uso principal:** Testes e experimentos com novas tecnologias.  
- **Observação:** Não utilizado publicamente.

---

### 🔒 IP Restrito ou Privado (RFC 1918)

Os IPs privados são usados para redes internas e não são roteáveis diretamente na internet. Aqui estão os intervalos privados definidos pela **RFC 1918**:

- **10.0.0.0/8:** Redes muito grandes (grandes empresas).  
- **172.16.0.0/12:** Redes médias (departamentos).  
- **192.168.0.0/16:** Redes pequenas (domésticas ou escritórios).

#### 🛡️ Características dos IPs Privados:
- **Não roteáveis na internet:** Dependem de NAT (Network Address Translation) para acessar a internet.  
- **Reutilizáveis:** Podem ser usados em diferentes redes sem conflito.  
- **Segurança:** Maior proteção, pois não podem ser acessados diretamente de fora da rede local.

#### 🌟 Exemplo de uso:
- Roteadores domésticos geralmente atribuem endereços como `192.168.0.x` ou `192.168.1.x` para dispositivos conectados.

---

### 📌 IPs Reservados (RFC 1918)

IPs reservados são intervalos especiais de endereços IP com funções específicas em redes. Eles não estão disponíveis para alocação pública e possuem finalidades como testes e gerenciamento interno.

#### 🔁 127.0.0.0/8 (Loopback/Localhost)
- **Uso principal:** Comunicação entre aplicações no mesmo dispositivo.  
- **Exemplo:** `127.0.0.1` é usado para testar serviços localmente.

#### 🔄 169.254.0.0/16 (APIPA)
- **Uso principal:** Atribuído automaticamente quando não há resposta de um servidor DHCP.  
- **Exemplo:** Dispositivos sem DHCP recebem IPs como `169.254.x.x` para permitir comunicação básica.

#### 🚦 0.0.0.0/8 (Endereço de Inicialização)
- **Uso principal:** Representa a ausência de um IP específico.  
- **Exemplo:** Usado no início do processo de inicialização de dispositivos antes da atribuição de um endereço válido.

#### 📡 255.255.255.255 (Broadcast Geral)
- **Uso principal:** Enviar mensagens para todos os dispositivos em uma sub-rede.  
- **Exemplo:** Usado para broadcast de rede local, como anúncios de serviços.
