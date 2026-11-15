# UMA NOVA CHANCE · PAN — site para GitHub Pages

## Como publicar
1. Extraia o ZIP. Envie **o conteúdo interno** (index.html, conteudo-medico.js e assets) para a raiz do repositório no GitHub.
2. Em Settings > Pages, selecione Deploy from a branch, main, / (root).
3. Aguarde a publicação e teste o site no celular.

## Fotos das feridas
Coloque fotos autorizadas em `assets/feridas/`, por exemplo `foto01.jpg`. Abra `conteudo-medico.js` e adicione na lista `feridas`:
```js
{ titulo: "Ferida 01", arquivo: "assets/feridas/foto01.jpg", descricao: "Registro autorizado" },
```

## Laudos médicos
Coloque PDFs autorizados em `assets/laudos/`, por exemplo `laudo01.pdf`. No mesmo arquivo adicione à lista `relatorios`:
```js
{ titulo: "Laudo 01", arquivo: "assets/laudos/laudo01.pdf", descricao: "Documento autorizado" },
```
**Atenção:** colocar arquivos nas pastas sem atualizar `conteudo-medico.js` não os faz aparecer no site. Fotos ficam em área com aviso de conteúdo sensível. GitHub Pages é público: qualquer pessoa com o link do arquivo poderá acessá-lo, mesmo se houver aviso na página. Oculte dados sensíveis e publique apenas documentos que você deseja tornar públicos.

## Doações
O site contém PIX com valor livre em BRL e imagens de QR Codes Wise em USD/EUR, provenientes da versão anterior. Confirme beneficiário e valor no aplicativo antes de divulgar. Teste o PIX com pequena quantia. O QR Code PIX depende de biblioteca externa; o código Copia e Cola é gerado localmente.

## Conteúdo médico
A seção Sobre a PAN contém informações educativas gerais e não substitui orientação médica. Revise a história pessoal e a documentação antes de publicar. A meta financeira não aparece no site.
