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





body {
  width: 1000px;
  margin: auto;
  font-family: Arial, Helvetica, sans-serif;
  color: #222;
}

.emoji {
  display: grid;
  border: 1px solid #222;
  border-radius: 8px;
  padding: 1.5rem;
  /* grid-template-rows: repeat(4, 0.5fr); */
  gap: .5em;
  }

.emoji h2 {
  margin: 0;
  border-bottom: 2px solid #ccc;
  display: flex;
  justify-content: center;
  gap: .3em;
}

.emoji a {
  display: flex;
  display: block;
  text-decoration: none;
  background-color: #781BAA;
  color: white;
  padding: 1rem;
  border-radius: 8px;
}

.align {
  width: auto;
  height: auto;
  margin: 2rem;
  padding: 10px;
}

.icon {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 4rem;
  order: -1;
}

.emojis {
  /* margin: auto; */
  width: 1000px;
  display: grid;
  gap: 1.5em;
  grid-template-rows: repeat(2, 1fr);
  grid-template-columns: repeat(2, 1fr);
  margin: 2rem;
}