

<!-- tabs:start -->

#### **POS Tagging of Verbs**


When it comes to verbs, we base our tense-aspect-mood distinctions on morphological form
only, i.e. if there is a morphological element that indicates that a verb is past, future or
present tense etc. then the verb will be tagged as v.past, v.fut and v.pres respectively. If
there is no such morphological information, we don't attempt to analyse and interpret it by
putting this information in the tag, but instead, use the more neutral invariant form.
Imperative forms that are morphologically distinct from the tense forms are tagged as v.ipv.

5(2) “to add together, to combine, to add”</br>
སྡོམ་ v.pres</br>
བསྡོམས་ v.past</br>
བསྡོམ་ v.fut</br>
སྡོམས་ v.ipv

However, if the morphology is invariant in all these tenses + the imperative, then the verb will
be tagged as v.invar, as illustrated with the verb ནུད་ 'to retreat, to withdraw':

(3) “to retreat, to withdraw”</br>
ནུད་ v.invar (so this can be present, future, past or imperative)</br>
It is possible that another form of the same verb is available, in which case that form will</br>
receive the appropriate tag, e.g.</br>

(4) “to manage, provide for”</br>
གཉེར་/v.invar</br>
གཉེརད་/v.past</br>

There are also cases where the morphology is invariant except for the imperative form:</br>

(5) “to smith”</br>
མཁར་ v.invar (so this can be all tense, i.e. present, future or past)</br>
མཁོར་ v.ipv</br>
Alternatively, a verb could have the same form for the future and present, but a different form
for the past tense, in which case the future/present forms will be tagged as v.fut.v.pres. The
past-tense form will then be tagged as v.past. 

Again imperative forms that are morphologically distinct from the tense forms are tagged as v.ipv.

(6) “to die”</br>
འགུམ་ v.fut.v.pres</br>
གུམ་ v.past</br>
གུམས་ v.ipv</br>

Similarly, there are verbs that have homophonous forms in the future and the past (and
optionally the imperative), which will result in a v.fut.v.past tag. 

This also goes for verbs that share present, future and imperatives.
(7) “to decline, to diminish”</br>
འགུད་ v.pres</br>
གུད་ v.fut.v.past</br>

(8) གསུང/v.fut.v.pres
6Note that this means that the imperative form is NOT tagged separately for those verbs and
can only be derived from the context, e.g. through following imperative markers:

(9)
གུད་/v.fut.v.past ཤིག་/cv.ipv</br>
གསུང/v.fut.v.pres ཤིག་/cv.ipv</br>

There are also verbs that have homophonous forms in the future, past and present (and
optionally the imperative), with also an alternative distinct form for the past.

(10) “to recover from illness”</br>
Present: དྲག་ LZ, DK, DS, TC.</br>
Past: དྲགས་ LZ. དྲག་ DK, [DS], TC.</br>
Future: དྲག་ LZ, DK, [DS], TC.</br>
Imperative: དྲག་ LZ, DK. – TC.</br>

In those cases we indicate with (ipv) that the form also appears in the imperative, but it will
result in the following tags:

(11)
དྲག་ → v.invar</br>
དྲགས་ → v.past</br>


#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། 

<!-- tabs:end -->

### Past tense with da-drag
<!-- tabs:start -->

#### **Past tense with da-drag**

In cases where the past tense is covertly marked through sandhi rules following da-drags,
we still tag the verb as v.past. As a consequence, the verbs that don't have this covert past-
tense marking will be tagged as v.fut.v.pres instead of v.invar.

(13) “to dispose of the dead”</br>
དུརད་/v.past</br>
དུར་/v.past དོ /cv.fin → v.past because of the sandhi in the final particle starting with d-
དུར་/v.fut.v.pres རོ /cv.fin → v.fut.v.pres because of the lack of sandhi in the final particle

With frequent special verbs like yin this works in the same way:

(14) “to be”</br>
ཡིནད་/v.past.yin</br>
ཡིན་/v.past.yin དོ /cv.fin → v.past because of the sandhi in the final particle starting with d-
ཡིན་/v.fut.v.pres.yin ནོ /cv.fin → v.fut.v.pres because of the lack of sandhi in the final particle

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། 

<!-- tabs:end -->

### Special Verbs
<!-- tabs:start -->

#### **Special Verbs**

Some verbs that exhibit special behaviour (e.g. they can behave like copulas or auxiliaries,
etc.) get an individual verbal tag. This effectively means these verbs are lemmatised, making
it easy to do research on them. Very often, these are verbs that change into some sort of
evidential or epistemic marker in any modern variety. Note that common light verbs are not
necessarily specified/tagged separately in this way because no one really has done enough
7research on light verbs to make a good list. The choice of which verbs to include is based on
what is known about the historical development of the verb, any other linguistic information
that may set them apart, and, finally, frequency counts from corpora. Some examples are
shown in (15):

(15)
a.རེད་ → v.invar.red “to be”</br>
b.རེད་བ་ → n.v.invar.red “to be”</br>
c.ཡོད་ → v.invar.yod “to exist, to have”</br>
d.ཡོད་པ་ → n.v.invar.yod “to exist, to have”</br>

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། 

<!-- tabs:end -->


### Homophonous 

<!-- tabs:start -->

#### **Homophonous Special Verbs**

There are cases where the forms of the verbs themselves are homophonous: if the verbs
have two different argument structures, then we have two separate verbs and we use two
separate tags verb1 "V1" and verb2 "V2":

(16) myong1 “to taste to perceive”, myong2 "to feel, to sense”
a. མྱོང་ → v.pres.myong1 - always transitive with [Erg. Abs.]</br>
b. མྱངས་ → v.past.myong1</br>
c. མྱང་ → v.fut.myong1</br>
d. མྱོང་ → v.invar.myong2 - always intransitive</br>

If Hill’s dictionary doesn’t give two different argument structures AND the Visual Dictionary of
Tibetan Verbs doesn’t give two different argument structures, then we don’t consider them to
be two separate verbs. We also do not consider མེད་ to be have two separate verbs (unlike
the dictionaries).

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད། 

<!-- tabs:end -->


### R&C

<!-- tabs:start -->

#### **Resultatives & Causatives**

If a special verb V1 is resultative/causative of a verb V2 we use the same special verb tag
for both.

(17)
a. འགྱུར་ → v.fut.v.pres.gyur (ipv)</br>
   བསྒྱུར་ → v.fut.v.past</br>
   སྒྱུར་ → v.pres.gyur (ipv) - alternative form འགྱུརད་</br>
   གྱུར་ → v.past.gyur - alternative forms གྱུརད་ (ipv); བསྒྱུརད་</br>
   སྒྱུརད་ → v.ipv.gyur</br>

b. འགྱུར་བ་ → n.v.fut.n.v.pres.gyur (ipv)</br>
   བསྒྱུར་བ་ → n.v.fut.n.v.past</br>
   སྒྱུར་བ་ → n.v.pres.gyur (ipv) - alternative form འགྱུརད་བ་</br>
   གྱུར་བ་ → n.v.past.gyur གྱུརད་བ་ (ipv) - alternative form བསྒྱུརད་བ་</br>
   སྒྱུརད་བ་ → n.v.ipv.gyur</br>

c. འགྱུར་ is the resultative of སྒྱུར་</br>
We added སྒྱུར་ to our special verb list and tag all its forms with the same special tag “gyur” we
8used for འགྱུར་ (see above).

There are cases where a verb V1 is in fact the causative of a verb V2. Causative forms are
treated as separate forms like any other verb that has two different argument structures.
        
(18) སྒྲིབ་ “ to obscure, to cover”</br>
        Present: སྒྲིབ་ v.pres</br>
        Past: བསྒྲིབས་ v.past</br>
        Future: བསྒྲིབ་ v.invar</br>
        Imperative: སྒྲིབས་ v.ipv</br>
        Causative of: འགྲིབ་ "to grow dim, to get dark"</br>
        Present/Future/Past: འགྲིབ་ v.invar</br>
        Past: གྲིབ་ འགྲིབས་ v.past</br>

#### **བོད་ཡིག**

དེ་ཡང་མགོན་པོ་གང་ཉིད་མཆོག་གིས་དད་ལྡན་མི་མང་བརྒྱ་ཕྲག་བརྒལ་བར་མཇལ་ཁ་སྩལ་རྗེས་ཕོ་བྲང་མཇལ་འཕྲད་ཁང་དུ་ཆེད་ཕེབས་ཀྱིས་རྒྱ་གར་གྱི་ནང་པའི་རྗེས་འཇུག་པ་བརྒྱ་ཕྲག་ཙམ་ལ་བཀའ་སློབ་སྩལ་དོན། </br>
དེ་རིང་འདིར་རྒྱ་གར་གྱི་ས་ཁུལ་མང་པོ་ཞིག་ནས་ནང་ཆོས་ལ་དོ་སྣང་ཡོད་མཁན་ཁྱོད་ཚོ་རུབ་རུབ་བྱས་ཏེ་ངོས་རང་ཐུག་པའི་གོ་སྐབས་བྱུང་བ་ལ་ཧ་ཅང་དགའ་བོ་བྱུང་། ངོས་རང་ནང་པའི་དགེ་སློང་ཞིག་རེད། ཆོས་ལུགས་ཚང་མར་གུས་ཞབས་བྱེད་ཀྱི་ཡོད། </br> ཆོས་ལུགས་ཚང་མར་ལྟ་གྲུབ་མི་འདྲ་བ་ཡོད་ཀྱང་སེམས་ཀྱི་ཞི་བདེ་དགོས་པ་དང་བྱམས་བརྩེ་དགོས་པ་ཚང་མས་གསུང་གི་ཡོད།         

<!-- tabs:end -->




