# Instructions

Fork this repository to start working on the assignment.

Here are the base CSS styles to start with.

```css
body {
  font-family: Arial, Helvetica, sans-serif;
  color: #222;
}

.emoji {
  border: 1px solid #222;
  border-radius: 8px;
  padding: 1rem;
  display: grid;
  margin: 200px;
  }

.emoji h2 {
  margin: 0;
  border-bottom: 2px solid #ccc;
}

.emoji a {
  text-decoration: none;
  background-color: #781BAA;
  color: white;
  padding: 1rem;
  border-radius: 8px;
  text-align: center;
}

.icon {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 4rem;
}

.emojis {
  display: grid;
  grid-template-rows: repeat(2, 1fr);
  grid-template-columns: repeat(2, 1fr);
  margin: 2rem;
}

