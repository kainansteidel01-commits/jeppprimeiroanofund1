# Essência dos Pés — projeto do 1º ano

Site independente da EMEB Vereador Evaldo Staidel, com o conteúdo do documento “Projeto ESCALDA PÉS (1).docx”. Mantém a logo da escola no cabeçalho e os recursos de acessibilidade do site anterior, com nova logo e cores em lilás e roxo.

## Como enviar para o GitHub

1. Extraia o ZIP.
2. Abra um repositório separado para este projeto.
3. Clique em **Add file → Upload files**.
4. Abra a pasta extraída `essencia-dos-pes` e envie TODOS os arquivos que estão dentro dela.
5. Clique em **Commit changes**.
6. Em **Settings → Pages**, escolha **Deploy from a branch**, selecione a branch que recebeu os arquivos (normalmente `main`) e **/(root)**. Salve e aguarde o endereço de publicação.

Os arquivos devem ficar juntos na raiz do repositório:

```text
index.html
logo-escola.png
logo-projeto.png
roteiro-narracao.txt
LEIA-ME.md
.nojekyll
```

**As duas logos ficam junto do HTML. Não é necessário criar uma pasta `assets`.** Preserve os nomes e extensões. A nova logo do projeto é PNG.

Para manter os dois projetos separados, não substitua o `index.html` do site Estação da Saúde. Configure o endereço deste novo site no novo repositório; não transfira o domínio do anterior se quiser mantê-lo funcionando nesse endereço.

## Acessibilidade

- Leitura em voz alta em português, com pausa, continuação, parada e velocidade ajustável.
- A voz é gerada pelo navegador; não é uma gravação MP3. Depende do suporte do aparelho e de suas vozes. Ao continuar após uma pausa, o trecho interrompido recomeça.
- A leitura acompanha o conteúdo da página e inclui as estratégias de inclusão, mesmo com os painéis fechados.
- Ampliação de texto, alto contraste, navegação por teclado, foco visível e descrições das logos.
- Integração com o VLibras, que exige internet e depende da disponibilidade do serviço. A tradução automática pode conter limitações e não substitui um intérprete.

Antes da feira, teste voz e tradução no site publicado, usando os aparelhos e a conexão do local. A verificação automatizada dos controles não substitui o teste real de áudio, Libras e leitores de tela.

## Conteúdo e atualizações

As propostas e os resultados esperados foram adaptados do documento enviado. A página apresenta as atividades como planejadas, respeitando preferências, limites e participação voluntária. Para alterar o texto, edite `index.html`; atualize também `roteiro-narracao.txt` se quiser manter essa cópia sincronizada.

O QR Code permanece para a etapa final, depois de definido o endereço publicado.
