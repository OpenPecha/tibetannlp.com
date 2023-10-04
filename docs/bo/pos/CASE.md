[<-back](en/pos/pos_tags.md)


<!-- tabs:start -->
#### **Case markers**

Case markers are always separated from the nouns they modify and receive their own
dedicated case tag. In our annotation scheme we do not annotate the absolutive case since
it is not overt. We do not add empty category tokens that can subsequently get tagged so in
a sentence like (7), བླ་མ་ 'lama' has no overt marker to indicate that it is in the absolutive.

(7)</br>
མར་པ n.prop</br>
ས་ case.agn</br>
བླ་མ་ n.count</br>
གསང་ v.invar</br>
སྟེ cv.sem</br>
། punc</br>
<utt>

case.all</br>
Allative case. The allative case is the clitic morpheme ལ་ -la when it occurs suffixed to
nouns, noun phrases or verbal nouns.

(8)ནམ་མཁའ་ལ་ ལྟ་“to look at the sky” (MB D 140r5 - Bialek 2022, p.60)

case.all can also mark oblique arguments of certain verbs. For more meanings, and
examples see Bialek 2022 pp.59-60. Bialek 2022 argues that when suffixed to a verbal noun
ལ་ indicates simultaneity or anteriority with the action of the main verb. She cites the following
example that is supposed to be simultaneous (but her translation actually indicates
causality), which we also tag as case.all:

(9)ཟས་དེ་ཡོན་ཏན་ཅན་ཞིག་འདུག་པ་ལ ། ངས་ཀྱང་ཟ། “As this food is excellent, I will eat [it]
too.” (GLR 27r6, Bialek 2022 p.152)

For more examples see Bialek 2022, p.148-149 and p. 152.

case.abl

Ablative case. The ablative case is the morpheme ལས་ -las when it occurs suffixed to nouns,
noun phrases or verbal nouns. After nouns, it usually means origin/source:
(10)
ནམ་མཁའ་ལས ་བབས་སོ། “[He]  came  down  from  the  sky.”
            (MB D 140r5 - Bialek 2022, p.91)

The comparative construction use the ablative ལས་ -las as the comparative marker. The
morpheme follows the noun/noun phrase which is compared, and the quality (adjective) for
which it is compared follows the particle:

(11)གཞན་ལས་ཆེ་བ་ “bigger (ཆེ་བ་) than the other one”
(SBM; apud Schwieger 2006: 315 - Bialek 2022, p.185)

When the morpheme ལས་
anterior to the following
consistent, we tag these
only occurs after verbs.
follows a verbal noun, it indicates that the action of the converb is
action. Even though this is referring to an event (a verb), to be
examples after verbal nouns as case.abl and not as cv.abl, which
If the verb is reduplicated it indicates continuation and it can be
15translated with “while”:

(12)ཁྱིམ་བདག་ཀྱང་གླང་འོངས་པར་མཐོང་བ་ལས་ མ་བཏགས་པས་ན། མིག་ཕྱུང་ཞིག
“Because (པས་ན) the householder, upon (ལས་) seeing that the ox came in, did not bind [it],
gouge out [his] eyes!” (MB D 272v1)

case.agn</br>
Agentive case. The agentive case is marked by any of the allomorphs གིས་ -gis, གྱིས་ -gyis, ཀྱིས་
-kyis, ས་ -s, ཡིས་ -yis when it occurs suffixed to nouns, noun phrases or verbal nouns. It marks
the subject of transitive verbs (we do not make distinctions when its role is more of a
“causative case”):

(13)དེ་ནས་སྤྲེའུ་ཕྲུག་རྣམས་ཀྱིས་ལོ་ཐོག་ཟོས་སོ། “Then, the monkey-children ate the crops.”
                         (GLR 23v4 - Bialek 2022, p.82)

case.ass</br>
Associative case. The associative case is the clitic morpheme དང་ -dang when suffixed to
nouns, noun phrases or verbal nouns. It has a coordination function - as the conjunction
“and”- between two or more nouns or noun phrases. It can mark oblique arguments of
certain verbs that express similarity, association, or separation (dissociation).

(14)སྨན་པ་དང་མོ་མ་རྣམས་“doctors and diviners”    (ML D 10r - Bialek 2022, p.84)

After a nominalised verb དང་ serves to coordinate two syntactically equal clauses with each
other. It can be translated as “and”.


(15)ལོ་གསུམ་ལོན་པ་དང་ །སྤྲེའུ་བྱང་ཆུབ་སེམས་དཔའ་བལྟར་ཕྱིན་པས།</br>
“Three years passed and (དང་) the bodhisattva-monkey went to inspect [them].”
(GLR 23r4. Bialek 2022 p.149)

case.comp</br>
Comparative case. The comparative construction is expressed using the morpheme པས་/བས་.
after a noun, noun phrase or verbal noun. Note that this function can also be expressed by
the ablative case marker (see case.abl and Hill 2012).

(16)གླང་པོ་ཆེ་བས་སྟོབས་ཆེ་བ་
lit.
“of
greater
strength than an elephant”
(ML D 17r - Bialek 2022, p.186)

For more complex examples see Bialek 2022, p.186.

case.ela</br>
Elative case. The elative case is the clitic morpheme ནས་ -nas when suffixed to nouns, noun
phrases or verbal nouns. Usually it expresses a place/time from which an action begins or
the cause for which an action occurs. It can form adverbs when suffixed to adjectives.

(17)
ནམ་མཁའ་ནས་
“from the sky” (GLR 22v5 - Bialek 2022. p.90)</br>
For more meanings, and examples see Bialek 2022 pp. 90-91.

case.fin</br>
Sentence-final particle. This is a sentence-final particle that does NOT occur after a verb.
Most of the time sentence-final particles occur after verbs and are thus tagged cv.fin.
However, they can also appear at the end of the sentence after noun phrases, verbal nouns
or
other
parts
of
speech,
as
shown
in
(18):

(18)</br>
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
<utt>

case.gen</br>
Genitive case. The genitive case is any of the allomorphs གི་ -gi, གྱི་ -gyi, ཀྱི་ -kyi, འི་ -'i, ཡི་ -yi,
when suffixed to a noun, noun phrase or verbal noun. The main function of the genitive
particle is to mark a noun or a noun phrase as possessive, modifying another noun.

(19)
རྒྱལ་པོའི་སྲས་གསུམ་ “king’s three sons” (GLR 25r4 - Bialek 2022, p.63)

Note that when a genitive particle is added to a nominalised phrase or clause it forms a
relative
clause:

(20)
ཤིན་ཏུ་དད་པའི ་སེམས་ “ a mind that utterly believes” (MB D 138v5, Bialek 2022 p.139)

case.loc</br>
Locative case. The locative case is the clitic morpheme ན་ -na when suffixed to a noun,
noun phrase or to a verbal noun. It can have temporal or spatial meaning.

(21)
གྲོང་ཁྱེར་དེ་ན་ “in that town”
(MB D 138r7 - Bialek 2022, p.58)

ན་ has temporal function when it follows a verbal noun, meaning 'if/when':

It has temporal function when it follows a verbal noun.

(22) ཉི་མའི་འོད་ཟེར་ཤར་བ་ན ༎ འབྱུང་པོའ ་ ི བྱ་རྣམས་ལོང་བར་འགྱུར།། “When rays of the sun have
risen, the birds of demons (i.e. owls and other nocturnal birds) become blind.”
(SSP 3c–d, Bialek 2022, p.152)

case.nare</br>
The case -na-re. The case suffix ན་རེ་ -na-re introduces direct speech.

(23)
“The
དྲག་སྲིན་མོ་ན་རེ །
rock-ogress
replied,
‘If
ཁྱེད་ངའི་ཁྱོ་མི་བྱེད་ན་ང་ཚོའི་དུས་བྱེད་དོ་ཟེར་ནས།
you
don’t
become
my husband, I will die.’”
(GLR 22r6 - Bialek 2022, p.158)

case.ques</br>
Question particle. Question particles usually follow verbs, but occasionally, they can follow
nouns or verbal nouns. These question particles that are NOT following verbs are tagged
case.ques (unlike cv.ques).

(24)</br>
བདག་ p.pers</br>
དེ་ d.dem</br>
ལ་ case.all</br>
ཅུང་ཟད་ adv.intense</br>
ཙམ་ d.tsam</br>
མི་ neg</br>
དགའ་བ n.v.fut.n.v.pres</br>
འམ་ case.ques</br>
<utt></br>
འཁོན་ v.fut.v.pres</br>
དུ་ cv.term</br>
འཛིན་པ་ n.v.pres</br>
མེད་ v.invar.med</br>
དོ cv.fin</br>
། punc</br>
<utt>

case.rung</br>
Case marker རུང་. རུང་ when it is NOT following a verb (unlike cv.rung).

(25)</br>
འཛམ་བུ n.prop</br>
འི་ case.gen</br>
གླིང་ n.count</br>
དབང་ n.count</br>
རུང་ case.rung</br>
འཆི་ v.fut.v.pres</br>
ཚེ་ n.rel</br>
བཞག་ v.past.bzhag</br>
དགོས་ v.invar.dgos</br>
འདུག་པ n.v.invar.dug</br>
ས case.agn</br>
། punc</br>
<utt>

case.sem</br>
Semi-final particle. Just like the sentence-final particle, the semi-final particle usually
appears after verbs. However, it can also occur after noun phrases or verbal nouns, in which
case it is tagged as case.sem (unlike cv.sem which occurs after verbs).

(26)
རྒྱལ་པོ་ n.count
གསལ་རྒྱལ་ n.prop
གྱི་ case.gen
བུ་མོ་ n.count
རྡོ་རྗེ n.count
འི་ case.gen
ལེའུ་ n.count
སྟེ་ case.sem
བདུན་པ num.ord
འོ case.fin
། punc
case.term
Terminative case. The terminative case is any of the allomorphs རུ་ -ru, སུ་ -su, ཏུ་ -tu, དུ་ -du, ར་
-r, when suffixed to a noun, noun phrase or verbal noun. It can have a locative meaning. In
addition, it can form adverbs.
(27)
ལྷའི་གནས་སུ་ “in a deities’ place” (MB D 140r3 - Bialek 2022 p.75)
The terminative can also be used also to express a beneficiary or a result of an action and it
19can mark oblique arguments of certain verbs (for more examples see Bialek 2022 p.75).

#### **བོད་ཡིག**

༄༅། །ཕྱི་ལོ་ ༢༠༢༣ ཟླ་ ༦ ཚེས་ ༡༥ ཉིན་སྤྱི་ནོར་༸གོང་ས་༸སྐྱབས་མགོན་ཆེན་པོ་མཆོག་གིས་རྒྱ་གར་གྱི་རྒྱལ་ས་ལྡི་ལིར་རྟེན་གཞི་བྱས་པའི་༸གོང་ས་ཏཱ་ལའི་བླ་མའི་ཀུན་ཁྱབ་འགན་ཁུར་ཐེབས་རྩས་(FURHHDL)མཐུན་འགྱུར་འོག་རྒྱ་གར་རྒྱལ་ཡོངས་མཐོ་རིམ་སློབ་གྲྭ་ཁག་ཏུ་སློབ་གཉེར་གནང་བཞིན་པའི་སློབ་ཕྲུག་ ༢༤ ལ་མཇལ་ཁ་དང་བཀའ་སློབ་སྩལ་ཡོད་པ་རེད།

<!-- tabs:end -->