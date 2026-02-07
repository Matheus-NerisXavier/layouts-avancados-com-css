# Position

- static -> default (padrão) 

- relative -> offset relativo a si mesmo -> normal flow -> stacking context

- absolute -> fica em um determinado local da tela (relativo ao containing block próximo ou initial) -> !normal flow -> stacking context

- fixed -> fixo na tela (relativo ao initial containing block) -> ! normal flow -> stacking context

- sticky -> relativo e fixo (relativo ao elemento pai que tenh amecanismo de scroll overflow) -> normal flow -> stacking context

## Props

- top, bottom
- left, right
- inset
- z-index