# Hadihajós reláció

1. $\Pi_{Hajónév}(\sigma_{felavatva<1921}(Hajók))$
1. $\Pi_{Osztály, Ország}(\sigma_{kaliber\ge16}(Hajóosztályok))$
1. $\Pi_{Hajónév}(\sigma_{Csatanév="Denmark Strait"\wedge eredmény="elsüllyedt"}(Kimenetelek))$
1. $\Pi_{Hajónév}(Hajók)\cup\Pi_{Hajónév}(Kimenetelek)$
1. $\Pi_{Ország}(\sigma_{tipus="bb"}(Hajóosztályok))\cap\Pi_{Ország}(\sigma_{tipus="bb"}(Hajóosztályok))$
1. $\Pi_{Hajónév,Ország}(Hajók\Join Hajóosztályok)$
1. $\Pi_{Hajónév,vízkiszorítás,ágyúkSzáma}(\sigma_{Csatanév="Guadalcanal"}(Hajók\Join Kimenetelek\Join Hajóosztályok))$
1. $\Pi_{Hajónév}(\sigma_{felavatva<1943}(Hajók))\cup\Pi_{Hajónév}(\sigma_{dátum<'1/1/43'}(Csaták\Join Kimenetelek))$
1. $\Pi_{Csatanév, eredmény}(Kimenetelek)\div\Pi_{eredmény}(Kimenetelek)$
