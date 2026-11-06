<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Profil Étudiant</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            max-width: 400px;
            text-align: center;
            animation: fadeIn 1s ease-in-out;
        }
        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: #cbd5e1;
            margin: 0 auto 1.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: #475569;
            border: 4px solid #667eea;
        }
        h1 {
            font-size: 1.8rem;
            color: #1e293b;
            margin-bottom: 0.5rem;
        }
        .subtitle {
            color: #64748b;
            font-size: 1rem;
            margin-bottom: 1.5rem;
        }
        .bio {
            font-size: 0.95rem;
            color: #475569;
            line-height: 1.6;
            margin-bottom: 1.5rem;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            justify-content: center;
        }
        .tag {
            background: #e0e7ff;
            color: #3730a3;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="avatar">🎓</div>
        <h1KAHAMBU SIWATHULA </h1>
        <div class="subtitle">Étudiant·e en Informatique / Tech</div>
        <p class="bio">
            Passionné·e par le développement web, les nouvelles technologies et la création de solutions innovantes. Bienvenue sur mon portfolio de TP !
        </p>
        <div class="skills">
            <span class="tag">HTML5</span>
            <span class="tag">CSS3</span>
            <span class="tag">Git & GitHub</span>
            <span class="tag">Résolution de problèmes</span>
        </div>
    </div>

</body>
</html>


