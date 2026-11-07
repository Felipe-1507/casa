# Casa BP — visualizador 3D

Site estático com duas abas: **Casa atual preservada** e **Melhorias futuras**, incluindo as alternativas A, B, C e D.

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
| `index.html` | Entrada do site, com as duas abas |
| `projeto-3d/` | Visualizador da casa atual, memorial, imagens e GLB/OBJ |
| `melhorias-futuras/` | Comparação A–D, relatórios, imagens e modelos GLB |
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
