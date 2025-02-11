---
{}
---
“THE ROOT OF WISDOM IS TO FEAR THE LORD, AND THE BRANCHES THEREOF ARE LONG LIFE.” ECCLESIASTICUS 1:20

(inscribed above the throne in the Chapel of the Company Anchorite)

*Go quietly.*

*The Haustorium is not quite so kind as Hush House, but the foolish do not become librarians.*

Welcome, early readers. Give exploration a try, beginning with the [[apachita|Apachita]] that guides the Know to the Haustorium.

<button id="catalogue-book-button">Catalogue a Book</button>

<script>
// Dynamic list of book pages using Liquid
const books = [
  {% for page in site.pages %}
    {% if page.path contains 'tomes' %}
      { url: "{{ page.url }}", title: "{{ page.title }}" },
    {% endif %}
  {% endfor %}
];

// Function to pick a random book page
function getRandomBook() {
  const randomIndex = Math.floor(Math.random() * books.length);
  return books[randomIndex];
}

// Add event listener to the button
document.getElementById('catalogue-book-button').addEventListener('click', function() {
  const randomBook = getRandomBook();
  if (randomBook) {
    window.location.href = randomBook.url; // Redirect to the random book page
  } else {
    alert("No books found.");
  }
});
</script>
