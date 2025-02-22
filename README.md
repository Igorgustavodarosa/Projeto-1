let tamanhoAtualFonte = 1;
aumentaFonteBotao.addEventListener("click", function (
  tamanhoAtualFonte += 0.1;
  document.body.style.fontSize = `${tamanhoAtualFonte}rem`;
) {});

alternaContraste.addEventListener("click", function () {
  document.body.classList("alto-contraste");
});
