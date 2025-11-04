# Fukxer-sales
Hs7a
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav a {
    color: white;
    text-decoration: none;
}

.hero {
    background-image: url('https://via.placeholder.com/1200x400?text=FUKXER+Banner');
    background-size: cover;
    color: white;
    text-align: center;
    padding: 4rem 2rem;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem;
}

.product {
    background: white;
    padding: 1rem;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.product img {
    max-width: 100%;
    height: auto;
}

button {
    background-color: #333;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

section {
    padding: 2rem;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}
