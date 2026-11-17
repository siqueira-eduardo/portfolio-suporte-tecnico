# Fundamentos de redes

## Conceitos essenciais

- **IP:** endereço lógico de um dispositivo na rede.
- **Máscara de sub-rede:** define a separação entre rede e hosts.
- **Gateway padrão:** caminho utilizado para alcançar outras redes.
- **DNS:** traduz nomes de domínio em endereços IP.
- **DHCP:** distribui configurações de rede automaticamente.
- **Switch:** conecta dispositivos em uma rede local.
- **Roteador:** encaminha tráfego entre redes.
- **Wi-Fi:** tecnologia de rede local sem fio.

## Ferramentas de diagnóstico

- `ipconfig`: consulta configuração IP no Windows.
- `ping`: testa alcance e latência até um destino.
- `tracert`: mostra o caminho até um destino.
- `nslookup`: consulta resolução de nomes.

## Modelo mental de diagnóstico

Dispositivo → conexão local → configuração IP → gateway → DNS → destino/serviço.

A sequência ajuda a delimitar a falha. Um teste isolado não comprova, por si só, a causa do problema.
