<!-- tabs:start -->

####  **Sentence segmentation**
Since we cannot rely on punctuation in Tibetan, we have to create clear protocols for
sentence segmentation. We follow these basic principles:

1. Sentences must have a matrix verb (unless they are copular clauses with dropped
copulas);
2. When in doubt, go for shorter sentences as they are easier to work with in a corpus
45and in any downstream NLP tasks;
3. Sentence boundaries do not necessarily reflect linguistic reality but should be
consistently annotated;
4. Direct speech is regarded as a separate sentence in the corpus.

#### **ཚིག་གྲུབ་བཅད་གཏུབ་**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། ནང་གསེས་ཀྱི་ལྟ་གྲུབ་མི་འདྲ་བའི་ཐོག་དྲི་བ་དྲིས་ལན་བྱེད་པ་ལྟ་བུ་ནང་པ་རང་གི་ནང་དུའང་གྲུབ་མཐའ་སྨྲ་བ་བཞི་ཞེས་མི་འདྲ་བ་ཡོང་གི་ཡོད། </br> དེང་སང་དུས་རབས་ཉེར་གཅིག་པར་འཕྲུལ་ཆས་སོགས་དངོས་པོ་ཧ་ཅང་ཡར་རྒྱས་ལ་ཕྱིན་ཡོད་ཀྱང་། མིའི་སེམས་ཀྱི་ཞི་བདེ་འཕྲུལ་ཆས་ཀྱི་ཐོག་ནས་བཟོ་ཐུབ་རྒྱུ་ཧ་ཅང་ཁག་པོ་རེད། </br> ང་ཚོ་མིའི་ཀླད་པ་ཆ་ཚང་བཀོག་ནས་འཕྲུལ་ཆས་ལ་བསྒར་ནའང་བསམ་བློ་གཏོང་བའི་ནུས་པ་མེད་པས་འཕྲུལ་ཆས་ཀྱིས་བྱང་ཆུབ་ཀྱི་སེམས་དང་སྟོང་ཉིད་ཀྱི་ལྟ་བ་བསྒོམ་མི་ཐུབ།  

<!-- tabs:end -->


### Protocols for < utt >

<!-- tabs:start -->

#### **Protocols for < utt >**
We summarise our detailed protocols for adding utterance boundaries "< utt >" in the
following table, which tells when to insert a sentence boundary, marked by < utt > and when
to make sure there is NO sentence boundary. Annotators should be aware that these
protocols have been automated and implemented in the POS-tagging script only partially, so
along with the word segmentation and POS tags, these utterance boundaries should be
double-checked and corrected manually. Examples of each scenar with and without
utterance boundaries are added and explained in sections 4.2 and 4.3.



| Insert < utt > to create sentence boundary:                                                      | Delete/double-check NO < utt >: |
| ---------------------------------------------                                                    | ------------------------------- |
| After cv.fin or case.fin (+ punc/line.number/page.number)                                        | After cv.ela   |
| After cv.ass (+ punc/line.number/page.number) OR case.ass if following an n.v.*                  | After cv.all   |
| After v.* (+ line.number/page.number) + punc                                                     | After cv.abl    |
| Before AND after direct speech including after case.nare and after cv.ques or case.ques          | After cv.loc if conditional   | 
| After cv.ipv (+ punc/line.number/page.number) (marking imperatives) case.ipv if it's after a n.v.*   | After relative clauses    |
| Before "resumptive" དེ (not དེ་ན )                                                                   | After cv.odd   |
| If n.v.* is the matrix verb, <utt> can follow (but this is very rare in Old Tibetan and still quite rare in CTib)                                                                                              | After cv.agn   |
| After cv.sem or case.sem                                                                         | After cv.are  |
| After cv.loc in cases after བསམས་ where བསམས་ན is introducing direct speech/thought 'in thinking'                                                                                           |    |

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། ནང་གསེས་ཀྱི་ལྟ་གྲུབ་མི་འདྲ་བའི་ཐོག་དྲི་བ་དྲིས་ལན་བྱེད་པ་ལྟ་བུ་ནང་པ་རང་གི་ནང་དུའང་གྲུབ་མཐའ་སྨྲ་བ་བཞི་ཞེས་མི་འདྲ་བ་ཡོང་གི་ཡོད། </br> དེང་སང་དུས་རབས་ཉེར་གཅིག་པར་འཕྲུལ་ཆས་སོགས་དངོས་པོ་ཧ་ཅང་ཡར་རྒྱས་ལ་ཕྱིན་ཡོད་ཀྱང་། མིའི་སེམས་ཀྱི་ཞི་བདེ་འཕྲུལ་ཆས་ཀྱི་ཐོག་ནས་བཟོ་ཐུབ་རྒྱུ་ཧ་ཅང་ཁག་པོ་རེད། </br> ང་ཚོ་མིའི་ཀླད་པ་ཆ་ཚང་བཀོག་ནས་འཕྲུལ་ཆས་ལ་བསྒར་ནའང་བསམ་བློ་གཏོང་བའི་ནུས་པ་མེད་པས་འཕྲུལ་ཆས་ཀྱིས་བྱང་ཆུབ་ཀྱི་སེམས་དང་སྟོང་ཉིད་ཀྱི་ལྟ་བ་བསྒོམ་མི་ཐུབ།  

<!-- tabs:end -->

###  Insert sentence boundaries
<!-- tabs:start -->
#### **Insert sentence boundaries**
We segment sentences in the cases outlined below. If there is a ། shad or any other form of
punctuation, the sentence boundary marked by "< utt >" follows the punctuation marker(s).
Note that these punctuation markers are often, but not always there. Even if they are not there, we follow the sentence segmentation protocols outlined in this section for consistency.

After cv.fin or case.fin</br>
Sentence-final particles are the clearest markers of utterance boundaries in Tibetan.
Whenever we find such markers, whether they're tagged as cv.fin or case.fin, we add an
utterance boundary, as shown in (1) and (2). Most of the time these sentence-final particles
will be followed by a single or double shad, in which case the < utt> marker follows that.

(1)མཚོན་ གྱི་ ཆར་པ་ ཕབ་ ནས ། མི་ དང་ སྤྲེ་ འུ་ དམག་ ཀྱང་ ཕལ་ཆེ ར་ བཀུམ་ མོ ། < utt>
(Ramayana)

(2)</br>
ཡང་ adv.proclausal</br>
ན་ case.loc</br>
ནི་ cl.top</br>
མི་ n.count</br>
འདི d.dem</br>
འི་ case.gen</br>
ཆུང་མ་ n.count</br>
མངའ་བྱད་ n.count</br>
ཤིན་ adv.intense</br>
ཏུ་ cv.term</br>
མཛེས་ v.invar</br>
ཤིང་ cv.impf</br>
བཟང་མོ་ n.count</br>
ཞིག་ d.indef</br>
གོ case.fin</br>
། punc</br>
< utt>

After cv.ass</br>

When the associative marker follows verbs and is thus tagged as cv.ass, this usually
indicates two main clauses are coordinated. Since དང་/cv.ass is used a lot it would be
impractical for parsing and other downstream NLP tasks to consider these two (or often
more) main clauses as one sentence in the corpus. Therefore, we consistently add an
utterance boundary after དང་/cv.ass as shown in (3) and (4):


(3) མཆེད་གཉིས་སྔར་གཤེགས་ཤིག་དང་ ། < utt > བདག་དོན་ཞིག་གཉེར་ཏེ། སླད་བཞིན་པར་མཆིའོ།     (MB D 139v2, Bialek 2022 p.146)
 
(4) ལོ་གསུམ་ལོན་པ་དང་ ། < utt > སྤྲེའུ་བྱ ང་ཆུབ་སེམས་དཔའ་བལྟར་ཕྱིན་པས། (GLR 23r4. Bialek 2022 p.149)

After v.*</br>

Since Tibetan is a head-final language, finite verbs appear at the end of main clauses. If
there are no sentence-final or similar particles to indicate the end of a sentence, the verb
itself is a clear sign that this is the end of a main clause. We therefore insert utterance
boundaries after verbs (tagged v.pres, v.past, etc.).

(5) བདག་ ལ་ བྱམས་པ་ ཁྱོད་ ལས་ གཞན་ མི་ བཞུགས ། < utt > (Ramayana)

Before AND after direct speech</br>
Direct and indirect speech are notoriously difficult in Tibetan. Often, the beginning and or
end of direct speech is marked with a verb ('he said, he asked'), a shortened derivative
thereof or a quotative particle. To facilitate future research on (in)direct speech, we create
separate sentences for both the clause in (in)direct speech and the verb or particle that
indicates the (in)direct speech. Note that this will superficially lead to more sentences in the
corpus, but since there are separate syntactic labels for each of these clauses (see parsing
manual), this should not create any issues when retrieving statistics based on number of
sentences in the corpus, as they easily be included or filtered out as necessary.

Sometimes, (in)direct speech can contain more than one main clause. In those cases each
mean clause in the (in)direct speech will be segmented as a separate sentence following the
usual protocols.

Note that this means that the quotative particle should NOT be included in the last main
clause of direct speech, as shown in the examples below. Note that the direct speech itself is
in red. In examples (6), (7) and (8) we show only the beginning and the end of the direct
speech.


Before direct speech:</br>
(6) ལྷ་མོ ས་ སྨྲས་པ ། < utt> ཀྱི་ གུད་ བུད་མེད་ དགི ས་ སྨྲས་པ་ ལ་ ལེགས་པ ར་ གྱུར་པ་ ག་ ལ་
ཡོད ༎་ < utt> (Ramayana)

After direct speech:</br>
(7) དཔལ་ བརྗོད་ འཕྲུལ་ གྱི་ བསྟེན་ གྲོགས་ ལྷ་མོ་ འདི ། ཁྱོད་ ལ་ འཚམ་ < utt> ཞེས ༎་ < utt>
(Ramayana)

(8) དབེན་བ་ འི་ གནས་ ན ། ལྷ་ འི་ དྲང་སྲོང་ མཛད་པ་ ལ་ ཇི་ ཡང་ མི་ དགོས་ མོད་ ཀྱི ༎་
སེམས་ཅན་ བསོད་ནམས་ ཐོབ་པ ར་ བྱ་བ་ འི་ ཕྱི ར ༎་ སྦྱིན་བ ར་ སྟོབས་པ་ འི་ ནོར་ བླང་ ངོ་
< utt> ཞེས་ བྱས་ སོ ༎་ < utt> (Ramayana)


After case.nare</br>
Direct speech can also be indicated in other ways, for example with the particle ན་
རེ་ /case.nare. To be consistent with the above rules concerning direct speech, we also insert
utterance boundaries after ན་རེ་ /case.nare, as shown in (9). Note again that the direct speech
might end without the quotative particle ཞེས as in this example - here we only have སྨྲས་སོ་
“said”):


(9) ལྷ་ འི་ བུ་ རྣམས་ ན་རེ ། <utt> ངེད་ མ་ཧ་དེ་བ འི་ དངོས་གྲུབ་ འདོད་པ ར་ ཟད་ ཀྱི ། ངན་པ་
བུད་ ཀྱི་ ངན་པ་ བུད་ ཀྱི་ དངོས་གྲུབ་ མི་ འདོད་ ཆེས་ <utt> སྨྲས་ སོ ༎་ <utt> (Ramayana)


After cv.ques and case.ques</br>
In line with our other protocols regarding direct speech, we also insert utterance boundaries
after question particles tagged as cv.ques, shown in (10) or case.ques (not following a verb),
shown
in
(11).


(10) ལྷའི་
དྲང་སྲོང་
ལ་
གསོལ་པ
༎་
<utt>
བརྩེ ར་ དགོངས ། གུས་པ ས་ འབུལ་བ་ བཞེས་ ལགས་ སམ་ <utt>
ཞེས་ བྱས་པ་ དང ༎་ <utt>
(Ramayana)


(11)</br>
བདག་ p.pers</br>
དེ་ d.dem</br>
ལ་ case.all</br>
ཅུང་ཟད་ adv.intense</br>
ཙམ་ d.tsam</br>
མི་ neg</br>
དགའ་བ n.v.fut.n.v.pres</br>
འམ་ case.ques</br>
< utt></br>
འཁོན་ v.fut.v.pres</br>
དུ་ cv.term</br>
འཛིན་པ་ n.v.pres</br>
མེད་ v.invar.med</br>
དོ cv.fin</br>
། punc</br>
< utt>

After cv.ipv</br>
Again, in line with our protocols regarding (in)direct speech, utterance boundaries should
also be added after imperative converbs tagged cv.ipv.


(12) ལྷ་མོ་ ནང་ ན་ དཀོན་བ་ འདི་ བཞེས་ ཤིག་ < utt> ཆེས་ དང གསོལ་པ་ ༎་ < utt> (Ramayana)


Before "resumptive" དེ (not དེ་ན)</br>
Sometimes the demonstrative དེ་ is not used as a modifier but as something that resembles a
resumptive pronoun. These "resumptives" come at the start of a sentence, which is why we
insert an utterance boundary before དེ་ in those cases. An example is shown in (13):


(13) < utt> </br>
དེ་ ནས་བྲག་སྲིན་མོ་ལངས་ཏེ། < utt> (GLR 22r6, Bialek 2022 p.118)


If n.v.* is the matrix verb</br>
There are some cases of verbal nouns acting as main clause/matrix verbs. In those cases,
we treat them like any other matrix verb and insert an utterance boundary after n.v.* (plus
possible punctuation). These cases are very rare in Old Tibetan and still rare in Classical
Tibetan, especially in the earlier period.

After cv.sem</br>
Semi-final particles are often used to combine two (or more) clauses that could each be
considered matrix clauses. To be consistent and pragmatic (i.e. avoiding very long
sentences in annotated corpora), when two or more entire clauses are combined we always
insert an utterance boundary after a semi-final particle, as shown in (14).


(14) ལོང་སྤྱོད་ ཆེ་བ་ ལས ༎་ ལྷ་ རྣམས་ ཀྱིས་ ལྟོ་ བགྱིས་ ཏེ་ ། < utt> རྣམ་ཐོས་ ཀྱི་ སྲས་ ཀྱིས ༎་
འགྲེང་ གཅིག་ མེད་པ ར་ ཁ་ བཏག་ བཉལ་ བཅད་ དེ ༎་ < utt> མེད་པ ར་ བྱས་ ནས་ ཡུལ་
ཡང་ ལྷ་ དང་ མི ས་ བཀང་ ངོ་ ༎་ < utt> (Ramayana)

There are also cases where there is only one verb after cv.sem. These cases are case it's
more like a verbal complex or cases of multiple, concatenated verbs. In those cases, we do
not add an utterance boundary after cv.sem, as shown in (15):


(15) དྲུང་དུ་པྱིན་ཏེ་ བལྟས་ན།
"When ( ན་ -na) [Vālin's wife] drew near, taking another look,"
(Rama A 204-207)


After cv.impf or case.impf</br>
Imperfective converbs and case markers often behave in a similar way as semi-final
particles: even though they can technically indicate subordination, they can also combine
two (seemingly) matrix clauses, in which case sentences would get very long. For practical
purposes, we therefore treat them in the same way as semi-final particles in the annotated
corpus and thus add an utterance boundary after cv/case.impf as shown in (16) and (17):

(16)ལྷ་ མི་ གང་ གིས་ ཀྱང་ མི་ ཐུབ་པ་ ལས་ ༎་ སྲིན་པོ་ འི་ འཁོར་ མང་པོ ༎་ ཡུལ་ འདི་ ན་ འཕགས་པ ར་ སྐྱིད་ ཅིང་ < utt> ལོང་སྤྱོད་ ཆེ་བ་ ལས ༎་ ལྷ་ རྣམས་ ཀྱིས་ ལྟོ་ བགྱིས་ ཏེ་ ། < utt>

(17)</br>
ལྷ་མཚམས་མ n.prop</br>
འི་ case.gen</br>
བུ་ n.count</br>
སུམ་ num.card</br>
ཅུ་ num.card</br>
རྩ་ num.card</br>
གཉིས་པོ་ num.card</br>
དེ་ d.dem</br>
ནི་ cl.top</br>
གཞོན་ n.count</br>
ཞིང་ case.impf</br>
< utt></br>
དར་ v.invar</br>
ལ་ cv.all</br>
བབ་ v.fut.v.past</br>
སྟེ cv.sem</br>
། punc</br>
< utt>

After cv.loc</br>
Following our protocols for (in)direct speech, in cases after བསམས་ where བསམས་ན is introducing
direct speech/thought 'in thinking', we add an utterance boundary as well:


(18) ཚེམ་བུ་ ན་ འདུག་པ་ གཅིག་ ཕུད་ དུ་ བཞག་པ་ དེ་ སྐྱེས་ ནས ༎་ བསམས་ ན ༎་ < utt>
ཡུལ་མི་ ཁྱིམ་ཚེས་ ཀུན་ ལ ༎ ་ ཕ་མ་ དང་ གཉེན་འདུན་ དུ་ བཅས་པ་ ཤེ་ དག་ ན ༎་ < utt> ང་
འི་ ཕ་མ་ དང་ གཉེན་འདུན་ གོ་གར་ སོང་ < utt>

" He grew up and thought: 'All the neighbours without exception in the land have parents and relatives.
Where did my parents and relatives go?"
(Ramayana)


4.3 No sentence boundaries after:</br>
To be very clear about how to segment sentences, in this section we furthermore highlight
cases when NO sentence boundaries are added, i.e. when the utterance should NOT be
split/segmented into multiple utterances. Most of these cases contain subordinate clauses
that do not have matrix verb, but instead, contain a converb linking the subordinate verb to
the main clause.


After cv.agn</br>
The agentive converb is often used for causative clauses. Since this is clearly introducing a
subordinate clause, we do NOT add an utterance boundary after cv.agn.


(19)</br>
ང་ p.pers</br>
མི་ neg</br>
ཉན་ v.fut.v.pres</br>
གྱིས་ cv.agn</br>
ཁྱོད་ p.pers</br>
དང་ case.ass</br>
ཁྱོ་ཤུག་ n.count</br>
ཏུ་ case.term</br>
བྱ་ v.fut.byed</br>
དགོས་ v.invar.dgos</br>
སོ cv.fin</br>
། punc</br>
< utt>

After cv.ela</br>
The elative converb is often used for temporal subordinate clauses and can be translated
with "after…" or "since…". Since this is clearly introducing a subordinate clause, we do NOT
add an utterance boundary after cv.ela.

(20)</br>
ཡུམ་ n.count</br>
གྱིས་ case.agn</br>
ད་ adv.temp</br>
ང p.pers</br>
ས་ case.agn</br>
བླ་མ་ n.count</br>
ལ་ case.all</br>
ཞུས་ v.past</br>
ནས་ cv.ela</br>
ཆོས་ n.count</br>
ཡོང་ v.invar.yong</br>
རང་ p.refl</br>
ཡོང་བ n.v.invar.yong</br>
ར་ case.term</br>
བྱ v.fut.byed</br>
འོ cv.fin</br>
། punc</br>
< utt>

After cv.all</br>
The allative (also known as the dative) converb can introduce subordinate clauses with a
temporal meaning, e.g. "during…" or "after…". In those cases the allative marker functions
as a subordinate conjunction and we therefore do NOT insert an utterance boundary after it.

(21)</br>
རེས་ n.count</br>
ཤིག་ d.indef</br>
སྡོད་ v.ipv</br>
ལ་ cv.all</br>
ལས་ n.count</br>
བྱེད་པ་ n.v.pres.byed</br>
ལྟ n.rel</br>
ར་ case.term</br>
གྱིས་ v.ipv.bgyid</br>
ཤིག་ cv.ipv</br>
གསུང་ v.invar</br>
། punc</br>
< utt>

After cv.abl</br>
Just like the elative and allative, the ablative can be used as a 'converb' to introduce a
temporal subordinate clause.

(22)</br>
ཆོས་ n.count</br>
འདི་ d.dem</br>
རྒྱུ་ n.count</br>
དང་ case.ass</br>
བཅས་ v.invar</br>
ལས་ cv.abl</br>
བྱུང་ v.past.byung</br>
། punc</br>
< utt>

After cv.loc if conditional</br>
The locative marker ན་ introduces conditional clauses and can usually be translated as 'if'.
We do not insert utterance boundaries here, because these are subordinate clauses.

(23)</br>
སྙིང་ n.count</br>
བཏོན་ v.past</br>
ན་ cv.loc</br>
འཆི་བ་ n.v.fut.n.v.pres</br>
ལས་ case.abl</br>
འོས་ n.count</br>
མེད v.invar.med</br>
། punc</br>
< utt>

After relative clauses</br>
Relative clauses are usually introduced by verbal nouns followed by a genitive marker.
Relative clauses are subordinate clauses and therefore we do NOT add an utterance
boundary between the relative and the main clause.

(24)</br>
བླ་མ་ n.count</br>
ཅི་གསུང་ n.count</br>
སྒྲུབ་པ n.v.pres</br>
འི་ case.gen</br>
སྐྱེས་བུ་ n.count</br>
ངོ་མཚར་ adj</br>
ཆེ་ v.pres</br>
སྙམ v.invar</br>
། punc</br>
< utt>

After cv.odd</br>
We also do NOT add utterance boundaries after the cv.odd:

(25)</br>
(…)</br>
དང་ case.ass</br>
བྱི་བ n.count</br>
འི་ case.gen</br>
རོ་ n.count</br>
བྱུང་ v.past.byung</br>
ཚད་ cv.odd</br>
ཐུ་ v.invar</br>
ཞིང་ cv.impf</br>
ཡོངས་པ n.v.past</br>
ས case.agn</br>
། punc</br>
< utt>

After verbal complex with cv.sem</br>
Semi-final particles often conjoin two clauses that could be considered main clauses, in
which case we add utterance boundaries. However, sometimes there is only one verb after
cv.sem, in which case it's more like a verbal complex and there should not be any utterance
boundary.

(26)</br>
དྲུང་དུ་པྱིན་ཏེ ་བལྟས་ན། "When ( ན་ -na) [Vālin's wife] drew near, taking another look,</br>
(Rama A 204-207)

After cv.are</br>
We do not insert utterance boundaries after cv.are

(27)</br>
ཁྱོད་ p.pers</br>
སུ་ p.interrog</br>
ཞིག་ d.indef</br>
འདི་ d.dem</br>
ལ་ case.all</br>
མ་ neg</br>
རེག་ v.pres</br>
ཤིག་ cv.ipv</br>
ཁོ་མོ p.pers</br>
འི་ case.gen</br>
ཁྱོ་ n.count</br>
འོངས་ v.past.ong</br>
ནས་ cv.ela</br>
གནོད་པ n.v.invar</br>
ར་ case.term</br>
གྱུར་ v.past.gyur</br>
ཏ་རེ་ cv.are</br>
ཆུང་མ་ n.count</br>
ལ་ case.all</br>
སྨྲས་པ n.v.past</br>
། punc</br>
< utt>

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། ནང་གསེས་ཀྱི་ལྟ་གྲུབ་མི་འདྲ་བའི་ཐོག་དྲི་བ་དྲིས་ལན་བྱེད་པ་ལྟ་བུ་ནང་པ་རང་གི་ནང་དུའང་གྲུབ་མཐའ་སྨྲ་བ་བཞི་ཞེས་མི་འདྲ་བ་ཡོང་གི་ཡོད། </br> དེང་སང་དུས་རབས་ཉེར་གཅིག་པར་འཕྲུལ་ཆས་སོགས་དངོས་པོ་ཧ་ཅང་ཡར་རྒྱས་ལ་ཕྱིན་ཡོད་ཀྱང་། མིའི་སེམས་ཀྱི་ཞི་བདེ་འཕྲུལ་ཆས་ཀྱི་ཐོག་ནས་བཟོ་ཐུབ་རྒྱུ་ཧ་ཅང་ཁག་པོ་རེད། </br> ང་ཚོ་མིའི་ཀླད་པ་ཆ་ཚང་བཀོག་ནས་འཕྲུལ་ཆས་ལ་བསྒར་ནའང་བསམ་བློ་གཏོང་བའི་ནུས་པ་མེད་པས་འཕྲུལ་ཆས་ཀྱིས་བྱང་ཆུབ་ཀྱི་སེམས་དང་སྟོང་ཉིད་ཀྱི་ལྟ་བ་བསྒོམ་མི་ཐུབ།  

<!-- tabs:end -->