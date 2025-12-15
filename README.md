<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hadia AI</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Ajout de React et Babel pour fonctionner sans build -->
  <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
</head>
<body class="min-h-screen bg-gray-50 flex items-center justify-center">
  <div id="root"></div>

  <!-- Ton code React écrit directement ici -->
  <script type="text/babel">
    function App() {
      return (
        <div className="text-center">
          <h1 className="text-4xl font-bold text-blue-600 mb-4">Hadia AI</h1>
          <p className="text-gray-700">Le projet est en ligne ! 🚀</p>
        </div>
      );
    }

    const root = ReactDOM.createRoot(document.getElementById('root'));
    root.render(<App />);
  </script>
</body>
</html>
