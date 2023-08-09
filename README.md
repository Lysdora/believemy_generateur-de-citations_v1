# believemy Generateur de citations v1

![Ceci est un exemple d’image](img/screenRandomQuote.png)

C'est un projet que j'ai realisé seule sans suivre le cours.

- J'ai commencé ma reflexion avec la methode Math.random pour generer un nombre aleatoire `const randomIndex = Math.floor(Math.random() * quote.length);
` j'ai multiplié par length de mon tableau.

- J'ai crée une variable qui reprendre l'index `const randomQuote = quote[randomIndex];`

- Avec mon eventlistener sur mon button j'ai preferé la simplicité de la function flechée pour generer la logique de mon code :baby_chick:

- `buttonQuote.addEventListener("click", () => {}`

- J'ai ensuite ajouter mes variables randomIndex et randomQuote dedans et j'ai changé le textContent de l'auteur et de la citation :

- `quoteContent.textContent = randomQuote[0];
quoteAuthor.textContent = randomQuote[1];`

C'est chouette le JavaScript :bee:
