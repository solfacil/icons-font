Abra a [demo](index.html) para ver uma lista de todos os glifos em sua fonte junto com seus códigos/ligaduras.

## Atualizando a fonte

- Acesse [IcoMoon](https://icomoon.io/app);
- Em `Import Icons` (no canto superior esquerdo), selecione o arquivo [selection.json](selection.json). Caso apareça a mensagem `Your icon selection was loaded.
Would you like to load all the settings stored in your selection file?`, pressione `Yes`;
- Adicione os `svgs` dos novos ícones, clicando e arrastando para a lista dos atuais ícones da fonte;

    **IMPORTANTE**
    - Todos os ícones precisam conter somente uma cor: ![#666666](https://via.placeholder.com/15/666666/000000?text=+) `#666666`

- Logo após adicionar todos os novos ícones, selecione todos os ícones da fonte e pressione `Generate Font` no canto inferior direito da tela;

- Na tela que aparecerá, verifique se não há nenhum ícone repetido e se o nome de todos os ícones não contém o prefixo "`icon-`" (este será adicionado quando o site exportar a fonte);

- Se todos os nomes estiverem corretos, pressione no botão de engrenagem ao lado do botão de `Download` no canto inferior direito. Verifique os seguintes dados:
    - Font Name: `SolIconFont`;
    - Class Prefix: `icon-`;
    - Não é necessário alterar as outras informações.

- Se tudo estiver correto, pressione o botão `Download` no canto inferior direito da tela;

- Para subir a nova versão no repositório:
    - Apague o arquivo `Read Me.txt`;
    - Altere o nome do arquivo `demo.html` para `index.html`;
    - Substitua todos os arquivos da sua pasta de clone do repositório;
    - Adicione os `.svg` dos ícones adicionados na pasta `svgs` da sua pasta de clone do repositório;
    - Abra um Pull Request;

## Informações do IcoMoon

Open [demo.html](index.html) to see a list of all the glyphs in your font along with their codes/ligatures.

To use the generated font in desktop programs, you can install the TTF font. In order to copy the character associated with each icon, refer to the text box at the bottom right corner of each glyph in demo.html. The character inside this text box may be invisible; but it can still be copied. See this guide for more info: https://icomoon.io/#docs/local-fonts

You won't need any of the files located under the *demo-files* directory when including the generated font in your own projects.

You can import *selection.json* back to the IcoMoon app using the *Import Icons* button (or via Main Menu → Manage Projects) to retrieve your icon selection.