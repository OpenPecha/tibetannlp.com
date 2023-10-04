# ངོ་སྤྲོད།

Our general philosophy with respect to any form of annotation is that it should be descriptive
rather than based on analyses to facilitate future research in any area. 

ང་ཚོའི་སྤྱི་བའི་ལྟ་གྲུབ་ནི། དབྱེ་ཞིབ་མཆན་འགྲེལ་དེ་དག་གིས། མ་འོངས་པར་ཡིག་ཆ་ཕྱོགས་གང་ཐད་ནས་ཞིབ་འཇུག་བྱེད་དགོས་རུང་། ཡིག་ཆའི་ཆ་ཤས་གང་ཡང་། འགྲེལ་བརྗོད་ཀྱི་རང་བཞིན་ལྡན་པ་དང་། གོ་བདེ་བའི་ངང་ཚུལ་ཡོད་པའི་མཐུན་རྐྱེན་སྟབས་བདེ་ཞིག་བསྐྲུན་རྒྱུ་དེའོ།།  

This general introduction provides examples of our general annotation principles to make annotators and
correctors familiar with our general annotation protocols and to provide background
regarding annotation decisions. It also gives detailed information about how to deal with
verbs in particular. Plenty of examples, some with, some without tags (depending on which
source they're from) are given throughout. They are numbered per section.

དེ་ལྟར་སྤྱི་བའི་ངོ་སྤྲོད་འདིས་ནི། མཆན་ཡིག་པ་དང་། ཞུ་དག་པ་རྣམ་པ་ཚོ་ལ་ང་ཚོའི་དབྱེ་ཞིབ་མཆན་འགྲེལ་གྱི་ངོ་བོ་ཤེས་སུ་འཇུག་རྒྱུ་དང་། ང་ཚོས་དབྱེ་ཞིབ་མཆན་འགྲེལ་གྱི་སྟངས་འཛིན་ཇི་ལྟར་བྱེད་མིན་གྱི་རིག་པ་གསལ་བཤད་བྱ་རྒྱུ་དང་། དམིགས་བསལ་བྱ་ཚིག་ཞིག་གི་ཐོག་ལ་ཡོང་ཚེ། ཡིག་ཆའི་རིགས་འདྲ་མིན་སྣ་ཚོགས་བརྒྱུད་ནས་དཔེར་བརྗོད་མང་དག་ཞིག་མཐོང་ཆོས་སུ་བསྐྲུན་རྒྱུའོ། ། དཔེར་བརྗོད་རེ་རེ་ནི་དབྱེ་ཞིབ་ཀྱི་མཆན་འགྲེལ་གྱི་སྡེ་ཚན་དང་བསྟུན་ནས་གྲངས་སུ་བཀོད་ཡོད། 

For segmentation we split words as much as possible and we create sentence boundaries
between main clauses and with direct speech. See section on Sentence Segmentation. 

ང་ཚོས་གང་ཐུབ་ཅི་ཐུབ་ཀྱི་བརྗོད་པའི་རིགས་རྣམས་བརྗོད་པའི་ཚན་པའམ་དུམ་བུར་བཅད་ཅིང་། བརྗོད་པའི་ནང་གི་བརྗོད་པའི་གཙོ་བོ་དང་། ཐད་ཀའི་བརྗོད་ཚིག་གཉིས་སོ་སོར་ཕྱེ་ཡོད། ཁྱེད་ཀྱིས་བརྗོད་པའི་ཚན་པ་རྣམས་དབྱེ་ཞིབ་མཆན་འགྲེལ་གྱི་སྡེ་ཚན་དུ་གཟིགས་ཆོག

For POS tagging, we apply morphological information in a conservative manner to make sure
that we can capture the origin of constructions that have changed over time. 

བརྗོད་པའི་དབྱེ་ཞིབ་མཆན་འགྲེལ་དུ།  ཡུན་རིང་པོ་ནས་འགྱུར་བ་ཕྱིན་པའི་སྐད་བརྡའི་ཁུངས་མ་རྣམས་ཏན་ཏན་རྙེད་སོན་ཡོང་བའི་ཆེད། ང་ཚོས་སྐད་བརྡའི་གནས་ཚུལ་ཞིག་ཕྲ་སྲུང་སྐྱོབ་ཀྱི་ངོ་བོར་བེད་སྤྱོད་བཏང་ཡོད།

For example,
complex postpositions, as shown here are split and all elements are tagged separately:

དཔེར་བརྗོད་ལྟར་ན། འདིར་དཀའ་བའི་ཚིག་ཕྲད། གཤམ་དུ་བསྟན་པ་བཞིན། བརྗོད་པའི་ཆ་རྐྱེན་རིགས་སོ་སོར་བཅད་གཏུབ་ཀྱིས་དབྱེ་བ་ཕྱེ་ཡོད། 


 སྒང་ལ་ “ on top” (see n.rel section)</br>
བུ་ n.count</br>
མཚམས་ n.count</br>
ཀྱི་ case.gen</br>
སྒང་ n.rel</br>
ལ་ case.all</br>
ལྟད་མོ་ n.count</br>
ལ་ case.all</br>
གཏོང་མཁན་ n.v.pres</br>
ཁྱོད་ p.pers</br>
མིན་པ་ n.v.fut.n.v.pres.min</br>
སུ་ p.interrog</br>
མང་ v.pres</br>
། pun