## Como utilizar?

Inicialize seu projeto com npm init -y, altere o package.json adicionando a linha "type": "module", e tente instalar seu módulo (pacote).

uma vez instalado, para chamar o criador de avatares basta usar o seguinte comando:
~~~js
import lib from "@my-username/mylib";

// String contendo SVG criado
let svgText = lib.getSVG("ana123")
console.log(svgText);
~~~




