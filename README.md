
body {
    font-family: 'Arial', sans-serif;
    background: linear-gradient(to right, #ffecd2, #fcb69f);
    margin: 0;
    padding: 0;
}

header {
    background-color: #ff6f61;
    color: white;
    text-align: center;
    padding: 2rem 1rem;
    border-bottom: 5px solid #ffa07a;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

nav li {
    margin: 0.5rem;
}

nav a {
    text-decoration: none;
    color: white;
    background-color: #ffa07a;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    transition: background 0.3s;
}

nav a:hover {
    background-color: #ffdab9;
    color: #333;
}

main {
    padding: 2rem;
}

section {
    margin-bottom: 4rem;
}

h2 {
    color: #ff4b2b;
    font-size: 2rem;
    margin-bottom: 1rem;
    border-bottom: 2px solid #ff4b2b;
    padding-bottom: 0.5rem;
}

.video-container {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
}

iframe {
    width: 100%;
    max-width: 480px;
    height: 270px;
    border: 3px solid #ff4b2b;
    border-radius: 10px;
}

footer {
    background-color: #ff6f61;
    color: white;
    text-align: center;
    padding: 1rem;
    border-top: 5px solid #ffa07a;
}
