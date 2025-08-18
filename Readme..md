always start the project with npm run watch:css
the styles written in input.css will be appended in the style.css
@apply -  using this we can use the tailwinds availble utility classes


never put comment using --  as it creates problem in generating the style.css file 
comment syntax - /* */

in the new v4 version 
we don't need to go with tailwind.config.js for changing the default value 
we can simply go with @theme{ --breakpoint-sm:200px} and don't need to go with extend to make the other break points to make work.

