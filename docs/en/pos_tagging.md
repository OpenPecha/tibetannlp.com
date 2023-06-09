### 3. POS tagging

In this section, we go through every single morphosyntactic (part-of-speech) tag and provide
11explanations and examples of when they are applied.

### 3.1 Adjectives

There is only one tag for adjectives: adj. We do not distinguish different types of adjectives
or different grades of adjectives. Note that in general, verbs derived from adjectives are
tagged (n.)v.invar unless they have -s, in which case they are (n.)v.past (see section on
verbs).

adj - adjectives</br>
Adjectives are notoriously difficult to define in any Sino-Tibetan language. For our annotation
purposes, we give the POS tag adj to those words that can occur in attributive position and
are not verbal nouns. Morphologically, they are almost always multisyllabic. The paragon of
adjectives are those that in -པོ་ , -མོ་ , -པ་, -མ་, -ཅན་, -ལྡན་, and -མེད་. Etymologically ཅན་, - ལྡན་ 'with',
and - མེད་ 'without' are verbs, but when they occur in forms that are functioning nominally, they
cannot be analysed as verbs. Therefore, we treat them together with the preceding syllable
as an adjective. Although words such as ནག་ 'black', གསར་ 'new', and ཆེ་ 'big' are frequently
treated like adjectives for pedagogical purposes, a single syllable in predicate position before
verbal suffixes is tagged as a verb 'to be black', 'to be new', etc. These words may appear to
occur attributively, but we see this as the formation of compounds. The compound བློན་ཆེན་
'prime minister' contrasts beautifully with the noun and adjective pair བློན་པོ་ ཆེན་པོ་ 'great
minister', etc.).

There are various cases where homophonous verbs and adjectives may cause ambiguity,
making it difficult to decide how to annotate them. We adhere to the following protocols for
those cases. First, verbs derived from adjectives are tagged (n.)v.invar, as shown in (1):

(1)</br>
རབ་ adv.intense</br>
ཏུ་ cv.term</br>
འབྱུང་བ n.v.fut.n.v.pres</br>
ར་ case.term</br>
དཀ v.invar → this is tagged as v.invar and not as adj</br>
འོ cv.fin</br>
། punc

Second, sometimes, nominalised forms are actually derived twice, i.e. first from adj → verb
and then from verb → verbal noun. An example of this is seen here where ཆུང་བ་ can only
mean 'the [time of] being small' and not 'the small person'. In those cases, they are tagged
as n.v.invar, as shown in (2):

(2)</br>
ཆུང་བ n.v.invar → this is left as a double derivation n.v.invar</br>
འི་ case.gen</br>
དུས་ n.rel</br>
12སུ་ case.term</br>
ལེན་དྲན་གྲི་ལེནྡྲ་ n.prop</br>
ན་ case.loc</br>
སྒྲོལ་མ n.count</br>
འི་ case.gen</br>
རྟེན་ n.count</br>
བཞུགས་པ n.v.invar</br>
འི་ case.gen</br>
ཕྱག་ n.count</br>
ཏུ case.term</br>
། punc</br>
<utt>

A similar example is found in (3): 'because his discipline was small, his accomplishments
also were few'. Note that the second verbal noun in this example is derived from the verb 'to
accomplish', so even though the nominalised form functions as a noun, it will still have the
n.v. tag. The issue of n.v. versus n.count tag only arises with adjectives like 'small' → 'to be
small' (=verbal) vs 'small person' (=nominal). More examples are given in (4-6) below.

(3)</br>
བརྩོན་འགྲུས་ n.count</br>
ཆུང་བ n.v.invar 'to be small'</br>
ས་ case.agn</br>
གྲུབ་པ n.v.past 'accomplishment'</br>
འང་ cl.focus</br>
ཉུང་བ n.v.past.n.v.pres 'to be small/few'</br>
ར་ case.term</br>
འགྱུར v.fut.v.pres</br>
། punc</br>
<utt>

(4)</br>
རྒྱལ་བུ་ n.count</br>
ཆུངས་བ n.v.past</br>
ས་ case.agn</br>
བློན་པོ་ n.count</br>
རྣམས་ d.plural</br>
ཀྱིས་ case.agn</br>
ཆོས་ཁྲིམས་ n.count</br>
བཤིག་ v.past</br>
སྟེ cv.sem</br>
། punc

(5)</br>
ཕྱི n.rel</br>
ར་ case.term</br>
འཁོར་བ་ n.v.fut.n.v.pres</br>
13ནི་ cl.focus</br>
ཉུང་ v.invar</br>
རབ་ adv.intense</br>
བོ cv.fin</br>
། punc

(6)</br>
ཚེ n.count</br>
འི་ case.gen</br>
མཐ n.rel</br>
ར་ case.term</br>
ཐུག་པ n.v.invar</br>
འི་ case.gen</br>
གྲངས་ n.count</br>
ནི་ cl.focus</br>
ཉུང་ v.invar</br>
སྟེ cv.sem

### 3.2 Adverbs

Adverbs modify verbs, adjectives or other adverbs. We distinguish between "directional",
"intensifying" and "mimetic" adverbs.

adv.dir</br>
Directional adverb. We use this tag for adverbs that end in - ཆད་ or -ཅད་. We also include ཕན་
ཚུན་ 'mutually' in this category, for lack of a better place to put it. Words tagged adv.dir
include: ཡན་ཆད་ 'above', མན་ཆད་ 'below', ཕྱིན་ཆད་ 'after', ཚུན་, ཚུན་ཆད་ and ཚུན་ཅད་ ‘ within’, སྔོན་ཆད་ 'before',
སླན་ཆད་ 'after', ཕན་ཆད་ and ཕན་ཅད་ ‘ onwards’, ཡན་ and ཡན་ཆད་ ‘ above’.

adv.intense</br>
Intensifying adverb. This tag was created for the adverbs རབ་(ཏུ་) 'very' and ཤིན་(ཏུ་) 'very',
because as uninflected stems they do not occur independently. The following words are also
tagged adv.intense: ཅུང་ཟད་, ཡེ་ , ཧ་ཅང་, ཆེས་, ནན་ཏ, and ཅུང་ཙམ་.

adv.mim</br>
Mimetic adverb. This tag is used for onomatopoeia and phonophors. Examples include ཁོར་
ཁོར་ཡུག་, ནར་ནར་, ཙབ་ཙོབ་, རྩོག་རྩོག་, ཁྲེ་ལོག་ལོག་, གཅེར་རེ་ , ཅེ་རེ་ , ཏབ་ཏབ་པོ , ཏབ་ཏོབ་, ཏུར་ཏུར་པོ་ , རིག་རིག་, ལིང་, and ཧྲིག་ཧྲིག་.

### 3.3 Case markers

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

### 3.4 Clitics

cl.focus</br>
Focus clitic. Focus clitics ཀྱང་ and ཡང་ are tagged cl.focus. Other words currently tagged with
this tag include: འང་, ཅང་, and ཕྱིར་ཡང་. The word ལྟ་ when it is not tagged as a verb, or a relator
noun, is also tagged as a focus clitic.

cl.top</br>
Topic clitic. This tag is introduced for the topic clitic -ni ནི་ . In this way we can automatically
create a topic phrase NP-TOP with the automatic chunkparsing.

(28)དེ་བཞིན་གཤེགས་པ་ནི་ ཡོན་ཏན་མངའོ། “Regarding Tathāgata, [he] possesses excellent
qualities.” (MB D 138v6, Bialek 2022 p.119)

cl.quot</br>
Quotative clitic. The 'quotative clitic' has the allomorphs ཅེས་, ཞེས་, and ཤེས་. The forms ཅེ་ན་, ཅེས་
པ, etc. reveal that these are originally verbs, but it in order to do justice to their new function
and to facilitate research into (in)direct speech, we keep the tag cl.quot. A selection of words
tagged with this tag are: ཞེས་, ཅེས་, ཞེས་པ་, ཞེ་ , ཅེས་པ་, ཤེ་ , ཅེ་ , ཅེས་བ་, ཞིས་ (a misspelling of ཞེས་), and ཞེས་བ.

### 3.5 Converbs

Unlike the name suggests, converbs in this annotation manual are not actually verbs, but the
subordinate conjunctions attached to subordinate clause verbs. These 'converbs' are
homophonous with their case marking counterparts, but will be tagged "cv.X" instead of
"case.X" because they always follow verbs. Note that to be consistent, after verbal nouns,
these markers are always tagged "case.X", because of the noun-like nature of the verbal
noun.

cv.abl</br>
There are few cases when cv.abl occurs after a verb stem. The ablative converb is the
morpheme ལས་ -las when it follows a verb. It usually means origin/source:

(29)</br>
འཕགས་པ་ n.v.invar</br>
ཐོགས་མེད་ n.prop</br>
ཐུབ་པ་དཔག་བསམ་ཤིང་ n.count</br>
གྱུར་ v.past.gyur</br>
ལས cv.abl</br>
། punc

cv.agn</br>
Agentive converb. The agentive converb has the allomorphs གིས་ -gis, གྱིས་ -gyis, ཀྱིས་ -kyis,
when it follows a verb. It forms causal clauses.

(30)</br>
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
<utt>

cv.all</br>
Allative converb. The allative converb is the clitic morpheme ལ་ -la when it follows a verb. It
has a coordinative function between two clauses.

(31) སྟག་མོ་འདི་ནི་ཉམ་ཆུང་ལ་ རིད་པ་ “this tigress, that was weak and (ལ་) meagre”</br>
(MB D 139r5, Bialek 2022, p. 148)

cv.are</br>
The converb are (འ་རེ་ ). This tag is used to tag the converb ཏ་རེ་ and its allomorphs (cf. Walter
Wimon, 1967, 'The Tibetan Particle "re",' Bulletin of the School of Oriental and African
Studies, 30.1, pp. 117-126). It is worth noting that the Tibetan sentences ending in འ་རེ་ are
often preceded by sentences ending in an imperative; the two kinds of sentences have to be
considered (and translated) together.

(32) ཐམས་ཅད་སྡུག་བསྔལ་བར་གྱུར་ཏ་རེ་
“lest misfortune should befall us all”</br>
(Vinayavastu ; Ti. T, XLI,237a1= N, hDul, Kha, 559A)

cv.ass</br>
Associative converb. The associative converb is the clitic morpheme དང་ -dang if it follows a
verb. This tag is particularly used with the polite imperative meaning of དང་. It is added at the
end of an imperative clause in order to connect this clause with the following, indicative one.
When དང་ connects an imperative clause with another clause, it also signals that the next
21clause has a subject distinct from the imperative clause.

(33) མཆེད་གཉིས་སྔར་གཤེགས་ཤིག་དང་ ། བདག་དོན་ཞིག་གཉེར་ཏེ། སླད་བཞིན་པར་མཆིའོ།</br>
“Oh, brothers, go on ahead! Having taken care of something, I will come after.”</br>
(MB D 139v2, Bialek 2022 p.146)

cv.cont</br>
Continuing converb. The continuing converb is formally similar to the genitive followed by -
ན་ and functionally similar to the imperfective converb in earlier strata of literature. The words
tagged with this tag are: གིན་, ཀྱིན་, གྱིན་. The function of this particle is to connect the main verb
with the following special verb. Their common trait is that they express the progressive
aspect.

(34) ཆོས་ཟབ་མོ་སྟོང་པ་ཉིད་ལ་མོས་པར་བེད་གིན་ ཡོད་དུས།
“While
[the
monkey]
was
devoting itself to the profound Buddhist teaching, the voidness, [. . .].”</br>
(GLR 22r4, Bialek p.195)

cv.ela</br>
Elative converb. The elative converb is the clitic morpheme ནས་ -nas when it follows verbs. It
has a resultative function.

(35)ལྷ་མོ་དེས་ དེ་སྐད་སྨྲས་པ ་ཐོས་ནས་ ཁམས་ཏེ།
uttered, [she] fainted away.”
“When the queen had heard these words
(MB D 139v7–140r1, Bialek 2022, p.144)

cv.fin</br>
Sentence-final particle after verbs. The sentence-final particle is an explicit marker of a
finite verb in the indicative mood. Words tagged with this tag include: སོ , འོ , དོ , ངོ , ནོ , ཏོ , རོ , ལོ , གོ , བོ ,
མོ , and པོ .

(36) དེའི་ཚེ་སྟག་མོས་རྒྱལ་བུའ་ཤ་ན་ཟད་པར་ཟོས་སོ ། “By that time the tigress has completely
eaten the flesh of the prince[’s body].”
(MB D 140r1. Bialek 2022, p.119)

cv.gen</br>
Genitive converb. The genitive converb is any of the allomorphs གི་ -gi, གྱི་ -gyi, ཀྱི་ -kyi, འི་ -'i, ཡི་
-yi, when it follows a verb. It usually marks an adversative relationship between the
preceding verb and the following one. If the verb is negated then it has more of a concessive
meaning, rendered as “although”, “but”.

(37) སྡིག་པ་བྱས་པ་ན་སེམས་ཅན་དམྱལ་བར་ལྟུང་གི ། དགེ་བ་བྱས་ན་མཐོ་རིས་སུ་སྐྱེད་སྟ
“If [one] committed an offence, [he] will fall to hell. Whereas (གི་ ), if [one] did good deeds, [he]
will be reborn in heaven.”
(MB D 140r7, Bialek 2022, p.147)

cv.impf</br>
Imperfective converb. The imperfecctive converb is the morpheme that has the three
allomorphs ཞིང་, ཅིང་, and ཤིང་ and always follows a verb. This converb can frequently be
rendered with “and” in English and it has mainly a coordinate function between two
predicates.

(38) རྒྱལ་པོ་དེ་ཕྱི་རོལ་ཏུ་འཆག་ཅིང་ དོང་ངོ་།
Lit. “The king took a walk outside and went.”</br>
(MB D 139r3–4, Bialek 2022, p.108)

cv.loc</br>
Locative converb. The locative converb is the clitic morpheme ན་ when it follows a verb. It
has
a
conditional
function: </br>

(39) སྐ་བ་ཡོད་ན་ངེས་པར་འཇིག་གོ། “If [something] has birth, [it] will certainly perish.”</br>
(MB D 140r6–7, Bialek 2022 p.145)

For more examples see Bialek 2022, p.145-146.

cv.ipv</br>
Imperative converb. The imperative converb is the morpheme that explicitly marks the
imperative or prohibitive mood, which has one of the three allomorphs ཤིག་, ཅིག་, and ཞིག་.
ཤིག་པ་ is also tagged with this tag.

(40) བདག་ལ་སྨྲོས་ཤིག་ “Tell us!”
(MB D 140r5, Bialek p.93)

cv.odd</br>
Odd converbs. Odd converbs are any that we discovered after fixing the tagset. So far we
the following words with this tag: ལས་ཆེ , ཨང་, ཚད་. We acknowledge that that this not a good tag,
but we need to do research on each of the individual markers in this category before we can
give them their own tag.

cv.ques</br>
Question converb. The question converb is any allomorph of the marker འམ, which is an
explicit marker of a polar questions or alternate questions. Words tagged with this tag
include: འམ, སམ, ནམ, དམ, གམ, ངམ, ཏམ, རམ, ལམ, བམ, མམ, ངེ་ , and མཾ་ .

(41)
Polar question:   ནུས་པ་ཡོད་དམ །  “Is  there  anybody  suitable?”</br>
(MB D 139r7, Bialek p.136)</br>

(42) Alternate questions: བདེན་ནམ་ མི་བདེན།  “Is [it] true or false (lit. not true)?”</br>
(ML D 18v, Bialek p.136)</br>

cv.rung</br>
The converb རུང་. When the morpheme རུང་ appears after a verb it functions as a converb with
a concessive meaning.

(43) ཨ་ཁུ་དང་ཨ་ནེ་གཉིས་ཅི་ལ་མི་འཆམ་རུང་ ལྟོ་ལ་འཆམ་པ་དང་།  “Although the paternal uncle
and aunt never agreed on anything, [they] did agree on food.”</br>
(ML D 12r, Bialek 2022 p.200)

cv.sem</br>
Semi-final converb. The semi-final converb is the morpheme that has the three allomorphs
ཏེ , སྟེ , and དེ . It usually follows a verb and it is also called gerundial particle - it can introduce a
fact, person, event, described in more details in the following sentence (can be rendered as
“and” or with a semicolon in English) or - as the name suggests - it can have a gerundial
function. In both cases the verb preceding the cv.sem and the verb of the main clause
(usually followed by a cv.fin) have the same subject.

(44) འཛམ་བུ་གླིང་འདི་ན་རྒྱལ་པོ་ཤིང་རྟ་ཆེན་པོ་ཞེས་བྱ་བ་ཞིག་ཡོད་དེ ། རྒྱལ་ཕྲན་ལྔ་སྟོང་སྙེད་ལ་
དབང་བྱེད་དོ།། “There was a king called Śiṅ-rta-čhen-po in this continent; [he] was ruling
over about five thousand vassals.”

(MB D 139r2, Bialek 2022, p.118)

(45) དེ་ནས་བྲག་སྲིན་མོ་ལངས་ཏེ། སྤེའུ་ལ་འདྲི་ཅེས་ཟེར་རོ༎
“The rock demoness arose and asked the monkey thus.” (GLR 22r6, Bialek 2022, p.118)

For more examples and specific uses of the cv.sem see Bialek 2022 pp. 118-119.

cv.term</br>
Terminative converb. The terminative converb is any of the allomorphs རུ་ -ru, སུ་ -su, ཏུ་ -tu,
དུ་ -du, ར་ -r, when it follows a verb or a verbal noun. The terminative after the verb stem
marks an infinitive clause that expresses purpose of an action:

(46) བདག་གི་བུ་དགུམ་པ་ལ་ཐུག་པ་འདིའི་སྐྱབས་མཛད་དུ་གསོལ།
“[I] beg [you] to save thesex`
sons of mine who are about to be killed.”</br>

(MB D 138v, Bialek 2022 p.146)

### 3.6 Determiners

Determiners are tagged d.X. We distinguish between demonstratives, emphasising
determiners, indefinite markers, plural markers, quantifiers and "tsam".

d.dem</br>
Demonstrative. This tag is used for the demonstratives འདི་ 'this' and དེ་ 'that'. These two
words are tagged as demonstratives also when used as determiners (i.e. we do not
distinguish r རྒྱལ་པོ་དེ་ 'that king' from དེ་ 'that one, him'). Words tagged with this tag include: དེ་ ,
འདི , ཡ, ཚུ, མ, ཕ, ཕྱི་ , ཕ་གི་ , མ་ཀི , མ་གི , མ་གི་ , མ་ཀི་ , འདི་པ, ཡ་གི་ .

d.emph</br>
Emphasising determiner. This category is for ཉིད་ in phrases such as རྒྱལ་པོ་ཉིད་ 'that very king'
or ལུས་ཉིད་ 'this body'. This syntactic use of ཉིད་ must be distinguished from its use in Buddhist
terminology - ཉིད་ inside of words, e.g. སྟོང་པ་ཉིད་ 'emptiness'. Apart from ཉིད་, ཁོ་ན་ 'the very, same'
is also tagged as d.emph. This use of ཁོ་ན་ should not be confused with its function as a third
person pronoun in Old Tibetan. In one case ཁོ་ appears not as a personal pronoun but as
what seems to be a variant of ཁོ་ན་; this ཁོ་ we also classify as an emphatic, e.g.

(47) སྨྲས་པའི་ཚིག་འདི་བདེན་ན་བདེན་པའི་ཚིག་བདེན་པའི་ཚིག་སྨྲས་པས། བདག་གི་ལུས་འདི་སྔ་མ་ཁོ་བཞིན་དུ་
རྨ་མེད་པར་གྱུར་ཅིག་ 'If these words that I have said are true, then because of saying true
words, let this my body be without wounds like before' (D341, vol 74, page 137b).

Words tagged with this tag include: ཉིད་, རབ་, ཁོ་ན་, and ཁོ་ .

d.indef</br>
Indefinite article. This category is used for the allomorphs of the indefinite marker ཅིག་,ཞིག་,
ཤིག་ as in ཕོ་ཉ་ ཅིག་ 'a messenger'. The indefinite marker, which occurs inside of noun phrases,
must be distinguished from the identically looking imperative converb (see cv.ipv), which
occurs suffixed to the imperative stems of verbs.

d.plural</br>
Plural marker. The plural markers རྣམས་ , དག་, and ཚོ་ are tagged as their own category 'plural'.
However, plural pronouns (བདག་ཅག་, ཁྱེད་ཅག་, འུ་བུ་ཅག་) are treated as one word and tagged as
pronouns (see p.pers). Words tagged with this tag include: རྣམས་, དག་, ཡོངས་, སྣ་ཚོགས་, ཚོ་ .

d.quant</br>
Quantifier. For quantifiers like ཀུན་ 'all', ཐམས་ཅད་ 'all', གཞན་ ‘ other’, ཀ་ ‘ all’, ག་ ‘ all’ - usually found
after numbers, རེ་ and རེ་རེ་ ‘ each’, ཤ་སྟག་ ‘ only, all’, ཁ་ ‘ some’, ཡ་རེ་ ‘ each one of two’, སྣ་རེ་ ‘ a few’,
གཞིན་ ‘ ?’, མང་པོ་ ‘ many’, སྤྱི་ ‘ all’, ཅུང་ཟད་ ‘ a few’, དུ་མ་ ‘ many’, ཤས་ ‘ some, a few’, མཐའ་དག་ ‘ all’, ཆུང་ཟད་ ‘ a
little’, སྣ་དགུ་ ‘ all kinds of’ (English quantifiers are 'all, every, some, a few, a lot, many, etc.').
Note many of these markers can also be used as arguments, in which case they are tagged
p.indef.

(48)</br>
རི་ n.count</br>
ཐམས་ཅད་ d.quant</br>
གྲོག་པོ n.count</br>
25ར་ case.term</br>
སོང་ v.past.gro</br>
། punc

(49)</br>
ཁོང་ p.pers</br>
གྲོགས་པོ་ n.count</br>
རྣམས་ d.plural</br>
ནི་ cl.top</br>
ཕྱག་རྟེན་ n.count</br>
གཞིན་ d.quant</br>
ཙམ་ d.tsam</br>
ལས་ case.abl</br>
མི་ neg</br>
གཏོང་བ n.v.pres</br>
ར་ case.term</br>
འདུག v.invar.dug</br>
ང p.pers</br>
ས་ case.agn</br>
གསེར་གཡུ་ n.mass</br>
ཀུན་ d.quant</br>
ཕུལ་ v.past</br>
ཏེ cv.sem</br>
། punc</br>
<utt>

(50)</br>
ད་ adv.temp</br>
ལྟ་ n.rel</br>
ཆོས་པ་ n.count</br>
བཟང་པོ adj</br>
ར་ case.term</br>
རློམ་པ n.v.invar</br>
འི་ case.gen</br>
མི་ n.count</br>
བསོད་ནམས་ཅན་ adj</br>
འགའ d.quant</br>
། punc</br>
<utt>

(51)</br>
སྡུག་ n.count</br>
སྣ་དགུ་ d.quant</br>
བཏང་ v.past</br>
རྗེས་ n.rel</br>
གསོན་སྙིང་ n.count</br>
ལ་ case.all</br>
དམར་ v.invar</br>
འདོན་ v.pres</br>
བྱེད་ v.pres.byed</br>
ཟེར་བ་ n.v.fut.n.v.pres</br>
ལ case.all</br>
། punc</br>
<utt>

(52)</br>
དྲིན་ n.count</br>
གཟོ་བ་ n.v.invar</br>
ཆུང་ཟད་ d.quant</br>
ཀྱང་ cl.focus</br>
མ་ neg</br>
བྱས་པ n.v.past</br>

(53)</br>
ངན་སོང་ n.count</br>
གི་ case.gen</br>
སྡུག་བསྔལ་ n.count</br>
མཐའ་དག་ d.quant</br>
ལས་ case.abl</br>
སྐྱོབ་པ n.v.pres</br>
ར་ case.term</br>
མཛད་པ་ n.v.invar.mdzad</br>
ལགས་ v.invar.lags</br>
སོ cv.fin</br>
། punc</br>
<utt>

(54)</br>
དེ d.dem</br>
ར་ case.term</br>
ཞག་ n.count</br>
ཤས་ d.quant</br>
བཞུགས་པ n.v.invar</br>
ས་ case.agn</br>
རྫི་བོ་ n.count</br>
ཞབས་ n.count</br>
ཕྱི n.rel</br>
ར་ case.term</br>
འབྲངས་པ་ n.v.past

(55)</br>
གཡོ་ཐབས་</br>
n.count</br>
དུ་མ d.quant</br>
ས་ case.agn</br>
ཁང་ n.count</br>
ཞིང་ n.count</br>
ཕྲོགས v.past</br>
། punc</br>
<utt>

(56)</br>
གདམས་ངག་ n.count</br>
སྤྱི་ d.quant</br>
ལ་ case.all</br>
རང་བྱན་ n.count</br>
ཚུད་ v.past.v.pres</br>
ནས cv.ela</br>
། punc</br>
<utt>

(57)</br>
ཐུགས་ n.count</br>
བསྙུང་བ n.v.invar</br>
འི་ case.gen</br>
མི་ n.count</br>
མང་པོ་ d.quant</br>
གྲི་ཁ n.count</br>
ར་ case.term</br>
ཤི་བ་ n.v.past</br>
གཟིགས་ v.past.v.pres</br>
ནས cv.ela</br>
། punc</br>
<utt>

(58)</br>
ཉན་ཐོས་ n.count</br>
གཉིས་ num.card</br>
ཀ d.quant</br>
འི་ case.gen</br>
མངོན་པ n.count

(59)</br>
ཡབ་ཡུམ་ n.count</br>
གྱི་ case.gen</br>
ཐུགས་ n.count</br>
ཀ d.quant</br>
ར་ case.term</br>
བཏང་ v.past</br>
28མི་ neg</br>
འཚལ v.invar.tshal2</br>
། punc</br>
<utt>

(60)</br>
རྣམ་ཐར་ n.count</br>
ཡང་ cl.focus</br>
དེ་ d.dem</br>
ཀ d.quant</br>
ས་ case.agn</br>
འཁྱོངས v.invar</br>
། punc</br>
<utt>

(61)</br>
སྲོད་ adv.temp</br>
ལ་ case.all</br>
ཐེག་ཆེན་ n.count</br>
འདི་ d.dem</br>
རྒྱུ་ n.count</br>
བཟང་ v.invar</br>
ལ་ cv.all</br>
འབྲས་བུ་ n.count</br>
ཁ་ d.quant</br>
གཡེལ་བ་ n.v.fut.n.v.pres</br>
འདྲ་ v.invar.dra2</br>
གསུང་ v.invar

(62)</br>
བརྒྱ་བྱིན་ n.prop</br>
དང་ case.ass</br>
ཚངས་པ n.prop</br>
འི་ case.gen</br>
རྒྱལ་པོ n.count</br>
ས་ case.agn</br>
ལག་པ་ n.count</br>
ཡ་རེ་ d.quant</br>
ནས་ case.ela</br>
ཟིན་ v.invar</br>
ཏེ cv.sem</br>
། punc</br>
<utt>

d.tsam</br>
Tsam and words with similar distribution. Words tagged with this tag include ཙམ་, སྙེད་, ཙམ་
29པ་, རྙེད་ (a misspelling for སྙེད་), ཙམ་པ, སྙད་, and སྙེད་པ.

### 3.7 Interjections

Interj</br>
Interjection. This tag is used for interjections. Words tagged with this tag include: ཀྱེ་མ་, ཀྱེ་ , ཨ་ལ་
ལ་, ཀྱི་ཧུད་, ཁོ་དེ , མ་ལ་, འོ་དོད་, ཧེ་ , ཨེ་མ་, and ཨེ་ཨེ་ .

### 3.8 Nouns

n.temp</br>
Temporal noun. Temporal nouns are those that occur in syntactic positions or have
morphological structure that suggests they are nouns. They refer to time, and are generally
not followed by case markers. Examples of temporal nouns are: ད་, སྔོན་, སྔ་, ད་དུང་, ནང་པ, ཕྱི་ཉིན་, ཁ་
སང་, དོ་ནུབ་, གདོད་, ཉིན་, དེ་རིང་, དེང་, ནུབ་, མཚན་མོ་ , ཅིག་ཅར་, གཟོད་, ཐོག་མ་, དབྱར་, དིང་སང་, མདང་, མཚན་, སང་, དགུན་, དེང་སང་,
ནངས་པ, ཕྱི་ , ཡུན་རིང་, སྲོད་, གདུགས་ཚོད་, གནངས་, གུང་, གློ་བུ, ཉིན་མཚན་, ད་ལོ , ནང་, ནངས་, ཕྱི་དྲོ་ , མཚན་ཡལ་, འདང་, སླན་ཆད་, ཁར་རྩང་,
ཁྲུགས་, གནའ་, གཟོད་མ་, ཉིན་ཞག་ཕྲུགས་, ད་ནང་, ད་རུང་, དོ་ནུབ, ནང་བ, ནངས་བ, ནམ་བཞིག་, ནུབ་མོ , ཕྱི་ཕྱི , མཚན་ཐོག་ཐག་, འཆར་ཁ་, འདང་
གསུམ་, འཕྲོ་ , རྒྱ་, སང་ཉིན་, སང་དགོང་, སང་ནང་པ, སྐྱ་རེངས་, སྔ་དྲོ་ , སྔ་སོ , སྔ་སོ་ , སྔོན , སྔོན་མ་.

n.count</br>
Count noun. Lexical nouns head a noun phrase and can have nominal suffixes such as -མོ་ ,
- པོ་ and -བུ་. We treat a - པ་ or - བ་ as part of the preceding word, regardless of the part-of-
speech of the preceding word. Sanskrit terms, e.g. ཀུན་ཏུ་རྒྱུ་ 'parivrājaka', are treated as a noun
together because it looks like a verb phrase, but functions syntactically as a noun.

In general, when two nouns occur in succession they are understood as a compound; the
dvandva compound ཕ་མ་ 'parents' is treated as one noun rather than two ( ཕ་ 'father' and མ་
'mother') and the tatpuruṣa compound ཁྱིམ་བདག་ 'householder' is likewise treated as one noun
rather than two ( ཁྱིམ་ 'home' and བདག་ 'lord'). When an adjective precedes its head this is also
treated as a compound. Thus, because དུག་བཙན་པོ་ would be the expected order for 'mighty
poison', we treat བཙན་དུག་ 'mighty poison' (vol. 74, page 147a) as a single word.

Apposition is the one category of exceptions when the concatenation of two nouns is not
treated as a compound. An example of this type is the two words བུ་ཁྱེའུ་ in the following
sentence:

(63) དེའ ་ ི ཚེ་ཡུལ་དེ་ན་ཁྱིམ་བདག་ཅིག་ལ་བུ་ཁྱེའུ ་ཞིག་བཙས་ན། 'At that time, in that land, when a child,
a son, was born to a householder'.

Rather than understanding ཁྱེའུ་ as an adjective modifying བུ་, or taking བུ་ཁྱེའུ་ as one word, the
second word simply sits after the first one to add greater specificity. The reason to not treat
apposition as compounding is because apposition occurs with proper nouns. For example, in
the sentence:

(64) དེའི་ཚེ་ན་རྒྱལ་པོ་གསལ་རྒྱལ་གྱི་བཙུན་མོ་ཆེན་པོ་ཧབར་ལི་ཞེས་བྱ་བ་ལ་བུ་མོ་ཞིག་བཙས་ནས་ 'At that
time a daughter was born to Ḥbar-li, the main queen of king Prasenajit',


In (64), རྒྱལ་པོ་ 'king' and གསལ་རྒྱལ་ 'Prasenajit' are in apposition; to unite the two as a compound
would lead to unintuitive, unwieldy, and therefore have unacceptable consequences.

n.mass</br>
Mass noun. We separate mass nouns from count nouns on the basis of two instances in our
corpus where otherwise two nouns not in apposition would follow each other: ནོར་བུ་སྦར་གང་ 'a
handful of jewels' and ཆུ་སྙིན་པ་གང་ 'a handful of water'. Knowing that there exists this syntactic
difference between count nouns and mass nouns, we tag all plausible mass nouns on the
basis of their meaning (e.g. ཟངས་ 'copper'). A final list of mass nouns can only be securely put
forward after the syntactic behavior of these words is better investigated. Words tagged with
this tag include: གསེར་, ཆུ་, རིན་པོ་ཆེ་ , ནོར་, ཤ་, ཆུ, ས་, ཁྲག་, ཆང་, སྨན་, སེར་བ་, ནོར་བུ་, མར་, ངུར་སྨྲིག་, དངུལ་, ཡི་གེ་ , ནས་,
ལྕགས་, སྤུ་, གངས་, ཙན་དན་, གསེར་གཡུ་, གོས་, དར་, ཤེལ་, གསེར་དངུལ་, པདྨ་རཱ་ག་, མར་ཁུ, ཟངས་, གོས་དར་, ཆུ་སྡོར་, ཐེར་ཕྲུག་, བཟའ་, བསུ་
ཆང་, བུམ་ཆུ, བཻདཱུརྱ, མཐོ་ཁྱད་, རིན་ཆེན་, སྣམ་བུ་, ཁ་བ་, ཆུ་མེ་ཤིང་, ཉ་ཕྱིས་, ཐལ་བ་, ཐུད་, དབུས་ཕྲུག་, བུར་, མཐོན་མཐིང་, མར་གད་, མར་སར་,
ཚོས་, ཟ་མ་བཅུད་, འཇིམ་པ་, འདག་, རིན་ཆེན་གསེར་, རྒྱགས་ཆུ་, རྡུལ་ཚོན་, རྣག་ཁྲག་, ལ་ཅ, ལ་ཆ, ལེ་བརྒན་, ཤ་ཁྲག་, སེང་ལྟེང་, སེང་ལྡེང་, སེར་, སྤེ ,
and སྤེན་བད་.

n.prop</br>
Proper nouns. This tag is used for proper nouns, i.e. personal and place names.

(65)</br>
བཅོམ་ལྡན་འདས་ n.count</br>
ཤཱཀྱ་སེང་གེ་ n.prop</br>
ལ་ case.all</br>
ཕྱག་ n.count</br>
འཚལ་ v.fut.v.pres.tshal1</br>
ལོ cv.fin

(66)</br>
ལག་ལྡན་ n.count</br>
བོད་ n.prop</br>
ཀྱི་ case.gen</br>
མཁས་མཆོག་ n.count</br>
རྣམས་ d.plural</br>
ལ་ case.all</br>
འདུད v.fut.v.pres</br>
། punc

n.rel</br>
Relator nouns. A relator noun is a noun, normally one syllable, which has a genitive before
it and a spatial case (allative, locative, terminative) after it, e.g. དེའི་ནང་ན་ 'inside of that', དེའ ་ ི དྲུང་དུ་
'before him', དེའ ་ ི འོག་ཏུ་ 'under that', དེའ ་ ི ཚེ་ན་ 'at that time'; relator nouns are not quantified and do
31not have adjectives, determiners or demonstratives. After identifying the class of relator
nouns, these words are tagged as relator nouns even in syntactic contexts missing the
genitive to left or the spatial case to the right.

For example, in the sentence:

(67) དེའི་ཚེ ་བློན་པོ་ཞིག་ཕྱི་རོལ་ནས་ནང་དུ་འོངས་པ་ལས། མི་བཙོན་དུ་བཟུང་བ་མཐོང་བ་དང། 'Then the
minister went inside from outside and saw the man who had been taken to prison'

In (67), the relator noun ཚེ་ is not followed by a spatial case and the relator noun ནང་ is not
preceded by a genitive. In the phrase བར་འགའ་ 'sometimes' we do not consider བར་ a relator
noun because it undergoes quantification, e.g.

(68) … བར་འགའ་ནི་གཏི་མུག་གི་ཕྱིར་ལུས་བཏང་ཡང་ཆོས་ཀྱི་ཕྱིར་བསོད་ནམས་ཀྱི་ཞིང་དང་ལན་འགའ་ཡང་མ་
ཕྲད་པའི་ལུས་འདི་ཅི་རུང། ' What is the use of this body which … sometimes has been used
because of ignorance, but has not yet met an occasion (to serve) as a field of merit'.

Words tagged with this tag include: ལྟ, ཕྱི , བཞིན་, ཚེ་ , སྐད་, བར་, དུས་, ནང་, རྗེས་, དྲུང་, ལྟ་བུ, འདྲ་, འོག་, སྟེང་, ལྟ་བུ་,
སླད་, ངང་, ཕྱོགས་, མཐའ་, སྒོ་ , བཞིན , ས, སླ, མདུན, དབུས་, ཐོག་, ཁོང་, ཕྱི་བཞིན་, ཁ, ཆེད་, ཐོག་མ, སྐབས་, གོང་, རྟིང་, ཐད་, གན་, མཇུག་,
འཕྲལ་, ལོགས་, ཁྲོད་, རྟེན་, སྨད་, ཁོངས་, གསེབ་, ཐ་མ, དུས, ཕུ་, དྲུད་, བསེབ་, མགོ , ཙ་, རིང་, རྩ, ལྟག་, སྐོར་, དཀྱིལ་, དབུང་, བྱང་, མཐའ་
ལོགས་, ཚུན་, ཞོར་, འཁྲིས་, འོག་བ, རྒྱབ་, སྐེ་ , སྐེད་, སྙིང་ཁ, སྟེངས་, སྟོད་. Several questions of delimiting relator nouns
require further consideration, in particular, the approach to ལྟ་ versus ལྟ་བུ་.

n.son</br>
Noun 'son'. We use this tag for སྲས་ In this way we can automatically create NP-NPR for
things like 'Ngawang's son'.

### 3.9 Verbal Nouns

Verbs are nominalised by adding a nominaliser like པ་, བ་, ཚུལ་, མཁན་, མི་ , or ས་ to the respective
stems, in which case they get a verbal noun tag n.v.X. Note that in general, verbs derived
from adjectives are (n.)v.invar unless they have -s, in which case they are (n.)v.past. Verbal
nouns can appear in all different tenses/moods we distinguish for verbs in general. Just like
with verbs, the tense/aspect/mood indication is based on morphology only (see section on
verbs). We do not derive potential tense or mood labels from the syntactic context as this
would entail adding linguistic analysis into the annotation, which we avoid (see general
principles in the introduction above).

n.v.fut</br>
Nominalization of a future verb stem. This tag is used for the nominalized versions of
future verb stems, i.e. a future verb stem followed by པ་, བ་, ཚུལ་, མཁན་, མི་ , or ས་. Some examples
are given in (68) and (69) below.

(69)</br>
རབ་ adv.intense</br>
ཏུ་ cv.term</br>
དབྱེ་བ་ n.v.fut</br>
ཉིད་ d.emph</br>
ཀྱིས་ case.agn</br>
དང་ case.ass</br>
། punc

(70)</br>
བྱིས་པ་ n.count</br>
འདི་ d.dem</br>
རྣམས་ d.plural</br>
ཀྱིས་ case.agn</br>
ཁྱེད་ p.pers</br>
ཀྱི་ case.gen</br>
འབབ་ས་ n.v.fut</br>
དང་ case.ass

n.v.fut.n.v.past</br>
Nominalization of a future or past stem of a verb.This tag is used for verb stems with the
same form in the future and in the past, followed by nominalisers like པ་, བ་, ཚུལ་, མཁན་, མི་ , or ས་.

(71)</br>
ཆེད་ n.rel</br>
དུ་ case.term</br>
བརྗོད་པ n.v.fut.n.v.past</br>
འི་ case.gen</br>
སྡེ་ n.count</br>
ནི cl.focus</br>
། punc

n.v.fut.n.v.pres</br>
Nominalization of a future or present stem of a verb. This tag is used for verb stems with
the same form in the future and in the present, followed by nominalisers like པ་, བ་, ཚུལ་, མཁན་, མ,
or ས་.

(72)</br>
སྡེ་སྣོད་ n.count</br>
གསུམ་ num.card</br>
དུ་ case.term</br>
འཇོག་པ n.v.fut.n.v.pres</br>
འི་ case.gen</br>
རྒྱུ་མཚན་ n.count</br>
དང་ case.ass</br>
། punc

n.v.ipv</br>
Nominalization of an imperative stem of a verb. The imperative stem of a verb is usually
not supposed to be nominalized. However, in rare cases there are nominalised forms which
appear to come from imperative stems, and we mark them accordingly.

(73)</br>
ལྷ་ཁ་ n.count</br>
སྙིང་པོ n.count</br>
ས་ case.agn</br>
སྒྲུབས་པ་ n.v.ipv</br>
ཡིན v.fut.v.pres.yin</br>
། punc

n.v.invar</br>
Nominalization of invariant verbs.This tag is used for invariant verb stems. Invariant verb
stems are so called because they have the same form in the present, future and past. When
they are nominalise, they are followed by nominalisers like པ་, བ་, ཚུལ་, མཁན་, མི་ , or ས་.

(74)</br>
ལྟ་བསྒོམ་ n.count</br>
གྱི་ case.gen</br>
གོལ་ས་ n.v.invar</br>
ཆོད་པ་ n.v.invar</br>
ཡིན v.fut.v.pres.yin</br>
། punc

n.v.past</br>
Nominalization of a past verb stem. This tag is used for the nominalized versions of past
verb stems, i.e. a past verb stem followed by nominalisers like པ་, བ་, ཚུལ་, མཁན་, མི་ , or ས་.

(75)</br>
མར་པ n.prop</br>
ས་ case.agn</br>
སྣ་ n.count</br>
ཁྲིད་ v.past</br>
ནས་ cv.ela</br>
རྨོས་པ n.v.past</br>
ས case.agn</br>
། punc

n.v.past.n.v.pres</br>
Nominalization of a past or present stem of a verb. This tag is used for verb stems with
the same form in the past and in the present, followed by nominalisers like པ་, བ་, ཚུལ་, མཁན་, མི་ ,
or ས་.

(76)</br>
འདི་ d.dem</br>
འདྲ n.rel</br>
འི་ case.gen</br>
སྙིང་རླུང་ n.count</br>
ལས་ n.count</br>
ཀྱིས་ case.agn</br>
ཟིན་པ་ n.v.past.n.v.pres</br>
རྣམས d.plural</br>
། punc

n.v.pres</br
Nominalization of a present verb stem. This tag is used for the nominalized versions of
present verb stems, i.e. a present verb stem followed by by nominalisers like པ་, བ་, ཚུལ་, མཁན་,
མི་ , or ས་.

(77)</br>
ཕ་མ་ n.count</br>
ཡང་ cl.focus</br>
སྒྲུབ་པ n.v.pres</br>
ས་ case.agn</br>
འདྲོངས v.past</br>
། punc

### 3.10 Negation

Negation in Tibetan can be marked by a negative marker or by a negative verb. For the two
verbs མིན་ and མེད་ negation is inherent to their meaning, but these verbs are therefore added
to the list of special verbs. In this section, we only discuss negative markers.

neg</br>
Negation. The two negation prefixes མ་ ma and མི་ mi are classified together in their own
category. The polar question prefix ཨེ་ e is also categorised under this tag because it
occupies the same syntactic position as མ་ and མི་ .

### 3.11 Numerals

In numbers we distinguish cardinals ( གཅིག་ གཉིས་ གསུམ་ etc.) and ordinals ( དང་པོ་ གཉིས་པ་ གསུམ་པ་ etc.).

numeral</br>
Actual numbers, e.g. "1967" or Tibetan ༥ are tagged as numeral.

(78)</br>
1967 numeral</br>
ལོ n.count</br>
ར་ case.ter</br>
སྐྱེ་དམན་ n.count</br>
འདི་ d.dem</br>
ཚོས་ n.mass</br>
འཛིན་ཆས་ n.count</br>
མང་པོ་ adj</br>
ཉོས v.past</br>
། punc</br>
(Goldstein 1993, p.90)

num.card</br>
Cardinal number. Cardinal numbers are tagged num.card. In higher numbers each
component digit is tagged separately to provide more insight into the internal structure.
When a numeral follows a noun we regard the two as separate words. In addition to obvious
cases like མི་ ལྔ་ 'five men', we also treat དཀོན་མཆོག་གསུམ་ 'triratna' as two words. We treat ཕྲག་ as a
cardinal number. There are occasions when the morphology of a word suggests that it might
contain a numeral (e.g. མངོན་སུམ 'real', ཕུན་སུམ་ཚོགས་ 'marvellous'), but there is no reason to see
such cases as synchronically analysable. Numbers that end with - པོ་ are also tagged
num.card. Derivatives of numerals are treated according to the function they have in the
sentence, thus གཅིག་པ་ 'sole' is an adjective, གཉི་ག་ 'both' is an indefinite pronoun, etc.

num.ord</br>
Ordinal number. Ordinal numbers are tagged num.ord. Some adjectives can be
distinguished from ordinal numbers only in context. For example, in the phrase རྡོ་རྗེ་རྩེ་ལྔ་པ་ 'a
five-pronged vajra' the noun phrase syntax and the overall meaning of the passage dictates
that ལྔ་པ་ is part of the word རྩེ་ལྔ་པ་ 'five-pronged' rather than an ordinal number 'fifth'.

### 3.12 Pronouns

Pronouns can be used to refer to real-life entities or those that are mentioned in the
contexts. We distinguish between indefinite, interrogative, personal and reflexive pronouns.

p.indef<br>
Indefinite pronoun. The words ལ་ལ་ 'some', སོ་སོ་ 'each', and གཉི་ག་ 'both' can function as
independent arguments of a sentence ("I like both", "Some say that's good"), in which case
they are not tagged as d.quant, but as indefinite pronouns with the tag 'p.indef'. Other words
tagged with this tag include: ཁ་, སོ་སོ་ , ལ་ལ་, རེ་རེ་ , རེ་ .

p.interrog</br>
Interrogative pronouns. This is the tag used for interrogative pronouns such as སུ་ 'who', ནམ་
'when', and གང་ 'where'. Words tagged with this tag include: ཅི་ , གང་, ཇི་ , ཅི , སུ་, ནམ་, ཇི་སྲིད་, ག་, ག་རེ་ , ཇི་
ཙམ་, ཅི་སྲིད་, and ཙུག་.

p.pers</br>
Personal pronouns. This tag is used for personal pronouns. Words tagged with this tag
include: བདག་, ཁྱོད་, ང་, ཁྱེད་, བདག་ཅག་, ངེད་, ཁོ་ , ཁོང་, རང་རེ་ , ཁོ་བོ་ , རང་, མོ་ , ཁོ་མོ་ , ཁྱེད་ཅག་, འོ་སྐོལ་, འུ་ཅག་, འོ་ཅག་. The
word རང་ is only tagged as p.pers when it functions as a full independent pronoun in its own
right; in ང་རང་ and ཁྱེད་རང་ the word རང་ is tagged p.pers. The word བདག་ is tagged as p.pers when
it is a humble equivalent of ང་. When this word means 'lord' or ' the self' (philosophy) it is
tagged n.count and when it means 'himself' it is tagged as p.refl.

p.refl</br>
Reflexive pronouns. This tag is used for reflexive pronouns. The only word tagged with this
tag རང་ and བདག་. The word རང་ is tagged as p.refl when it functions as a reflexive, in a
sentence (invented) such as ཁོས་ དེ་རིང་ རང་ གི་ ཟན་ ཟོས་ སོ་ ' Today, he ate his own food' or in long
form personal pronouns such as ང་རང་ and ཁྱེད་རང་. When རང་ is full independent pronoun
meaning 'I' or ' you' it is tagged p.pers. The word བདག་ is tagged p.refl only when it means
'himself'.

### 3.13 Punctuations

punc</br>
Punctuation. While a tsheg, ‘dot’ (ཚེག་), is considered part of the preceding syllable, all other
punctuation marks are tagged as punctuation. Such marks include །, ༑, །།, ༄༅༅།, and །།།།.
Punctuation marks are broken apart to aid tokenization, e.g. we tag ༄/punc ༅/punc །/punc.

skt</br>
Sanskrit or other metalinguistic elements. This tag was invented for the odd Sanskrit
word that occurs in Tibetan (e.g. in mantras) not as a syntactic word in its own right, but as
something metalinguistic at least vis à vis Tibetan.

### 3.14 Verbs

The tense/mood/aspect on the verb is based on the morphology only at this POS-tagging
level. Verbs derived from adjectives are (n.)v.invar unless they have -s, in which case they
are (n.)v.past. Even adjectives that only have present and past forms would be invar if they
are used as verbs and the form is the same, e.g. དཀའ་ 'difficult, hard' (or དཀ་ before cv.fin) (no
future or imperative form for this):
(79)
རབ་ adv.intense
ཏུ་ cv.term
འབྱུང་བ n.v.fut.n.v.pres
ར་ case.term
དཀ v.invar
འོ cv.fin
། punc
37v.fut
Future stem of a verb. This tag is used for future verb stems.
(80)
བླ་མ་ n.count
སྔ adv.temp
ས་ case.agn
བསྲུང་ v.fut
ལ་ cv.all
v.fut.v.past
Future or past stem of a verb. This tag is used for verb stems that are morphologically
ambiguous between the past and future.
(81)
བསྡད་ v.fut.v.past
ན་ cv.loc
འགྲོ་ v.fut.v.pres.gro
སྙིང་ n.count
འདོད v.invar.dod
v.fut.v.pres
Future or present stem of a verb. This tag is used for verb stems that are morphologically
ambiguous between the past and present.
(82)
ཕྱིན་ v.past.gro
ན་ cv.loc
སྡོད་ v.fut.v.pres
སྙིང་ n.count
འདོད v.invar.dod
། punc
v.ipv
Imperative stem of a verb. This tag is used for imperative verb stems.
(83)
རྣལ་འབྱོར་པ་ n.count
དེ་ d.dem
ནང་ n.count
དུ་ case.term
བོས་ v.ipv
ཤོག་ v.invar.shog
གསུང་ v.invar
། punc
38v.invar
Present, past, or future stem of a verb. This tag is used for verb stems that are
morphologically ambiguous among present, past, and future.
(84)
སྤྲིན་ n.count
ནག་པོ་ adj
ལྡིང་ v.invar
ཞིང་ cv.impf
། punc
If a verb has only one stem then we tag the verb as v.invar་:
(85)
ལྟས་མི་ n.count
རྣམས་ d.plural
ཀྱིས་ case.agn
སླེབ་ v.fut.v.pres
སྟེ་ cv.sem
མ་ neg
བརྡེག་ v.invar
ཅིག cv.ipv
། punc
If a verb has only two stems and they are morphologically ambiguous, then we tag the
verb as v.invar, e.g. Present/Past: དགེ་
(86)
བདག་ p.pers
ཉིད་ d.emph
གཅིག་པུ adj
འི་ case.gen
འཚོ་བ་ n.v.invar
དགེ v.invar
། punc
v.past
Past stem of a verb. This tag is used for past verb stems.
(87)
ཞིང་ n.count
འོར་མ་གྲུ་གསུམ་ n.prop
ཡང་ cl.focus
ཨ་ཁུ n.count
39འི་ case.gen
ལག་ n.count
ནས་ case.ela
བླངས་ v.past
ཏེ cv.sem
v.past.v.pres
Past or present stem of a verb. A verb stem that is both morphologically ambiguous
between the past and present.
(88)
ནམ་མཁའ་ n.count
ལ་ case.all
འཇ n.count
འི་ case.gen
གུར་ n.count
ཕུབ v.past.v.pres
། punc
v.pres
Present stem of a verb. This tag is used for present verb stems.
(89)
ཕྱག་མཆོད་ n.count
ལྷ་ n.count
དང་ case.ass
མཁའ་འགྲོ n.count
ས་ case.agn
འབུལ v.pres
། punc

#### 3.14.1 Particular Cases
Sometimes a stem can be linked to two different verbs: as བསྒོམ་ - which can be present of
བསྒོམ་ but also future of a different verb སྒོམ་ - very similar meanings and both voluntary. We tag
this case as v.fut.v.pres.

#### 3.14.2 Special verbs

Special Verbs and Verbal Nouns</br>
Although this annotation scheme does not provide full lemmatisation, we do have special
tags for a large number of 'special verbs'. These are any verbs that are of special interest
from a linguistic point of view, e.g. because they can function as auxiliaries or light verbs,
because they change/grammaticalise in later stages of the language, or because they have
additional functions, e.g. negation or copula. To make the annotation process more feasible,
40we focus only on those verbs that occur relatively frequently (this is checked in our corpora).
In the list of 'special verbs' below, the numbers in parenthesis refer to that.

In our special verb tags we don’t use ‘ for the a-chung འ for practical reasons: the apostrophe
would be confusing as part of a POS tag.

As already explained in section 1 we base our tense-aspect-mood distinctions on
morphological form only, i.e. if there is a morphological element that indicates that a verb is
past, future or present tense, we tag it as such. We do use an v.ipv tag if the imperative is
morphologically distinct from the other forms:

(90) “to do, to make”</br>
བྱེད་ → v.pres.byed</br>
བྱས་ → v.past.byed</br>
བྱ་ → v.fut.byed</br>
བྱོས་ → v.ipv.byed - alternative form བྱོ་

However, often the imperative cannot be morphologically distinguished from other verb
forms. In such cases, we consistently provide the tense/aspect/mood tag that is usually
associated with that form, e.g. རནད་ 'to be proper,to be the right time' is consistently tagged as
v.past.ran as that is what the morphology indicates and the POS tags are based on that. If
that same form can also have an imperative function, we add "(ipv)" in parentheses behind
the form, to remind annotators that in some contexts, this can have an imperative meaning.
If this is the case the POS tag remains based on the original morphology, i.e. v.past.ran, but
the imperative will be clear from the context (and this will be made extra clear by the
syntactic annotation in the parsed version of the corpus), as shown in (90):

(91) “to taste, to experience”</br>
མྱོང་ → v.pres.myong1</br>
མྱངས་ → v.past.myong1 (ipv)</br>
མྱང་ → v.fut.myong1

Homophonous special verbs, i.e. those that have different argument structures, get separate
tags, e.g. verb1 vs verb2. This facilitates future research on these forms. When doing such
research, it is advisable to extract both verbs from the corpus and do a manual check as
there may be missing arguments in the sentences. In the following list, the verbs highlighted
in orange might need an additional manual check in terms of POS tagging, because their
argument structure may be more complex. When forms are ambiguous, the list furthermore
indicates when these forms are given the special verb tag and/or what the alternative tag is
and when that would be used.

གདའ་ (72) → v.invar.gda “to be, to be there”</br>
གདའ་བ་ → n.v.invar.gda “to be, to be there”</br>
བགྱིད་ (27) → v.pres.bgyid “to do, to make”</br>
བགྱིས་ → v.past.bgyid</br>
གྱི་ → v.ipv.bgyid - alternative form གྱིས་</br>
བགྱི་ → v.fut.bgyid</br>
བགྱིད་པ་ → n.v.pres.bgyid “to do, to make”</br>
བགྱི་བ་ → n.v.fut.bgyid</br>
བགྱིས་པ་ → n.v.past.bgyid</br>
འགྱུར་ (191) → v.fut.v.pres.gyur (ipv) “to change, to transform”</br>
འགྱུརད་ → v.pres.gyur - alternative form སྒྱུར་ (ipv)</br>
གྱུར་ → v.past.gyur - alternative forms གྱུརད་ (ipv), བསྒྱུརད་</br>
བསྒྱུར་ → v.fut.v.past.gyur</br>
སྒྱུརད་ → v.ipv.gyur</br>
འགྱུར་ “ to become”, is resultative of སྒྱུར་ “ to change, to transform” - note that this is also one of
the imperative forms of འཇགས་/v.invar (this is not a special verb)</br>
བསྒྱུར་བ་ → n.v.fut.n.v.past.gyur</br>
གྱུར་བ་ → n.v.past.gyur - alternative forms གྱུརད་བ་ (ipv), བསྒྱུརད་བ་</br>
འགྱུར་བ་ → n.v.fut.n.v.pres.gyur (ipv)</br>
འགྱུརད་བ་ → n.v.pres.gyur - alternative form སྒྱུར་བ་ (ipv)</br>
སྒྱུརད་ → n.v.ipv.gyur</br>
གྲགས་ (4) → v.invar.grags - “to be known as”</br>
ཆོག་ (2) → v.invar.chog - “to be suitable, to be able, to be permitted, to be allowed”</br>
ཆོག་པ་ → n.v.invar.chog - “to be suitable, to be able, to be permitted, to be allowed”</br>
ཐག་ (114) → v.invar.thag - if preceded by verb + མ་/neg: “as soon as” (otherwise it is a noun
“distance”, “cloth”)</br>
ཐག་པ་ (5) → n.v.invar.thag - if preceded by verb + མ་/neg: “as soon as”</br>
ཐང་ (4) → v.invar.thang “to be able”</br>
ཐང་པ་ → n.v.invar.thang “to be able”</br>
བཏུབ་ → v.invar.thub1 “to be able, to make able” - argument structure [Abs. Obl.]</br>
ཐུབ་ → v.pres.thub1 - argument structure [Abs. Obl.]</br>
བཏུབས་ → v.past.thub1 - argument structure [Abs. Obl.]</br>
བཏུབ་པ་ → n.v.invar.thub1 “to be able, to make able” - argument structure [Abs. Obl.]</br>
ཐུབ་པ་ → n.v.pres.thub1 - argument structure [Abs. Obl.]</br>
བཏུབས་པ་ → n.v.past.thub1 - argument structure [Abs. Obl.]</br>
ཐུབ་ → v.invar.thub2 “to be able, capable of” - argument structure [Erg. Abs.] note that this</br>
form can be also the present of thub1: even if the ergative is left out, look at oblique
preceding ཐུབ་, if there is an oblique immediately preceding the verb then is most likely thub1.
Any possible locative case will be at the beginning of the sentence.</br>
ཐུབ་པ་ → n.v.invar.thub2 “to be able, capable of” - argument structure [Erg. Abs.]. See note
above for disambiguating ཐུབ་.</br>
དཀའ་ → v.invar.dka “to be difficult”</br>
དཀའ་བ་ (4) → n.v.invar.dka “to be difficult”</br>
དགོས་ (148) → v.invar.dgos - “to need” note that དགོས་ may perhaps be related as the future
stem of འཁོ་ (Zeisler 2004: 454 n. 138)</br>
དགོས་ (95) → v.invar.dgos “to need”</br>
དགོས་པ་ (79) → n.v.invar.dgos - alternative form དགོས་བ་ “ to need”</br>
དྲ་ → v.fut.dra1 - argument structure is [Erg. Abs.]</br>
དྲས་ → v.past.dra1 - argument structure is [Erg. Abs.]</br>
དྲོས་ → v.ipv.dra1 - argument structure is [Erg. Abs.]</br>
དྲ་བ་ → n.v.fut.dra1 - argument structure is [Erg. Abs.]</br>
དྲས་པ་ → n.v.past.dra1 - argument structure is [Erg. Abs.]</br>
དྲོས་པ་ → n.v.ipv.dra1 - argument structure is [Erg. Abs.]</br>
འདྲ་ → v.pres.dra1 “to cut, to clip”- argument structure is [Erg. Abs.]</br>
འདྲ་བ་ → n.v.invar.dra1 “to cut, to clip” [Erg. Abs.]</br>
འདྲ་ (12) → v.invar.dra2 “to be similar” - argument structure [Abs. Ass.]</br>
འདྲ་བ་ → n.v.invar.dra2 - if preceded by a n.v.*; argument structure is [Abs. Ass.]</br>
དྲག་ (3) → v.invar.drag “to recover from illness”</br>
དྲགས་ → v.past.drag</br>
དྲག་པ་ → n.v.invar.drag “to recover from illness”</br>
དྲག་པ་ → n.v.past.drag</br>
ནུས་ (97) → v.invar.nus - when preceded by verb or verbal noun + མ་/neg: “to be able” - in
other cases, it is the past (or ipv) of ནུ་ and treated as all other verbs</br>
ནུས་པ་ (53) → n.v.nus.invar - alternative form ནུས་བ་; - when preceded by verb or verbal noun +</br>
མ་/neg: “to be able” - in other cases, this form is the past (or ipv) of ནུ་ and treated as all other
'non-special' verbs</br>
ཕོད་ → v.past.phod “to handle, to cope with” (ipv)</br>
ཕོད་པ་ → n.v.past.phod “to handle, to cope with” (ipv)</br>
འཕོད་ (14) → v.fut.v.pres.phod “to handle, to cope with”</br>
འཕོད་པ་ (11) → n.v.fut.n.v.pres.phod “to handle, to cope with”</br>
བཙལ་ → v.fut.v.past.tshal1 - the argument structure for tshal1 is [Erg. Abs.]</br>
བཙལད་ → v.past.tshal1 - the argument structure for tshal1 is [Erg. Abs.]</br>
འཚལ་/v.fut.v.pres.tshal1 ནོ /cv.fin: འཚལ་ (9) → v.fut.v.pres.tshal1 - “to greet, to prostrate for</br>
respect; (when prefixed by ཕྱག་ ) to pay respect” - because of the lack of sandhi in the final
particle; the argument structure for tshal1 is [Erg. Abs.]</br>
འཚལ་/v.past.tshal1 དོ /cv.fin: འཚལ་ → v.past.tshal1 - because of the sandhi in the final particle
starting with d-; the argument structure for tshal1 is [Erg. Abs.]</br>
འཚལ་བ་ → n.v.fut.n.v.pres.tshal1 “to greet, to prostrate for respect; (when prefixed by ཕྱག་ ) to
pay respect” - the argument structure for tshal1 is [Erg. Abs.]</br>
བཙལ་བ་ → n.v.fut.n.v.past.tshal1 - the argument structure for tshal1 is [Erg. Abs.]</br>
བཙལད་བ་ → n.v.past.tshal1 - the argument structure for tshal1 is [Erg. Abs.]</br>
འཚལད་བ་ → n.v.past.tshal1 - the argument structure for tshal1 is [Erg. Abs.]</br>
འཚལ་ → v.invar.tshal2 “to beg, to desire, to ask” - the argument structure for tshal2 is [Abs.
Obl.]</br>
འཚལ་བ་ → n.v.invar.tshal2 “to beg, to desire, to ask” - the argument structure for tshal2 is [Abs.
Obl.]</br>
བཞག་ → v.past.bzhag “to assign, to establish, to designate”</br>
བཞག་པ་ → n.v.past.bzhag “to assign, to establish, to designate”</br>
བྱེད་ (105) → v.pres.byed “to do”</br>
བྱ་ → v.fut.byed</br>
བྱས་ → v.past.byed</br>
བྱོས་ → v.ipv.byed - alternative form བྱོ་</br>
བྱ་བ་ → n.v.fut.byed</br>
བྱས་པ་ → n.v.past.byed</br>
བྱོ་བ་ → n.v.ipv.byed - alternative form བྱོས་པ་</br>
འབྱུང་ (168) → v.fut.v.pres.byung (ipv) “to arise, to emerge, to appear”</br>
འབྱུང་བ་ → n.v.fut.n.v.pres.byung (ipv) “to arise, to emerge, to appear”</br>
བྱུང་ → v.past.byung (ipv)</br>
བྱུང་བ་ → n.v.past.byung (ipv)</br>
མཆི་ (4) → v.fut.v.pres.mchi “to go”</br>
མཆིས་ → v.past.mchi → the argument structure for mchi is [Obl. Abs.]</br>
མཆི་བ་ → n.v.fut.n.v.pres.mchi “to go” → the argument structure for mchi is [Obl. Abs.]</br>
མཆིས་པ་ → n.v.past.mchi → the argument structure for mchi is [Obl. Abs.]</br>
མཆིས་ → v.invar.mchis “to be, to exist” → the argument structure for mchis [Abs. Obl.]</br>
མཆིས་པ་ → n.v.invar.mchis “to be, to exist” → the argument structure for mchis [Abs. Obl.]</br>
མཛད་ (32) → v.invar.mdzad “to do” (honorific)</br>
མཛད་པ་ → n.v.invar.mdzad</br>
མཛོད་པ་ → n.v.ipv.mdzad</br>
མིན་/v.fut.v.pres.min ནོ /cv.fin: མིན་ (12) → v.fut.v.pres.min - because of the lack of sandhi in the
final particle</br>
མིནད་ → v.past.min</br>
མིན་/v.past.min དོ /cv.fin: མིན་ → v.past.min - because of the sandhi in the final particle starting
with d-</br>
མིན་པ་ → n.v.fut.n.v.pres.min</br>
མིནད་པ་ → n.v.past.min</br>
མེད་ (19) → v.invar.med “to not be, exist” - note that some dictionaries will give two different
argument structures, but since they contain the same cases just in a different order this is
more likely to be due to focus in copular and existential clauses than that there are really two
homophonous verbs med.</br>
མེད་པ་ → n.v.invar.med “to not be, exist, to be without”</br>
མོད་ (120) → v.invar.mod - when preceded by a verb: “indeed, although, but, though”</br>
མོད་པ་ → n.v.invar.mod - when preceded by a verb: “indeed, although, but, though”</br>
མྱོང་ (6) → v.pres.myong1 “to taste, to perceive” - this form is always transitive with [Erg. Abs.]
arguments</br>
མྱང་ → v.fut.myong1</br>
མྱངས་ → v.past.myong1 (ipv)</br>
མྱོང་བ་ → n.v.pres.myong1 “to taste, to perceive” - this form is always transitive with [Erg. Abs.]
arguments</br>
མྱང་བ་ → n.v.fut.myong1</br>
མྱངས་པ་ → n.v.past.myong1</br>
མྱོང་ → v.invar.myong2 “to sense, to feel” - v.invar.myong2 is always intransitive</br>
མྱོང་བ་ → n.v.invar.myong2 “to sense, to feel” - n.v.invar.myong2 is always intransitive</br>
འགྲོ་ (39) → v.fut.v.pres.gro “to go”</br>
སོང་ → v.past.gro - alternative forms ཕྱིན་, ཕྱིནད་</br>
འགྲོ་བ་ → n.v.fut.n.v.pres.gro “to go</br>
སོང་བ་ → n.v.past.gro - alternative forms ཕྱིན་པ་, ཕྱིནད་པ་</br>
འདུག་ (304) → v.invar.dug “is, there is, to exist”</br>
འདུག་པ་ → n.v.invar.dug “is, there is, to exist”</br>
འདོད་ (49) → v.invar.dod “to wish, to want”</br>
འདོད་པ་ → n.v.invar.dod “to wish, to want”</br>
འོང་ (17) → v.fut.v.pres.ong “to come”</br>
འོང་བ་ → n.v.invar.ong “to come”</br>
འོངས་ → v.ong.past (ipv)</br>
འོངས་པ་ → n.v.past.ong</br>
ཤོག་/v.ipv.ong ཅིག་/cv.ipv: note that ཤོག་ is generally regarded as the imperative of འོང་ “ to come”,
but historically the imperative of གཤེགས་ “ to go away, to leave”; when shog is not followed by
cv.ipv it can be v.invar.shog or v.ipv.ong. This needs to be manually checked.</br>
ཡིན་/v.fut.v.pres.yin ནོ /cv.fin: ཡིན་ (209) → v.fut.v.pres.yin - because of the lack of sandhi in the
final particle “to be”</br>
ཡིན་/v.past.yin དོ /cv.fin: ཡིན་ → v.past.yin - because of the sandhi in the final particle starting
with d-</br>
ཡིནད་ → v.past.yin</br>
ཡིན་པ་ (41) → n.v.fut.n.v.pres.yin - alternative form ཡིན་བ་ “ to be”</br>
ཡིནད་པ་ → n.v.past.yin</br>
ཡིན་ལུགས་ → n.v.fut.n.v.pres.yinlugs “as it is”</br>
ཡོང་ (41) → v.invar.yong “will, to come”</br>
ཡོང་བ་ → n.v.invar.yong “will, to come”</br>
ཡོད་ (98) → v.invar.yod “to exist, to have”</br>
ཡོད་ → v.invar.yod “to have, to exist”</br>
ཡོད་པ་ → n.v.invar.yod “to have, to exist”</br>
རན་ (7) v.invar.ran “to be the time or right moment, to be proper”</br>
རན་/v.past.ran དོ /cv.fin: རན་ → v.past.ran - because of the sandhi in the final particle starting</br>
with d- ; - རན་/v.past is attested as a past form - this is why རན་ is v.invar.ran and not</br>
v.fut.v.pres.ran as done for verbs like yin/yind and min/mind.</br>
རནད་ → v.past.ran (ipv)</br>
རན་པ་ (2) → n.v.invar.ran “to be the time or right moment, to be proper”</br>
རནད་པ་ → n.v.past.ran (ipv)</br>
རེད་ → v.invar.red “to be”</br>
རེད་བ་ → n.v.invar.red “to be” - alternative form རེད་པ་</br>
རྒྱུ་ → v.invar.rgyu “to cause; [following a verb, indicates]: to be done”</br>
རྒྱུ་བ་ → n.v.invar.rgyu to cause; [following a verb, indicates]: to be done”</br>
ལགས་ (116) → v.invar.lags “to be” (honorific)</br>
ལགས་པ་ (18) → n.v.invar.lags “to be” (honorific)</br>
ཤེས་ (23) → v.invar.shes “to be able, to be possible, can”</br>
ཤེས་པ་ (35) → n.v.invar.shes “to be able, to be possible, can”</br>
ཤོག་ (56) → v.invar.shog “may it be” - particle indicating the optative</br>
ཤོག་/v.ipv.ong ཅིག་/cv.ipv: note that ཤོག་ is generally regarded as the imperative of འོང་ “ to come”,
but historically the imperative of གཤེགས་ “ to go away, to leave”; when shog is not followed by
cv.ipv it can be v.invar.shog or v.ipv.ong. This needs to be manually checked.</br>
ཤོག་པ་ → n.v.invar.shog “may it be”</br>
སྲིད་ (14) → v.invar.srid “to be possible, to be able”</br>