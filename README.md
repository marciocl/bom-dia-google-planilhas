# bom-dia-google-planilhas
Um Script que dá bom dia quando uma google planilha abre através de um pop-up 

// Na barra de ferramentas do google planilhas clique em editor de script copie o código abaixo, pressiona enter e pronto.

function onOpen() 
{
  var ui = SpreadsheetApp.getUi();
  ui.alert(‘Bom dia!’);
}

// O trecho do código ('Bom dia!') na linha 8 pode ser substituido com o propósito de mudar o que esta escrito desde que seja respeitada a sintaxe. 
