<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplu HTML cu CSS</title>
    <style>
        /* CSS pentru întreaga pagină */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        /* Stiluri pentru header */
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Stiluri pentru secțiunea principală */
        main {
            padding: 20px;
        }

        /* Stiluri pentru cardurile de conținut */
        .card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 10px 0;
            text-align: center;
        }

        .card h2 {
            margin-top: 0;
            color: #333;
        }

        .card p {
            color: #555;
        }

        /* Stiluri pentru footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Stiluri pentru buton */
        .btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
            display: inline-block;
        }

        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Pagina mea cu HTML și CSS</h1>
    </header>

    <!-- Main content -->
    <main>
        <section class="card">
            <h2>Despre mine</h2>
            <p>Acesta este un exemplu de pagină web creată cu HTML și CSS. Aici, voi adăuga informații despre mine și proiectele mele.</p>
            <a href="#" class="btn">Citește mai mult</a>
        </section>

        <section class="card">
            <h2>Proiecte</h2>
            <p>Am lucrat la diverse proiecte interesante care includ dezvoltare web, aplicații mobile și multe altele.</p>
            <a href="#" class="btn">Vezi proiectele</a>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Exemplu Pagina Web</p>
    </footer>

</body>
</html>
