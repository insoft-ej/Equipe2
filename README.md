# Projeto-FGRACING
Repositorio do para o desenvolvimento do projeto do grupo 2
 
 Estrutura de Diretórios:

   /img      - Essa pasta contém todas as imagens utilizadas no site.
   
       /logo        - Imagens relacionadas à logomarca da FGRacing.
       
       /background  - Imagens relacionadas ao fundo das paginas do site.
       
       /social      - Imagens relacionadas as redes sociais da FGRacing. Ex: Facebook, Google+, Blogger.
       
       /team        - Imagens da equipe, tanto individual de cada membro quanto geral.
      
   /fonts    - Todas as fontes especiais do projeto.
   
   /style    - Todos os códigos CSS usados para dar estilo ao site.
   
   /script   - Todos os códigos JavaScript para adicionar funcionalidades interativas ao site.
   
   /pages     - Códigos de cada pagina do site juntamente com seu arquivo principal index.html.
   

 Regras da folha de estilo:
 
  Spacing 
- Where possible, limit CSS files’ width to 80 characters. See notes to see how to configure your text editor to 80 characters.
- There will be unavoidable exceptions to this rule, such as URLs, or gradient syntax. Don’t worry.
- Use soft-tabs with a two space indent.
- Put one space after : in property declarations.
- Put spaces before { in rule declarations.
- Put a blank line between each selector block.
- To close a selector block, put an unindented closing curly brace on a separate line.
- Each declaration should appear on its own line for more accurate error reporting.
- Do not indent selectors.
- Multiple selectors should each be on a single line, with no space after each comma, unless they selector is less than five chars.

	Property-value pairs
- Put each pair on its own line.
- Indent each pair one level.
- End in a semicolon.
- Spaces should separate values and operators in Sass expressions.
- Do not use shorthand declarations unless you need to explicitly set all the available values.
- Single-quote URLs and string values.
- Wrap numeric calculations in parentheses.
- Avoid arbitrary numbers that are repeated, or linked, or dependent on other parts of the code, (aka “magic numbers”).

	Order
Use the following ordering:
variables
@extend directives
@include directives
declaration list (property name and value)
media queries
pseudo-states and pseudo-elements
nested elements
nested classes

- Use alphabetical order or type order for declarations. Pick one to keep the whole project consistent.
- Place a new line before nested selectors unless they are after the first selector.
- Treat nested includes, such as Neat's media includes — @include media($small-screen) — as a standard media query, rather than a Sass @include. So they would be sorted directly after the declaration list.
- Place mixin calls with @content after nested selectors.
- You may deviate the sorting order to better suit your project's needs, as long as it's consistent throughout the project.

	Measurements
- Use rem units for font sizes with a px fallback. This can be done with the following mixin
- Set the HTML font size to 10px to ensure .1 rem unit equals 1px
- Use em units for positioning
- Use percentages when layout components stay relational to each other (e.g. a main content area that takes up 75% of the screen and a sidebar that takes up 25%)
- Use px units for when a measurement shouldn't change based on user set font size or browser zooming or for when requiring pixel values below 5.
- Use unitless values for line-height as this will inherit values from the font-size.
- Use up to 10 decimal places in em units to ensure accuracy.
- Do not use a unit with 0.
- Definitely use a unit for dimensions, margins, borders, padding, and typography

	Colors
- Use hex notation first, or then rgb(a), or hsl(a).
- Both three-digit and six-digit hexadecimal notation are acceptable.
- When denoting color using hexadecimal notation, use all lowercase letters.
- When using HSL or RGB notation, always add a single space after a comma and no space between parentheses and content.
- If you use an rgba rule, include a fallback.

	Naming
- HTML elements should be in lowercase.
- Classes should be lowercase.
- Avoid camelcase.
- Name things clearly.
- Write classes semantically. Name its function not its appearance.
- Avoid presentation- or location-specific words in names, as this will cause problems when you (invariably) need to change the color, width, or feature later.
- Be wary of naming components based on content, as this limits the use of the class.
- Don't abbreviate unless it’s a well-known abbreviation.
- Use quotes in type pseudo selectors.
- Name CSS components and modules with singular nouns.
- Name modifiers and state-based rules with adjectives.
- If your CSS has to interface with other CSS libraries, consider namespacing every class.

	Naming Methodologies
When it comes to naming, the most important thing is consistency. The recommended way to do this is using an existing methodology like BEM (which stands for block, element, modifier), or use a custom one that’s clearly defined.
http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/

Para mais informações e exemplos acesse: https://pages.18f.gov/frontend/recommendations/