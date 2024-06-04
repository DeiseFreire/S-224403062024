:two_hearts: **LaTex: Função Composta gog(x)**

Este documento LaTex demonstra o cálculo da função composta `gog(x)`, onde:

* `f(x) = 3x - 1`
* `g(x) = x^2 + x - 1`

**Funções Definidas**

As funções `f(x)` e `g(x)` são definidas da seguinte maneira:

```latex
\bbox[orange, 8px]{f\left( x \right) = 3x - 1} \quad \text{e} \quad \bbox[orange, 8px]{g\left( x \right) = x^{2} + x - 1}
```

:two_hearts: **Cálculo de gog(x)**

A função composta `gog(x)` é calculada aplicando `g(x)` duas vezes, primeiro a `x` original e depois ao resultado de `g(x)`.

```latex
gog\left( x \right) = g\left( g\left( x \right) \right) = g\left( x^{2} + x - 1 \right)
```

Substituindo `g(x)` por sua definição na expressão anterior:

```latex
gog\left( x \right) = \left( x^{2} + x - 1\right)^{2} + \left( x^{2} + x - 1 \right) - 1 
```

:two_hearts: **Cálculo de (x² + x - 1)²**

Para encontrar `gog(x)`, precisamos calcular o quadrado de `x² + x - 1`. Segue o desenvolvimento:

```latex
\left[ x^{2} + \left( x - 1 \right) \right]^{2} =  \\

\Rightarrow x^{4} + x^{2} \cdot \left( x - 1 \right) + \left( x - 1 \right)^{2}   \\

\Rightarrow x^{4} + 2x^{3} - 2x^{2} + x^{2} - 2x + 1 \\ \\

\left[ x^{2} + \left( x - 1 \right) \right]^{2} = x^{4} + 2x^{3} - x^{2} - 2x + 1
```

:two_hearts: **Simplificando gog(x)**

Agora, podemos substituir o resultado de `(x² + x - 1)²` na expressão de `gog(x)` e simplificar:

```latex
\colorbox{Apricot}{Logo: $gog\left( x \right) = x^{4} + 2x^{3} - 2x - 1 + x^{2} + x - 1 - 1 $} \\

\Rightarrow \bbox[#CC3333]{\color{white}{gog\left( x \right) = x^{4} + 2x^{3} - x - 1}}
```

:two_hearts: **Conclusão**

Este documento LaTex demonstrou que a função composta `gog(x)` é igual a `x^4 + 2x^3 - x - 1`.

:two_hearts: **Imagem**
![imagem](https://github.com/DeiseFreire/S-224403062024/blob/main/imagem.png)

:two_hearts: **Tags**

#latex #mathematics #functioncomposition #mathfunctions #pdflatex #overleaf #texlive #education #opensource 

![brazil](https://github.com/pedromxavier/flag-badges/raw/main/badges/BR.svg)

