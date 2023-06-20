[<-back](en/pos/pos_tags.md)

<!-- tabs:start -->
#### **ADJ - Adjectives**

There is only one tag for adjectives: adj. We do not distinguish different types of adjectives or different grades of adjectives. Note that in general, verbs derived from adjectives are tagged (n.)v.invar unless they have -s, in which case they are (n.)v.past (see section on verbs).

adj - adjectives</br>
Adjectives are notoriously difficult to define in any Sino-Tibetan language. For our annotation purposes, we give the POS tag adj to those words that can occur in attributive position and are not verbal nouns. Morphologically, they are almost always multisyllabic. The paragon of adjectives are those that in -པོ་ , -མོ་ , -པ་, -མ་, -ཅན་, -ལྡན་, and -མེད་. Etymologically ཅན་, - ལྡན་ 'with', and - མེད་ 'without' are verbs, but when they occur in forms that are functioning nominally, they cannot be analysed as verbs. Therefore, we treat them together with the preceding syllable as an adjective. Although words such as ནག་ 'black', གསར་ 'new', and ཆེ་ 'big' are frequently treated like adjectives for pedagogical purposes, a single syllable in predicate position before verbal suffixes is tagged as a verb 'to be black', 'to be new', etc. These words may appear to occur attributively, but we see this as the formation of compounds. The compound བློན་ཆེན་ 'prime minister' contrasts beautifully with the noun and adjective pair བློན་པོ་ ཆེན་པོ་ 'great minister', etc.).

There are various cases where homophonous verbs and adjectives may cause ambiguity, making it difficult to decide how to annotate them. We adhere to the following protocols for those cases. First, verbs derived from adjectives are tagged (n.)v.invar, as shown in (1):

(1)</br>
རབ་ adv.intense</br>
ཏུ་ cv.term</br>
འབྱུང་བ n.v.fut.n.v.pres</br>
ར་ case.term</br>
དཀ v.invar → this is tagged as v.invar and not as adj</br>
འོ cv.fin</br>
། punc

Second, sometimes, nominalised forms are actually derived twice, i.e. first from adj → verb and then from verb → verbal noun. An example of this is seen here where ཆུང་བ་ can only mean 'the [time of] being small' and not 'the small person'. In those cases, they are tagged as n.v.invar, as shown in (2):

(2)</br>
ཆུང་བ n.v.invar → this is left as a double derivation n.v.invar</br>
འི་ case.gen</br>
དུས་ n.rel</br>
སུ་ case.term</br>
ལེན་དྲན་གྲི་ལེནྡྲ་ n.prop</br>
ན་ case.loc</br>
སྒྲོལ་མ n.count</br>
འི་ case.gen</br>
རྟེན་ n.count</br>
བཞུགས་པ n.v.invar</br>
འི་ case.gen</br>
ཕྱག་ n.count</br>
ཏུ case.term</br>
། punc

A similar example is found in (3): 'because his discipline was small, his accomplishments also were few'. Note that the second verbal noun in this example is derived from the verb 'to accomplish', so even though the nominalised form functions as a noun, it will still have the n.v. tag. The issue of n.v. versus n.count tag only arises with adjectives like 'small' → 'to be small' (=verbal) vs 'small person' (=nominal). More examples are given in (4-6) below.

(3)</br>
བརྩོན་འགྲུས་ n.count</br>
ཆུང་བ n.v.invar 'to be small'</br>
ས་ case.agn</br>
གྲུབ་པ n.v.past 'accomplishment'</br>
འང་ cl.focus</br>
ཉུང་བ n.v.past.n.v.pres 'to be small/few'</br>
ར་ case.term</br>
འགྱུར v.fut.v.pres</br>
། punc

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

#### **རྒྱན་ཚིག**

༄༅། །ཕྱི་ལོ་ ༢༠༢༣ ཟླ་ ༦ ཚེས་ ༡༥ ཉིན་སྤྱི་ནོར་༸གོང་ས་༸སྐྱབས་མགོན་ཆེན་པོ་མཆོག་གིས་རྒྱ་གར་གྱི་རྒྱལ་ས་ལྡི་ལིར་རྟེན་གཞི་བྱས་པའི་༸གོང་ས་ཏཱ་ལའི་བླ་མའི་ཀུན་ཁྱབ་འགན་ཁུར་ཐེབས་རྩས་(FURHHDL)མཐུན་འགྱུར་འོག་རྒྱ་གར་རྒྱལ་ཡོངས་མཐོ་རིམ་སློབ་གྲྭ་ཁག་ཏུ་སློབ་གཉེར་གནང་བཞིན་པའི་སློབ་ཕྲུག་ ༢༤ ལ་མཇལ་ཁ་དང་བཀའ་སློབ་སྩལ་ཡོད་པ་རེད།

<!-- tabs:end -->
