FrameLayout

Como funciona: coloca os elementos um em cima do outro (empilhados).

Útil para: Mostrar apenas 1 elemento.

Fazer sobreposição (ex: imagem de fundo + texto por cima).

Vantagem: simples e leve.

Desvantagem: ruim para telas complexas.

LinearLayout

Como funciona: organiza os elementos em linha reta, podendo ser:

Vertical (um embaixo do outro).

Horizontal (um ao lado do outro).

Útil para: formulários, menus simples, listas pequenas.

Vantagem: fácil de usar.

Desvantagem: se usar muitos níveis aninhados → desempenho ruim.

RelativeLayout

Como funciona: cada elemento pode ser colocado em relação a outro (ex: “esse botão fica abaixo do título”).

Útil para: organizar telas com elementos que dependem da posição uns dos outros.

Vantagem: flexível.

Desvantagem: foi substituído pelo ConstraintLayout, hoje pouco usado.

ConstraintLayout

Como funciona: organiza os elementos por restrições (constraints), que podem ser ligadas ao pai ou a outros elementos.

Útil para: Telas complexas. Interfaces responsivas (funcionam bem em várias telas).

Vantagem: moderno, eficiente, reduz o uso de muitos layouts aninhados.

Desvantagem: exige mais aprendizado.

RecyclerView Como funciona: mostra uma lista reciclável de elementos (itens reaproveitam a mesma estrutura para não pesar).

Útil para: Listas grandes (contatos, feed do Instagram). Exibir dados que mudam dinamicamente. 

Vantagem: muito eficiente. 

Desvantagem: precisa de mais configuração (Adapter + ViewHolder).
