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















