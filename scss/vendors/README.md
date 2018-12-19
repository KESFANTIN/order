# Vendors

A maioria dos projetos terá uma pasta `vendors /` contendo todos os arquivos CSS de bibliotecas e estruturas externas
 - Normalize, Bootstrap, jQueryUI, FancyCarouselSliderjQueryPowered e assim por diante. Colocá-los de lado na mesma 
 pasta é uma boa maneira de dizer "Ei, isso não vem de mim, não do meu código, não da minha responsabilidade".

Se você tiver que substituir uma seção de qualquer fornecedor, eu recomendo que você tenha uma 8ª pasta chamada `vendors-extensions /`, 
na qual você pode ter arquivos nomeados exatamente depois dos fornecedores que eles sobrescrevem. Por exemplo, 
`vendors-extensions / _bootstrap.scss` é um arquivo que contém todas as regras CSS destinadas a declarar novamente alguns 
dos CSS padrão do Bootstrap. Isso é para evitar a edição dos arquivos do fornecedor, o que geralmente não é uma boa ideia.

Reference: [Sass Guidelines](http://sass-guidelin.es/) > [Architecture](http://sass-guidelin.es/#architecture) > [Vendors folder](http://sass-guidelin.es/#vendors-folder)
