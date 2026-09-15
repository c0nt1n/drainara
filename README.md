# Site — Dra. Inara Contin Rassi

Oftalmologia e blefaroplastia. Site institucional de página única, em HTML,
CSS e JavaScript puros, sem build: o que está no repositório é exatamente o
que vai pro ar.

    index.html              a página inteira
    assets/css/site.css     toda a folha de estilo
    assets/js/site.js       menu, lacunas e entrada em cena
    assets/img/             fotos e arte (ver assets/img/LEIA-ME.txt)

Publicado no GitHub Pages pelo workflow `.github/workflows/deploy.yml`, que
dispara a cada push na branch `main`.

Para ver localmente:

    python3 -m http.server 8123

e abrir <http://127.0.0.1:8123>.

---

## O que ainda falta

Cada item abaixo aparece na página como uma etiqueta tracejada **◇ FALTA**, no
lugar exato onde o conteúdo entra. Elas somem sozinhas quando o dado é
preenchido — não precisa caçar no código.

### Dados de registro
- [x] CRM-SP 136.284 — UF confirmada pelo cliente
- [x] RQE 77580

### Sobre ela
- [x] Texto de apresentação — no site como veio, com um único ajuste de
      concordância ("às doenças de retina, **ao** envelhecimento das pálpebras")
- [x] Graduação removida a pedido dela (da página e dos dados estruturados)
- [x] Residência médica: pelo MEC e CBO, no Instituto Suel Abujamra
- [x] Especializações: Oftalmologia, Retina e Cirurgia Plástica Ocular —
      Instituto Suel Abujamra, USP e UPO
- [x] Títulos: Especialista em Oftalmologia pelo CBO e pelo MEC
- [x] Experiência: HCFMUSP, Beneficência Portuguesa, preceptoria no IPS
- [x] Onde opera: Albert Einstein (Perdizes e Morumbi), Beneficência
      Portuguesa / BP Mirante, H Olhos e Mira Hospital Oftalmológico
- [ ] **Abrir a sigla "IPS"** na linha de preceptoria. Sozinha ela não diz
      nada para o paciente, e não achei a que instituição corresponde
- [ ] **Retina entra no topo do site?** O texto dela diz "especialista em
      cirurgia plástica ocular, retina e oftalmologia geral", mas o cabeçalho,
      o menu e as duas frentes falam só de oftalmologia e blefaroplastia,
      porque foram montados a partir da lista de procedimentos enviada antes.
      Decidir se retina vira uma terceira frente e entra na assinatura

### Contato
- [x] WhatsApp (11) 93045-5259 — os três pontos de agendamento
      (botão do topo, botão da capa e a linha do contato) abrem a conversa com
      a mensagem pronta: "Olá! Vim pelo site e gostaria de agendar uma consulta
      com a Dra. Inara." O "vim pelo site" serve de rastreio de origem: dá para
      medir quanto do agendamento vem daqui sem precisar de ferramenta nenhuma
- [x] Telefone da clínica (11) 3884-9477, logo abaixo do WhatsApp. É outro
      número — não confundir com a antiga linha "Ligar", que só repetia o
      WhatsApp e saiu por isso
- [x] E-mail: inaraoftalmologia@gmail.com — confirmado pelo cliente. O que
      tinha vindo antes (`inaraoftalmogia`, sem o "lo") era erro de digitação
- [x] Instagram: [@drainaracontin](https://www.instagram.com/drainaracontin/)

### Consultório
- [x] Endereço: Rua Maria Figueiredo, 595 — conjunto 83, Paraíso, São Paulo/SP
- [x] Mapa do Google incorporado na página
- [x] CEP 04002-003 — confirmado pelo cartão do próprio perfil dela no Google
- [x] Link e mapa apontam para o Perfil da Empresa no Google, pelo CID
      `0xbfa3eecd7478d5cf` (decimal 13809143448637855183). O pino mostra
      "Dra. Inara Contin Rassi - Oftalmologista", não um endereço genérico
- [x] Endereço do perfil conferido: já está na Rua Maria Figueiredo. A
      Avenida Angélica que aparecia em diretórios é registro antigo
- [ ] O cartão do mapa exibe a nota do Google (5,0, 2 avaliações). É a
      interface do próprio Google, não conteúdo publicado por nós — mas se
      ela preferir não exibir nota nenhuma, dá para voltar o mapa para a
      busca por endereço, que não mostra
- [ ] Dias e horários de atendimento — a lista de informações práticas
      (convênios, estacionamento, acessibilidade, metrô) saiu da página a
      pedido do cliente. Quando esses dados chegarem, vale reintroduzir só
      os que estiverem preenchidos

### Conteúdo clínico
- [x] Lista de procedimentos — agora é exatamente a que você mandou
- [x] Convênios: atendimento particular, com nota fiscal para reembolso
- [x] Saiu a pergunta "Blefaroplastia é estética ou o convênio cobre?" a
      pedido da médica. O FAQ foi de 6 para 5 perguntas
- [ ] O bloco "Aparelhos do consultório" saiu a pedido do cliente. O parágrafo
      de Oftalmologia ainda cita tomografia de coerência óptica e microscopia;
      dizer se essa menção fica ou sai também

### Capa
- [x] Foto da sala de espera na capa (`entrada.jpg`), na tela larga — trocada
      pela versão tratada que o cliente mandou (1448x1086, mais nítida que a
      anterior de 2000x1500 apesar de menor)
- [x] Versão em pé da mesma sala (`entrada-vertical.jpg`, 1086x1448) para
      celular e tablet, por um `<picture>`. Deitada, a foto aparecia no celular
      por uma fatia de pouco mais de um terço da largura
- [ ] A versão tratada tem 1448 px de largura: em monitor grande (2560 px ou
      mais) ela é esticada. Se houver essa mesma edição em resolução maior,
      vale trocar
- [ ] A vertical veio pelo WhatsApp, reduzida para ~1080 px. Serve em qualquer
      celular; o original deixaria o tablet melhor

### Fotos
- [x] Retrato da Dra. Inara na capa (IMG_4739)
- [x] Foto dela no consultório, seção "Sobre" (IMG_4702)
- [x] Galeria: sala de exames vazia (lote antigo) e sala de imagem com ela
- [x] `aparelhos.jpg` refeita pelo cliente: mesma cena, ângulo mais fechado e
      melhor qualidade, no lugar da IMG_4796
- [x] Ilustrações removidas a pedido dela (visual mais limpo)
- [x] Galeria refeita: sala de exames, exames de imagem e sala de espera
- [x] `recepcao.jpg` removida — era o mesmo ambiente da capa, em resolução baixa
- [x] `lounge.jpg` trocada pela foto original do Google Meu Negócio, em
      1400x1867 — a anterior (1107 px, do chat) aparecia embaçada
- [ ] `exames.jpg` (1280 px) ainda é a versão reduzida que veio pelo chat

### Domínio e publicação
- [x] Domínio definido: **drainaracontinrassi.com.br**, na Hostinger. Já está
      no `canonical`, no `og:url`/`og:image` e no `url` dos dados estruturados
- [x] O `noindex` **continua no repositório de propósito**: ele segura a
      prévia do GitHub Pages fora do Google. Quem tira é o pacote da Hostinger
      — o zip é gerado sem essa linha, sem os arquivos internos (README,
      LEIA-ME, .github) e com o `?v=dev` trocado pelo commit, como o workflow
      faz. Não suba a pasta do repositório nem o "Download ZIP" do GitHub
- [ ] Zip no Windows: nunca pelo `Compress-Archive` do PowerShell 5.1 — ele
      grava as pastas com `\` e o extrator da Hostinger cria arquivos soltos
      com nome `assets\css\site.css`, e o site sobe sem estilo

### Antes de publicar de verdade
- [ ] Revisar o texto do rodapé sobre publicidade médica. Blefaroplastia tem
      componente estético, e as normas do CFM são rígidas: nada de antes e
      depois, depoimento de paciente ou promessa de resultado
