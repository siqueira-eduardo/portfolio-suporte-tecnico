# Diagnóstico inicial de conexão com a internet

## Objetivo

Identificar se a falha está restrita a um dispositivo, à rede local ou ao acesso externo, sem realizar alterações indevidas.

## Perguntas iniciais

- O problema afeta apenas um equipamento?
- Outros sites ou sistemas também falham?
- A conexão é Wi-Fi ou cabeada?
- O problema começou após alguma mudança?
- Há mensagem de erro específica?

## Sequência segura de verificação

1. Conferir se Wi-Fi ou cabo estão conectados.
2. Verificar se o modo avião está desativado.
3. Comparar com outro dispositivo autorizado na mesma rede.
4. Conferir se o equipamento recebeu configuração de rede válida.
5. Testar o acesso ao gateway e a um destino externo, conforme ferramentas e permissões disponíveis.
6. Se necessário, verificar resolução DNS.
7. Registrar horários, resultados e mensagens apresentadas.

## Comandos úteis no Windows

```bat
ipconfig /all
ping <gateway>
nslookup exemplo.com
```

Substitua `<gateway>` pelo endereço real do gateway da rede. Use apenas em equipamento e rede autorizados.

## Interpretação básica

- Sem endereço IP válido: investigar DHCP, adaptador ou configuração local.
- Gateway inacessível: investigar conexão local, VLAN, Wi-Fi ou equipamento de rede.
- IP externo acessível, mas nome não resolve: investigar DNS.
- Falha em vários dispositivos: possível incidente de rede ou provedor; escalar conforme procedimento.

## Cuidados

Não redefina roteadores, altere DNS corporativo ou execute comandos de reparo sem autorização. Registre os testes antes de qualquer mudança.
