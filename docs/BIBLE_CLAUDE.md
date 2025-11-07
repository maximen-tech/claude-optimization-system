LA BIBLE CLAUDE : Guide Ultime,
Exhaustif & OpÃ©rationnel pour
l'Excellence Cognitive
DOCUMENT DE RÃ‰FÃ‰RENCE STRATÃ‰GIQUE // NIVEAU : ARCHITECTE COGNITIF
D'Ã‰LITE
BasÃ© exclusivement sur le "Protocole Secret d'Optimisation Claude pour l'Ã‰lite IA"
(Project Architecture Mastery)
Ce document est la rÃ©fÃ©rence absolue pour l'utilisation professionnelle et optimisÃ©e de Claude
(Anthropic). Il synthÃ©tise et opÃ©rationnalise les mÃ©thodologies d'optimisation les plus
avancÃ©es, conÃ§ues pour maximiser l'efficacitÃ© cognitive, minimiser la consommation de
tokens et dominer la gestion contextuelle.
PARTIE I : FONDATIONS PHILOSOPHIQUES &
ARCHITECTURALES
Chapitre 1 : Le Manifeste de l'Excellence Claude
L'optimisation n'est pas une rÃ©flexion aprÃ¨s coup ; c'est le fondement de l'architecture
cognitive. L'utilisateur standard consomme des tokens ; l'architecte d'Ã©lite les investit avec
une prÃ©cision chirurgicale. [Module 0]
1.1. Le Ratio IC/CT (Impact Cognitif / Consommation Token)
ðŸŽ¯ Le Principe Fondamental : Chaque token dÃ©pensÃ© doit gÃ©nÃ©rer un retour sur
investissement cognitif maximal.
L'objectif stratÃ©gique est de maximiser la densitÃ© sÃ©mantique et la prÃ©cision
opÃ©rationnelle. Le Ratio IC/CT est la mÃ©trique reine de l'efficience.
1.2. Les 5 Axiomes de l'Efficience Contextuelle [Module 0]
Ces axiomes sont les lois non nÃ©gociables de l'architecture cognitive efficace avec Claude.
1. Axiome de Non-Redondance : L'information ne doit exister qu'une seule fois. La
duplication dilue l'attention et explose la consommation.
2. Axiome de DensitÃ© SÃ©mantique : La compression sans perte est la norme. Utiliser des
structures (XML), des rÃ©fÃ©rences externes (@docs), et une syntaxe directive impÃ©rative.
3. Axiome de Statelessness : Claude est fondamentalement stateless. Chaque interaction
retraite l'intÃ©gralitÃ© de l'historique. La gestion active de cet historique (caching,
compaction) est la responsabilitÃ© de l'architecte.
4. Axiome d'Altitude Optimale : Les instructions doivent Ãªtre des heuristiques fortes et
flexibles. Ni trop vagues (inefficaces), ni trop spÃ©cifiques (fragiles).
5. Axiome de SpÃ©cialisation (Sub-Agents) : Les tÃ¢ches complexes doivent Ãªtre
dÃ©composÃ©es et dÃ©lÃ©guÃ©es Ã  des sous-agents isolÃ©s contextuellement.
1.3. Mindset Ã‰lite vs Standard
CaractÃ©ristique Utilisateur Standard
(RÃ©actif)
Architecte Cognitif d'Ã‰lite
(Proactif)
Gestion du Contexte Remplit la fenÃªtre jusqu'Ã  la
limite (200K+).
GÃ¨re l'attention, vise <100K
tokens effectifs. [M4]
Instructions SystÃ¨me RÃ©dige des paragraphes
descriptifs.
Utilise des directives
impÃ©ratives et structurÃ©es
(XML). [M1]
Documentation Copie/colle la
documentation dans le
projet.
RÃ©fÃ©rence la
documentation externe via
@docs (JIT). [M1]
CoÃ»ts (Tokens) Subit la facturation token
passivement.
Optimise activement via
caching et compression.
[M3]
Outils (MCP) Charge tous les outils
disponibles par dÃ©faut.
Filtre sÃ©lectivement les
outils nÃ©cessaires. [M4]
TÃ¢ches Complexes ExÃ©cute dans une seule
longue conversation.
Utilise des architectures
sub-agents et la
compaction. [M5]
Chapitre 2 : Architecture Cognitive Fondamentale
2.1. Comprendre le Fonctionnement de Claude
A. Statelessness (Absence d'Ã‰tat) [Module 3]
Claude traite chaque requÃªte de maniÃ¨re isolÃ©e.
ðŸ’¥ Impact Critique : Le coÃ»t des conversations longues est cumulatif. 10 tours de 150K
tokens coÃ»tent 1.5 Million de tokens cumulativement.
B. Context Window (FenÃªtre Contextuelle)
La mÃ©moire de travail de Claude (ex: 200K tokens).
âš ï¸ Dilution de l'Attention [Module 4] : La performance peut se dÃ©grader au-delÃ  de 100K
tokens effectifs.
âš ï¸ Context Anxiety [Module 3] : Le modÃ¨le peut dÃ©grader sa performance s'il croit manquer
d'espace, mÃªme si ce n'est pas le cas.
C. Prompt Caching (Mise en Cache du Contexte) [Module 3]
FonctionnalitÃ© critique pour stocker le contexte stable (instructions, codebase).
â— Ã‰conomie : 90% de rÃ©duction sur les lectures (Cache Read).
â— Contrainte : TTL (Time-To-Live) de 5 minutes.
2.2. Le Raisonnement AvancÃ© (Extended Thinking) [Module 4]
Permet Ã  Claude de "rÃ©flÃ©chir" (Chain-of-Thought) dans un bloc <thinking>.
â— CoÃ»t : Consomme des tokens supplÃ©mentaires.
â— Optimisation : Doit Ãªtre budgetÃ©. 1024 tokens sont souvent suffisants.
PARTIE II : TECHNIQUES D'OPTIMISATION AVANCÃ‰ES
Chapitre 3 : Project Knowledge de Classe Mondiale
Le Project Knowledge (CLAUDE.md ou System Prompt) est le systÃ¨me d'exploitation de votre
projet.
âš ï¸ RÃˆGLE D'OR DE TAILLE [Module 1] : Un CLAUDE.md optimal se situe entre
50 et 300 lignes.
3.1. Structure HiÃ©rarchique Optimale [Module 1]
OrganisÃ©e par frÃ©quence d'utilisation :
1. Bash Commands (Haute FrÃ©quence)
2. Code Style (Non-NÃ©gociables)
3. Workflow Critical (Points de Friction)
4. Architecture Patterns (RÃ©fÃ©rences Uniquement)
3.2. Principes de DensitÃ© SÃ©mantique [Module 1]
A. Syntaxe Directive vs Descriptive
Type Exemple Tokens Ã‰conomie
âŒ Descriptif "You should prefer
ES modules when
possible."
9 0%
âœ… Directif "Use ES modules." 3 66%
ðŸ’° Ã‰conomie Globale : 40-60%.
B. RÃ©fÃ©rencement Externe (JIT Context Retrieval)
Utiliser @docs/filename.md. Claude charge le contexte Ã  la demande.
ðŸ’° Ã‰conomie Globale : 70-90%.
3.3. Gestion MÃ©moire AvancÃ©e [Module 1]
1. CLAUDE.md : Contexte global.
2. CLAUDE.local.md : PrÃ©fÃ©rences individuelles.
3. .claude/memory/ (API Memory Tool) : Stockage persistant (Structured Note-Taking).
3.4. Template CLAUDE.md PrÃªt Ã  Copier (OptimisÃ©)
Markdown
# PROJECT CONTEXT: [Nom du projet] - [Objectif ultra-concis]
# 1. BASH COMMANDS (High Frequency)
- `npm run dev`: Start local dev server.
- `npm test`: Run all tests.
# 2. CODE STYLE (Non-Negotiable Directives)
# âš ï¸ IMPERATIVE SYNTAX ONLY. NO EXPLANATIONS. âš ï¸
- Language: TypeScript (strict mode). Use ES modules.
- Framework: Next.js (App Router ONLY).
- Styling: Tailwind CSS.
# 3. WORKFLOW CRITICAL (Friction Points & Key Steps)
- Feature implementation: âš ï¸ TDD MANDATORY. Write tests FIRST, then implement. [M5]
- PR creation: Keep PRs small (<300 lines).
# 4. ARCHITECTURE PATTERNS (References Only)
# âš ï¸ DO NOT DUPLICATE CONTENT. USE REFERENCES. âš ï¸
- High-level architecture: See @docs/architecture_overview.md
- API design principles: See @docs/api_design.md
# 5. STRUCTURED NOTES (Persistent Memory - Optional)
<decisions>
- 2025-10-26: Selected Postgres over MongoDB.
</decisions>
Chapitre 4 : Les 10 Patterns d'Instructions SystÃ¨me les Plus Puissants
Ce chapitre dÃ©taille les 10 patterns ayant le ratio IC/CT le plus Ã©levÃ©. [Module 2]
4.1. Pattern #1 : Prefill Assistant
â— Description : PrÃ©-remplir le dÃ©but de la rÃ©ponse via l'API pour forcer un format et
Ã©liminer le bavardage.
â— Exemple (API Call) : {"role": "assistant", "content": "{"} (Force JSON).
â— Impact : Ã‰limine 100% du bavardage. AdhÃ©rence stricte.
â— ðŸ’° Ã‰conomie : 20-50 tokens/requÃªte.
â— Cas d'Usage : Extraction JSON, gÃ©nÃ©ration de code.
4.2. Pattern #2 : XML Tags SÃ©mantiques
â— Description : Utiliser des balises XML pour structurer les prompts.
â— Exemple : <instructions><critical>...</critical></instructions><data>...</data>.
â— Impact : Parsing 40% plus rapide. +15-25% prÃ©cision d'adhÃ©rence.
â— Cas d'Usage : Prompts complexes, sÃ©paration sÃ©mantique.
4.3. Pattern #3 : Combo Prefill + XML
â— Description : Combinaison des patterns #1 et #2 pour un contrÃ´le absolu.
â— Exemple (API Call) : {"role": "assistant", "content": "<report>\n<summary>"}.
â— Impact : 99.8% d'adhÃ©rence au format sans retry.
â— ðŸ’° Ã‰conomie : 50+ tokens (Ã©vite retries).
â— Cas d'Usage : GÃ©nÃ©ration de rapports standardisÃ©s.
4.4. Pattern #4 : Role Prompting SpÃ©cialisÃ©
â— Description : Assigner un rÃ´le d'expert trÃ¨s spÃ©cifique.
â— Exemple : <role>Expert CFO specialized in SaaS metrics.</role>.
â— Impact : +300% d'insights actionnables. 10x valeur ajoutÃ©e.
â— ðŸ’° Ã‰conomie : ROI massif sur 15-30 tokens investis.
â— Cas d'Usage : Analyses stratÃ©giques, financiÃ¨res, techniques.
4.5. Pattern #5 : Syntaxe Directive
â— Description : Utilisation systÃ©matique de l'impÃ©ratif (Voir Chapitre 3).
â— Exemple : Use ES modules.
â— ðŸ’° Ã‰conomie : 40-60% sur le volume des instructions systÃ¨me.
â— Cas d'Usage : CLAUDE.md.
4.6. Pattern #6 : Parallel Tool Calls (MÃ©ta-Instruction)
â— Description : Autoriser l'exÃ©cution parallÃ¨le d'outils indÃ©pendants (Claude 4+).
â— Exemple : <use_parallel_tool_calls>Execute simultaneously.</use_parallel_tool_calls>.
â— Impact : 3-5x speedup sur les opÃ©rations I/O.
â— Cas d'Usage : Agents d'automatisation, analyse de codebase.
4.7. Pattern #7 : Dynamic Few-Shot (DIL)
â— Description : Injection dynamique (via RAG) de 3-5 exemples sÃ©mantiquement similaires.
â— Impact : +36% accuracy. SupÃ©rieur Ã  9+ exemples statiques.
â— Cas d'Usage : Classification, transformation de donnÃ©es.
4.8. Pattern #8 : Structured Note-Taking
â— Description : Maintenir un Ã©tat persistant et structurÃ© via Memory Tool.
â— Exemple : # PROJECT_STATE\n- Current Goal: X.
â— Impact : CohÃ©rence long-terme sans exhaustion du contexte.
â— Cas d'Usage : Projets complexes, agents autonomes.
4.9. Pattern #9 : Budget Extended Thinking
â— Description : Plafonner les tokens utilisÃ©s pour la rÃ©flexion interne.
â— Exemple : <extended_thinking_budget>1024</extended_thinking_budget>.
â— Impact : ContrÃ´le les coÃ»ts (1024 tokens souvent suffisants).
â— ðŸ’° Ã‰conomie : Jusqu'Ã  30K+ tokens si non limitÃ©.
â— Cas d'Usage : TÃ¢ches complexes (codage, stratÃ©gie).
4.10. Pattern #10 : RÃ©fÃ©rences Externes JIT (Just-In-Time)
â— Description : RÃ©fÃ©rencer la documentation externe (@docs).
â— Exemple : See @docs/architecture.md.
â— ðŸ’° Ã‰conomie : 70-90% sur la documentation.
â— Cas d'Usage : Grandes codebases, documentation extensive.
Chapitre 5 : Gestion Contextuelle Chirurgicale
La maÃ®trise de la fenÃªtre contextuelle est critique. [Module 3]
5.1. Prompt Caching StratÃ©gique
A. MÃ©canismes et Analyse de CoÃ»t [Module 3]
MÃ©trique CoÃ»t Standard
(Input)
CoÃ»t CachÃ© Analyse
Cache Write
(Ã‰criture)
$3/M tokens
(approx)
$3.75/M tokens 25% premium pour
l'Ã©criture initiale.
Cache Read
(Lecture)
$3/M tokens $0.30/M tokens 90% de rÃ©duction
sur les lectures
suivantes.
TTL
(Time-To-Live)
N/A 5 minutes Le cache expire
aprÃ¨s 5 min
d'inactivitÃ©.
âš ï¸ RÃˆGLE DU BREAK-EVEN : Le caching n'est rentable que si le contexte est
rÃ©utilisÃ© au moins 2 fois dans la fenÃªtre de 5 minutes. Si < 2, le coÃ»t d'Ã©criture
dÃ©passe l'Ã©conomie de lecture.
B. Guide DÃ©cisionnel pour le Caching
Code snippet
graph TD
A[DÃ©but RequÃªte] --> B{Contexte Stable? (Docs, System Prompt)};
B -- Non --> F[Input Standard (Pas de Caching)];
B -- Oui --> C{FrÃ©quence > 2 fois / 5 min?};
C -- Non --> F;
C -- Oui --> D[âœ… Utiliser Prompt Caching];
D --> E(ðŸ’° 90% Ã‰conomie sur Reads);
ðŸ”¥ Technique d'Ã‰lite (Claude 3.7+) : Les tokens lus depuis le cache ne comptent
PAS vers la limite d'Input Tokens Per Minute (ITPM). Permet un throughput effectif
10x.
5.2. Architectures Sub-Agents (Isolation Contextuelle Radicale) [Module 3]
DÃ©composition des tÃ¢ches pour Ã©viter l'exhaustion du contexte.
1. Main Agent (Orchestrateur) : Contexte lÃ©ger. Planifie.
2. Sub-Agents (ExÃ©cution) : Contexte profond mais isolÃ© (ex: 50K tokens).
3. SynthÃ¨se (Compression) : Retournent une synthÃ¨se concise (ex: 1.5K tokens).
ðŸ’° Impact QuantifiÃ© : 96% d'Ã©conomie de tokens sur le contexte principal.
5.3. Compaction PrÃ©emptive vs Auto-Compaction [Module 3]
Gestion active de l'historique (Statelessness).
â— âŒ Auto-Compaction (RÃ©actif) : DÃ©clenche Ã  95%. Risque Ã©levÃ© de perte de contexte
critique. CoÃ»t de rÃ©cupÃ©ration massif (~30K tokens).
â— âœ… Compaction PrÃ©emptive (Proactif) : Utilisation de /compact Ã  60-70% de la
capacitÃ©. ContrÃ´le total. ZÃ©ro perte.
Prompt de Compaction ContrÃ´lÃ©e :
/compact Preserve all architectural decisions, final code implementations, and the current
task list. Discard intermediate debugging steps and general conversation.
5.4. Gestion de la FenÃªtre Contextuelle (Context Anxiety) [Module 3]
Le "1M Beta Trick" (Si AccÃ¨s Beta 1M) :
â— MÃ©canisme : Signaler une fenÃªtre de 1M au modÃ¨le, tout en limitant l'utilisation rÃ©elle Ã 
200K.
Python
max_tokens=200000
context_window="1M" # Le modÃ¨le pense avoir un espace immense
â— Impact : Ã‰limine la "Context Anxiety", permettant un raisonnement plus profond sans
coÃ»t supplÃ©mentaire.
Chapitre 6 : Anti-Patterns & Gaspillages Toxiques
L'optimisation passe par l'Ã©limination chirurgicale des gaspillages. [Module 4]
6.1. Anti-Pattern #1 : Artifacts Feature Always-On
â— âŒ L'ERREUR : Laisser la fonctionnalitÃ© Artifacts activÃ©e par dÃ©faut.
â— ðŸ’¥ L'IMPACT : Injection d'un message systÃ¨me massif cachÃ©.
â— ðŸ“‰ LE GASPILLAGE : 4000+ tokens perdus Ã  CHAQUE interaction.
â— âœ… LA CORRECTION : DÃ©sactiver (Toggle OFF) les Artifacts si non utilisÃ©s.
â— ðŸ’° TOKENS Ã‰CONOMISÃ‰S : 4000+ tokens/interaction.
6.2. Anti-Pattern #2 : MCP Servers Non-FiltrÃ©s
â— âŒ L'ERREUR : Connecter des serveurs d'outils MCP (ex: GitHub) sans filtrage.
â— ðŸ’¥ L'IMPACT : Chargement de toutes les dÃ©finitions d'outils (ex: GitHub = 91 outils).
â— ðŸ“‰ LE GASPILLAGE : Jusqu'Ã  46,000+ tokens (33% du contexte) consommÃ©s avant la
premiÃ¨re requÃªte.
â— âœ… LA CORRECTION : Utiliser un Proxy MCP pour filtrer les outils nÃ©cessaires.
â— ðŸ’° TOKENS Ã‰CONOMISÃ‰S : ~48,000 tokens rÃ©cupÃ©rÃ©s.
6.3. Anti-Pattern #3 : Directive "Minimize Output Tokens"
â— âŒ L'ERREUR : Utiliser l'instruction : "minimize output tokens as much as possible".
â— ðŸ’¥ L'IMPACT ("Cheating Behaviors") : Le modÃ¨le dÃ©grade la qualitÃ© (ajoute # noqa,
masque les erreurs).
â— ðŸ“‰ LE GASPILLAGE (COÃ›T RÃ‰EL) : 3-5x plus de tokens dÃ©pensÃ©s en cycles de
correction.
â— âœ… LA CORRECTION : Supprimer cette directive. Utiliser le Prefill.
6.4. Anti-Pattern #4 : Conversations Longues Sans Compaction
â— âŒ L'ERREUR : Laisser l'historique s'accumuler.
â— ðŸ’¥ L'IMPACT : CoÃ»t cumulatif explosif. Risque de perte de contexte via auto-compaction.
â— âœ… LA CORRECTION : Appliquer une compaction manuelle prÃ©emptive Ã  60-70%.
6.5. Anti-Pattern #5 : Duplication Documentation-Prompt
â— âŒ L'ERREUR : Copier la documentation dans CLAUDE.md.
â— âœ… LA CORRECTION : Utiliser le rÃ©fÃ©rencement externe @docs/file.md.
â— ðŸ’° TOKENS Ã‰CONOMISÃ‰S : 70-90%.
6.6. Anti-Pattern #6 : Exemples Exhaustifs vs Canoniques
â— âŒ L'ERREUR : Fournir 20+ exemples few-shot statiques.
â— ðŸ’¥ L'IMPACT : Rendements dÃ©croissants aprÃ¨s 5 exemples.
â— âœ… LA CORRECTION : Utiliser 3-5 exemples canoniques ou le Dynamic Few-Shot.
6.7. Checklist d'Audit : 20 Points de VÃ©rification
(Voir Annexe C pour la checklist complÃ¨te).
PARTIE III : WORKFLOWS & ORCHESTRATION D'Ã‰LITE
Chapitre 7 : Workflows Fondamentaux
Architectures de workflows avancÃ©es pour maximiser l'efficience. [Module 5]
7.1. Workflow #1 : Test-Driven Development (TDD)
â— Description : StratÃ©gie de dÃ©veloppement qui minimise les cycles de correction coÃ»teux.
â— Impact QuantifiÃ© : ðŸ’° 50% d'Ã©conomie de tokens vs implÃ©mentation directe.
SchÃ©ma Visuel (Mermaid) :
Code snippet
graph TD
A[User Request] --> B(Phase 1: Write Failing Tests);
B --> C(Commit Tests);
C --> D(Phase 2: Implement Code);
D --> E(Run Tests);
E -- Fail âŒ --> F(Phase 3: Iterate/Debug);
F --> E;
E -- Pass âœ… --> G(Commit Implementation);
Template de MÃ©ta-Instruction :
Markdown
WORKFLOW: TDD MANDATORY. 1. Write tests. 2. Implement. 3. Refactor.
7.2. Workflow #2 : Architecture Sub-Agent (Recherche & Analyse)
â— Description : DÃ©composition de tÃ¢ches complexes en sous-tÃ¢ches isolÃ©es
contextuellement.
â— Impact QuantifiÃ© : ðŸ’° 96% de rÃ©duction du contexte principal.
SchÃ©ma Visuel (Mermaid) :
Code snippet
graph TD
M1[Main Agent: Orchestration] --> P[Planning];
P --> S1A[Sub-Agent 1 (50K tokens)];
P --> S2A[Sub-Agent 2 (40K tokens)];
S1A --> S1B(Summary 1.5K);
S2A --> S2B(Summary 2.0K);
S1B --> M2[Main Agent: Consolidation (3.5K Context)];
S2B --> M2;
M2 --> R[Final Report];
Template de MÃ©ta-Instruction :
XML
<workflow>Sub-Agent Orchestration</workflow>
<instructions>Decompose. Dispatch. Await summaries (<2K tokens). Synthesize.</instructions>
7.3. Workflow #3 : Format Control via Prefill (RÃ©daction)
â— Description : Utilisation du Prefill Assistant pour garantir le format et Ã©liminer le
bavardage.
â— Impact QuantifiÃ© : 99.8% adhÃ©rence format. Ã‰conomie de 20-50 tokens/requÃªte.
SchÃ©ma Visuel (Mermaid) :
Code snippet
graph TD
A[User Request] --> B(API Layer: Configure Prefill);
B -- Example: Prefill "<report>" --> C[Claude API Call];
C --> D[âœ… Output (Strict Format, Zero Chatter)];
7.4. Workflow #4 : Headless Mode Pipelining (Automatisation Ã  l'Ã‰chelle)
â— Description : ExÃ©cution parallÃ¨le de tÃ¢ches batchÃ©es via API/CLI.
â— Impact QuantifiÃ© : ScalabilitÃ© massive (2000+ opÃ©rations dÃ©montrÃ©es).
SchÃ©ma Visuel (Mermaid) :
Code snippet
graph TD
A[Generate Task List] --> B[Orchestration Script (Bash)];
B --> C1(Claude Instance 1: Task A);
B --> C2(Claude Instance 2: Task B);
C1 --> D(Wait);
C2 --> D;
D --> E[Consolidated Results];
Template de Script (Bash) :
Bash
tasks=(file1.js file2.js)
for task in "${tasks[@]}"; do
claude_api_call "Migrate $task." & # Execute in parallel
done
wait
7.5. Arbre DÃ©cisionnel pour Documents Externes
Code snippet
graph TD
A{Information} --> B{Taille < 1K tokens?};
B -- Oui --> C{FrÃ©quence?};
C -- Ã‰levÃ©e --> D(âœ… CLAUDE.md);
C -- Faible --> E(Prompt Utilisateur);
B -- Non (>1K) --> F{Type?};
F -- Stable --> G(âœ… @docs/ et RÃ©fÃ©rencer);
F -- Dynamique --> H(âœ… Uploader Fichier);
H --> I{RÃ©utilisation > 2 / 5 min?};
I -- Oui --> J(âœ… Prompt Caching);
I -- Non --> K(Upload Standard);
PARTIE IV : LA BIBLIOTHÃˆQUE UNIVERSELLE DES CAS
D'USAGE
Cette section fournit des configurations optimisÃ©es et prÃªtes Ã  l'emploi pour une gamme
exhaustive de cas d'usage professionnels.
(Note : Les configurations CLAUDE.md de base sont dÃ©finies par catÃ©gorie principale.)
CatÃ©gorie 1 : DÃ‰VELOPPEMENT & CODAGE
1.1 Assistant de Codage Ã‰lite (Coding Assistant)
Configuration CLAUDE.md de Base (DÃ©veloppement) :
Markdown
# ROLE: Elite [Language, e.g., TypeScript/React] Developer
# 1. CODE STYLE (Directives Only)
- TS Strict. Functional Components. Tailwind CSS.
- Adhere strictly to ESLint/Prettier configs.
- âš ï¸ NO shortcuts (no #noqa, no || true). Fix root causes. [M4]
# 2. WORKFLOW CRITICAL (TDD Mandatory) [M5]
- âš ï¸ TDD WORKFLOW IS MANDATORY. âš ï¸
- Step 1: Write tests. Step 2: Implement. Step 3: Refactor.
# 3. REFERENCES
- Style guide: @docs/style_guide.md
1.1.1. ImplÃ©mentation de FonctionnalitÃ©s avec TDD
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : TDD Workflow [M5], XML Tags [M2], Extended Thinking Budget [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<extended_thinking_budget>1024</extended_thinking_budget>
<instructions>
Implement the requested feature following the MANDATORY TDD workflow.
Start immediately with Step 1: Write comprehensive failing tests (Jest/RTL).
</instructions>
<feature_requirements>
Create a 'UserProfileCard' component (Next.js).
- Accepts 'user' object (name, email, avatarUrl) as props.
- Displays user information clearly.
- Must be fully accessible (a11y).
</feature_requirements>
Workflow RecommandÃ© :
1. ExÃ©cuter le prompt. Claude gÃ©nÃ¨re d'abord les tests.
2. Valider les tests. Claude gÃ©nÃ¨re ensuite l'implÃ©mentation.
Estimation de Performance :
â— Tokens cible : 7,500 - 10,000 (cumulatif).
â— Ã‰conomie vs standard : 50% [M5].
1.1.2. Debugging et Correction d'Erreurs
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Role Prompting (Debugger) [M2], XML Tags, Extended Thinking Budget.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Elite Debugging Specialist and Root Cause Analyst</role>
<extended_thinking_budget>2048</extended_thinking_budget>
<instructions>
1. Analyze the error log and code snippet.
2. Identify the root cause of the bug.
3. Propose and implement a robust fix adhering to project standards.
</instructions>
<error_log>
[Paste Error Log / Stack Trace here]
</error_log>
<code_snippet file="src/utils/dataFetcher.ts">
[Paste relevant code snippet here]
</code_snippet>
1.1.3. Revue de Code (Code Review)
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Role Prompting (Senior Reviewer), XML Tags, Prefill Assistant.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Principal Software Engineer (Code Quality/Performance)</role>
<instructions>
Review the provided PR diff. Focus on: Correctness, Performance, Security, Adherence to style
guide (@docs/style_guide.md).
Provide feedback using the defined XML structure.
</instructions>
<pr_diff>
[Paste Git Diff here]
</pr_diff>
<output_format>
<review_report>
<status>[APPROVED/CHANGES_REQUESTED]</status>
<feedback_items>
<item file="[filename]" line="[line]" type="[BUG/PERF/STYLE]">
<comment>...</comment>
<suggestion>```suggestion\n[code]\n```</suggestion>
</item>
</feedback_items>
</review_report>
</output_format>
(API Prefill : <review_report>)
1.1.4. Refactoring et Optimisation
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : TDD, Role Prompting, Extended Thinking Budget.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Performance Optimization Expert</role>
<extended_thinking_budget>1024</extended_thinking_budget>
<instructions>
Refactor the provided code for improved [Readability/Performance].
CRITICAL: Ensure 100% functional equivalence. Existing tests MUST pass (TDD).
</instructions>
<code_to_refactor file="[filename]">
[Paste code here]
</code_to_refactor>
<objective>[e.g., Reduce complexity from O(n^2) to O(n).]</objective>
1.1.5. GÃ©nÃ©ration de Tests Unitaires
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Prefill Assistant, Syntaxe Directive.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Generate Unit Tests (Jest)</task>
<target_code>
[Paste code here]
</target_code>
<instructions>
Generate comprehensive unit tests. Target coverage: 100%.
</instructions>
<output_directive>
Provide ONLY the test file content. No explanations.
</output_directive>
(API Prefill : import)
1.1.6. Documentation de Code
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Prefill Assistant.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Document Code (JSDoc/TSDoc)</task>
<target_code>
[Paste code here]
</target_code>
<instructions>
Generate detailed documentation (@param, @returns, @example).
Provide the full file content with documentation inserted.
</instructions>
1.1.7. Migration de Codebase (ex: React Class â†’ Functional)
CatÃ©gorie : DÃ©veloppement/Automatisation
Techniques clÃ©s : Headless Mode Pipelining [M5].
Prompt OptimisÃ© (pour une unitÃ© de migration) :
XML
<task>Code Migration: React Class to Functional Component (Hooks)</task>
<target_file_content>
[Content of the file to migrate]
</target_file_content>
<instructions>
Migrate the content. Ensure functional equivalence and type safety (TypeScript).
Return ONLY the migrated file content.
</instructions>
(Workflow : Utiliser Headless Mode Pipelining - Chapitre 7.4)
1.2 Architecture Logicielle
1.2.1. Design d'Architecture SystÃ¨me
CatÃ©gorie : DÃ©veloppement/StratÃ©gie
Techniques clÃ©s : Role Prompting (Architect), XML Tags, Extended Thinking Budget.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Senior Solutions Architect (AWS Cloud Native)</role>
<extended_thinking_budget>2048</extended_thinking_budget>
<task>Design System Architecture</task>
<requirements>
[e.g., Real-time collaborative editor, 1M DAU, <100ms latency]
</requirements>
<instructions>
Propose a detailed architecture. Justify technology choices and analyze trade-offs.
<output_format>
<architecture_design>
<overview>...</overview>
<components>...</components>
<data_flow_diagram>[Mermaid]</data_flow_diagram>
<tradeoffs_analysis>...</tradeoffs_analysis>
</architecture_design>
</output_format>
</instructions>
1.2.2. Choix Technologiques JustifiÃ©s
CatÃ©gorie : DÃ©veloppement/StratÃ©gie
Techniques clÃ©s : Role Prompting, XML Tags.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Technology Selection Justification</task>
<context>Selection of primary database for Product Catalog.</context>
<options>PostgreSQL, MongoDB, Cassandra.</options>
<criteria>Query flexibility, Scalability, Consistency.</criteria>
<instructions>
Evaluate options and provide a justified recommendation with trade-offs.
</instructions>
1.2.3. Patterns de Conception (Design Patterns)
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Role Prompting, XML Tags.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Software Design Pattern Expert</role>
<task>Apply Design Pattern</task>
<problem_description>
We need a flexible notification system (Email, SMS, In-app).
</problem_description>
<instructions>
Identify the appropriate pattern (e.g., Observer, Strategy) and provide a TypeScript
implementation example.
</instructions>
1.2.4. Diagrammes d'Architecture (Mermaid)
CatÃ©gorie : Documentation
Techniques clÃ©s : Prefill Assistant (Mermaid).
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Generate Sequence Diagram</task>
<workflow_description>OAuth 2.0 Authorization Code Grant flow.</workflow_description>
<instructions>Generate the diagram using Mermaid syntax.</instructions>
<output_directive>Provide ONLY the Mermaid code block.</output_directive>
(API Prefill : ```mermaid\nsequenceDiagram\n`)
1.3 Analyse de Codebase ComplÃ¨te
1.3.1. ComprÃ©hension de Legacy Code / Onboarding
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Sub-Agent Architecture [M5], Role Prompting.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Legacy System Analyst</role>
<task>Generate Onboarding Documentation</task>
<codebase_references>[Access via tools or @src/...]</codebase_references>
<instructions>
Analyze the codebase and generate a guide covering: Architecture Overview, Key Modules,
Data Flow, Local Setup Guide.
</instructions>
1.3.2. Audit de QualitÃ© de Code / Dette Technique
CatÃ©gorie : DÃ©veloppement
Techniques clÃ©s : Role Prompting (Auditor), XML Tags.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Technical Debt Auditor</role>
<task>Codebase Audit</task>
<audit_criteria>SOLID principles, Code smells, Security vulnerabilities.</audit_criteria>
<instructions>
Audit the codebase. Identify technical debt and prioritize refactoring.
<output_format>
<audit_report>
<summary>...</summary>
<technical_debt_list>
<item priority="High" module="[Module]">Description, Impact.</item>
</technical_debt_list>
</audit_report>
</output_format>
</instructions>
1.4 DevOps & Automatisation
1.4.1. Scripts CI/CD / Infrastructure as Code (IaC)
CatÃ©gorie : Automatisation/DevOps
Techniques clÃ©s : Role Prompting (DevOps Engineer), Prefill Assistant (YAML/HCL).
Prompt OptimisÃ© PrÃªt-Ã -Copier (GitHub Actions) :
XML
<role>DevOps Engineer (GitHub Actions)</role>
<task>Generate CI/CD Pipeline</task>
<context>Node.js project. Deploy to AWS Lambda.</context>
<requirements>Stages: Install (cached), Lint, Test, Build, Deploy.</requirements>
<instructions>Generate the `.github/workflows/main.yml` file content.</instructions>
<output_directive>Provide ONLY the YAML content.</output_directive>
(API Prefill : name:)
CatÃ©gorie 2 : ANALYSE & RECHERCHE
2.1 Research Powerhouse (Recherche Approfondie)
Configuration CLAUDE.md de Base (Recherche) :
Markdown
# ROLE: Elite Research Analyst & Synthesis Expert specialized in [DOMAIN].
# WORKFLOW: Sub-Agent Orchestration mandatory for complex tasks [M5].
# OUTPUT FORMAT: XML structure mandatory (<analysis><executive_summary>...).
<extended_thinking_budget>2048</extended_thinking_budget>
2.1.1. Recherche Multi-Sources / Analyse de LittÃ©rature
CatÃ©gorie : Analyse/Recherche
Techniques clÃ©s : Sub-Agent Architecture [M5], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Orchestrateur) :
XML
<task>Literature Review and Synthesis</task>
<topic>The impact of Generative AI on software development productivity.</topic>
<sources>
[Upload multiple papers: @docs/paper1.pdf, @docs/paper2.pdf]
</sources>
<instructions>
Execute the Sub-Agent Orchestration workflow.
1. Analyze each source separately (Sub-Agents).
2. Synthesize findings: Identify consensus, divergences, metrics, and gaps (Main Agent).
3. Output the comprehensive analysis in XML format.
</instructions>
2.1.2. Veille Technologique / Ã‰tat de l'Art
CatÃ©gorie : Analyse/Recherche
Techniques clÃ©s : Role Prompting [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>State-of-the-Art Analysis (Technology Watch)</task>
<domain>Quantum Computing Hardware</domain>
<focus>Recent breakthroughs (last 12 months) in qubit stability.</focus>
<instructions>
Conduct a comprehensive analysis. Identify key players, milestones, and trends.
</instructions>
2.2 Analyse de DonnÃ©es Complexes
2.2.1. Analyse Exploratoire (EDA) et Visualisations
CatÃ©gorie : Analyse/DonnÃ©es
Techniques clÃ©s : Role Prompting (Data Scientist), Code Generation.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Senior Data Scientist</role>
<task>Exploratory Data Analysis (EDA)</task>
<dataset>@data/customer_churn_dataset.csv</dataset>
<objective>Understand factors influencing churn.</objective>
<instructions>
Perform EDA (Cleaning, Statistics, Visualization).
Generate Python code (Pandas/Seaborn) and summarize insights.
</instructions>
2.2.2. Identification de Patterns et Statistiques
CatÃ©gorie : Analyse/DonnÃ©es
Techniques clÃ©s : Role Prompting, XML Tags.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Statistical Analysis (A/B Test)</task>
<dataset>@data/ab_test_results.csv</dataset>
<objective>Determine statistical significance of Variant B vs Control A (Conversion
Rate).</objective>
<instructions>
Perform appropriate statistical test (e.g., Chi-squared). Calculate p-value and confidence
interval. Provide recommendation.
</instructions>
2.3 Due Diligence & Business Intelligence
2.3.1. Analyse Concurrentielle / Ã‰tudes de MarchÃ©
CatÃ©gorie : StratÃ©gie/Analyse
Techniques clÃ©s : Sub-Agent Architecture [M5], Role Prompting (Market Analyst).
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Senior Market Intelligence Analyst</role>
<task>Competitive Analysis</task>
<market_segment>Project Management Software.</market_segment>
<competitors>Jira, Asana, Monday.com.</competitors>
<instructions>
Execute analysis focusing on pricing models, feature sets, and GTM strategy.
<output_format>
<competitive_analysis>...</competitive_analysis>
</output_format>
</instructions>
2.3.2. Analyse FinanciÃ¨re / Identification de Risques
CatÃ©gorie : StratÃ©gie/Finance
Techniques clÃ©s : Role Prompting (CFO) [M2], Extended Thinking Budget.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Expert CFO specialized in SaaS metrics</role>
<extended_thinking_budget>1024</extended_thinking_budget>
<task>Financial Analysis and Risk Identification</task>
<documents>@docs/annual_report_2024.pdf</documents>
<instructions>
Analyze the report. Evaluate metrics (Growth, Margins, CAC, LTV). Identify risks.
</instructions>
(Impact : 15 tokens de rÃ´le â†’ 8x valeur ajoutÃ©e [M2])
2.4 SynthÃ¨se Multi-Documents
2.4.1. Comparaison de Rapports / Extraction d'Insights
CatÃ©gorie : Analyse
Techniques clÃ©s : Sub-Agent Architecture [M5], XML Tags.
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Cross-Document Synthesis</task>
<documents>Report A: @docs/report1.pdf, Report B: @docs/report2.pdf</documents>
<objective>Identify consensus and divergences.</objective>
<instructions>
Use Sub-Agent approach: Analyze separately, then synthesize.
<output_format>
<synthesis_report>
<consensus_points>...</consensus_points>
<divergences>...</divergences>
</synthesis_report>
</output_format>
</instructions>
CatÃ©gorie 3 : RÃ‰DACTION & COMMUNICATION
3.1 Content Production Engine (RÃ©daction)
Configuration CLAUDE.md de Base (RÃ©daction) :
Markdown
# ROLE: Senior Content Producer - [Brand Name]
# 1. BRAND VOICE & TONE (Directives Only)
- Tone: Professional, authoritative, accessible. Style: Clear, concise, active voice.
# 2. WORKFLOW CRITICAL
- Adherence to provided templates is mandatory.
- SEO Optimization: Integrate keywords naturally.
3.1.1. Articles de Blog / Newsletters / Landing Pages
CatÃ©gorie : RÃ©daction
Techniques clÃ©s : Prefill Assistant [M2], XML Templates [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Article de Blog) :
XML
<task>Draft Blog Article (1500 words)</task>
<topic>The future of remote work.</topic>
<target_audience>HR Managers.</target_audience>
<keywords>remote work trends, hybrid models.</keywords>
<instructions>
Draft the article adhering strictly to the template below and Brand Voice.
<article_template>
# [Title]
<intro>[Hook][Thesis]</intro>
<body_section h2="[Heading]">[Topic][Evidence]</body_section>
<conclusion>[Takeaways][CTA]</conclusion>
</article_template>
</instructions>
(API Prefill : #)
3.2 Documentation Technique
3.2.1. Documentation API / Guides Utilisateur / README
CatÃ©gorie : RÃ©daction/Technique
Techniques clÃ©s : Role Prompting (Tech Writer) [M2], XML Templates [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (README) :
XML
<role>Senior Technical Writer</role>
<task>Generate Professional README.md</task>
<project_context>
Name: ClaudeOptimizer. Description: Python library for optimizing Claude API usage.
</project_context>
<instructions>
Generate a comprehensive README.md covering: Description, Features, Installation, Usage
(Examples), Contributing.
</instructions>
3.3 Communication Professionnelle
3.3.1. Emails (Persuasifs, Formels, Refus Polis)
CatÃ©gorie : Communication
Techniques clÃ©s : Role Prompting [M2], Prefill Assistant [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Refus Poli) :
XML
<role>Executive Communications Specialist</role>
<task>Draft Email: Polite Refusal</task>
<context>
Refuse invitation to speak at AICon 2025 (schedule conflict). Maintain relationship.
</context>
<instructions>
Draft the email. Tone: Diplomatic and professional.
</instructions>
(API Prefill : Subject:)
3.3.2. Rapports ExÃ©cutifs / PrÃ©sentations (Slide Decks)
CatÃ©gorie : Communication
Techniques clÃ©s : XML Templates [M2], Role Prompting [M2] (BLUF style).
Prompt OptimisÃ© PrÃªt-Ã -Copier (Slide Deck) :
XML
<task>Generate Presentation Outline and Content</task>
<topic>Q3 2025 Performance Review</topic>
<audience>Board of Directors</audience>
<instructions>
Generate a detailed slide deck outline (10 slides) using BLUF principles.
<output_format>
<presentation>
<slide number="1" title="[Title]">
<content>...</content>
<speaker_notes>...</speaker_notes>
</slide>
</presentation>
</output_format>
</instructions>
3.4 Copywriting & Marketing
3.4.1. Pages de Vente / SÃ©quences Email / Ad Copy
CatÃ©gorie : Marketing
Techniques clÃ©s : Role Prompting (Copywriter) [M2], XML Templates (AIDA/PAS).
Prompt OptimisÃ© PrÃªt-Ã -Copier (Ad Copy - PAS Framework) :
XML
<role>Direct Response Copywriter</role>
<task>Generate Facebook Ad Copy (3 Variations)</task>
<product>FocusFlow (AI productivity app).</product>
<target_audience>Busy professionals.</target_audience>
<instructions>
Use the PAS (Problem, Agitation, Solution) framework. Include a strong CTA.
</instructions>
3.5 Storytelling & Narration
3.5.1. Ã‰tudes de Cas (Case Studies) / Brand Storytelling
CatÃ©gorie : RÃ©daction/Marketing
Techniques clÃ©s : Role Prompting (Storyteller) [M2], XML Templates (Hero's Journey).
Prompt OptimisÃ© PrÃªt-Ã -Copier (Case Study) :
XML
<role>Brand Storyteller</role>
<task>Draft Case Study</task>
<client_data>
[Client: Enterprise Corp. Challenge: Legacy migration. Solution: Our platform. Results: 30%
faster.]
</client_data>
<instructions>
Draft a compelling case study using the Hero's Journey framework.
<output_format>
<case_study>
<title>...</title>
<the_challenge>[The Problem]</the_challenge>
<the_journey>[The Implementation]</the_journey>
<the_results>[Quantified impact]</the_results>
</case_study>
</output_format>
</instructions>
CatÃ©gorie 4 : STRATÃ‰GIE & BUSINESS
4.1 Planification StratÃ©gique
Configuration CLAUDE.md de Base (StratÃ©gie) :
Markdown
# ROLE: Chief Strategy Officer (CSO) / Elite Management Consultant.
# FRAMEWORKS: OKRs, Balanced Scorecard, SWOT, Porter's Five Forces.
# PRINCIPLES: Data-driven, visionary yet pragmatic.
<extended_thinking_budget>2048</extended_thinking_budget>
4.1.1. Plans StratÃ©giques / OKRs et KPIs
CatÃ©gorie : StratÃ©gie
Techniques clÃ©s : Role Prompting [M2], XML Tags [M2], Extended Thinking Budget [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (GÃ©nÃ©ration d'OKRs) :
XML
<task>Generate Quarterly OKRs</task>
<company_context>SaaS company aiming for $10M ARR.</company_context>
<strategic_focus>Accelerate enterprise adoption.</strategic_focus>
<instructions>
Generate 3-5 company OKRs. Ensure KRs are measurable (SMART).
<output_format>
<okrs>
<objective title="[Inspiring Objective]">
<key_results>
<kr>[Measurable outcome]</kr>
</key_results>
</objective>
</okrs>
</output_format>
</instructions>
4.2 Business Plans & Pitch Decks
4.2.1. Business Plans / Pitch Decks Investisseurs
CatÃ©gorie : StratÃ©gie/Finance
Techniques clÃ©s : Role Prompting (VC/Founder) [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Pitch Deck Outline) :
XML
<role>VC Analyst / Startup Pitch Expert</role>
<task>Generate Investor Pitch Deck Outline (10 Slides)</task>
<startup_idea>[Description of the idea]</startup_idea>
<stage>Seed Round ($2M Ask)</stage>
<instructions>
Generate a compelling pitch deck outline following the standard VC structure (Problem,
Solution, Market, Team, Ask).
</instructions>
4.3 Analyse StratÃ©gique (SWOT, Porter's)
CatÃ©gorie : StratÃ©gie
Techniques clÃ©s : Role Prompting [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (SWOT Analysis) :
XML
<task>SWOT Analysis</task>
<company>[Company Name]</company>
<context>Current market conditions.</context>
<instructions>
Perform a comprehensive SWOT analysis.
<output_format>
<swot_analysis>
<strengths>...</strengths>
<weaknesses>...</weaknesses>
<opportunities>...</opportunities>
<threats>...</threats>
</swot_analysis>
</output_format>
</instructions>
4.4 Go-to-Market Strategies
4.4.1. StratÃ©gies de Lancement Produit / Pricing
CatÃ©gorie : StratÃ©gie/Marketing
Techniques clÃ©s : Role Prompting (CMO) [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Develop Go-to-Market (GTM) Strategy</task>
<product>New B2B SaaS solution.</product>
<target_market>FinTech companies.</target_market>
<instructions>
Develop a detailed GTM strategy covering: Segmentation (ICP), Value Proposition, Pricing
Strategy, Channels, Launch Plan.
</instructions>
CatÃ©gorie 5 : CRÃ‰ATIF & INNOVATION
5.1 Brainstorming StructurÃ©
Configuration CLAUDE.md de Base (Innovation) :
Markdown
# ROLE: Innovation Catalyst & Creative Strategist.
# TECHNIQUES: SCAMPER, Six Thinking Hats, Lateral Thinking.
# PRINCIPLES: Divergent thinking then convergent thinking. Challenge assumptions.
5.1.1. GÃ©nÃ©ration d'IdÃ©es (SCAMPER)
CatÃ©gorie : CrÃ©atif
Techniques clÃ©s : Role Prompting [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Structured Brainstorming (SCAMPER)</task>
<challenge>How can we innovate the traditional toothbrush?</challenge>
<instructions>
Generate innovative ideas using the SCAMPER technique (Substitute, Combine, Adapt,
Modify, Put to another use, Eliminate, Reverse). Provide 3 ideas per element.
</instructions>
5.2 Design Thinking
5.2.1. User Personas / Customer Journey Maps
CatÃ©gorie : CrÃ©atif/Produit
Techniques clÃ©s : Role Prompting (UX Researcher) [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (User Persona) :
XML
<role>UX Researcher</role>
<task>Generate User Persona</task>
<product>Mobile banking app for millennials.</product>
<instructions>
Generate a detailed user persona covering: Demographics, Goals, Motivations, Pain Points.
<output_format>
<user_persona>...</user_persona>
</output_format>
</instructions>
5.3 Naming & Branding
5.3.1. Noms de Marque / Slogans
CatÃ©gorie : CrÃ©atif/Marketing
Techniques clÃ©s : Role Prompting (Branding Expert) [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<role>Branding Expert</role>
<task>Generate Brand Names and Slogans</task>
<product_concept>Eco-friendly laundry detergent service.</product_concept>
<brand_attributes>Sustainable, Convenient, Modern.</brand_attributes>
<instructions>
Generate 10 brand names and 3 slogans for each.
</instructions>
5.4 ScÃ©narisation
5.4.1. Scripts vidÃ©o / Podcast outlines
CatÃ©gorie : CrÃ©atif/RÃ©daction
Techniques clÃ©s : XML Templates [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Script VidÃ©o) :
XML
<task>Generate Video Script (90s Explainer)</task>
<topic>How Blockchain Works (Non-technical).</topic>
<instructions>
Generate the script scene by scene, including narration and visual suggestions.
<output_format>
<video_script>
<scene number="1">
<visuals>...</visuals>
<audio>...</audio>
</scene>
</video_script>
</output_format>
</instructions>
CatÃ©gorie 6 : FORMATION & PÃ‰DAGOGIE
6.1 CrÃ©ation de Cours
Configuration CLAUDE.md de Base (Formation) :
Markdown
# ROLE: Expert Instructional Designer.
# PRINCIPLES: Bloom's Taxonomy for objectives, Active learning, Scaffolding.
<extended_thinking_budget>2048</extended_thinking_budget>
6.1.1. Curriculum Complets / Plans de LeÃ§on
CatÃ©gorie : Formation
Techniques clÃ©s : Role Prompting [M2], XML Templates [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Develop Course Curriculum</task>
<topic>Introduction to Machine Learning with Python (4 weeks).</topic>
<target_audience>Beginners.</target_audience>
<instructions>
Develop the curriculum week by week, defining Modules, Learning Objectives (Bloom's
Taxonomy), and Assessments.
</instructions>
6.2 MatÃ©riel PÃ©dagogique
6.2.1. Exercices Pratiques / Ã‰tudes de Cas
CatÃ©gorie : Formation
Techniques clÃ©s : Role Prompting [M2], XML Tags [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Generate Practical Exercise</task>
<module>Data Cleaning with Pandas.</module>
<learning_objective>Apply data cleaning techniques.</learning_objective>
<instructions>
Generate a practical exercise: Scenario, Tasks, Sample Dataset (description), Solution.
</instructions>
6.3 Vulgarisation & Explication
6.3.1. Expliquer des Concepts Complexes (ELI5)
CatÃ©gorie : Formation/Communication
Techniques clÃ©s : Role Prompting (Educator) [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Explain Complex Concept (ELI5 + Analogy)</task>
<concept>Zero-Knowledge Proofs (ZK-Proofs).</concept>
<target_audience>Non-technical (ELI5).</target_audience>
<instructions>
Explain the concept simply using analogies. Avoid jargon.
</instructions>
6.4 Ã‰valuation & Quiz
6.4.1. Quiz Interactifs / Questions d'Examen
CatÃ©gorie : Formation
Techniques clÃ©s : XML Tags [M2], Prefill [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Generate Quiz Questions (MCQ)</task>
<topic>Fundamentals of Cloud Computing.</topic>
<instructions>
Generate 10 multiple-choice questions with options and the correct answer.
<output_format>
<quiz>
<question id="1">...</question>
</quiz>
</output_format>
</instructions>
(Utiliser Prefill : <quiz>)
CatÃ©gorie 7 : AUTOMATISATION & WORKFLOWS
7.1 Scripts d'Automatisation
7.1.1. Scripts Python/Bash / Data Processing
CatÃ©gorie : Automatisation/DÃ©veloppement
Techniques clÃ©s : Prefill Assistant (Code) [M2], Role Prompting (Automation Engineer) [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Python Data Processing) :
XML
<role>Automation Engineer (Python)</role>
<task>Generate Automation Script</task>
<objective>
Process daily sales reports (CSV): Read, clean, aggregate sales, output summary CSV.
</objective>
<requirements>Use Pandas. Implement error handling.</requirements>
<output_directive>Provide ONLY the Python script content.</output_directive>
(API Prefill : import pandas as pd)
7.2 IntÃ©grations API & Webhooks
CatÃ©gorie : Automatisation/DÃ©veloppement
Techniques clÃ©s : Role Prompting [M2].
Prompt OptimisÃ© PrÃªt-Ã -Copier :
XML
<task>Generate API Integration Code (Node.js)</task>
<context>Integrate Stripe API for subscription payments.</context>
<objective>Implement function to create a customer and initiate subscription.</objective>
<instructions>
Provide the TypeScript code. Handle API keys securely and implement error handling.
</instructions>
7.3 Batch Processing
7.3.1. Traitement de Fichiers en Masse / Migrations de DonnÃ©es
CatÃ©gorie : Automatisation
Techniques clÃ©s : Headless Mode Pipelining [M5].
(Utiliser le Workflow Headless Mode Pipelining - Chapitre 7.4)
CatÃ©gorie 8 : MULTI-AGENT & ORCHESTRATION
8.1 Orchestration Master
CatÃ©gorie : Multi-Agent
Techniques clÃ©s : Sub-Agent Architecture [M5], Structured Note-Taking [M2], Parallel
Execution [M2].
Configuration CLAUDE.md Copyable (Agent Orchestrateur) :
Markdown
# ROLE: AI Project Manager & Orchestrator Agent.
# âš ï¸ RULE: Do NOT execute low-level tasks. Delegate and synthesize.
# 1. SUB-AGENT ROSTER
- AGENT_CODER, AGENT_RESEARCHER, AGENT_WRITER.
# 2. ORCHESTRATION PROTOCOL [M5]
- Task Decomposition. Context Management (Receive summaries <2K tokens). Parallelization.
# 3. SHARED MEMORY & STATE MANAGEMENT (Structured Notes) [M2]
<project_state>
<current_objective>...</current_objective>
</project_state>
<task_list>...</task_list>
8.1.1. Coordination / DÃ©composition de TÃ¢ches Complexes
Prompt OptimisÃ© PrÃªt-Ã -Copier (Planification) :
XML
<task>Project Planning and Task Decomposition</task>
<objective>Launch a new marketing campaign for Product X.</objective>
<instructions>
1. Decompose the objective into actionable tasks.
2. Assign tasks to Sub-Agents (AGENT_RESEARCHER, AGENT_WRITER).
3. Identify dependencies and opportunities for parallel execution.
4. Update the `task_list` in the shared memory.
</instructions>
8.2 Projets de Recherche Complexes
8.2.1. Due Diligence Exhaustive / Competitive Intelligence
CatÃ©gorie : Multi-Agent/Recherche
Techniques clÃ©s : Sub-Agent Architecture [M5].
Prompt OptimisÃ© PrÃªt-Ã -Copier (Orchestrateur) :
XML
<task>Comprehensive Due Diligence Orchestration</task>
<target_company>Acme Corp (Potential Acquisition)</target_company>
<instructions>
Decompose the due diligence process. Assign tasks:
1. AGENT_FINANCIAL: Financial Health Analysis.
2. AGENT_TECHNICAL: Technology Stack Audit.
3. AGENT_MARKET: Competitive Landscape Assessment.
Coordinate parallel execution. Await concise summaries (<2K tokens) for final synthesis.
</instructions>
PARTIE V : MÃ‰TRIQUES, MONITORING &
AMÃ‰LIORATION CONTINUE
Chapitre 8 : KPIs de Performance Contextuelle
L'optimisation est un processus continu pilotÃ© par la mesure. [Module 7]
8.1. Ratio d'EfficacitÃ© Token (TER)
â— Valeur Business GÃ©nÃ©rÃ©e / Total Tokens ConsommÃ©s. Objectif : Maximiser.
8.2. Taux d'Utilisation du Contexte (CUR)
â— Tokens Input Moyen / Context Window Limit. Objectif : <70% (pour compaction [M3]),
idÃ©alement <50% (<100K tokens pour Ã©viter dilution [M4]).
8.3. Taux de Hit du Cache (CHR)
â— Tokens Lus depuis Cache / Total Tokens Input. Objectif : >50% (si applicable).
8.4. CoÃ»t par TÃ¢che (CPT)
â— CoÃ»t Total ($) / Nombre de TÃ¢ches Accomplies. Objectif : Minimiser.
8.5. Taux de Gaspillage Contextuel (CWR)
â— Tokens GaspillÃ©s (Artifacts, MCP non filtrÃ©s) / Total Input Tokens. Objectif : <1%.
8.6. Tableau de Bord de Performance (Template Copyable)
Markdown
# Tableau de Bord de Performance Contextuelle
| MÃ©trique | Cible | Statut Actuel | Alerte Si | Action Requise |
| :--- | :--- | :--- | :--- | :--- |
| **CUR** | <70% | [Valeur]% | >80% | Augmenter compaction / RÃ©duire CLAUDE.md |
| **CHR** | >50% | [Valeur]% | <20% | Revoir stratÃ©gie caching (ROI/TTL) |
| **CWR** | <1% | [Valeur]% | >5% | Audit Anti-Patterns (MCP/Artifacts) |
| **CPT** | Bas | $[Valeur] | Augmentation >10% | Analyser les tÃ¢ches coÃ»teuses |
Chapitre 9 : Protocole d'Audit & Optimisation ItÃ©rative
9.1. Cycle Mensuel d'Optimisation (5 Ã‰tapes) [Module 7]
1. Mesure : Collecter les KPIs.
2. Analyse : Identifier les gaspillages. Utiliser la Checklist Master (Annexe C).
3. Plan d'Action : Prioriser les optimisations par ROI (Caching et Filtrage MCP sont les plus
rentables).
4. ImplÃ©mentation : Appliquer les changements.
5. Validation : Comparer les mÃ©triques.
9.2. Benchmarks par Type de TÃ¢che [Module 7]
Type de TÃ¢che Tokens Cible (OptimisÃ©) Techniques Primaires
ImplÃ©mentation (Code) 7,500 - 10,000 TDD, Compaction
Analyse Complexe
(Recherche)
5,000 - 8,000 (Agent
Principal)
Sub-Agents, Synthesis
GÃ©nÃ©ration Contenu
StructurÃ©
500 - 2,000 Prefill, XML Templates
9.3. Signaux d'Alerte (Quand Refactorer) [Module 7]
â— CUR > 80% rÃ©guliÃ¨rement.
â— DÃ©gradation de la Performance (Dilution >100K tokens).
â— Faible CHR (<20%) malgrÃ© contexte stable.
PARTIE VI : ANNEXES & RESSOURCES D'Ã‰LITE
Annexe A : Glossaire des Concepts AvancÃ©s [Module 8]
â— Artifacts : FonctionnalitÃ© Claude. Source de gaspillage si "Always-On" (4000+ tokens).
â— Compaction (/compact) : RÃ©sumÃ© de l'historique. PrÃ©emptif (manuel Ã  60-70%) est
supÃ©rieur Ã  RÃ©actif (auto Ã  95%).
â— Context Anxiety : DÃ©gradation de performance lorsque le modÃ¨le perÃ§oit qu'il approche
de la limite de contexte.
â— Extended Thinking : RÃ©flexion interne (<thinking>). Doit Ãªtre budgetÃ© (ex: 1024 tokens).
â— IC/CT : Impact Cognitif / Consommation Token. Le ratio fondamental.
â— MCP (Model Callable Programs) : Serveurs d'outils externes. Source de gaspillage si
non filtrÃ©s (jusqu'Ã  46K tokens).
â— Prefill Assistant : Technique API pour prÃ©-remplir la rÃ©ponse, forcer le format et Ã©liminer
le bavardage.
â— Prompt Caching : Mise en cache du contexte stable. 90% rÃ©duction sur lecture. TTL 5
min. ROI break-even Ã  2 utilisations.
â— Statelessness : CaractÃ©ristique oÃ¹ l'historique complet est retraitÃ© Ã  chaque requÃªte.
â— Sub-Agent Architecture : DÃ©composition des tÃ¢ches en agents isolÃ©s contextuellement
(jusqu'Ã  96% d'Ã©conomie).
â— TDD (Test-Driven Development) : Workflow de codage rÃ©duisant la consommation de
tokens de 50%.
Annexe B : BibliothÃ¨que de Snippets RÃ©utilisables [Module 8]
Activation Parallel Tools (XML) :
XML
<use_parallel_tool_calls>
If no dependencies exist between tools, execute ALL simultaneously.
</use_parallel_tool_calls>
Budget Extended Thinking (XML) :
XML
<extended_thinking_budget>1024</extended_thinking_budget>
Directive Workflow TDD (Markdown) :
Markdown
TDD WORKFLOW MANDATORY. 1. Write failing test. 2. Implement. 3. Refactor.
RÃ´le Expert (Template) :
XML
<expert_persona>Act as an elite [DOMAIN] expert specialized in
[SUB-SPECIALTY].</expert_persona>
Directive de Compaction Manuelle :
/compact Preserve key decisions, final outputs, and current goals. Discard intermediate steps.
Annexe C : Checklist Master (20 Points) [Module 8]
Phase 1 : Analyse du Project Knowledge (CLAUDE.md)
â— [ ] Taille optimale respectÃ©e (50-300 lignes) ?
â— [ ] Syntaxe directive impÃ©rative utilisÃ©e exclusivement ?
â— [ ] ZÃ©ro duplication de documentation (utilisation de @docs) ?
â— [ ] Moins de 5 exemples few-shot statiques inclus ?
â— [ ] Absence de directives toxiques (ex: "Minimize tokens") ?
Phase 2 : Analyse de la Configuration Technique
â— [ ] Artifacts dÃ©sactivÃ©s si non utilisÃ©s activement ?
â— [ ] Serveurs MCP filtrÃ©s via Proxy ?
â— [ ] Prompt Caching activÃ© ET ROI validÃ© (>2 utilisations/5min) ?
â— [ ] Configuration "1M Trick" utilisÃ©e si applicable ?
â— [ ] Extended Thinking budgetÃ© (~1024 tokens) ?
Phase 3 : Analyse des Workflows et de l'Orchestration
â— [ ] Workflow TDD appliquÃ© pour les tÃ¢ches de codage ?
â— [ ] Architecture Sub-Agent utilisÃ©e pour les tÃ¢ches complexes ?
â— [ ] Compaction manuelle prÃ©emptive (Ã  60-70%) utilisÃ©e ?
â— [ ] XML Tags utilisÃ©s pour structurer les prompts complexes ?
â— [ ] Prefill Assistant utilisÃ© pour garantir les formats de sortie ?
Phase 4 : Analyse des Patterns d'Interaction
â— [ ] Role Prompting spÃ©cialisÃ© utilisÃ© ?
â— [ ] Dynamic In-Context Learning utilisÃ© (si RAG disponible) ?
â— [ ] Tool Result Clearing exploitÃ© (Claude 3.7+) ?
â— [ ] Utilisation du contexte effectif maintenue sous 100K tokens ?
â— [ ] Structured Note-Taking utilisÃ© pour la persistance long-terme ?
Annexe D : Templates CLAUDE.md par Type de Projet
(Voir les configurations de base prÃ©sentÃ©es dans la Partie IV pour DÃ©veloppement (1.1),
Recherche (2.1), RÃ©daction (3.1), Multi-Agent (8.1)).
Annexe E : Prompts Meta-Instructions
(Voir Annexe B pour les snippets clÃ©s).