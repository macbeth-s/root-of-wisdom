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
// Generate an array of book URLs using Liquid
const books = [
  {% for page in site.pages %}
    {% if page.path contains 'tomes' %}
      "{{ page.url }}", // Add the page URL as a string in the array
    {% endif %}
  {% endfor %}
].filter(Boolean); // This will remove any empty values that may result from the Liquid loop

// Check if the books array is populated correctly
console.log('Books Array:', books);  // Debugging: See the generated books array

// Check if the books array is empty
if (books.length === 0) {
  alert("No books found.");
}

// Function to pick a random book page
function getRandomBook() {
  const randomIndex = Math.floor(Math.random() * books.length);
  return books[randomIndex];
}

// Add event listener to the button
document.getElementById('catalogue-book-button').addEventListener('click', function() {
  const randomBook = getRandomBook();
  if (randomBook) {
    console.log('Redirecting to:', randomBook);  // Debugging: log the selected book URL
    window.location.href = randomBook; // Redirect to the random book page
  }
});
</script>
