# Documentació

## Guia d'estils
S'ha instal·lat stylelint amb una configuració estàndard amb algunes regles específiques de scss.

## HTML
S'ha afegit la propietat lang al HTML per a definir l'idioma principal del document.

S'han usat etiquetes semàntiques. Per definir el layout principal s'ha usat un header un main i un footer.

S'ha afegit un min-height de 100vh al main per garantir que el peu quede sempre a la part de baix de la pantalla.

He evitat en la mesura del possible fer resets globals seguint les guies d'estil estàndard de stylint per a scss. En el seu lloc s'han usat mixins per fer resets allà on ha sigut necessari, per exemple a l'estil de les llistes.

La responsivitat s'ha assolit amb flexbox i media queries.

## Dependències externes

S'han afegit com a dependències externes:

- Hamburgers (llibreria per fer el botó de menú animat)
- Fontawesome

## Validació
La web s'ha validat en els següents estàndards:
- CSS3: https://jigsaw.w3.org/css-validator/
- HTML5: https://validator.w3.org/
- Accessibility Review (Guidelines: WCAG 2.0 (Level AA)): https://achecker.ca/checker/index.php

## Deploy
La web s'ha publicat a https://eines2.netlify.app i el codi font està allotjat a https://github.com/jvmonjo/eines2-pac1
