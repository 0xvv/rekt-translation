**Le front end principal de Curve Finance, [curve.fi](https://curve.fi), a subi un détournement DNS hier, amenant les utilisateurs à approuver un contrat malveillant.**

Environ 575 k$ ont été dérobés aux utilisateurs ayant approuvé le contrat, les fruits du larcin ayant été transferé vers des CEXs et Tornado Cash. On dirait que les [sanctions de l'OFAC](https://rekt.news/eye-of-the-storm/) ne font pas peur à ceux qui transgressent déjà la loi...

La faille n'était pas présente sur [curve.exchange](https://curve.exchange), l'interface web secondaire du projet, vers laquelle l'équipe a dirigé les utilisateurs pendant la gestion de l'incident. Le site cloné du hacker a rapidement été supprimé, cependant certains serveurs de noms [ne sont toujours pas à jour](https://twitter.com/CurveFinance/status/1557367150192562178).

**Cet épisode et d'autres du même type, sont des rappels brutaux que le web3 tourne toujours sur le web2.**

Quand le coeur même de la DeFi est dépendant de l'infrastructure legacy...

*... à quel point pouvons nous revendiquer être décentralisé ?*

Comme pour les autres détournements DNS, l'identification de la cause exacte est le rôle du fournisseur, nous devons nous fier à leur récit des évenements, sans pouvoir le corroborer avec des informations on-chain.

**Pour le moment, [iwantmyname](https://iwantmyname.com/) n'a pas commenté sur ce qui a mené au détournement, mais [Curve pense](https://twitter.com/CurveFinance/status/1557115032646959105) que le serveur de nom lui-même à été compromis, plutôt qu'une erreur au niveau des comptes.**

Le fondateur et P.D.G. de Curve [Michael Egorov](https://twitter.com/newmichwill) a confirmé les suspicions de son équipe auprès de rekt.news :

>Pour le moment je peux dire que le serveur de nom du registraire dns iwantmyname a été compromis
Pas de piratage de compte
Nous avons changé de serveur de nom
De plus, une bonne partie de l'argent a été gelé par des services centralisés
Ce qu'on pourrait faire mieux... on devrait essayer de s'éloigner des choses du web2 comme les dns pour être honnête, ce serait génial

Plus de détails sont fournis [ici](https://twitter.com/CryptoShine/status/1557108025944674306).

**Tous les utilisateurs qui ont interagi avec la plateformes devrait révoquer leurs approbations au contrat malveillant immédiatement :**

**[0x9eb5f8e83359bb5013f3d8eee60bdce5654e8881](https://etherscan.io/address/0x9eb5f8e83359bb5013f3d8eee60bdce5654e8881).**

**Addresse de l'assaillant : [0x50f9202e0f1c1577822bd67193960b213cd2f331](https://etherscan.io/address/0x50f9202e0f1c1577822bd67193960b213cd2f331)**

Les [fonds volés](https://twitter.com/PeckShieldAlert/status/1557202180569833472) (340 ETH, soit environ 575 k$ au total) ont été déposés sur des CEXs, FixedFloat (292 ETH dont 112 [ont été gelés](https://twitter.com/FixedFloat/status/1557116267378708481)) et Binance (20 ETH) ainsi que sur Tornado Cash (27.7 ETH).

**De nos jours, pour la majeure partie des utilisateurs, la DeFi est aussi vulnérable que les sites webs hebergés de manière centralisée avec lesquels ils interagissent.**

Alors que les contrats qui sécurisent le backend des protocoles établis sont [testés par le feu](https://rekt.news/leaderboard/) et deviennent progressivement plus robustes, les pirates s'orientent de plus en plus vers le front end. Ce vecteur d'attaque se base sur la confiance que les utilisateurs ont en les contrats les faisant négliger la sécurité de l'interface web.

Sans vraie décentralisation de chacune des étapes nous allons continuer à voir des attaques de type approval-harvest, comme celles qui ont affectées les utilisateurs de [BadgerDAO](https://rekt.news/badger-rekt/), [Mad Meerkat Finance](https://rekt.news/madmeerkat-finance-rekt/) et, plus récemment, la [brèche Namecheap](https://twitter.com/LefterisJP/status/1540306236087877635) qui a affecté les front ends de quatre protocoles de Defi.

Malgré tous les efforts fournis dans la sécurité des smart contracts, les audits et la décentralisation du pouvoir de gouvernance, la réputation d'un projet peut quand même être détruite par la faute d'une société du web2.

Mis à part [surveiller tous les changements du site](https://twitter.com/AlexSmirnov__/status/1540322738975416321), les protocoles de la Defi (et surtout les utilisateurs) n'ont pas d'autre choix que de faire confiance aux infrastructures de sécurité et aux [membres de l'équipe](https://twitter.com/NamecheapCEO/status/1540378726055174144) d'une autre entreprise.

**La prochaine étape logique serait que les protocoles hébergent leur Dapps avec IPFS et ENS afin d'éliminer la dépendance envers les fournisseurs DNS du web2.**

**L'immense majorité des utilisateurs ne veulent pas interagir directement aves les contrats, la sécurité des front ends ne devrait pas être secondaire.**

*Pour encore combien de temps le web3 va t'il dépendre du web2 ?*

