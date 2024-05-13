Tu peux ajouter de nouvelles classes CSS chaque fois que tu veux créer un nouveau style. Veille à donner au style un nom judicieux.

Essaie de faire en sorte que ton style soit réutilisable et ne contienne que les propriétés que tu veux utiliser ensemble.

![Un scarabée entouré d'une bordure blanche. La bordure est plus large en bas.](images/beetle-photo.png)

Cette classe `photo` crée un style de photo imprimée qui peut être appliqué à une image.

## --- code ---

language: CSS
filename: style.css
line_numbers: false
--------------------------------------------------------

/\* Printed photo style \*/

.photo {
border: 1px solid #D0D0D0; /\* Add a solid border _/
width: 14rem;
height: 15rem;
background: #ffffff;
padding-top: 1rem;
padding-left: 1rem;
padding-right: 1rem;
padding-bottom: 3rem;
box-shadow: 8px 8px 10px 4px #888888; /_ right and bottom shadow, blur, spread, and colour \*/
transform: rotate(3deg);
}

\--- /code ---

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<section>
  <img class="photo" src="beetle.jpg">
</section>

\--- /code ---
