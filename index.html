<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chimie du Non_Homme</title>
    <style>
        /* Styles de base et mobile-first */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            line-height: 1.6;
            padding-bottom: 70px; /* Espace pour la barre de navigation */
        }
        header {
            background-color: #1f1f1f;
            padding: 15px;
            text-align: center;
            border-bottom: 2px solid #00bcd4;
        }
        header h1 { font-size: 1.4em; color: #00bcd4; }
        header p { font-size: 0.8em; color: #b0b0b0; }

        /* Barre de navigation inférieure */
        .navbar {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            background-color: #1f1f1f;
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            border-top: 1px solid #333;
            z-index: 100;
        }
        .navbar button {
            background: none;
            border: none;
            color: #b0b0b0;
            font-size: 0.9em;
            padding: 8px 12px;
            cursor: pointer;
            border-radius: 5px;
            transition: all 0.2s;
        }
        .navbar button.active, .navbar button:hover {
            color: #00bcd4;
            background-color: #2a2a2a;
        }

        /* Contenu principal */
        .container { padding: 15px; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }

        /* Recherche */
        #searchInput {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border-radius: 8px;
            border: 1px solid #444;
            background-color: #2a2a2a;
            color: #e0e0e0;
            font-size: 1em;
        }

        /* Liste des définitions */
        #definitionsList { list-style: none; }
        .definition-item {
            background-color: #1e1e1e;
            border-radius: 8px;
            padding: 12px;
            margin-bottom: 10px;
            border-left: 4px solid #00bcd4;
        }
        .definition-item .term {
            font-weight: bold;
            color: #00bcd4;
            font-size: 1.1em;
            cursor: pointer;
        }
        .definition-item .definition {
            margin-top: 5px;
            color: #ccc;
            font-size: 0.95em;
        }
        .category-badge {
            display: inline-block;
            background-color: #333;
            color: #b0b0b0;
            font-size: 0.7em;
            padding: 2px 6px;
            border-radius: 4px;
            margin-top: 5px;
            margin-right: 5px;
        }

        /* Challenge */
        #challenge-area { text-align: center; padding: 20px 10px; }
        #timer { font-size: 2.5em; font-weight: bold; color: #ff4081; margin: 10px 0; }
        #challenge-question { font-size: 1.3em; font-weight: bold; color: #00bcd4; margin: 20px 0 10px; }
        #challenge-input {
            width: 90%;
            padding: 12px;
            font-size: 1.1em;
            border-radius: 8px;
            border: 1px solid #444;
            background-color: #2a2a2a;
            color: #fff;
            text-align: center;
            margin-bottom: 10px;
        }
        #feedback { height: 25px; font-weight: bold; margin: 10px 0; }
        .correct { color: #4caf50; }
        .incorrect { color: #f44336; }
        #start-challenge {
            background-color: #00bcd4;
            color: #121212;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.2s;
        }
        #start-challenge:hover { background-color: #00e5ff; }
        #score { font-size: 1.2em; margin-top: 15px; color: #ff4081; font-weight: bold; }
        .hidden { display: none; }

        /* Ajouter un terme */
        #add-term-form input, #add-term-form textarea, #add-term-form select {
            width: 100%;
            padding: 12px;
            margin-bottom: 12px;
            border-radius: 8px;
            border: 1px solid #444;
            background-color: #2a2a2a;
            color: #e0e0e0;
            font-size: 1em;
        }
        #add-term-form button {
            background-color: #00bcd4;
            color: #121212;
            border: none;
            padding: 15px;
            font-size: 1.1em;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
        }
        #add-term-form button:hover { background-color: #00e5ff; }
        #add-message { text-align: center; margin-top: 10px; font-weight: bold; }

        /* Styles pour les petits écrans */
        @media (min-width: 600px) {
            .container { max-width: 600px; margin: 0 auto; }
            header h1 { font-size: 1.8em; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Chimie du Non_Homme</h1>
        <p>Prêt pour le concours ?</p>
    </header>

    <main class="container">
        <!-- Onglet Base de Connaissances -->
        <section id="tab-definitions" class="tab-content active">
            <input type="text" id="searchInput" placeholder="Rechercher un terme ou une définition...">
            <ul id="definitionsList"></ul>
        </section>

        <!-- Onglet Challenge -->
        <section id="tab-challenge" class="tab-content">
            <div id="challenge-area">
                <div id="challenge-start">
                    <p>Prêt à te défier ? Tu as 1 minute pour répondre à un maximum de questions.</p>
                    <button id="start-challenge">Démarrer le Challenge</button>
                </div>
                <div id="challenge-game" class="hidden">
                    <div id="timer">01:00</div>
                    <div id="challenge-question">Question...</div>
                    <input type="text" id="challenge-input" placeholder="Ta réponse ici" autocomplete="off">
                    <div id="feedback"></div>
                    <div id="score">Score: 0</div>
                </div>
            </div>
        </section>

        <!-- Onglet Ajouter un Terme -->
        <section id="tab-add" class="tab-content">
            <form id="add-term-form">
                <input type="text" id="new-term" placeholder="Terme (ex: Ion)" required>
                <textarea id="new-definition" placeholder="Définition (ex: Atome ou molécule ayant perdu ou gagné un ou plusieurs électrons.)" rows="3" required></textarea>
                <select id="new-category">
                    <option value="Général">Général</option>
                    <option value="Chimie Organique">Chimie Organique</option>
                    <option value="Chimie Inorganique">Chimie Inorganique</option>
                    <option value="Chimie Analytique">Chimie Analytique</option>
                    <option value="Chimie Physique">Chimie Physique</option>
                    <option value="Chimie des Matériaux">Chimie des Matériaux</option>
                </select>
                <button type="submit">Ajouter le Terme</button>
            </form>
            <div id="add-message"></div>
        </section>
    </main>

    <nav class="navbar">
        <button class="active" data-tab="definitions">📚 Définitions</button>
        <button data-tab="challenge">⚡ Challenge</button>
        <button data-tab="add">➕ Ajouter</button>
    </nav>

    <script>
        // Base de données initiale (extraite de sources fiables)
        const initialData = [
            { term: "Acide", definition: "Espèce moléculaire capable de céder un proton H+ (acide de Bronsted) pour donner la base conjuguée correspondante, ou d'accepter un doublet électronique (acide de Lewis).", category: "Général" },
            { term: "Base", definition: "Espèce chimique capable de capter un proton H+ ou de donner un doublet électronique.", category: "Général" },
            { term: "Atome", definition: "Plus petite partie d'un élément chimique qui conserve les propriétés de cet élément. Il est composé d'un noyau (protons et neutrons) et d'électrons.", category: "Général" },
            { term: "Molécule", definition: "Ensemble d'atomes liés entre eux par des liaisons chimiques, formant la plus petite particule d'un composé chimique qui conserve ses propriétés.", category: "Général" matière },
            { term: "Ion.", definition: "Atome ou moléc Uneule ayant perdu ou gagné un ou plusieurs électrons, portant ainsi une charge électrique nette.", category: "Général" },
            { term: "Cation", definition: "Ion chargé positivement, ayant perdu un ou plusieurs électrons.", category: "Général" },
            { term: "Anion", definition: "Ion chargé négativement, ayant gagné un ou plusieurs électrons.", category: "Général" },
            { term: "Réaction chimique", definition: "Processus au cours duquel des substances (réactifs) se transforment en d'autres substances (produits).", category: "Général" },
            { term: "Catalyseur", definition: "Substance qui accélère une réaction chimique sans être consommée par celle-ci.", category: "Général" },
            { term: "Équation chimique", definition: "Représentation symbolique d'une réaction chimique, montrant les réactifs et les produits avec leurs coefficients stœchiométriques.", category: "Général" },
            { term: "Mole", definition: "Unité de mesure de la quantité de mole contient exactement 6,02214076×10^23 entités élémentaires (atomes, molécules, ions, etc.).", category: "Général" },
            { term: "Nombre d'Avogadro", definition: "Constante valant 6,02214076×10^23 mol^-1, représentant le nombre d'entités dans une mole.", category: "Général" },
            { term: "Masse molaire", definition: "Masse d'une mole d'une substance, exprimée en g/mol.", category: "Général" },
            { term: "Concentration molaire", definition: "Quantité de matière de soluté dissoute par unité de volume de solution, exprimée en mol/L.", category: "Général" },
            { term: "pH", definition: "Potentiel hydrogène, mesure de l'acidité ou de la basicité d'une solution. pH = -log[H+].", category: "Général" },
            { term: "Oxydation", definition: "Perte d'électrons par une espèce chimique.", category: "Général" },
            { term: "Réduction", definition: "Gain d'électrons par une espèce chimique.", category: "Général" },
            { term: "Endothermique", definition: "Se dit d'une transformation qui absorbe de la chaleur.", category: "Chimie Physique" },
            { term: "Exothermique", definition: "Se dit d'une transformation qui libère de la chaleur.", category: "Chimie Physique" },
            { term: "Enthalpie", definition: "Fonction d'état définie par la somme de l'énergie interne d'un système et du produit de sa pression par son volume.", category: "Chimie Physique" },
            { term: "Entropie", definition: "Fonction d'état qui sert à mesurer le degré de désordre d'un système.", category: "Chimie Physique" },
            { term: "Énergie d'activation", definition: "Énergie minimale qu'il faut fournir à des réactifs pour qu'il y ait une réaction chimique.", category: "Chimie Physique" },
            { term: "Isomère", definition: "Molécule organique qui possède la même formule brute qu'une autre molécule, mais qui a une formule semi-développée ou une formule développée différente.", category: "Chimie Organique" },
            { term: "Groupe fonctionnel", definition: "Atome ou groupe d'atomes qui confère des propriétés caractéristiques à une molécule organique (ex: hydroxyle -OH, carboxyle -COOH).", category: "Chimie Organique" },
            { term: "Alcane", definition: "Hydrocarbure saturé, de formule générale CnH2n+2.", category: "Chimie Organique" },
            { term: "Alcène", definition: "Hydrocarbure insaturé comportant au moins une double liaison carbone-carbone, de formule générale CnH2n.", category: "Chimie Organique" },
            { term: "Alcyne", definition: "Hydrocarbure insaturé comportant au moins une triple liaison carbone-carbone, de formule générale CnH2n-2.", category: "Chimie Organique" },
            { term: "Alcool", definition: "Composé organique contenant un groupe hydroxyle (-OH) lié à un atome de carbone saturé.", category: "Chimie Organique" },
            { term: "Aldéhyde", definition: "Composé organique contenant un groupe carbonyle (C=O) lié à un atome d'hydrogène et à un atome de carbone.", category: "Chimie Organique" },
            { term: "Cétone", definition: "Composé organique contenant un groupe carbonyle (C=O) lié à deux atomes de carbone.", category: "Chimie Organique" },
            { term: "Acide carboxylique", definition: "Composé organique contenant un groupe carboxyle (-COOH).", category: "Chimie Organique" },
            { term: "Amine", definition: "Composé organique dérivé de l'ammoniac (NH3) par remplacement d'un ou plusieurs atomes d'hydrogène par des groupes alkyles ou aryles.", category: "Chimie Organique" },
            { term: "Polymère", definition: "Macromolécule constituée de l'enchaînement répétitif d'unités monomères.", category: "Chimie Organique" },
            { term: "Analyte", definition: "Espèce chimique recherchée, détectée et éventuellement dosée selon un protocole analytique.", category: "Chimie Analytique" },
            { term: "Chromatographie", definition: "Technique de séparation des constituants d'un mélange basée sur leur distribution différentielle entre une phase mobile et une phase stationnaire.", category: "Chimie Analytique" },
            { term: "Titrage", definition: "Dosage volumétrique permettant de déterminer la concentration d'une espèce en solution en utilisant une réaction chimique.", category: "Chimie Analytique" },
            { term: "Spectroscopie", definition: "Étude de l'interaction entre la matière et un rayonnement électromagnétique.", category: "Chimie Analytique" },
            { term: "Ligand", definition: "Ion ou molécule lié à un atome central (souvent un métal) dans un complexe de coordination.", category: "Chimie Inorganique" },
            { term: "Hapticité", definition: "Aptitude d'un ligand comportant deux ou plusieurs atomes consécutifs reliés par un système d'électrons π à s'attacher globalement, par une seule liaison impliquant les électrons π délocalisés à l'atome central d'une entité de coordination.", category: "Chimie Inorganique" },
            { term: "Graphène", definition: "Variété allotropique du carbone, qui se présente sous la forme d'un feuillet constitué d'un pavage hexagonal régulier d'atomes de carbone.", category: "Chimie des Matériaux" },
            { term: "Nanocomposite", definition: "Matériau nanostructuré composé de plusieurs phases dont une au moins présente des éléments structuraux de dimension nanométrique.", category: "Chimie des Matériaux" }
        ];

        // --- Gestion des données ---
        let terms = [];
        let challengeInterval;
        let challengeTimeout;
        let currentChallengeTerm = null;
        let score = 0;
        let timeLeft = 60;

        // Charger les données depuis localStorage ou utiliser les données initiales
        function loadData() {
            const stored = localStorage.getItem('chimieNonHommeData');
            if (stored) {
                terms = JSON.parse(stored);
            } else {
                terms = [...initialData];
                saveData();
            }
        }

        // Sauvegarder les données dans localStorage
        function saveData() {
            localStorage.setItem('chimieNonHommeData', JSON.stringify(terms));
        }

        // --- Navigation par onglets ---
        const navButtons = document.querySelectorAll('.navbar button');
        const tabContents = document.querySelectorAll('.tab-content');

        navButtons.forEach(button => {
            button.addEventListener('click', () => {
                // Mettre à jour l'état actif des boutons
                navButtons.forEach(btn => btn.classList.remove('active'));
                button.classList.add('active');

                // Afficher l'onglet correspondant
                const tabId = button.dataset.tab;
                tabContents.forEach(tab => {
                    tab.classList.remove('active');
                    if (tab.id === `tab-${tabId}`) {
                        tab.classList.add('active');
                    }
                });

                // Actions spécifiques lors du changement d'onglet
                if (tabId === 'definitions') {
                    renderDefinitions();
                } else if (tabId === 'challenge') {
                    resetChallenge();
                }
            });
        });

        // --- Onglet Définitions ---
        const definitionsList = document.getElementById('definitionsList');
        const searchInput = document.getElementById('searchInput');

        function renderDefinitions(filter = '') {
            definitionsList.innerHTML = '';
            const filteredTerms = terms.filter(item =>
                item.term.toLowerCase().includes(filter.toLowerCase()) ||
                item.definition.toLowerCase().includes(filter.toLowerCase())
            );

            if (filteredTerms.length === 0) {
                definitionsList.innerHTML = '<li class="definition-item">Aucun résultat trouvé.</li>';
                return;
            }

            filteredTerms.forEach(item => {
                const li = document.createElement('li');
                li.className = 'definition-item';
                li.innerHTML = `
                    <div class="term">${item.term}</div>
                    <div class="definition">${item.definition}</div>
                    <span class="category-badge">${item.category}</span>
                `;
                definitionsList.appendChild(li);
            });
        }

        searchInput.addEventListener('input', (e) => {
            renderDefinitions(e.target.value);
        });

        // --- Onglet Challenge ---
        const startBtn = document.getElementById('start-challenge');
        const challengeStartDiv = document.getElementById('challenge-start');
        const challengeGameDiv = document.getElementById('challenge-game');
        const timerEl = document.getElementById('timer');
        const questionEl = document.getElementById('challenge-question');
        const challengeInput = document.getElementById('challenge-input');
        const feedbackEl = document.getElementById('feedback');
        const scoreEl = document.getElementById('score');

        // Audio context pour le son d'ambiance (un simple bip périodique)
        let audioCtx;

        function playBackgroundSound() {
            if (!audioCtx) return;
            const oscillator = audioCtx.createOscillator();
            const gainNode = audioCtx.createGain();
            oscillator.type = 'sine';
            oscillator.frequency.setValueAtTime(220, audioCtx.currentTime); // La 3
            gainNode.gain.setValueAtTime(0.03, audioCtx.currentTime); // Volume bas
            oscillator.connect(gainNode);
            gainNode.connect(audioCtx.destination);
            oscillator.start();
            oscillator.stop(audioCtx.currentTime + 0.1); // Bip court
        }

        function startChallenge() {
            // Initialiser l'audio context au premier clic (nécessaire sur mobile)
            if (!audioCtx) {
                try {
                    audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                } catch (e) {
                    console.warn("AudioContext non supporté");
                }
            }

            resetChallenge();
            challengeStartDiv.classList.add('hidden');
            challengeGameDiv.classList.remove('hidden');
            score = 0;
            scoreEl.textContent = `Score: ${score}`;
            timeLeft = 60;
            timerEl.textContent = '01:00';
            feedbackEl.textContent = '';
            feedbackEl.className = '';
            challengeInput.value = '';
            challengeInput.focus();

            // Lancer le chrono
            challengeInterval = setInterval(() => {
                timeLeft--;
                const minutes = Math.floor(timeLeft / 60).toString().padStart(2, '0');
                const seconds = (timeLeft % 60).toString().padStart(2, '0');
                timerEl.textContent = `${minutes}:${seconds}`;

                // Jouer un son de fond périodique
                if (audioCtx && timeLeft > 0 && timeLeft % 2 === 0) {
                    playBackgroundSound();
                }

                if (timeLeft <= 0) {
                    endChallenge();
                }
            }, 1000);

            // Afficher la première question
            askQuestion();
        }

        function endChallenge() {
            clearInterval(challengeInterval);
            clearTimeout(challengeTimeout);
            challengeGameDiv.classList.add('hidden');
            challengeStartDiv.classList.remove('hidden');
            alert(`Temps écoulé ! Ton score est de ${score}.`);
            resetChallenge();
        }

        function resetChallenge() {
            clearInterval(challengeInterval);
            clearTimeout(challengeTimeout);
            challengeStartDiv.classList.remove('hidden');
            challengeGameDiv.classList.add('hidden');
            feedbackEl.textContent = '';
            feedbackEl.className = '';
            challengeInput.value = '';
            questionEl.textContent = 'Question...';
            timerEl.textContent = '01:00';
            scoreEl.textContent = 'Score: 0';
            currentChallengeTerm = null;
        }

        function askQuestion() {
            if (terms.length === 0) {
                questionEl.textContent = "Ajoutez des termes pour commencer !";
                return;
            }
            // Choisir une définition au hasard
            const randomIndex = Math.floor(Math.random() * terms.length);
            currentChallengeTerm = terms[randomIndex];
            questionEl.textContent = `Quel terme correspond à cette définition : "${currentChallengeTerm.definition}"`;
            challengeInput.value = '';
            challengeInput.focus();
        }

        function checkAnswer() {
            if (!currentChallengeTerm) return;
            const userAnswer = challengeInput.value.trim().toLowerCase();
            const correctAnswer = currentChallengeTerm.term.toLowerCase();

            if (userAnswer === correctAnswer) {
                score++;
                scoreEl.textContent = `Score: ${score}`;
                feedbackEl.textContent = 'Correct !';
                feedbackEl.className = 'correct';
                // Passer à la question suivante après un court délai
                clearTimeout(challengeTimeout);
                challengeTimeout = setTimeout(() => {
                    askQuestion();
                }, 500);
            } else {
                feedbackEl.textContent = 'Incorrect !';
                feedbackEl.className = 'incorrect';
                // Ne pas passer à la question suivante immédiatement pour laisser le temps de lire
                // On efface le feedback après un délai
                clearTimeout(challengeTimeout);
                challengeTimeout = setTimeout(() => {
                    feedbackEl.textContent = '';
                    feedbackEl.className = '';
                }, 1000);
            }
        }

        startBtn.addEventListener('click', startChallenge);

        challengeInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                e.preventDefault();
                checkAnswer();
            }
        });

        // --- Onglet Ajouter un Terme ---
        const addForm = document.getElementById('add-term-form');
        const newTermInput = document.getElementById('new-term');
        const newDefinitionInput = document.getElementById('new-definition');
        const newCategorySelect = document.getElementById('new-category');
        const addMessage = document.getElementById('add-message');

        addForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const term = newTermInput.value.trim();
            const definition = newDefinitionInput.value.trim();
            const category = newCategorySelect.value;

            if (!term || !definition) {
                addMessage.textContent = 'Veuillez remplir tous les champs.';
                addMessage.style.color = '#f44336';
                return;
            }

            // Vérifier si le terme existe déjà
            const exists = terms.some(item => item.term.toLowerCase() === term.toLowerCase());
            if (exists) {
                addMessage.textContent = 'Ce terme existe déjà dans la base.';
                addMessage.style.color = '#f44336';
                return;
            }

            // Ajouter le nouveau terme
            terms.push({ term, definition, category });
            saveData();

            // Réinitialiser le formulaire
            newTermInput.value = '';
            newDefinitionInput.value = '';
            addMessage.textContent = 'Terme ajouté avec succès !';
            addMessage.style.color = '#4caf50';

            // Re-render la liste des définitions si elle est visible
            renderDefinitions(searchInput.value);

            // Effacer le message après quelques secondes
            setTimeout(() => {
                addMessage.textContent = '';
            }, 3000);
        });

        // --- Initialisation ---
        loadData();
        renderDefinitions();
    </script>
</body>
</html>