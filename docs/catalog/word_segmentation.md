Our main protocol is that case markers and converbs are split from the preceding noun
phrases. In general, we split as much as possible to create more insight into the internal
(and historical) structure. In what follows, we first present examples of these case markers
(tagged "case.X") and converbs (tagged "cv.X"), followed by examples of personal names,
titles and compounds (see also section on n.count). All data are taken from our training data
or other corpora.

### 2.1 Case markers & converb segmentation
(1)</br>
དེ d.dem</br>
ར་ case.term</br>
ང p.pers</br>
ས་ case.agn</br>
ཀྱང་ cl.focus</br>
བླ་མ n.count</br>
འི་ case.gen</br>
བཀའ་ n.count

(2)</br>
རྩ་རི་ n.prop</br>
འབྲེལ་ v.past.v.pres</br>
ནས་ cv.ela</br>
ཡོད་ v.invar.yod</br>
དེ cv.sem</br>
། punc

### 2.2 Personal Names and Titles

With personal names, which are tagged as n.prop ('proper noun'), we split as much as
possible to create more insight into the internal structure of the sentence. The same goes for
commonly used titles, as shown in (3):

(3) རྒྱལ་པོ་ཆེན་པོ་ → རྒྱལ་པོ་ /n.count ཆེན་པོ་ /adj

(4)</br>
དྲིན་ཅན་ adj</br>
མར་པ་ n.prop</br>
ལོ་ཙྪ་བ n.count

(5)</br>
ལྷོ་ n.count</br>
ལ་ཡག་ n.prop</br>
གི་ case.gen</br>
བ་རང་ n.prop</br>
ལྦ་ཅན་ n.prop</br>
རྣམས་ d.plural</br>
ལགས་ v.invar.lags</br>
སོ cv.fin</br>
། punc

(6)</br>
གཙང་ n.prop</br>
སྒྱེར་ཕུ n.prop</br>
འི་ case.gen</br>
ཀློག་སྐྱ་ n.prop</br>
ཆེན་པོ adj

### 2.3 Compound nouns

In general, when two nouns occur in succession they are understood as a compound. Since
our main principle is to split meaningful segments as much as possible, we have very few
compounds. There are a few obvious compounds that we do not split, however, e.g. the
dvandva compound ཕ་མ་ 'parents' is treated as one noun rather than two ( ཕ་ 'father' and མ་
'mother') and the tatpuruṣa compound ཁྱིམ་བདག་ 'householder' is likewise treated as one noun
rather than two ( ཁྱིམ་ 'home' and བདག་ 'lord'). When an adjective precedes its head this is also
treated as a compound. Thus, because དུག་བཙན་པོ་ would be the expected order for 'mighty
poison', we treat བཙན་དུག་ 'mighty poison' as a single word. Similarly, གང་ན་བ་ 'whereabouts' and
བདག་གི་བ་ 'that which is mine' are single words.


### 2.4 Complex & light verb constructions

We do not annotate light-verb constructions but we introduce a list of special verbs and
verbal nouns that will help researchers to identify such potential constructions later.

(7)</br>
སྐྱེས་བུ་ n.count</br>
དེ་ d.dem</br>
ལ་ case.all</br>
ཕྱག་ n.count</br>
འཚལ་ v.fut.v.pres.tshal1</br>
ལོ cv.fin</br>
We furthermore split complex verb constructions as much as possible:

(8)</br>
རིན་ཆེན་ n.count</br>
བདུན་ num.card</br>
གྱིས་ case.agn</br>
ཡོངས་ d.plural</br>
སུ་ case.term</br>
བཀང་ v.past</br>
བྱས་ v.past.byed</br>
ནས cv.ela</br>
། punc

(9)</br>
གསེར་ n.mass</br>
ལས་ case.abl</br>
བརྡུངས་ v.past</br>
བྱས་ v.past.byed</br>
འདྲ་ v.invar.dra2</br>
ཞིང་ cv.impf</br>
པངྨ་ n.count</br>
རྒྱས་པ་ n.v.past</br>
བཞིན n.rel</br>
། punc

(10)</br>
དོན་ n.count</br>
རྣམས་ d.plural</br>
གཉིས་ num.card</br>
ལྡན་ v.invar</br>
གཟུང་ v.fut</br>
སླ་ v.pres</br>
དང་ cv.ass