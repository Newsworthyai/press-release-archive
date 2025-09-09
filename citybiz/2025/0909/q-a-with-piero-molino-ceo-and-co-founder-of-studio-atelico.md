# Q&amp;A with Piero Molino, CEO and Co-Founder of Studio Atelico

Piero Molino, PhD, is CEO and co-founder of Studio Atelico, a company building generative AI video games and technology that runs on device. He was also the Chief Scientist and co-founder of Predibase (acquired by Rubrik), a company that specializes in LLM/SLM fine-tuning and serving.

 He previously worked as a research scientist exploring machine learning and natural language processing at Yahoo!, IBM Watson, Geometric Intelligence (acquired by Uber), Uber (where he was a founding member of the Uber AI organization), and Stanford University. At Uber he worked on research topics including Dialogue Systems, Language Generation, Graph Representation Learning, Computer Vision, Reinforcement Learning and Meta Learning.

 What makes us stand out is that we’re not building AI for efficiency or automation, we’re building it to make games that couldn’t exist before.

 He also worked on several deployed systems like COTA, an ML and NLP model for Customer Support, Dialogue Systems for driver hands free dispatch, on the Uber Eats Recommender System with graph learning, and on collusion detection. He is the author of Ludwig, a Linux-Foundation-backed open source declarative deep learning framework with more than 12k stars on GitHub.

 What was the inspiration behind starting Studio Atelico and what are the company’s goals?

 The inspiration for Studio Atelico comes directly from my lifelong passion for both games and AI. I grew up coding games (starting at age 6 with my own Pac-Man on Amiga) and dreamed of combining AI with video games ever since playing titles like Populus, SimCity, and Dungeon Keeper.

 The turning point came when I saw the Generative Agents paper from Stanford and realized generative AI was mature enough to finally revolutionize games. But when talking to more than 40 developers at GDC, I found they were all struggling with cloud AI’s costs, restrictions, and technical limitations. This pain point inspired me to assemble a team from Uber, Meta, SEGA, Creative Assembly, Stanford, and MIT to build a better alternative: an on-device, modular AI engine for games.

 When we started Studio Atelico, we wanted to create games that couldn’t exist before; worlds and characters that feel alive, reactive, and improvisational, going beyond branching stories or prefab content. With our Atelico AI Engine, we can achieve that. However, our technology wasn’t just made for us but for other developers that would empower them. It’s a toolkit for studios of all sizes to build AI-powered experiences without prohibitive cloud costs. This toolkit keeps AI on-device and sustainable, to reduce costs, give developers full control, and minimize AI’s environmental footprint.

 Lastly is the ethical use of AI. We want to ensure artists give explicit consent, have fair compensation when their work is used in AI fine-tuning, and share in the revenue. We emphasize that AI is an amplifier of creativity, not a replacement.

 What are some of the practical results that are coming out of Studio Atelico that audiences and developers can expect?

 With our Atelico AI Engine, developers can expect it to run on-device which avoids crippling cloud costs and latency. It follows a modular design that allows developers to pick and combine components (e.g. agent-based NPCs, dynamic narration, adaptive gameplay and more). Additionally, our engine utilizes fine-tuned small models trained specifically for gaming tasks to bridge the quality gap with big cloud models while staying efficient. The engine can also be embedded in major engines such as Unreal, Unity and Godot.

 Last November, we put out our Generative Agents Realtime Playground (GARP) demo which simulated a village with 20+ Non-Player Characters (NPCs) who plan their day, form memories, converse, and even throw surprise birthday parties; NPCs act differently each day and coordinate naturally with one another, which takes emergent behavior to the next level compared to what audiences typically expect from traditional NPCs. It also runs in real time on a single GPU (RTX 3080) at no extra cost, compared to the ~$500/day cloud costs of the Stanford prototype.

 Right now, we’re working on our first game which will include mechanics that couldn’t exist without our AI Engine. We’re really looking forward to sharing more on this in the future.

 How does Studio Atelico’s technology work?

 Studio Atelico’s technology is an on-device AI engine that plugs into game engines like Unreal or Unity, similar to a physics engine. It runs small, specialized AI models trained for specific games and tasks, which makes them both fast and small enough for on-device real-time gameplay without the crushing costs of cloud AI.

 In other words, it’s AI that runs locally that’s tailored for games, giving developers more control and players richer, reactive worlds.

 Can you expand on Studio Atelico’s philosophy when it comes to AI and gaming?

 Our philosophy at Studio Atelico is simple: AI should expand creativity, not replace it.

 We don’t see AI as a way to make development cheaper or to automate existing pipelines. Instead, we want it to unlock new genres, mechanics, and experiences that couldn’t exist before.

 For us, AI is a new kind of tool for developers, like how physics engines once opened up whole new categories of gameplay. That’s why we focus on “blue ocean” opportunities as Satoru Iwata, Nintendo’s former CEO, would put it, rather than chasing cost savings or shortcuts.

 Just as importantly, we believe in ethics and respect for artistry. Consent, compensation, and collaboration with artists are baked into our process, so AI always amplifies human creativity rather than undermining it.

 We don’t use AI as a shortcut, we use it as a canvas stretcher, widening creative possibilities for developers and players while keeping artistry at the core.

 How extensively is generative AI going to affect game development at large?

 From a game development perspective, developers will use it like they use any other tool. From a gameplay perspective, it will become embedded in most games like physics, 3D rendering, networking and similar technological advancements.

 What makes Studio Atelico stand out from its competitors?

 What makes us stand out is that we’re not building AI for efficiency or automation, we’re building it to make games that couldn’t exist before.

 We utilize on-device AI, not cloud AI. This means that our engine runs locally on players’ hardware, avoiding the massive costs, latency, and restrictions that come with cloud models. This gives developers full creative control and freedom to monetize however they want.

 Instead of general-purpose AI, we train small, specialized models tuned for specific games and tasks. This makes them feel faster, more efficient, and better at delivering the feel developers and players want.

 Our ethical and philosophical outlook on AI is another pillar that sets us apart. We’re committed to explicit consent, compensation, and collaboration with artists. AI, in our vision, amplifies artistry and doesn’t seek to replace it. We also view AI as a tool, not a shortcut. While many studios use AI to cut costs or speed up asset production, we focus on using it to open up new genres, mechanics, and forms of emergent gameplay.

 And lastly, our GARP demo, mentioned previously, showed a living village of 20+ characters running in real time on a single GPU, something no other team has done at this scale or cost.

 Your company recently announced its $5M funding round, how will this capital be used?

 We’re using the $5M to build games that couldn’t exist before, strengthen the Atelico AI Engine so other studios can use it, and invest in artists through fair, ethical collaboration. This funding gives us the runway to prototype bold new gameplay, refine our toolkit, and ensure creativity, not just cost-cutting, this is the heart and soul of Studio Atelico and our work.

 Your recent blog mentioned how Studio Atelico is building, “games that couldn’t exist before,” can you expand upon that?

 When we talk about “games that couldn’t exist before,” we mean mechanics and systems that hand-authored design can’t practically support. For example, in a strategy game like Civilization, diplomacy could move beyond static dialogue trees into AI-driven negotiation, where factions weigh your history, reputation, and current actions to propose alliances or betrayals in ways that feel organic. In a detective game, NPCs could mislead you, hide evidence, or form alibis on their own, with the truth emerging from their autonomous choices rather than being pre-scripted. We’re also exploring the idea of an AI director, similar to what Valve did with Left 4 Dead’s pacing system, but far broader, where AI doesn’t just govern NPCs, but dynamically adjusts world events, quests, or even narrative arcs to respond to the way you play.

 On top of that, our tech enables on-the-fly content generation that adapts to the player. That could be as small as an NPC improvising dialogue in the voice of a bard reacting to your latest blunder, or as large as generating a new game mechanic mid-play if you try something the designers hadn’t anticipated. For instance, a village could invent a holiday based on your actions, or a crafting system could expand with recipes discovered through your experiments. These are systems where AI doesn’t just fill in gaps: it actively shapes the experience around the player, making each playthrough feel personal, reactive, and alive.

 Where do you see the future of AI as it becomes more ingrained in technology and culture?

 Like every other technology, AI will become better understood in its usefulness and its limits when it becomes just another tool in developers’ toolboxes. The same happened with databases, with networking technology, with the web, they become just so engrained that they become normal.

 What can we expect from Studio Atelico in the future?

 The release of our first game, followed by the availability of the engine for other developers to use in their games!

 The post Q&A with Piero Molino, CEO and Co-Founder of Studio Atelico appeared first on citybiz. 

---

[Original/Source Press Release](https://www.citybiz.co/article/740656/qa-with-piero-molino-ceo-and-co-founder-of-studio-atelico/)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/studio-atelico-revolutionizes-gaming-with-on-device-generative-ai-technology/e01e7949d33c92433ed71c012d1ecd7f) 


Pickup - [https://burstable.news/news](https://burstable.news/news/202509/202727-studio-atelico-develops-on-device-ai-engine-to-revolutionize-gaming-with-sustainable-ethical-technology)

Pickup - [https://estallarnoticias.com/](https://estallarnoticias.com//202509/202739-studio-atelico-desarrolla-motor-de-ia-en-dispositivo-para-revolucionar-los-videojuegos-con-experiencias-generativas-unicas)

Pickup - [https://actueclair.com](https://actueclair.com/202509/202866-studio-atelico-revolutionne-le-jeu-video-avec-une-ia-generative-fonctionnant-sur-appareil)
 



[Reddit Post](https://www.reddit.com/r/technology_press/comments/1ncq80r/studio_atelico_revolutionizes_gaming_with/) 



![Blockchain Registration](https://cdn.newsramp.app/citybiz/qrcode/259/9/plum_yBB.webp)