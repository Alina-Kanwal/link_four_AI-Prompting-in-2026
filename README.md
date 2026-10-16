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
