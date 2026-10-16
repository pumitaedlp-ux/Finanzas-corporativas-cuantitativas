# Finanzas de Empresas · Resumen integral en LaTeX

**[Español](#español) · [Português](#português)**

> **Próximamente:** versión del resumen en portugués.
>
> **Em breve:** versão do resumo em português.
>
> **Apoyá el proyecto · Apoie o projeto:** [link.mercadopago.com.ar/quantumpuma](https://link.mercadopago.com.ar/quantumpuma)

---

## Español

Resumen de estudio de las **cinco unidades** de la materia **Finanzas de Empresas**, escrito en LaTeX en un único archivo `.tex`. Reúne la teoría, las definiciones, las fórmulas y las figuras de toda la bibliografía de la cátedra, sin repeticiones, para poder estudiar sin volver a los materiales originales.

### Contenido

| Unidad | Tema | Incluye |
|:-:|---|---|
| 1 | Empresa y modelos financieros | Función financiera, objetivo de la empresa, valor actual y flujo de fondos disponible (FCFF) |
| 2 | Cash flow y planificación financiera | Estados financieros, impuestos, razones financieras, cash flow y estados proyectados |
| 3 | Estructura de capital, costo de capital y punto de equilibrio | Modigliani-Miller, impuestos y quiebra, WACC, métodos de valuación, punto de equilibrio y leverage |
| 4 | Política de dividendos y valuación de bonos y acciones | Dividendos y recompras, bonos, modelo de Gordon, PVGO y PER |
| 5 | Decisiones de inversión, riesgo y costo del capital | VPN y TIR, EVA, riesgo y rendimiento, portafolios, CAPM, APT y costo del capital |

### Características

- **Un solo archivo**, `Resumen_Finanzas_de_Empresas.tex`, con un capítulo por unidad.
- **Bloques con estética pixel art inspirada en Minecraft**: diamante para las definiciones y oro para las fórmulas.
- **Índices de definiciones (125) y de fórmulas (100)** ordenados por unidad, además del índice general y de referencias cruzadas entre unidades.
- **273 figuras** de los apuntes, insertadas con código LaTeX estándar (`figure` + `\includegraphics` + `\caption`).
- **Bloques opcionales** que se muestran u ocultan cambiando una línea: ejemplos numéricos (piedra), fichas de referencia (madera) y controles de cinco preguntas (esmeralda).

### Cómo compilar

1. Descargar `Resumen_Finanzas_de_Empresas.tex`.
2. Copiar las imágenes (`.jpg`, `.png` o `.pdf`), con su nombre original, en la misma carpeta del `.tex`. Si no están ahí, también se buscan en las subcarpetas `images/` y `MFJQ images/`.
3. Compilar con **pdfLaTeX** tres veces, para que se completen los índices y las referencias. Overleaf y `latexmk` repiten las pasadas solos.

Al comienzo del archivo, en el bloque `COMPLETAR`, se pueden escribir el curso y el nombre del alumno y elegir qué bloques se ven:

```latex
\renewcommand*{\Curso}{}
\renewcommand*{\Alumno}{}
\mostrarejemplosfalse     % \mostrarejemplostrue  muestra los ejemplos
\mostrarfichasfalse       % \mostrarfichastrue    muestra las fichas
\mostrarcontrolesfalse    % \mostrarcontrolestrue muestra los controles
```

### Bibliografía

- R. A. Fornero, texto de cátedra, Parte I: «Empresa y modelos financieros».
- G. L. Dumrauf, *Finanzas corporativas: un enfoque latinoamericano*, 3.ª ed., Alfaomega.
- S. Ross, R. Westerfield y J. Jaffe, *Finanzas corporativas*, McGraw-Hill.
- R. Brealey, S. Myers y F. Allen, *Principios de finanzas corporativas*, McGraw-Hill.
- L. J. Gitman, *Principios de administración financiera*, Pearson.
- Apuntes y notas de clase de la cátedra.

### Próximamente

Una versión del resumen en **portugués**.

### Apoyá el proyecto

Si el resumen te sirvió, podés hacer un aporte voluntario por Mercado Pago. Ingresá al link, elegí cómo pagar, ¡y listo!

**[link.mercadopago.com.ar/quantumpuma](https://link.mercadopago.com.ar/quantumpuma)**

### Aviso

Es un resumen de estudio de acceso gratuito; los aportes son voluntarios. Los textos y las figuras originales pertenecen a sus autores y editoriales.

---

## Português

Resumo de estudo das **cinco unidades** da disciplina **Finanzas de Empresas** (Finanças de Empresas), escrito em LaTeX em um único arquivo `.tex`. Reúne a teoria, as definições, as fórmulas e as figuras de toda a bibliografia da disciplina, sem repetições, para estudar sem precisar voltar aos materiais originais. O texto atual está em espanhol; **em breve haverá uma versão em português**.

### Conteúdo

| Unidade | Tema | Inclui |
|:-:|---|---|
| 1 | Empresa e modelos financeiros | Função financeira, objetivo da empresa, valor presente e fluxo de caixa livre da empresa (FCFF) |
| 2 | Fluxo de caixa e planejamento financeiro | Demonstrações financeiras, impostos, índices financeiros, fluxo de caixa e demonstrações projetadas |
| 3 | Estrutura de capital, custo de capital e ponto de equilíbrio | Modigliani-Miller, impostos e falência, WACC, métodos de avaliação, ponto de equilíbrio e alavancagem |
| 4 | Política de dividendos e avaliação de títulos e ações | Dividendos e recompras, títulos de dívida, modelo de Gordon, PVGO e P/L |
| 5 | Decisões de investimento, risco e custo do capital | VPL e TIR, EVA, risco e retorno, carteiras, CAPM, APT e custo do capital |

### Características

- **Um único arquivo**, `Resumen_Finanzas_de_Empresas.tex`, com um capítulo por unidade.
- **Blocos com estética pixel art inspirada no Minecraft**: diamante para as definições e ouro para as fórmulas.
- **Índices de definições (125) e de fórmulas (100)** organizados por unidade, além do sumário e de referências cruzadas entre as unidades.
- **273 figuras** das apostilas, inseridas com código LaTeX padrão (`figure` + `\includegraphics` + `\caption`).
- **Blocos opcionais** que aparecem ou somem mudando uma linha: exemplos numéricos (pedra), fichas de referência (madeira) e controles de cinco perguntas (esmeralda).

### Como compilar

1. Baixe o arquivo `Resumen_Finanzas_de_Empresas.tex`.
2. Copie as imagens (`.jpg`, `.png` ou `.pdf`), com o nome original, para a mesma pasta do `.tex`. Se não estiverem lá, elas também são procuradas nas subpastas `images/` e `MFJQ images/`.
3. Compile com **pdfLaTeX** três vezes, para completar os índices e as referências. O Overleaf e o `latexmk` repetem as compilações sozinhos.

No início do arquivo, no bloco `COMPLETAR`, é possível escrever a turma e o nome do aluno e escolher quais blocos aparecem:

```latex
\renewcommand*{\Curso}{}
\renewcommand*{\Alumno}{}
\mostrarejemplosfalse     % \mostrarejemplostrue  mostra os exemplos
\mostrarfichasfalse       % \mostrarfichastrue    mostra as fichas
\mostrarcontrolesfalse    % \mostrarcontrolestrue mostra os controles
```

### Bibliografia (edições em espanhol)

- R. A. Fornero, texto da disciplina, Parte I: «Empresa y modelos financieros».
- G. L. Dumrauf, *Finanzas corporativas: un enfoque latinoamericano*, 3.ª ed., Alfaomega.
- S. Ross, R. Westerfield e J. Jaffe, *Finanzas corporativas*, McGraw-Hill.
- R. Brealey, S. Myers e F. Allen, *Principios de finanzas corporativas*, McGraw-Hill.
- L. J. Gitman, *Principios de administración financiera*, Pearson.
- Apostilas e notas de aula da disciplina.

### Em breve

Uma versão do resumo em **português**.

### Apoie o projeto

Se o resumo foi útil para você, pode fazer uma contribuição voluntária pelo Mercado Pago. Acesse o link, escolha como pagar e pronto!

**[link.mercadopago.com.ar/quantumpuma](https://link.mercadopago.com.ar/quantumpuma)**

### Aviso

Este é um resumo de estudo de acesso gratuito; as contribuições são voluntárias. Os textos e as figuras originais pertencem a seus autores e editoras.
