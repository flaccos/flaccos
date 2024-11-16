<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benvenuto nel mio sito web!</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">Chi Sono</a></li>
                <li><a href="#contact">Contatti</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section">
        <h1>Benvenuto nel mio sito web!</h1>
        <p>Qui troverai informazioni su di me e i miei progetti.</p>
        <button onclick="changeContent()">Clicca per un messaggio speciale</button>
        <p id="special-message" style="display:none;">Grazie per aver visitato il mio sito!</p>
    </section>

    <section id="about" class="section">
        <h2>Chi Sono</h2>
        <p>Sono un appassionato di sviluppo web e amo creare siti e applicazioni per il web.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contattami</h2>
        <p>Puoi contattarmi via email: <a href="mailto:esempio@email.com">esempio@email.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Il Mio Sito Web</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
