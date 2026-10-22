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
custom instuctions: wo instuctions jo hum khud Settings mein ja kar khud likhni hoti hain like ""I woki in custom suppot", wo chat ke andar bolne se khud save nahi hoti.
Claude mein Personal preferences, ChatGPT mein Personalization > Custom instructions, Gemini mein Personalization settings m save hongi.
Apni layer chhoti rakhein: sirf wo likhein jo AI khud nahi nikal sakta (job, audience, hard limits), aur har kuch mahine mein wo lines delete karein jin ke bina farq nahi parta. Anthropic ne July 2026 mein apni zyada tar standing instructions delete kin aur quality kam nahi hui.
Bare vs context-rich prompt = sirf sawal likhna “bare” hai, aur sawal ke saath apni files ya details dena “context-rich” hai, aur dusre se jawab aap ke hisaab se aata hai.
Teacher ka example: Lesson plan ke saath syllabus, graded worksheets aur test format attach kiye, to plan generic(normal) se class k lea kaam ka ban gaya.
Prompt bhejne se pehle 5 cheezein check karein Document (If neceesay then atach),  Limit (how lenghty text),  koi poani bt (like custome nrz hy) , outcome k shakl (like table, gmail ) , kis tk outcome jayega (boss, custoimer) 
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
Generic jawab: aap ne likha “email likho.” AI ne aam si email likhi jo kisi ke liye bhi ho sakti hai.
Wajah: AI ko pata hi nahi tha ke email kis ko jaani hai, kitni lambi, kis lehje mein.
Hal (context dena)
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
Document ka prompt (copy karne ke qabil): “Grade each criterion out of 10, with a one-sentence justification. Then tell me how to take each one to the next level, including the ones that already scored high. If something is at 9, tell me how to get to 9.5. There is always a next level.”
Matlab: AI se har criterion par number aur ek line ki wajah maangein, aur phir har ek ko behtar karne ka tareeqa bhi, chahe score pehle se high ho.
///////////////////////////////////////////Brainstorm-iterate loop
pehle context do, kai options maango, feedback do, dobara maango, aur sirf aakhir mein ek option ko poora likhwao.
Four kinds of ask = brainstorming, research, drafting, analysis (har ek mein “grip” alag hota hai).
**Chhota example:** Aap ko naraz customer ko email likhna hai.
1. **Context:** "Order 10 din late hai, customer naraz hai, refund ya replacement de sakte hain."
2. **Options:** "3 tones mein reply do: maafi-first, solution-first, friendly."
3. **Feedback:** "Option 2 pasand, bas 'unfortunately' hata do."
4. **Final:** "Option 2 ka poora email likho."
ound 1 k lea zrori bat 
Ji Alina, **haan**, ye Round 1 ka hi hissa hai.
Round 1 = pehle research maangna (5 sab se mazboot arguments aur 3 counter-arguments, ek ek line mein). "Map the ground" us research round ka maqsad batata hai: likhne se pehle dekho ke pehle se kya maloom hai (competitors pehle, product name baad mein; prior research pehle, strategy memo baad mein).
Ye koi alag round nahi hai.
Iterate karne ke 2 tareeqe: Grading (score do) aur Diagnosis (kamzor pehle result mein bataein ke kaunsa hissa fail hua, jaise audience ignore hua, length toot gayi, tone behak gaya; sirf wohi hissa badal kar dobara bhejein).
Score batata hai kitna door hain, diagnosis batata hai kya hilana hai.
iterate karne ke 2 tareeqe:
Grading = AI ko score dene ko kahein ([“is email ko 10 mein se score do”]).
Diagnosis = aap khud batayein ke result mein kaunsa hissa kharab hai ([“tone rude hai, length zyada hai”]), aur sirf wohi hissa badalne ko kahein.
Outline = post ka dhancha: sirf headings aur order, poora likha hua nahi.
Critique = AI se kehna ke is kaam ki kamiyan aur kharabiyan batao.
Grade = 10 mein se score dena.
Revise = critique ke mutabiq kaam ko dobara theek karna.
Heading = section ka title.
Bullets = chhote chhote points (har heading ke neeche 3 se 5).
Draft = poora likha hua pehla version.
Ranked list = list jis mein sab se zyada asar wali tabdili sab se upar ho.
Outline mein ek heading badalna: “Chhoti team ke fayde” ki jagah “Bari team ke fayde” likh dein, to poori post ka rukh badal jata hai (ab saari post bari team par hogi).
Final draft mein ek lafz badalna: “acha” ki jagah “behtar” likh dein, to sirf wahi ek jagah badalti hai, baaqi post waisi hi rehti hai.
Isi liye: outline mein ek chhoti tabdili ka asar bada hota hai, aur AI lafz-ba-lafz likhta hai, is liye pehle outline sahi karte hain taake poori shakal pehle se theek ho. KYUN KY DRIFT 600 wods p mushtammil ak bari tehrir hy is la wahan glti pkana mushkil hota hy.
Draft = kisi cheez ka poora likha hua pehla version, jo abhi final nahi hota aur jis mein tabdili ho sakti hai
Plateau = jab score barhna band ho jaye aur 9.5 ke aas paas ek jagah ruk jaye
14. Roz ke 6 mauqe jahan loop use hota hai
Har jagah wohi 2 cheezein: pehle context (apni situation), phir options aur feedback.
Example (4-day trip): “Budget $800, dates 5-8 March, 2 log, hum museums se bore hote hain” likh kar 5 rough itineraries maango, 2 reject karo, baaqi par dobara maango. Iska matlab: pehle apni zaroorat batao, phir AI ke options ko apne taste se filter karo.
Baaqi 5 mauqe isi shakal ke hain: product ka naam (10 naam maango, 3 chuno), mushkil email (3 tones, ek chuno), contractor chunna (3 quotes ko side-by-side score karo), learning path (3 course shapes, ek chuno), logo brief (5 mood-board directions, ek chuno).
Iska matlab: loop sirf likhne ke liye nahi, kisi bhi faisle ke liye chalta hai.
15. Grading har jagah lagu (Grading pehle parh chuke hain, is liye skip)
Sirf naya hissa: score kaam ke apne criteria par hota hai.
Example: itinerary par cost, pacing (rafta), group ka fit; naam par yaad rakhna (memorability), fit, risk; email par clarity (saaf hona), tone, asar.
Iska matlab: har kaam ke liye apne checks banao, sab par ek jaisa score nahi lagta.
Pacing = trip ki rafta, yaani din mein kitni jagahein dekhna hai (bohat zyada bhaag-daud ya aaram se).
16. Kab rukein
Apna kaam jo dobara use hoga (portfolio piece, template): score 9.5 ke aas paas thehre (plateau) tab tak chalein.
Ek baar deliver hone wala kaam: pehle ruk jayein. Jab agla prompt kam badle aur aap ki apni 2 minute ki edit tez ho, to khud sambhal lein.
Example: ek customer ko ek email bhejni hai. Do rounds ke baad aap ek lafz khud theek kar leti hain.
Iska matlab: har kaam ko 9.5 tak le jana zaroori nahi, wo kaam ki ahmiyat par depend karta hai.
17. One loop, four kinds of ask
Har request brainstorm nahi hoti, aur sab se aam ghalti ye hai ke sahi loop ghalat grip (pakad, yani limits kitni kasi hain) ke saath chalate hain.
Iska matlab: loop wohi hai, bas kahan kasna hai aur kahan dhila rakhna hai ye kaam ki qism se tay hota hai.
18. Marketer ka example
Marketer ne launch campaign ke liye model brief likha: channels, exact tagline, 3-part structure, tone, 40 words cap, aur 5 ideas maange. AI ne ek hi idea ke 5 rewordings (ek hi baat 5 tareeqe se) diye. 20 maange to 20 padosi ideas aaye.
Kuch toota nahi, bas us ke limits ne structure, tagline, tone aur length sab pin kar diye, sirf chhota sa kona bacha.
Iska matlab: brainstorming mein bohat zyada limits lagao to AI naye ideas ki jagah ek hi idea ke versions deta hai.
19. Fix: zyada lafz nahi, limits kam
1. **Options maangte waqt** sirf zaroori limits dein (product kya hai, kis ke liye hai, kya nahi chahiye), baaqi sab khula chhor dein, taake AI 5 sach mein alag ideas de.
2. **Ek idea chun lene ke baad** uski poori detail dein (tone, length, structure) taake wo bilkul waisa bane jaisa chahiye.
3. **Example:** Pehle "chai ke ad ke 5 alag ideas do, audience students hain" likhein. Ek chun kar phir likhein "ye idea 40 words mein, funny tone mein likho".
20. 4 kinds of ask (grip kahan kasein, kahan dhila rakhein)
Brainstorming: k wqt sub kuch phly btadena say AI avchy idea ni day payega
“chai ke ad ke 5 alag ideas do, audience students hain, mazaak nahi” sahi hai. “Funny tone mein, 40 words, 3 parts mein” pehle hi likhna ghalat hai.
Research (zameen ka naqsha chahiye): kasein scope, sources, kya evidence maana jayega; dhila rakhein jawab (aap kya paane ki ummeed rakhti hain wo mat batayein). Ulta karne par: aap ke andazon ka naqsha, zameen ka nahi.
Drafting (ek cheez bani hui chahiye): sab kuch kasein(btayen) (voice, length, structure, facts, format). Ulta karne par: ghalat cheez ka fluent (saaf-suthra) draft.
Analysis (data asal mein kya kehta hai): kasein data, definitions, exact sawal; dhila rakhein conclusion (kabhi mat bataiye). Ulta karne par: aisa analysis jo sawal poochne wale ki khushamad kare.
Example (analysis): “50 complaints dekh kar batao sab se zyada wajah kya hai” sahi hai, “mujhe lagta hai delivery ki wajah hai, confirm karo” ghalat hai. Iska matlab: conclusion pehle likh dein to AI wohi sabit karta hai jo aap ne kaha.
21. Concept 4 se takrao nahi
Apni situation ka context (budget, audience, bad knee) hamesha poora dein.
Jawab ki shakal par ye rule hai:
Options maangte waqt khula chhorein (structure, tone, length mat batayein).
Ek option chun kar usay banwate waqt tay karein (tone, length, structure sab batayein).
22. 4 kinds chain banate hain
jawab kharab ho to pehle dekho ke aap ne kaam ki kaunsi qism par kaunsi grip lagayi.
23. School students ke liye “Magic Loop”
4 steps: Load (AI ko sab batao), Options (kai ideas maango), Feedback (kya pasand, kya nahi), Repeat (sahi hone tak).
Ek secret Step 0 bhi hai: pehle research.
Iska matlab: wohi loop, school ke bachon ke liye chhote naamon mein.
/////////////////////////////////////////////2. Image input
**Acha (strong):** Poora scene, bade alag shapes, whiteboard aur diagrams, aur haath ki likhai (high stakes mein dobara check). Receipts aur notes type karwane mein bhi acha hai, lekin totals check karein.
**Fail (weak):** Bareek detail (jaise gym machines pehchanna), bhari tasveer mein chhoti cheezein ginna, aur kinare ka chhota print parhna.
Heading 3 (Image output) ka khulasa:
Image banwane ke liye prompt khud likhne ke bajaye text AI se likhwayen, taake woh zyada ameer (rich) hota hai. Saath hi style ke alfaaz (cinematic, watercolor, anime waghera) seekh lein, kyunke yeh image model ko seedha control karte hain.
4. Diffusion model (image banane wala tareeqa)
Diffusion model wo AI hai jo image banata hai.
Wo pehle ek noise se shuru karta hai. Noise matlab random dots ka grid, jisme koi tasveer nahi hoti (jaise purani TV par dhundli dots).
Phir wo qadam ba qadam noise saaf karta jata hai, aur aakhir mein tasveer nikal aati hai.
Text ki tarah ek ek lafz nahi likhta. Poori image ek saath aati hai. Is liye beech mein rok kar waqt nahi bacha sakte.
Purane models ki ghaltiyan: haath mein 6 ungliyan, signs par ulta seedha text, comic mein character badal jana.
Naye models (Nano Banana, ChatGPT Images) text theek likhte hain aur character ek jaisa rakhte hain.

Is heading mein bataya gaya hai: Image AI kaise banata hai (noise saaf kar ke), aur naye models purani ghaltiyan kaafi had tak theek kar chuke hain.
5. Ab bhi hone wali ghaltiyan aur unka hal
Text ghalat likha aaye (jaise “HAPRY BIRTDAY”): text quotes mein likhein, aur 3 versions bana kar sahi wala chunein.
Character badal jaye (panel 1 mein kaale baal, panel 2 mein bhoore): aisa model use karein jo character ek jaisa rakhe. Pehli image agle ke liye reference ke taur par dein.
Haath ki ghalti (6 ungliyan): haath aadhe frame se bahar rakhein, jeb mein rakhein, ya saaf likh kar describe karein.
Background mein ajeeb cheezein (cycle kursi mein mil jaye): simple background maangein ya khud describe karein.
Ghalat shape (aap ko lambi image chahiye, aaya square): aspect ratio likhein. Aspect ratio matlab image ki chaudai aur lambai ka nisbat, jaise “16:9”.
Is heading mein bataya gaya hai: Naye models mein bhi 5 masle aa sakte hain, aur har masle ka seedha hal hai.
6. Diagram banane ki recipe (bina designer ke)
Maqsad: 10 se 15 minute mein acha diagram. 4 steps:
Step 1: Claude se kahein ke baat ko SVG mein banaye. SVG ek aisi tasveer hai jo text ki shakal mein likhi hoti hai. Result sahi hoga lekin saada (sirf dabbe aur arrows).
Step 2: SVG ko PNG (aam image file) mein badlein, bari size mein (1600 se 2400 pixels).
Step 3: PNG ko ChatGPT ya Gemini mein dein aur kahein: design khoobsurat karo, lekin sab labels aur arrows wahi rakho.
Step 4: Agar koi label ya arrow ghalat ho jaye to type kar ke theek karwayein. 3 se 4 baar mein kaam ban jata hai.
Yaad rakhne wali baat: pehle structure (Claude se), phir finish (ChatGPT ya Gemini se). Dono ka kaam ulta karne se natija kharab aata hai.
Example (cake): Ek baap ne beti ke liye cat wala cake chaha. Nano Banana se kai designs banwaye, beti ne ek chuna, baker ne wohi bana diya. Kharch takreeban $0.30.
Iska matlab: Designer na ho tab bhi AI se aisa naksha ban sakta hai jis par professional kaam kar sake.
Is heading mein bataya gaya hai: Diagram 2 tools se banta hai: pehle Claude structure banata hai, phir ChatGPT ya Gemini us ko khoobsurat banata hai.
7. Audio (awaaz) andar aur bahar
Bol kar prompt dena: bolne se zyada detail aati hai aur jawab behtar hota hai. Aise bolein jaise dost ko samjha rahe hon.
Meeting ki recording dena: recording ya uska transcript (likha hua text) dein, aur kahein “decisions, baqi sawal, aur kis ka kya kaam hai bata do”. Document ke mutabiq ye bohat qeemti aadat hai.
Chalte phirte use: safar ya walk ke dauran awaaz se baat kar sakte hain. Lekin bola hua edit nahi hota, is liye typing se thora rough hota hai.

Audio mein kya acha aur kya kamzor:
Saaf awaaz type karna: bohat acha. (Mushkil: bhari accent, technical lafz, ya kai log ek saath bol rahe hon.)
Kaun kya bola: 2 log hon to theek, 4 ya zyada hon to kamzor. Kisi ko quote karne se pehle check karein.
Tone, mazaq, jazbaat: behtar ho raha hai, par bharosa nahi. AI se kahein jahan shak ho wahan flag kare.
Music: general AI kamzor hai, alag tool use karein.
Live baat-cheet: casual baat ke liye acha, gehri technical baat mein text par jayein.
Example (doctor): Doctor ne mareez ki razamandi se 45 minute ki baat record ki. AI se kaha: clinical note banao, jo samajh na aaye flag karo. 8 minute mein draft mila, check mein 5 minute lage. Typing mein 25 minute lagte.
Iska matlab: AI ne doctor ka faisla nahi kiya, sirf typing ka kaam kiya.
Is heading mein bataya gaya hai: AI ko awaaz de kar ya awaaz se jawab le kar kaam jaldi hota hai, lekin kaun bola aur tone par bharosa nahi karna.
8. Aage kya hoga
Ab ek hi prompt mein text, image, audio aur files sab mila kar de sakte hain (jaise image + voice memo + PDF + screenshot).
Asal skill yeh hai: is kaam ke liye kaunse inputs sahi hain, ye chunna.
Video avatars (AI se bani bolti hui shakal):
Pehle se record shuda (HeyGen, Synthesia, D-ID): kai zabanon mein training ke liye pehle hi acha.
Live wale (Tavus waghera): kam khatre ke kaam, jaise customer ke aam sawaal (FAQ) chhantna.
Abhi roz ki aadat nahi. Jab kaam ko text ke bajaye chehra chahiye ho to ek baar try karein.
Is heading mein bataya gaya hai: Aane wale waqt mein alag alag inputs mix hon ge, aur video avatars abhi sirf experiment ke liye hain.
Concept 9: Building small apps with one prompt
(Part 3: Beyond text)
Exam mein scenario aaye ke “ek chhota tool chahiye, kaun sa tareeqa sahi hai”, to is concept se aap hadd (limit) pehchan sakengi.
1. Pehle baat: kya ban sakta hai
AI ek prompt se chhote games, websites aur tools bana sakta hai.
Bade software nahi, lekin chhoti kaam ki cheezein ab un logon ke bhi haath mein hain jinhon ne kabhi code nahi likha.
Is heading mein bataya gaya hai: Ek prompt se chhoti app ban sakti hai, bade software nahi.
2. App kahan chalti hai (Artifact)
Teeno bade tools (Claude, ChatGPT, Gemini) chhoti app chat ke andar hi, side panel mein dikha dete hain, aap us par click kar ke use kar sakte hain.
Side panel mein sirf preview nahi hota. Wo ek artifact hota hai. Artifact (chat se bana hua asli chalne wala object): aap isay edit kar sakte hain, link se share kar sakte hain, embed kar sakte hain, ya code download kar sakte hain.
Claude is feature ko Artifacts kehta hai. ChatGPT aur Gemini isay Canvas kehte hain.
Do faide:
Artifact kisi ko dene ke liye poori chat bhejna zaroori nahi. Zyada tar tools isay public link par daal dete hain jise kholne ke liye account nahi chahiye.
Artifact wahin update hota hai. Aap kahein “button bara karo”, to tool jo bana hai usi ko edit karta hai, naya dobara nahi banata.
Is se aage 3 qareebi qisme hain:
AI app-builders (v0, Bolt, Lovable): saada zaban mein bayan se poora web project bana dete hain.
Command-line coding agents (Claude Code, OpenCode): asal codebase lete hain, kai files edit karte hain, tests chalate hain.
File-aware desktop apps (Cowork, OpenWork): aap ki apni files par permission ke saath kaam karte hain. Inka zikar Concept 11 mein hai.
Is heading mein bataya gaya hai: Chhoti app chat ke side panel mein artifact ban kar chalti hai jo edit, share aur update ho sakta hai. Bade kaam ke liye alag tools hain.
3. Recipe: 3 slots
Prompt mein 3 cheezein likhein:
Goal: yeh cheez kya kare?
Input: user kya dega?
Output: user ko kya dikhega?
Is heading mein bataya gaya hai: App ka prompt in 3 sawalon ka jawab hona chahiye: kya kare, kya mile, kya dikhe.
4. Misalein jo aaj chal rahi hain
Pomodoro timer: peela theme, 25 minute kaam ke session, 5 minute break, har cycle ke end par click ki awaaz.
Bill splitter: total bill, tax aur doston ke naam dein. App tax samet bill baant kar har ka hissa dikhaye.
Outfit picker: aaj ka mausam (temperature aur barish) aur closet ki cheezein dein. App libaas suggest kare.
Fireworks simulator: screen par click karein, wahan rang birange fireworks dikhein.
Place-obstacles game: user rukawatein aur goal rakhe, phir simulation chale jo goal tak pahunchne ki koshish kare.
Is heading mein bataya gaya hai: Yeh 5 chhoti, ek screen par aane wali apps hain jo aaj ek prompt se ban jati hain.
5. Abhi bhi mushkil kya hai
Internet par multiplayer: networking, accounts aur players ko milana, ek prompt se bahar hai.
Doosri zaban mein live coaching: jaise French tutor jo sune, pronunciation theek kare aur bolte waqt khud ko adapt kare. Yeh abhi bhi mushkil hai.
Yaad rakhne wali line: jo cheez ek screen par aaye, jis mein accounts na hon aur bahar ki services na hon, wo chalti hai. Is se aage ek prompt kaafi nahi, aur aksar asal engineering chahiye hoti hai.
Is heading mein bataya gaya hai: Ek screen wali, bina accounts aur bahari services wali app banti hai. Multiplayer ya live tutor jaise bade kaam ke liye engineering chahiye.
6. Document ka example: typing game
Ek baap software engineer nahi tha. Usne apni beti (7 saal) ke liye peela, billi wala typing game banwaya, kyunke teacher ne kaha tha ke bachche tez type kar sakte hain. Prompt sirf 3 jumlon ka tha:
Goal: 7 saal ke bachche ke liye chhote aam lafz type karne ki practice.
Input: lafz screen par aate hain, khiladi unhein neeche pahunchne se pehle type kare.
Output: peela theme, ek pyari billi jo sahi lafz par khush ho, aur levels ke saath badhti raftaar.
Natija: perfect nahi aur pehli koshish mein nahi, lekin ek ghante ke andar “bachche ke liye kaafi acha” ban gaya.
Iska matlab: Asal skill coding nahi, saaf brief likhna aur rounds mein behtar karna hai.
//////////////////////////////////Concept 10: Data analysis (model code likhta aur chalata hai)
(Part 3: Beyond text)
Exam mein scenario aaye ke “AI ne numbers bataye, kya un par bharosa karein”, to is concept se aap pehchan sakengi ke jawab asli calculation se aaya ya sirf andaze se.
1. Code execution kya hai
Is heading mein bataya gaya hai: AI numbers ke sawal par apna program likh kar chalata hai, is liye hisaab dimaagi andaze se behtar hota hai.
2. Pehle yaqeen karein ke code sach mein chala
Yeh is poore section ki khamosh ghalti hai: model har sawal par code nahi chalata. Woh khud faisla karta hai, aap ke sawal ke andaaz par.
Chhote sawalon par woh kabhi kabhi code chhod kar sirf ek nazar dekh kar jawab de deta hai. Jawab confident hota hai lekin peeche koi hisaab nahi. Bahar se yeh asli analysis jaisa hi lagta hai.
3 aadatein:
Seedha kahein: “Write and run code to answer this. Show me the code you ran.” Yeh ek line asal analysis aur sirf acha lagne wale andaze mein farq daal deti hai.
Check karein ke code maujood hai: agar jawab mein koi code block nahi, to model ne shayad koi code nahi chalaya.
Pehle ek jaanchne wali baat poochein: “Analysis se pehle mujhe file ki exact rows ki ginti, columns ke naam aur date range batao.” Agar model asal mein file parh raha hai to yeh jawab sahi honge. Agar andaza laga raha hai to rows ki ginti ajeeb tarah ka gol number hogi aur column ke naam sahi lagte hue bhi ghalat honge.
Sab se mazboot tareeqa: model se tareeqa ka elaan karwayein: “Are you running code on the file, or estimating? If estimating, stop and run code instead.”
Is heading mein bataya gaya hai: Model kabhi kabhi code chalaye bina andaza laga deta hai, is liye code maangein, code dekhein, aur pehle file ke asal tathya (rows, columns, dates) puchein.
3. Document ka example: Bubble tea shop
Ek chhoti dukaan ke paas saal bhar ki sales ka data hai (drinks, tareekhein, miqdar). Malik ne poocha: “Which drinks had the biggest changes in sales over the year? Graph them. Write and run code to answer this and show me the code you ran.”|
Iska matlab: Jawab asli data par bana (code ke saath), is liye us par bharosa kiya ja sakta hai, aur AI ne sirf numbers nahi diye balke aage ka mashwara bhi diya.
4. Yeh kin kaamon ke liye acha hai
Ghar ka kharch: saal bhar ke bank ya card transactions dein. Poochein ke kaun si category barhi, kaun se mahine ajeeb the, aur kaun si bhooli hui subscriptions hain.
Zaati tracking: daud, chalna, neend, wazan, screen time. Jo bhi app CSV (rows aur columns wali saadi spreadsheet file) export kar sake, us se aap ko apne saal bhar ka data mil jata hai.
Chhote karobar ke records: sales, inventory, customer list, kharch ki files.
Jo bhi spreadsheet aap ko kisi ne bheji aur aap kholna nahi chahte: school ki grade reports, utility statements, science data, survey results.
Is heading mein bataya gaya hai: Har wo kaam jahan aap ke paas numbers ki file ho aur sawal poochna ho.
Maan lein aap ke paas 2 files hain:
File A: Poore saal ki sales (January se December).
File B: Sirf October se December ki sales.
File B ka data File A ke andar pehle se maujood hai. Agar dono AI ko denge aur kuch nahi likhenge, to AI sochega ke yeh do alag alag data hain, aur October se December ki sales do baar jama kar dega. Total ghalat aayega.
Hal: AI ko ek line likh kar bata dein:
“File A poore saal ka data hai. File B sirf uska hissa hai, isay totals mein mat ginna.”
Iska matlab: Jo cheez doosri file mein dohrayi gayi ho, uska label laga dein, taake AI usay do baar na gine.
6. Code chalne ke baad bhi kya dobara dekhna hai
Pehli baat: Haan, AI bhi ghalti kar sakta hai. Isi liye is point mein likha hai ke check karna zaroori hai, aur check insaan (aap) karti hain.
“Junior analyst” ka matlab: Jaise ek tez naya employee jo zyada tar kaam sahi karta hai, lekin kabhi kabhi ghalti bhi karta hai. Is liye boss (aap) uska kaam dekhti hain.
Check kyun zaroori hai: AI ka andaze wala jawab bilkul waisa hi lagta hai jaisa asli hisaab ka jawab. Dekhne se farq nahi pata chalta.
“Ghalti data ke baare mein sikhati hai” ka matlab: Kabhi AI ki ghalti AI ki apni wajah se nahi hoti, balke aap ke data mein masla hota hai, jaise column ka naam saaf nahi, ya data double hai. Jab aap ghalti pakadti hain, to aap ko apne data ka woh masla pata chal jata hai.
*****Data analysis say rlted ak exammple
Ek runner ne apne 6 mahine ke daud ke record ki file AI ko di. AI ne code chala kar woh patterns dhoondhe jo runner ko khud nazar nahi aaye the.
Example:
Runner ne poocha: “Meri raftaar aur faasla kaise badh rahe hain? Koi pattern hai?”
AI ne 2 baatein dhoondhin: lambi daud ke baad raftaar gir jati hai, aur teesre mahine mein faasla badhna ruk gaya.
Mashwara: har chauthe hafte aaram karein, aur lambi daud dheemi raftaar se karein.
Iska matlab: Roz ke numbers dekhne se pattern nahi dikhta, lekin AI poora data ek saath dekh kar chhupi hui baatein bata deta hai.
8. Ek kaam ka pattern: pehle chart ka plan maangein
Data upload karne ke baad pehla prompt sawal hi hona zaroori nahi. Yeh bhi ho sakta hai: “Describe this dataset. What columns are here, what do they represent, and what 3 charts would best show what is going on?”
Jawab parhein, jo chart chahiye wo chunein, phir wo maangein.
Is se ghalat samjha hua column ghalat analysis banne se pehle pakda jata hai.
Is heading mein bataya gaya hai: Pehle AI se data ki tashreeh aur 3 chart ke plan maangein, taake ghalat column pehle hi pakda jaye.
## Concept 11 (chhota version)
**1. AI desktop app kya hai**
- Aap ke computer par chalti hai, aur **aap ki ijazat se** files dhoondh, parh aur un par kaam kar sakti hai (Cowork, OpenWork).
**2. Mehfooz workflow (4 steps)**
- Kaam batayein, **plan maangein (kaam nahi)**, plan parh kar badlein, phir manzoori dein.
**3. Do khatre (exam mein zaroor)**
- Delete ki hui files aksar **recycle bin mein nahi jati**, ghaib ho jati hain.
- Edit ka purana version nahi bachta, jab tak **version control** (har purana version mehfooz rakhne wala software) na ho.
**4. Permission ka usool**
- **Sab se chhoti permission** dein (sirf zaroori folder). "Full disk access" nahi.
- Permission **track record** se badhti hai, company par bharosa se nahi.
**5. Permission ladder (chhoti se bari)**
- AI ko ijazat chhote se bade ki taraf deni chahiye: pehle sirf ek chhota folder parhna, phir ek folder mein parhna aur likhna, phir poora project parhna magar likhna sirf ek chhote subfolder mein, aur aakhir mein kaam ke mutabiq mukhtalif permissions.
- "Jo chahiye karo" jaisi khuli ijazat se **hamesha inkar.**
**6. Example:** Consultant ne 240 PDFs ke folder par kaha "scheme batao, **abhi kuch mat hilao**". Plan dekha, theek kiya, phir manzoori di.
**Iska matlab:** Pehle plan, phir aap ki manzoori.
**Exam scenario ka jawab ek line mein:** Naya AI app ho to **read-only, chhote folder, plan pehle, manzoori baad mein.**
Concept 12 (chhota version): Cost, speed, aur kaun sa model kab
1. Cost aur speed
Text sab se sasta aur tez hai, video sab se mehnga aur dheema (takreeban 16 guna). Images aur deep research beech mein hain.
Entry level par free versions kaafi hain (ChatGPT, Claude, Gemini, Meta AI, DeepSeek). Paid plan tab chahiye jab bhari deep research, bohat bari uploads, video, ya roz unlimited istemal ho.
Image aur video ke round mehnge hain, is liye prompt pehle se detail mein likhein (text AI se likhwayen).
2. Kaun sa model
AI jagged (kahin tez, kahin kamzor) hai: koi ek best model nahi, aur leader har kuch mahine mein badalta hai.
2 aadatein: wohi prompt 2 se 3 models mein chalayein, aur ek tool se shaadi na karein.
Arena (public leaderboard jahan log vote karte hain). Mahine mein ek baar dekhein, lekin ek leaderboard par poora bharosa na karein.
3. Models ki taqat
Claude: mushkil sochna, lambe documents, diagrams, code. ChatGPT: image generation, voice. Gemini: tez search, deep research, Google Workspace. Meta AI: WhatsApp aur Instagram ke andar, free, lekin inputs Meta ke training mein jaa sakte hain, is liye private cheezon ke liye na-munasib. DeepSeek: sasta, weights public.
4. Model ladder (ek brand ki seerhiyan: tez sasta, reasoning, flagship)
Asaan kaam ke liye sasta, mushkil kaam ke liye bhari. Ghalat chunao dono taraf mehnga.
5. Teen aadatein
Do tabs rakhein, prompt notebook banayein, model ki ghaltiyan note karein.
Exam jawab ek line mein: Ek model par bharosa na karein. Wohi prompt 2 se 3 models mein chalayein, aur kaam ke hisaab se sasta ya bhari model chunein.
Sahi tarteeb (aasaan example: ek client ko lambi email):
Draft: Model A (jaise Claude) email likhta hai.
Grading: Model A usay khud 1 se 10 par grade karta hai (clarity, accuracy, structure, kya missing hai). Jaise 7.
Sudhaar: Model A apni hi suggestions par amal kar ke email behtar banata hai. Tab tak dohrao jab tak grade barhna band na ho (aksar 9).
Alag family se grading: Wohi email aur wohi rubric Model B (jaise ChatGPT ya Gemini) ko dein. Wo 7.5 de sakta hai aur kuch masle bata sakta hai jo A ne nahi dekhe.
Options chunna: B ki critique A ko wapas dein: “kaun se points apnane laiq hain, kaun se radd karo, aur wajah batao.” A chunta hai.
Ruknay ki shart: Jab do alag models ka score target se upar ho.
3. Single-model loop

Sirf grade aur amal wala hissa bhi kaam karta hai. Concept 6 se takraav nahi, kyunke rubric (naam liye hue criteria) khushamad ko tool bana deta hai.

4. 3 levels

Rubric critique (fori) → self-critique loop (drafts) → multi-model (bohat ahem kaam).

5. Privacy

Draft kai tools mein paste hota hai, to har tool ki data policy parhein. NDA wale kaam ke liye sirf checked tools.

6. Honest caveat

Teen models bhi ek hi cheez par ghalat ho sakte hain. Score tarraqqi ka ishara hai, sachchai ka nahi. Qanooni, tibbi, maali kaam mein insani maahir zaroori.

7. Kab skip karein

Chhoti email ya aam lookup mein. Loop sirf wahan jahan ghalti mehngi ho.

8. Example: Consultant ke 40 page memo ko doosri family ne 7.5 diya aur 11 masle dhoondhe, jin mein se 3 pehle model ne kabhi nahi uthaye the. Pehle model ne 7 apnaye, 4 radd kiye.
Iska matlab: Alag family ka model wo ghaltiyan pakadta hai jo apna model nahi pakadta.

































