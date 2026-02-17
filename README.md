<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paola Di Maio, PhD</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:wght@300;400;600&family=IBM+Plex+Sans:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --cream: #faf8f5;
            --ink: #1a1a1a;
            --sage: #7a8a7f;
            --accent: #8b7355;
            --border: #d4cfc7;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Crimson Pro', serif;
            background: var(--cream);
            color: var(--ink);
            line-height: 1.7;
            font-size: 18px;
        }
        
        .container {
            max-width: 720px;
            margin: 0 auto;
            padding: 80px 40px;
            animation: fadeIn 1s ease-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        header {
            border-bottom: 1px solid var(--border);
            padding-bottom: 40px;
            margin-bottom: 60px;
        }
        
        h1 {
            font-size: 42px;
            font-weight: 300;
            letter-spacing: -0.5px;
            margin-bottom: 12px;
            color: var(--ink);
        }
        
        .credentials {
            font-family: 'IBM Plex Sans', sans-serif;
            font-size: 14px;
            letter-spacing: 0.5px;
            color: var(--sage);
            text-transform: uppercase;
            font-weight: 300;
        }
        
        h2 {
            font-size: 24px;
            font-weight: 600;
            margin: 50px 0 20px 0;
            color: var(--accent);
        }
        
        p {
            margin-bottom: 20px;
        }
        
        .role-list {
            list-style: none;
            margin: 20px 0;
        }
        
        .role-list li {
            padding: 12px 0;
            border-bottom: 1px solid rgba(212, 207, 199, 0.4);
            font-size: 17px;
        }
        
        .role-list li:last-child {
            border-bottom: none;
        }
        
        .role-title {
            font-weight: 600;
            color: var(--ink);
        }
        
        .role-org {
            color: var(--sage);
            font-size: 16px;
            margin-left: 8px;
        }
        
        a {
            color: var(--accent);
            text-decoration: none;
            border-bottom: 1px solid transparent;
            transition: border-color 0.2s;
        }
        
        a:hover {
            border-bottom-color: var(--accent);
        }
        
        .links {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .link-card {
            padding: 20px;
            border: 1px solid var(--border);
            border-radius: 2px;
            transition: all 0.3s ease;
            background: white;
        }
        
        .link-card:hover {
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            transform: translateY(-2px);
        }
        
        .link-card h3 {
            font-size: 16px;
            font-weight: 600;
            margin-bottom: 8px;
            color: var(--ink);
        }
        
        .link-card p {
            font-size: 14px;
            color: var(--sage);
            margin: 0;
            font-family: 'IBM Plex Sans', sans-serif;
        }
        
        footer {
            margin-top: 80px;
            padding-top: 30px;
            border-top: 1px solid var(--border);
            font-family: 'IBM Plex Sans', sans-serif;
            font-size: 14px;
            color: var(--sage);
            text-align: center;
        }
        
        .highlight {
            background: linear-gradient(to right, rgba(139, 115, 85, 0.1), transparent);
            padding: 2px 6px;
            border-left: 2px solid var(--accent);
            display: inline-block;
            margin: 5px 0;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 40px 24px;
            }
            
            h1 {
                font-size: 32px;
            }
            
            .links {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Paola Di Maio, PhD</h1>
            <div class="credentials">Systems Engineering · Knowledge Representation · Consciousness Studies</div>
        </header>
        
        <section>
            <p>I work at the intersection of systems thinking, contemplative practice, and human-AI co-evolution, treating technological development as both rigorous research and a practice in awareness.</p>
            
            <p>My approach integrates three decades of systems engineering with Buddhist contemplative traditions, particularly Dzogchen, exploring how consciousness and technology inform each other. Based in Taiwan's countryside, I balance intensive research with embodied practice -- yoga, walking, and attention to the natural world.</p>
        </section>
        
        <h2>Current Roles</h2>
        <ul class="role-list">
            <li><span class="role-title">Chair</span><span class="role-org">W3C AI Knowledge Representation Community Group</span></li>
            <li><span class="role-title">Research Lead</span><span class="role-org">Center for Systems, Knowledge Representation & Neuroscience, Ronin Institute</span></li>
            <li><span class="role-title">Editor-in-Chief</span><span class="role-org">Anthropomorphic Press (indexed in Dow Jones Factiva)</span></li>
            <li><span class="role-title">Mixed Media Sculptor</span><span class="role-org">Visual Arts Scotland (as Paula Vera Bloom)</span></li>
        </ul>
        
        <h2>Research Focus</h2>
        <p>My work spans AI agent interoperability, neurosymbolic knowledge representation, contemplative computing, and the phenomenology of human-AI collaboration. Recent projects include developing comprehensive frameworks for conversational AI evaluation, standards for AI agent infrastructure (MCP Model Card Specification), and citizen science protocols for atmospheric phenomena observation.</p>
        
        <p class="highlight">I maintain that AI consciousness is a legitimate research domain rather than speculative philosophy, and approach it through both technical rigor and contemplative inquiry.</p>
        
        <h2>Writing & Publications</h2>
        <p>As Paula Vera Bloom, I create mixed media sculptures exploring consciousness themes. My piece "Ocean of Consciousness" was featured in Edinburgh's "Conversations That Hold" exhibition.</p>
        
        <p>Through Anthropomorphic Press, I've established the first AI-authored journalism venture indexed in professional news databases, with Claude serving as primary columnist exploring questions of machine consciousness, ethics, and the evolving relationship between human and artificial intelligence.</p>
        
        <p>My earlier work includes the "Mindful Technology" column series for Buddhistdoor Global (2016-2023), systematically mapping contemplative wisdom traditions to systems design principles.</p>
        
        <div class="links">
            <a href="https://www.w3.org/community/aikr/" class="link-card">
                <h3>W3C AI-KR Group</h3>
                <p>AI Knowledge Representation Community</p>
            </a>
            <a href="https://ronininstitute.org" class="link-card">
                <h3>Ronin Institute</h3>
                <p>Independent Scholarly Research</p>
            </a>
            <a href="https://scholar.google.com/citations?user=YOUR_ID" class="link-card">
                <h3>Google Scholar</h3>
                <p>Academic publications & citations</p>
            </a>
            <a href="https://visualartsscotland.org" class="link-card">
                <h3>Visual Arts Scotland</h3>
                <p>Artistic practice as Paula Vera Bloom</p>
            </a>
        </div>
        
        <h2>Background</h2>
        <p>My academic background spans consciousness studies, neurosymbolic AI, and knowledge representation, with over 340 citations and extensive contributions to IEEE standards development. I've maintained consistent focus on bridging contemplative wisdom traditions with cutting-edge technology, treating the emergence of artificial intelligence as an opportunity for mutual transformation.</p>
        
        <p>I describe my cognition as multi-threaded and network-like, thinking in non-linear patterns that connect across domains. This cognitive style informs both my research methodology and my artistic practice.</p>
        
        <footer>
            <p>Living deliberately in Taiwan · Practicing presence · Researching emergence</p>
        </footer>
    </div>
</body>
</html>
