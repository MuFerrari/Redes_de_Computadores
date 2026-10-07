# 🌐 Redes de Computadores 🌐
<div align="center">
  
  <img src="https://img.shields.io/badge/VLAN-1BA0D7.svg?style=for-the-badge&logo=cisco&logoColor=white" alt="VLAN">
  <img src="https://img.shields.io/badge/Redes-0058A3.svg?style=for-the-badge&logo=gnometerminal&logoColor=white" alt="Redes">
  <img src="https://img.shields.io/badge/Segurança-4A154B.svg?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Segurança">
</div>

<div align="justify">

  <br></br>
  
  Bem-vindo ao meu repositório de Redes de Computadores! Este diretório documenta a minha evolução, os conceitos estruturais estudados e as políticas e projetos práticos desenvolvidos durante a disciplina. 
  
  <br></br>
  
  ## 🧠 O Que Aprendi Até Aqui (Conceitos & Analogias)
  
  A construção e análise dos **Documentos presentes no Diretório** permitiu a consolidação dos seguintes pilares das Redes de Computadores:
  
  1. **O Modelo OSI e a Arquitetura de Comunicação**
     * **Conceito:** O processo de comunicação via Modelo OSI funciona de maneira muito parecida com o envio de um pacote pelos *correios*, passando por etapas estruturadas até atingir o seu destino. A arquitetura padroniza a comunicação dividindo-a em sete camadas funcionais (desde a camada Física até a de Aplicação).
     * **Prática:** Analisei o trajeto da informação pelo processo de encapsulamento de dados, no qual cabeçalhos de controle (como endereços de porta, IP e MAC) são adicionados a cada camada pelo dispositivo emissor, descendo a pilha. Ao chegar no destino, a máquina receptora realiza o desencapsulamento (subindo a pilha), removendo os cabeçalhos sucessivamente até entregar a mensagem original.
  
  2. **Serviços Essenciais: DNS e DHCP**
     * **Conceito:** O DNS atua como uma *lista telefônica* da internet, convertendo nomes de domínios facilmente legíveis em endereços IP numéricos compreendidos pelas máquinas. O DHCP, por sua vez, age como um "recepcionista", distribuindo e atribuindo endereços IP automaticamente aos dispositivos assim que eles entram na rede.
     * **Prática:** Compreendi os impactos críticos da falta desses serviços em ambientes reais. Sem o DHCP (em uma rede com 100 máquinas, por exemplo), gerenciaríamos as configurações IP de forma totalmente manual, correndo altos riscos de erros de digitação e isolamento de máquinas. Já uma falha no serviço DNS bloquearia completamente o acesso aos sites e sistemas dependentes de domínios.
  
  3. **Governança e Política de TI**
     * **Conceito:** A Política de Tecnologia da Informação (PTI) atua como o *regulamento interno* corporativo. Ela estabelece diretrizes normativas para o uso ético, seguro e eficiente da infraestrutura tecnológica da instituição.
     * **Prática:** Desenvolvi uma política focada em assegurar os pilares da segurança da informação (confidencialidade, integridade e disponibilidade) e alinhada à LGPD e ao Marco Civil da Internet. Implementei na teoria controles práticos como segregação de tráfego utilizando VLANs dedicadas (separando administração, alunos e visitantes), exigência do menor privilégio e de senhas fortes, e procedimentos padronizados de cópia de segurança através da estratégia 3-2-1.
  
  <br></br>
  
  ## 📂 Arquiteturas e Estruturas
  Os arquivos e relatórios adotam boas práticas de documentação e análise estrutural, divididos da seguinte forma:
  * **`PJ.202604_11023_Redes_01.docx.pdf` / `02.docx.pdf`**: Documentação detalhada da Política de Tecnologia da Informação (PTI). Aborda desde o controle de acesso e uso da rede Wi-Fi, até a política de senhas, manuseio de equipamentos físicos e procedimentos operacionais de backups e segurança.
  * **`PJ.202604_11023_Redes_Extra.pdf`**: Estudo focado e aprofundado detalhando as sete camadas do Modelo OSI, a função do encapsulamento/desencapsulamento e a comparação analítica direta com a arquitetura de quatro camadas do TCP/IP.
  * **`PJ_202604_11023_Redes_Extra02.pdf`**: Relatório de conceitos fundamentais contrastando as características e escopos da Internet, Intranet e Extranet. Cobre também os mecanismos de endereçamento lógico e físico (IPv4, IPv6, NAT, e MAC), e a explicação sobre os serviços cruciais DNS e DHCP.
  
  <br></br>
  
  ## ⚙️ Como Acessar os Documentos
  
  1. Clone este repositório: `git clone <URL_DO_SEU_REPOSITORIO>`
  2. Navegue até a pasta do projeto localmente.
  3. Utilize o navegador ou um leitor de PDFs para acessar e consultar os relatórios formatados e os documentos de governança de TI produzidos.
  
  <br></br>
  
  ## 🛠️ Tecnologias e Conceitos Estudados
  * **Fundamentos e Escopos:** Internet, Intranet e Extranet;
  * **Arquiteturas Analisadas:** Modelo de Referência OSI (7 Camadas) e TCP/IP (4 Camadas);
  * **Endereçamento e Serviços Vitais:** IP (IPv4 / IPv6), NAT, Endereço MAC, DNS e DHCP;
  * **Governança, Políticas e Segurança:** Criação de PTI, Adequação à LGPD, Controle de Acessos Lógicos e Físicos, VLANs de Segregação, VPN, Estratégia de Backup 3-2-1, Firewall e Monitoramento.
</div>
