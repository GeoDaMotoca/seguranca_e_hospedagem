## 🧠 Questões Teóricas sobre DNS

**1.** O que significa a sigla DNS e qual é sua principal função?
R= Domain Name System(Sistema de nomes de domínio), eles são responsáveis por traduzir nomes de domínio em endereços IP, funcionam como uma agenda da internet permirtindo que usuários acessem sites usando nomes fáceis de lembrar.

**2.** Por que o DNS foi criado? Qual problema ele resolveu na Internet?
R= Foi criado na década de 1980 para resolver o problema de escalabilidade e gerenciamento de endereços na internet, que crescia rapidamente e tornava inviável o uso de um método centralizado e manual.

**3.** O que é um nome de domínio? Dê um exemplo.
R= Um nome de domínio é um endereço legível usado para identificar e acessar um site na internet, substituindo o uso de números (IP).
Exemplo: www.google.com

**4.** Qual é a função de um servidor DNS?
R= O servidor DNS traduz nomes de domínio em endereços IP, permitindo que o navegador encontre o site desejado na internet.

**5.** Cite dois tipos de registros DNS e explique brevemente um deles.
R= O DNS possui vários tipos de registros, como o A, que associa um domínio a um endereço IPv4, e o CNAME, que funciona como um apelido, permitindo que um nome alternativo aponte para outro domínio. 
Por exemplo, o registro CNAME pode fazer com que blog.exemplo.com seja direcionado para www.exemplo.com, facilitando o gerenciamento de vários subdomínios.

---

## 🪟 Questões sobre DNS no Windows

**6.** Qual comando do Windows é utilizado para testar a resolução de nomes DNS?
R= O comando nslookup.

**7.** Para que serve o comando `ipconfig /all` em relação ao DNS?
R= Ele mostra todas as configurações de rede, incluindo os servidores DNS usados pelo computador.

**8.** Qual comando pode ser usado para limpar o cache DNS no Windows?
R= ipconfig /flushdns

**9.** Onde o Windows armazena temporariamente as informações de DNS?
R= No cache DNS local (memória temporária do sistema).

**10.** Ao acessar um site no Windows e ocorrer erro de DNS, cite uma possível causa.
R= Uma possível causa é que o cache DNS está desatualizado ou o servidor DNS está fora do ar.

---

## 🐧 Questões sobre DNS no Linux

**11.** Qual arquivo do Linux contém os servidores DNS configurados no sistema?
R= O arquivo /etc/resolv.conf.

**12.** Qual comando pode ser usado no Linux para consultar registros DNS de um domínio?
R= O comando dig (ou nslookup).

**13.** Para que serve o comando `ping` em relação ao DNS?
R= Ele verifica se o domínio consegue ser resolvido em IP e se há conectividade com o endereço.

**14.** Qual a função do arquivo `/etc/hosts` no processo de resolução de nomes?
R= Ele faz uma resolução local, associando nomes a IPs antes de consultar o DNS.

**15.** Cite uma diferença básica entre a configuração de DNS no Windows e no Linux.
R= No Windows, o DNS é configurado principalmente via interface gráfica (Configurações de Rede) ou comandos como ipconfig.
No Linux, a configuração geralmente é feita em arquivos de texto, como /etc/resolv.conf e /etc/hosts.

---
