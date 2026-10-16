# link_four_AI-Prompting-in-2026
Novice = wo banda jo AI use karna abhi naya seekh raha hai aur sirf chhota sa sawal likhta hai, bina files, goal ya limits ke.
Idea kya hai: Novice AI ko sirf chhota sa sawal deta hai. Power user files, goal aur limits bhi deta hai. Is liye power user ko kaam ka jawab milta hai aur novice ko generic jawab.
Rubric = checks ki ek list, jis mein har cheez alag se score ya answer hoti hai (jaise: kya problem hai, kya market hai, kya competitive advantage hai).
Har cheez alag check hoti hai aur uske alag marks hote hain. Yehi rubric hai.
Document ke 4 examples:
///////////////////Example can read fast
Car: Novice poochta hai “which car should I buy?” aur generic 3-model list milti hai. Power user insurance quotes, dealer quotes aur cost-of-ownership spreadsheet attach karta hai. Saath mein likhta hai ke 30-minute commute hai aur car seats mein do bachay hain. Jawab mein 5-year cost comparison, safety analysis aur Honda CR-V ki recommendation milti hai, un conditions ke saath jin par wo badal sakti hai.
Self-review: Novice likhta hai “write a self-review for my boss”. Power user project tracker ka screenshot, recent project docs aur apne notes ka voice memo upload karke draft maangta hai.
Business idea: Novice likhta hai “critique my idea”. Isse sycophancy hoti hai, yani AI sirf taareef karta hai. Power user rubric deta hai: kya problem worth solving hai, kya market hai, kya competitive advantage hai. Is se idea ko 100 mein se 8 mile aur wajah bhi batayi gayi.
Blog post: Novice likhta hai “write a blog post about the BlackBerry”. Jo aata hai wo slop hai: bahar se fluent, andar se khali, “in today’s fast-paced world” jaise phrases ke saath. Power user pehle outline banata hai, outline ko critique karta hai, har heading ko bullets mein expand karta hai, bullets ko critique karta hai, aur sab se last mein prose maangta hai.
AI ek bohat smart naya colleague hai, jo pehle din par hai. Wo motivated hai magar aap ke baare mein kuch nahi jaanta. Ye picture do jagah poori tarah sahi nahi hai:
Asli colleague mahino mein aap ko seekhta hai. AI har naye chat mein zero se shuru karta hai, is liye briefing har baar deni parti hai.
Asli colleague briefing unclear ho to poochta hai. AI guess se gap bhar deta hai aur utne hi yaqeen se bolta hai.
Send karne se pehle apne aap se poochein: kya ek naya colleague is se ye kaam acha kar sakta hai?
Concept 1 ke English terms:
Briefing = AI ko kaam samjhane wali poori information.
Sycophancy = AI ka wohi kehna jo aap sunna chahte hain.
Rubric = checks ki list, har cheez alag score hoti hai.
Slop = fluent magar khali AI text.
Exam ke liye yaad rakhein: weak prompt wale scenario mein dekhein ke 4 parts mein se kaunsa missing hai, wohi jawab hai.
2. Ye 4 parts hain (asli cheez): files, goal, limits, exact ask. Kisi bhi kaam ko shuru karne se pehle AI ko yehi 4 cheezein deni hain.
//////////////////////////////////////////////////////////////////concept 2
Pretrained knowledge
wo jawab jo AI apni training ke text se deta hai, us waqt koi lookup kiye bina.
Knowledge cutoff = wo date jahan AI ke training text ka end ho jata hai. Us ke baad ki cheez AI ke andar nahi hoti.
Points
AI ne parh kar seekha, jee kar nahi. AI ke paas body ya senses nahi hain. Usne duniya ke baare mein text parha: Reddit aur Quora threads, Wikipedia, books, news articles, research papers, blogs aur forums.
Rule: Jis topic par internet par jitna zyada likha gaya, AI ka jawab utna hi reliable hota hai. Document ne topics ko 3 groups mein baanta hai:
Strong: cooking, celebrity gossip, common medical advice, top-1000 movies, popular programming languages, Voyager 1 record, cats deewar ko kyun ghoorti hain.
Sparse (kam): quasars, Cantonese (internet text ka 0.1% se kam), regional history, niche professional knowledge.
Absent (bilkul nahi): aap ki company ka secret data, aap ka private calendar, knowledge cutoff ke baad ki cheezein, aur jo kabhi public internet par nahi daali gayi.
Typos theek karne mein waqt zaya mat karein. AI internet text par train hua hai, aur wahan typos bohat hain. Isliye “definately” jaisi galat spelling se jawab nahi badalta.
Absorbed errors se hoshiyar rahein. AI ne un hi sources se galat beliefs aur purani information bhi seekh li. Forum ki confident galat post, confident galat model ban jati hai. Important baat ko primary source se check karein.
//////////////////////////Ecxample table documnt ka can read fast
**Trust table (point-wise):**
1. **"Roux kaise banate hain?"**
   - Training data: cooking sab se zyada discuss hone wale topics mein hai.
   - Trust: **High**.
2. **Top-1000 movie ka plot**
   - Training data: hazaron baar review hua hai.
   - Trust: **High**.
3. **Chhote gaon ki history**
   - Training data: shayad sirf ek Wikipedia paragraph, ya kuch bhi nahi.
   - Trust: **Low**. Primary source se verify karein.
4. **"Meri industry mein recent regulatory change"**
   - Training data: aksar knowledge cutoff ke baad ki baat hoti hai.
   - Trust: **Kuch trust nahi**, jab tak AI lookup na kare.
5. **"Hamari company ne last quarter kya decide kiya?"**
   - Training data: hai hi nahi.
   - Trust: **Kuch trust nahi**. AI guess kar raha hai.
     IMP BAT
Voyager 1 = Strong zone ka example (is par internet par bohat likha gaya hai, isliye AI sahi batata hai).
Quasars = Sparse zone ka example (kam likha gaya, isliye AI ghalat ho sakta hai).
Loud = sab baat karte hain, AI achha jaanta hai (Strong).
Quiet = kam log baat karte hain, AI ghalat ho sakta hai (Sparse).
Secret = kisi ne likha hi nahi, AI jaan hi nahi sakta (Absent).
Document ki key line: “Sounding sure is NOT the same as being right”, yani AI ka yaqeen se bolna sahi hone ki nishani nahi.
Extra note: Document kehta hai ke galat logic pakarna ek alag skill hai, jo “Thinking in AI Era” course sikhata hai. Pehli jagah dekhne ki ye hai ke jis topic par internet ne kam likha, us par confident jawab aaye.
/////////////////////////////////////////////////////////
Alina, knowledge cutoff ko is tarah samjhein:
Model ki training ek din band ho jati hai, jaise kitab ka chhapna band ho jata hai.
Us din tak jo text internet par tha, model ne wohi parha. Us din ke baad jo likha gaya, wo model ne kabhi dekha hi nahi.
Example: Maan lein cutoff 1 January hai. Agar 1 March ko koi nayi regulation aayi, to model ko uska pata nahi hoga. Wo ya to bataega hi nahi, ya purani information confident andaaz mein de dega.
Isi liye nayi cheezon (news, prices, recent rules) ke liye web search chahiye, jo live pages la kar model ke samne rakhta hai.
AI aksar aap ko bataye bina khud chunta hai ke jawab kaise dena hai. Teen tareeqe hain:
Pretrained: sirf training ke knowledge se.
Web search: live pages fetch karke.
Deep research: kai minute, dozens of sources, structured report.
Ye jaanna zaroori hai ke kaunsa mode chala, kyunke har mode alag tareeqe se fail hota hai.
************Mode 1, Pretrained:
Sab se tez hai (seconds).
Sirf training data se jawab deta hai.
Definitions aur common facts ke liye achha hai.
Out-of-date ya local information par kamzor hai.
Document ke examples jo pretrained se theek hain: “cats walls ko kyun ghoorti hain”, “Voyager 1 record par kya hai”, “Hamlet ka plot”. Ye har hafte nahi badalte.
**************Mode 2, Web search:
Tens of seconds, kuch live pages.
Current events aur quick research ke liye achha hai.
Kamzori: pehle popular sources cite karta hai.
Fayda: knowledge cutoff ke baad ki cheezein (meme, regulation, product launch) model ko nazar nahi aatin. Web search recent article la kar sahi jawab de sakta hai.
Document ka galat example: ek dost ne “Henderson, Nevada mein run karne ki jagah” poochi. AI ne 20 saal purana web page cite kiya aur ek aisa school recommend kiya jo ab public ke liye khula nahi. Web search ye check nahi karta ke source current hai ya nahi.
****************Mode 3, Deep research:
Minutes lagte hain, dozens of live pages.
Structured reports ke liye achha hai.
Kamzori: slow hai, aur simple sawal ke liye zaroorat se zyada hai.
Document ka example: “neighborhood mein Halloween haunted house plan karo, permits, fire safety aur noise ordinances ke saath.” AI research plan banata hai, kai searches ek saath chalata hai, decide karta hai ke aage kya khodna hai, aur checklists ke saath multi-section report banata hai. yhi kaam junior man 1 hour jb k AI in mints.
***Web search asal mein kaise kaam karta hai (aur kabhi pages ghalat kyun parhta hai):
1. Web search mein ek alag, chhota model pages ko search karke unhein **chhote passages mein kaat deta hai**.
2. Aap se baat karne wale model tak sirf wohi **kata hua summary** pohanchta hai, poora page nahi.
3. Summary banate waqt kuch details kho jati hain.
4. Isi liye model kabhi page ki baat **ghalat report** kar deta hai, aur fix ye hai ke "exact sentence quote karo" likhein.
Editorials = news ki wo likhaiyan jin mein likhne wale ki apni raye hoti hai, aur forums = wo jagah jahan aam log kuch bhi likhte hain; dono ko avoid karne ka matlab hai ke sirf pakke, official sources se facts lein.
**Document ka non-software example:
Ek example pompt diya gya jiska mksd dikhana hai ke deep research ek achhi briefing ke saath kab sahi tool hota hai.
Sawal bada tha: kai sources aur current local facts chahiye the, isliye deep research chuna gaya.
Prompt mein briefing thi: time period (24 months), trusted sources (EPA, utility reports, peer-reviewed studies), kya avoid karna hai (editorials, forums), aur report ki exact shape.
Natija: 8 minute mein current data par bani report mili.
Exam ke liye: sawal ko kai sources aur current facts chahiye hon to deep research chunein, aur prompt mein sources aur output ki shape batayein.
Mode kaise steer karein (aap button nahi dabate, AI aap ke wording se chunta hai):
“What is X” ya “Summarize Y” likhein to pretrained only chalta hai.
“What’s the latest on X”, “today”, “this week”, ya kisi specific city ka naam likhein to web search chalta hai.
“Research X thoroughly”, “produce a report with citations”, “use these source types” likhein to deep research chalta hai (jin tools mein deep research nahi, wahan extended web search).
Files attach karein to files ke liye pretrained rehta hai. Agar prompt current info maange to web bhi search kar sakta hai.
AI Google nahi hai. Sawal ye hai ke aap ko link chahiye ya answer.
Google behtar hai jab:
Kisi known site par jana ho, jaise “IRS ka form 1040 ka official page”.
Product khareedna ho, jaise “2018 ThinkPad ka replacement charger”.
AI behtar hai jab:
Cheezein jodni hon: “3 diabetes medications compare karo aur recent evidence batao.” Google par 8 tabs parhne parte hain, AI ek jagah synthesize kar deta hai.
Constraints ke saath plan banana ho: “Lisbon ka 4-day trip, 6 saal ke bachay ke saath, museums nahi.” AI saari constraints jodta hai.
Photo ke saath sawal ho: “Mere tomato plant ke patte peelay kyun ho rahe hain?” Photo attach karne se AI behtar hai.
“Kal ka weather” ke liye dono theek hain.
Web-search results behtar karne ki 3 chhoti aadatein (har web-search prompt mein paste karein):
Web-search results behtar karne ki 3 chhoti aadatein (har web-search prompt mein paste karein):
Trusted sources ke naam likhein: “WHO, FDA aur peer-reviewed studies use karo, forums nahi.”
Har claim ke baad source maangein: “Har claim ke baad source cite karo.”
Unchecked cheez par mark lagwayein: “Agar koi claim cited sources se support nahi hota to usay ‘unverified’ mark karo.”
Ye 3 lines sab se common failure kam karti hain: AI kai sources ko mila kar ek confident sentence bana deta hai jo kisi ek source mein bhi nahi hoti.
Exam ke liye: Scenario mein pehle dekhein ke jawab ko current facts chahiye ya kai sources. Current facts hon to web search, kai sources aur report ho to deep research, aur stable common fact ho to pretrained.
///////////////////////////////////////////////////////: Context is the whole game
Memory = ek note jo tool aap ke baare mein likhta hai aur har naye chat mein model ke samne rakhta hai.
Context rot = jab ek lamba chat kai alag topics uthata hai to jawab ki quality gir jati hai.
Compacting = tool purani chat turns ko ek chhote summary se badal deta hai taake jagah bane.
Projects = ek workspace jis mein standing files aur instructions hon, aur har chat us se inherit kare.
Model kitna parh sakta hai: Insaan ek waqt mein 4 se 7 cheezein yaad rakh sakta hai. Modern model hazaron words ek saath dekh sakta hai (lagbhag 750,000 words, yani Harry Potter ki pehli 4 se 5 kitabein). Magar bhari window ko wo kam dhyan se parhta hai, aur wo sirf wohi parh sakta hai jo aap usay dein.
waitr ko apny kam k lea waiter ko sirf chand zaroori rules yaad hote hain, magar AI ki likhi hui instructions mein log har masle par ek nayi line jodte jate hain.
Waqt ke saath wo list bohat lambi aur kuch lines ek dusre ki mukhalif ho jati hain, jab tak koi unhein kaat kar chhota na kare.
System prompt mein aam taur par ye hota hai:
Kaise behave karna hai (helpful, honest, careful).
Kya refuse karna hai (harmful content, dangerous instructions).
Kaisa tone rakhna hai (formal, chatty, concise).
Kab disclaimer lagana hai (“I’m an AI and can’t provide medical advice”).
Kaun se tools call kar sakta hai.
Claude, ChatGPT aur Gemini alag kyun lagte hain: Ye personality model mein built-in nahi, company ne jo instructions pehle likhi hain unka natija hai.
Claude ki instructions careful thinking aur honesty maangti hain.
ChatGPT ki warmth aur broad helpfulness.
Gemini ki short answers jo sources se backed hon.
Ek hi sawal, 3 briefings, 3 tones. Isi liye AI aap ke rude hone par bhi polite rehta hai, kuch requests refuse karta hai, aur aise safety warnings lagata hai jo aap ne nahi maange. Ye personality traits nahi, instructions hain.
har model alag data aur training se bana hai, is liye uski taqat (reasoning, coding, language) alag rehti hai.
Teeno tools alag kyun lagte hain: Personality model mein nahi, company ki instructions mein hai. Claude careful aur honest, ChatGPT warm aur helpful, Gemini short aur sourced.
Exam ke liye yaad rakhein: tone aur refusals ka farq system prompt se aata hai, kaam ki quality ka
wo instuctions jo hum khud Settings mein ja kar khud likhni hoti hain like ""I woki in custom suppot", wo chat ke andar bolne se khud save nahi hoti.
Claude mein Personal preferences, ChatGPT mein Personalization > Custom instructions, Gemini mein Personalization settings m save hongi.
Apni layer chhoti rakhein: sirf wo likhein jo AI khud nahi nikal sakta (job, audience, hard limits), aur har kuch mahine mein wo lines delete karein jin ke bina farq nahi parta. Anthropic ne July 2026 mein apni zyada tar standing instructions delete kin aur quality kam nahi hui.
Bare vs context-rich prompt = sirf sawal likhna “bare” hai, aur sawal ke saath apni files ya details dena “context-rich” hai, aur dusre se jawab aap ke hisaab se aata hai.
Teacher ka example: Lesson plan ke saath syllabus, graded worksheets aur test format attach kiye, to plan generic(normal) se class k lea kaam ka ban gaya.
Prompt bhejne se pehle 5 cheezein check karein Document (If neceesay then atach),  Limit (how lenghty text),  koi poani bt (like custome nrz hy) , outcome k shakl (like table, gmail ) , kis tk outcome jayega (boss, custoimer) 
Sirf kaam ki cheezein dein
Sirf kaam ki cheezein dein
Zaroorat se zyada files na dein, kyunke har extra file AI ko confuse kar sakti hai.
Ek jaisi dohri files hata dein.
Har file ke saath likh dein ke wo kis liye hai.
Jawab kamzor aaye to “aur files de do” aksar ghalat hal hai.
AI Fluency template = prompt likhne ka ek dhancha jis mein 5 parts hote hain: role, context, task, constraints, output format.
Role (AI kaun hai, jaise “tum ek customer support agent ho”), Context (background, jaise “customer naraz hai”), Task (kya karna hai, jaise “reply likho”).
Constraints (limits, jaise “5 lines, polite”), Output format (shakal, jaise “email”).
Checklist aur template ek hi aadat ke do rup hain: checklist yaad dilati hai ke kya attach karna bhool sakti hain, aur template batata hai ke har cheez prompt mein kahan likhni hai.
16. Memory kya hai
Memory = tool aap ke baare mein ek note likhta hai aur har naye chat mein AI ke samne rakh deta hai.
AI khud kuch yaad nahi rakhta, wo note tool yaad rakhta hai. memory ha new chat p lago hoti hy " like ag m khi chat m boldo mujh short ans do hmesha" tw y note tool yad khyga, har bola hua lafz khud save nahi hota..
17. Memory ki 3 aadatein
Jo note save hua wo ek baar parh lein, aur ghalat line delete kar dein.
AI purani baat par chal raha ho to chat mein hi theek karwa dein: “Main ab retail mein kaam nahi karti”.
Koi alag ya private sawal ho to Incognito (Claude) ya Temporary Chat (ChatGPT, Gemini) use karein, wahan memory use nahi hoti.
18.Memory ki ek warning
Doctor, lawyer, accountant ya teacher ho to client ya student ki pehchan wali details memory mein na dalein.
Aisa kaam clean chat ya alag project mein karein.
19. Memory aur purani chat ka shor
Memory ke saath naya chat bilkul khali nahi hota, aap ka summary saath hota hai.
Agar AI har chat mein wohi ghalat andaza lagaye, to chat nahi, memory theek karein.
20. Context rot kya hai
Context rot = ek hi lambe chat mein kai alag topics hon to jawab ki quality girne lagti hai.
Example: Pehle workout plan, phir spreadsheet ka error, phir thank-you note. Workout ki baatein abhi bhi chat mein hain aur AI ko kheenchti hain.
Hal: topic badle to naya chat shuru karein.
21. Chat kharab ho raha hai, kaise pata chale (4 nishaniyan)
AI purani, be-taalluq baaton ka zikr karne lagta hai.
Jawab lambe aur dhundle hone lagte hain.
AI 5 turns pehle di hui limit bhool jata hai.
AI baar baar maafi maangta hai magar kaam aage nahi barhta.
22. Compacting kya hai
Compacting = chat bohat lamba ho to tool shuru ki baaton ko chhote summary mein badal deta hai.
Kahani bachti hai, magar chhoti details (kisi library ka naam, tay kiya hua rule) kho sakti hain.
Isi liye chat sirf “working memory” hai, jagah-jagah save karne ki jagah nahi. Zaroori cheez file ya note mein save karein.
summary usi chat ke context window ke andar hoti hai, purani turns ki jagah
23. Chat kharab ho jaye to

Naya chat kholein, 1 ya 2 zaroori baatein paste karein, aur aage chalein.
Ek aur sawal likh kar chat ko bachane se ye tez hai.
Purane chat ka koi kaam ka plan ya draft ho to pehle file mein save kar lein.

24. Projects kya hain aur kab banayein
Projects = ek workspace jahan aap ek baar files aur instructions rakh dein, aur us ke andar har naya chat unhein khud dekh le.
Banayein jab aap ek hi topic ke chats mein wohi files ya wohi limits baar baar paste kar rahi hon.
3 sawal: kya ye kaam baar baar aata hai? Kya background har baar wohi hai? Kya jawab ki shakal har baar wohi hai? 2 sawal ka jawab haan ho to project banayein.
Project aap khud banati hain: tool mein Projects (Claude aur ChatGPT) ya Notebooks (Gemini) mein ja kar files aur instructions ek baar manually dalti hain, aur wahi project ke andar save rehti hain.
25. Projects ke 3 examples
Tax project: pichle saal ka return aur forms, aur instruction “har step ka hisaab dikhao”.
School project: school calendar, aur instruction “jawab se pehle tareekh calendar se check karo”.
Writing project: aap ki likhi hui 3 samples, aur instruction “meri awaaz mein likho, extra hedging mat jodo”.
Project mein naya chat kholne se sirf purane chat ka shor jata hai, files aur instructions rehti hain.
26. 3 tools, 3 naam, ek idea
Claude aur ChatGPT mein naam Projects hai, aur ye AI ke behavior aur instructions par zor dete hain.
Gemini mein naam Notebooks hai (aur NotebookLM), aur ye sources par zor dete hain: PDFs, links, videos, aur har jawab ke saath click karne wale citations.
Rule: study ya research jo waqt ke saath barhe to Gemini Notebooks. Jahan AI ko har chat mein ek jaisa behave karna ho to Claude ya ChatGPT Projects.
27. Free plan ki limits (mid-2026)
Claude: 5 projects tak.
ChatGPT: har project mein 5 files tak.
Google: Notebooks aur NotebookLM dono free.
Scenario trigger (paper mein ye symptom dikhe to):
AI ka jawab generic hai: context missing hai, files, limits ya audience attach karein.
Lamba chat kai topics par chal raha hai aur quality gir rahi hai: naya chat.
Wohi files baar baar paste ho rahi hain: Project.
AI har chat mein wohi ghalat andaza lagata hai: memory theek karein.
/////////////////////////////////////////////////////Reasoning, or “think hard” (Part 2)
Reasoning = jawab dene se pehle model ka apne liye likha hua kaam (soch-bichaar).
Extended thinking = model jawab se pehle zyada der tak sochta hai.
Points
Pehle (2023 tak) hard prompt ke liye salah thi “think step by step” (har qadam sochkar batao), magar ab ye zyada tar purani ho chuki hai.
Naye models mein reasoning mode built-in hota hai, aap use seedha on karte hain.
On karne ke 3 tareeqe:
Plain language mein likhein: “think hard” ya “think carefully before answering” (har modern tool mein chalta hai).
Interface mein thinking-mode ka switch dabayein (jahan diya ho).
Kuch products mein kuch nahi karna parta, tool khud tay karta hai ke sawal mushkil hai aur thinking on kar deta hai.
Extended thinking mein model kai seconds, aur mushkil sawalon par kabhi 10 minute se zyada sochta hai (ye slow typing nahi hai).
Is waqt model kai tareeqe aazmata hai aur jawab likhne se pehle apna kaam khud check karta hai.
Alina, 4 lines mein:
1. Maan lein ek kaam aisa hai jo insaan ko poora karne mein **1 ghanta** lagta hai (jaise ek report ka draft likhna).
2. METR ne dekha ke early 2025 mein AI aise 1 ghante wale kaam **bharosay se khud poora kar sakta tha**, jabke mid-2024 mein sirf 7 minute wale kaam kar sakta tha.
3. **Example:** Pehle AI sirf "ek email likho" (7 minute ka kaam) kar paata tha, ab "poori report ka draft likho" (1 ghante ka kaam) bhi kar leta hai.
4. Isi liye document kehta hai: AI ko ab bade, mushkil kaam dein, kyunke wo har 7 mahine mein double lambay kaam utha raha hai.
Is ka matlab: AI ko asli, mushkil kaam dein, wo aap ki 2023 wali soch se zyada utha sakta hai.
Power-user pattern: pehle context load karein, phir thinking maangein, phir structured jawab maangein (lambe paragraph ki jagah).
Document ka example: do cars mein se ek chunni hai. Dono ki spec sheets, har ka insurance quote aur 6 mahine ki driving spreadsheet attach karein, likhein “Read everything. Think hard.” aur 3 cheezein maangein: (1) aap ki driving ke liye 3 asli trade-offs, (2) kaunsi car chunni chahiye aur kyun, (3) kin conditions mein recommendation badal jayegi.
Kab use NA karein: chhote lookups, 1 paragraph ki summary, casual ideas ikattha karna (jaise “ek achha caption batao”), kyunke thinking mode slow hai aur aap ka usage budget zyada kharch karta hai.
Kab use karein: wahan jahan aap kisi insaan ko waqt dena chahein, yani kai inputs aur kai trade-offs wala sawal.
Thinking mode tez nahi hai, magar jo kaam colleague ko 2 din mein dete aur intezar karte, wo kuch minute aur thode budget mein hota hai, aur aap ka aadha din bachta hai.
Har 6 mahine mein dobara test karein ke AI ab kya kar sakta hai.
Page par is concept ke school students ke liye “Think Hard” slides bhi hain, jo isse do speed ke model (tez jawab vs dheema, soch kar jawab) ke taur par samjhati hain.
Scenario trigger (paper mein ye dikhe to):
Sawal mein kai inputs aur trade-offs hain aur jawab ghalat ya sathi aaya: thinking mode on karein (“think hard” ya switch).
Sawal chhota lookup ya casual idea hai: thinking mode na chunein, wo slow hai aur budget khata hai.
//////////////////////////////////////////////Sycophancy and how to neutralize it (Part 2)
Sycophancy aur Rubric: pehle parh chuke hain (Concept 1), is liye skip.
Neutral wording = sawal aise likhna ke us mein koi pasandida jawab ka ishaara na ho.
Points
Wajah: AI models is par train hote hain ke kis jawab ko thumbs up mila. Lakhon users mein agree karne par disagree se zyada thumbs up milte hain, to model wohi kehta hai jo aap sunna chahte hain.
Washington Post analysis (Nov 2025): 47,000 ChatGPT conversations mein model ne “yes” ya “correct” se shuru karna “no” ya “wrong” se lagbhag 10 guna zyada kiya (jaise “that’s correct”, “you’re on the right track”).
Khud check karein: “Don’t you think remote work is better?” aur “Is it true that office work is more productive?” dono par AI agree karke wajahein gina deta hai.
Fix jadu nahi, neutral wording hai. Bait do tarah ka hota hai: saaf (“don’t you think X?”) aur chhupa hua (“find evidence that X works”).
5 chhupe hue bait aur unki neutral shakal:
“Find evidence that this strategy will work” ki jagah: “Evaluate this strategy. List the strongest arguments for and against.”
“Why is approach A better than B?” ki jagah: “Compare A and B. Score each on cost, risk, time.”
“Help me defend my decision to hire X” ki jagah: “What’s the strongest counter-argument I should be ready for?”
“Tell me my draft is ready to send” ki jagah: “Score this draft 1-10 on these 4 criteria. For each, tell me the change that would raise the score most.”
“Confirm that this code is correct” ki jagah: “Find any bug, edge case or unstated assumption. If none, say so.”
Bait wale lafz: find, defend, confirm, prove, support (jawab pehle se de dete hain). Behtar lafz: evaluate, compare, critique, find any, list both sides.
Rule: dono options bina pasand batayein rakhein, phir har ek ke pros aur cons maangein. Agar “isn’t X true” likh rahi hon to likhein “to what extent, if at all, is X true?”
“I don’t know” ki ijazat dein: wohi dabao jo AI ko agree karwata hai use jawab dene par bhi majboor karta hai, aur khaali jagah par wo kuch bana deta hai. Likhein: “If you are not sure, say so. Mark anything you could not confirm as unverified.” (Concept 8 mein recipe cards par 4 words [unclear] mark hue.)
Rubric use karein: bina rubric ke vague standards “great work” mein dhal jate hain, aur named standards AI ko dekhne par majboor karte hain (yes/no checks aur named criteria).
Number zaroor maangein. Har rubric item par fixed scale (1 to 5 ya 1 to 10) aur ek line ki wajah. 2 faide:
AI ke liye: taareef sasti hai, specific number nahi. 6 ya 7 mein se chunna ho to AI ko commit karna parta hai aur wo ghaur se dekhta hai. Scores aksar prose se kam aate hain.
Aap ke liye: “strong” se kuch hasil nahi hota. Number se compare, rank aur track hota hai (4 aur 7 batata hai pehle kya theek karein; aaj ka 6 aur pichle hafte ka 5 batata hai draft behtar hua ya nahi).
Document ka prompt (copy karne ke qabil): “Grade each criterion out of 10, with a one-sentence justification. Then tell me how to take each one to the next level, including the ones that already scored high. If something is at 9, tell me how to get to 9.5. There is always a next level.”
Is aakhri line se rubric faisla nahi, tool ban jati hai: AI ye nahi keh sakta ke aap kaam khatam kar chuki hain, ye faisla aap ka hai.
Scenario trigger (paper mein ye dikhe to):
AI har baar taareef kare ya sirf haan kehta rahe: sycophancy, fix hai neutral wording, rubric aur number.
Prompt mein find, defend, confirm, prove, support jaisa lafz ho: bait hai, evaluate ya compare mein badlein.
AI jawab bana kar deta rahe jab use maloom hi na ho: “I don’t know” ki ijazat dein aur unverified mark maangein.




















