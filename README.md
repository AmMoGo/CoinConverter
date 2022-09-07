# CoinConverter
My second JavaScript project: a currency converter that converts from dollar to real (Brazilian currency). Which can also be used as a base as a converter between temperature scales, converter between measurement units and etc.

function Converter()  {
  var valorElemento = document.getElementById("valor");
  var valor = valorElemento.value;
  var valorEmDolarNumerico = parseFloat(valor);
  
  var valorEmReal = valorEmDolarNumerico * 5;
  console.log(valorEmReal);
  
  var elementoValorConvertido = document.getElementById("valorConvertido");
  var valorConvertido = "O resultado em Real eh R$ " + valorEmReal;
  elementoValorConvertido.innerHTML = valorConvertido;
}
