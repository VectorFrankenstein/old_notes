- There are 54 families that are significant at heterosporous nodes
	- ```
	  OG0000019
	  OG0000022
	  OG0000033
	  OG0000036
	  OG0000050
	  OG0000051
	  OG0000064
	  OG0000068
	  OG0000080
	  OG0000085
	  OG0000087
	  OG0000099
	  OG0000104
	  OG0000108
	  OG0000110
	  OG0000112
	  OG0000126
	  OG0000133
	  OG0000134
	  OG0000145
	  OG0000157
	  OG0000160
	  OG0000161
	  OG0000163
	  OG0000164
	  OG0000171
	  OG0000177
	  OG0000183
	  OG0000205
	  OG0000218
	  OG0000221
	  OG0000233
	  OG0000243
	  OG0000258
	  OG0000287
	  OG0000302
	  OG0000304
	  OG0000308
	  OG0000326
	  OG0000330
	  OG0000333
	  OG0000368
	  OG0000399
	  OG0000451
	  OG0000492
	  OG0000634
	  OG0000717
	  OG0000857
	  OG0000860
	  OG0001114
	  OG0001186
	  OG0001616
	  OG0001845
	  OG0002601
	  ```
	- We have all but only `OG0002601` has a treefile.
- When Paul made the "indication" data table, he used wide format that looked as follows
  
  |Species name|Type one|Type two |Type_n|
  |--|--|--|--|
  |one|1|null|null|
  |two|null|1|null|
  
  this I melted to the following format
  
  |Species_name|clade|Spory_type|
  |--|--|--|
  |one|clade data|spory type|
  |n|clade_data|spory type|
- This made a file that I named `species_classification.tsv` with sum `457563ab4deedf64119f431f20a23a5d41dab7836f683761c0dda5a3e1648c03c14663271079335b61f24d0583485667254e5839a2f21b32affecb6e309911d9`
- All families turned into trees, except the following ones (owing to misalignment in pal2nal):
	- OG0000033
	- OG0000160
	- OG0000634
-
- # Cafe data
- ## Onotologies
	- Even though `OG0000233` was shared between Angiosperms and heterosporous ferns, it did not have any Arabidopsis genes and thus made getting any information about ontologies impossible.
-
- # Busted Ph
- OG0019140 did not have any homosporous genes