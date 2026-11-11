# Casa BP — visualizador 3D

Site estático com cinco abas: **Casa atual**, **Estudos A–D** e **Proposta escolhida** e **Garagem fechada** e **BYD Seal 3D**. A abertura inicial mostra a proposta escolhida, revisão 05 de 10/11/2026: suíte ampliada 4,00 m para a frente, com dormitório de 8,94 m², closet separado de 3,57 m² e porta ripada de correr, copa e cozinha integradas por um vão de 2,40 m, mesa 80 cm mais ao fundo e janela de correr de 2,40 × 1,20 m para o quintal. A parte nova tem 2,54 m de largura interna; o corredor fica com 1,60 m ao lado dessa parte e mantém 2,00 m junto à casa atual. Recuo frontal estimado de 2,00 m: confirmar se o avanço é permitido. A opção de tubo solar na copa é um estudo de luz natural direta, sujeito à avaliação da laje; não é cálculo de iluminação. O carro da vaga é uma reconstrução visual da Chevrolet Tracker Premier 2026, com escala documentada e detalhes aproximados. Use **Tracker na vaga** ou **Tracker em detalhe**; o modelo independente permite mudar cores e baixar o GLB do carro. Na suíte, use os controles **Porta fechada** e **Porta aberta** para comparar a privacidade e a passagem direta ao dormitório.

## Alternativa de garagem G01 · 11/11/2026

A proposta escolhida continua preservada como abertura inicial. A quarta aba **Garagem fechada** mostra uma alternativa separada com vaga de 2,80 × 5,07 m, portão de enrolar animado e controles para comparar cobertura leve ou estudo em laje, alinhados à suíte. A faixa descoberta diante da sala tem 1,56 m²; a varanda existente de 1,44 m² continua coberta. O caminho passa pela garagem, com cerca de 57 cm junto ao espelho direito da Tracker e desnível de 14 cm até o pátio; não é uma passagem acessível. Não foi testada a abertura das portas do carro nem a manobra. O fechamento pode reduzir a luz da sala.

Use o endereço com **#garagem** para entrar diretamente nessa aba. A pasta **proposta-garagem/** contém o visualizador, memorial, vistas e dois GLBs: cobertura leve e laje em estudo. Estrutura, fundações, encontro com a ampliação, ventilação, drenagem e permissão para fechar o recuo frontal precisam de projeto e verificação local. A cobertura ilustrativa do quarto não comprova capacidade de apoio para a garagem.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `casa-3d`.
2. Envie **o conteúdo desta pasta**, mantendo as subpastas. O arquivo `index.html` precisa aparecer na raiz do repositório, junto deste README. Não envie apenas o ZIP nem deixe tudo dentro de uma pasta adicional chamada `github-pages`.
3. Na aba **Code**, confira se os arquivos estão na branch `main`.
4. Abra **Settings → Pages → Build and deployment**.
5. Em **Source**, escolha **Deploy from a branch**.
6. Selecione **main** e **/(root)**; clique em **Save**.
7. Quando a publicação terminar, abra **Visit site** na própria tela do Pages. Se disponível, mantenha **Enforce HTTPS** ativado.

O endereço costuma seguir este formato: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Não é necessário instalar Node.js, executar build ou configurar servidor no GitHub. O computador do proprietário pode ficar desligado após a publicação. Todas as bibliotecas necessárias ao visualizador já estão incluídas no HTML.

No plano GitHub Free, use um repositório público. O conteúdo publicado no Pages é acessível pela internet; este pacote não inclui autenticação.

## Usar no celular

Abra o endereço HTTPS no Chrome ou Safari. Use as abas superiores para alternar entre a casa atual e as melhorias. Toque em **Controles** dentro do visualizador para selecionar as alternativas, cobertura, corte e demais opções. Arraste para girar e use o gesto de pinça para aproximar.

## Arquivos

| Caminho | Conteúdo |
| --- | --- |
| `index.html` | Entrada do site, com as cinco abas |
| `projeto-3d/` | Visualizador da casa atual, memorial, imagens e GLB/OBJ |
| `melhorias-futuras/` | Comparação A–D, relatórios, imagens e modelos GLB |
| `proposta-escolhida/` | Modelo escolhido e atualizado, mobiliado, com vistas e memorial |
| `.nojekyll` | Indica publicação estática sem processamento Jekyll |
| `THIRD_PARTY_NOTICES.txt` | Licença da biblioteca de visualização |

Os PDFs originais de arquitetura, elétrica e hidráulica, os servidores locais e a pasta node_modules não fazem parte deste pacote. Os relatórios PDF incluídos são os memoriais gerados para apresentação. A geometria da casa atual foi mantida; apenas o acesso ao PDF original foi removido da cópia para publicação.

Os modelos são estudos arquitetônicos. Dimensões estimadas, desnível dos fundos e intervenções estruturais continuam sujeitos às conferências descritas nos memoriais. As alternativas não são projetos de execução.

## Atualizar futuramente

Substitua os arquivos publicados pelos de uma nova exportação e faça um novo commit na main. O Pages volta a publicar a branch selecionada. As fontes editáveis e o script de empacotamento foram mantidos na pasta de trabalho original, fora deste pacote estático.

## Documentação oficial

- [Configurar a origem de publicação](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Criar um site do GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Usar HTTPS](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https)


## BYD Seal detalhado · S01

A aba **BYD Seal 3D** abre o carro independente; no endereço, use **#seal**. Em **Garagem fechada**, escolha **BYD Seal** para comparar com a Tracker. O link **?carro=seal#garagem** seleciona o Seal diretamente. A casa e as dimensões da garagem são preservadas.

Malha “2024 BYD Seal”, de Ddiaz Design, adaptada sob **CC BY-NC-SA 4.0**, com 136.565 triângulos e interior. Dimensões nominais calibradas: 4,800 × 1,875 × 1,460 m, entre-eixos de 2,920 m; 2,150 m com espelhos como referência oficial europeia. Formas e detalhes não são CAD oficial. Cores e materiais são de apresentação. Consulte **veiculos/byd-seal/CREDITOS-E-LICENCA.html** para fontes, licença e alterações.

A garagem mede 5,07 m no comprimento: o Seal deixa somente 27 cm de folga total, cerca de 13,5 cm em cada ponta. Não foi comprovada a manobra nem a abertura de portas e porta-malas. Os GLBs históricos da casa e da garagem com Tracker continuam preservados. O botão de exportação do visualizador da garagem usa o carro selecionado, com licença e créditos incluídos nos metadados do Seal.
