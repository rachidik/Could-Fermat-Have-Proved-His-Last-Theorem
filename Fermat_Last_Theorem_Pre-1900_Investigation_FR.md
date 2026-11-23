# Fermat aurait-il pu démontrer son dernier théorème ? Une enquête avec les outils d’avant 1900

22 novembre 2026 · @Rachid EL BAJI

## Le verdict en bref

On ne connaît aucune démonstration complète du dernier théorème de Fermat qui n’utilise que des mathématiques antérieures à 1900, et Fermat n’en possédait presque certainement pas. Pourtant, personne ne peut démontrer qu’une telle démonstration est impossible. Ce que l’on peut démontrer, c’est l’endroit exact où chaque méthode classique s’arrête.

- **La descente**, la méthode de Fermat lui-même, établit complètement le théorème pour les exposants 4 et 3. Les deux démonstrations sont données en entier ci-dessous, sans aucun outil postérieur à 1763.
- **Les congruences**, la méthode de Sophie Germain, ne peuvent pas aboutir, et cela se démontre. Pour l’exposant 5, elles montrent que 32 341 210 divise xyz, et rien de plus fort.
- **La factorisation**, la méthode de Lamé et de Kummer, est la voie la plus puissante d’avant 1900. Elle démontre le théorème pour tout exposant divisible par 4 ou par un nombre premier régulier, et elle bute sur 37.
- **La logique** ne fournit aucun théorème d’impossibilité. Les spécialistes s’attendent à ce que le théorème soit, en principe, démontrable en arithmétique élémentaire, mais on ne connaît aucune démonstration élémentaire courte.

Le dossier historique va dans le même sens. Fermat n’a jamais répété l’affirmation générale, n’a rédigé de démonstration que pour un seul exposant, et s’est trompé sur un autre résultat qu’il attribuait à la descente.

## Règles du jeu et boîte à outils d’avant 1900

Chaque affirmation ci-dessous porte l’une de quatre étiquettes, et chaque outil utilisé à l’intérieur d’une démonstration est daté d’avant 1900.

| Étiquette | Signification |
| --- | --- |
| **\[Fait\]** | Histoire documentée, dont les sources figurent dans la dernière section |
| **\[Mathématiques\]** | Un théorème accompagné d’une démonstration complète, donnée ici ou dans la littérature citée |
| **\[Reconstruction\]** | Une stratégie de démonstration assemblée pour cet article à partir d’outils d’époque |
| **\[Spéculation\]** | Un jugement sur la pensée de Fermat qu’aucun document ne permet de trancher |

La boîte à outils, du plus ancien au plus récent :

| Outil | Origine | Utilisé ici pour |
| --- | --- | --- |
| Décomposition unique des entiers en facteurs premiers ; des facteurs premiers entre eux dont le produit est une puissance parfaite sont eux-mêmes des puissances parfaites | Euclide, Éléments VII–IX, vers 300 av. J.-C. | Toutes les démonstrations |
| Formule des triplets pythagoriciens | Euclide, Éléments X | Exposant 4 |
| Substitutions de la corde et de la tangente, donnant de nouvelles solutions rationnelles | Diophante, IIIᵉ siècle ; Fermat | La remarque sur la corde, dans la section sur l’impossibilité |
| Théorème des restes chinois | Sunzi, entre le IIIᵉ et le Vᵉ siècle ; Gauss 1801 | Le plafond des congruences |
| Identité de composition pour a² + Nb² | Brahmagupta, VIIᵉ siècle | Exposant 3 |
| Descente infinie | Fermat ; décrite dans sa lettre de 1659 | Exposants 4 et 3 |
| Petit théorème de Fermat | Fermat 1640 ; démonstration par Euler en 1736 | Premier cas de Kummer |
| Dérivée d’un polynôme | Newton et Leibniz, années 1660–1680 | L’analogue polynomial uniquement |
| Nombres de Bernoulli | Jacques Bernoulli, 1713 | Critère de régularité de Kummer |
| Diviseurs premiers de a² + 3b² | Énoncé par Fermat ; démontré par Euler, 1759–1763 | Exposant 3 |
| Formes quadratiques réduites et nombre de classes | Lagrange 1773 ; Gauss 1801 | La rupture à 23 |
| Congruences, résidus de puissances modulo les nombres premiers et leurs puissances, racines de l’unité | Gauss, Disquisitiones Arithmeticae, 1801 | Théorème de Germain ; plafond des congruences ; factorisation |
| Relations entre facteurs pour xᵖ + yᵖ | Barlow 1810 ; Abel 1823 | Premières réductions |
| Théorème de Sophie Germain | Germain, au plus tard en 1819 ; imprimé par Legendre, 1823–1827 | Premier cas |
| Sommes de Jacobi | Jacobi, 1827–1837 | Pourquoi le plan de Germain échoue |
| Entiers cyclotomiques, nombres idéaux, unités, nombres premiers réguliers | Kummer, 1844–1850 | La voie la plus puissante |
| Formule du genre pour les applications entre courbes | Riemann 1857 ; Hurwitz 1891 | Une remarque sur la descente |

Pour Fermat, Euler, Germain et Kummer, les origines indiquées sont appuyées par les sources de la dernière section. Les autres lignes donnent les dates de référence usuelles.

Les éléments postérieurs n’apparaissent que dans deux rôles, tous deux signalés. Le calcul moderne revérifie l’arithmétique de l’époque. Les résultats postérieurs à 1900 (Dickson 1909, Jensen 1915, logique mathématique) sont cités pour juger les méthodes, jamais à l’intérieur d’une démonstration.

## Ce que Fermat a réellement écrit et démontré

Fermat a laissé une seule phrase privée affirmant l’existence d’une démonstration générale, et une seule démonstration rédigée, celle de l’exposant 4. **\[Fait\]**

| Année | Ce que montrent les documents |
| --- | --- |
| Années 1630 | Fermat écrit son affirmation dans la marge de son Diophante de 1621. La date habituellement retenue est 1637 environ. L’exemplaire annoté est perdu. |
| 1636–1657 | Ses lettres proposent les cas n = 3 et n = 4 comme défis. L’affirmation générale n’y reparaît jamais. |
| 1640–1658 | Il conjecture que tout nombre 2^(2^n) + 1 est premier, et dit ne pas en avoir de démonstration. |
| 1659 | Sa lettre de synthèse à Carcavi énumère des résultats obtenus par descente. Elle cite les cubes, non toutes les puissances. Elle contient aussi l’affirmation sur 2^(2^n) + 1. |
| 1670 | Son fils Samuel fait imprimer la note marginale, cinq ans après la mort de Fermat. |
| 1732 | Euler montre que 641 divise 2^32 + 1. L’affirmation de 1659 était fausse. |
| 1770 | Euler publie pour n = 3 une démonstration qui comporte une lacune. |
| 1819–1823 | Germain démontre son théorème sur le premier cas. Legendre le fait imprimer. |
| 1825 | Dirichlet et Legendre règlent n = 5. |
| 1839 | Lamé règle n = 7. |
| 1847 | Lamé annonce une démonstration générale. Liouville et Kummer font observer qu’elle suppose l’unicité de la factorisation, laquelle est en défaut. |
| 1847–1850 | Kummer démontre le théorème pour tous les nombres premiers réguliers. |
| 1857 | Les critères de Kummer couvrent 37, 59 et 67, donc tous les exposants inférieurs à 100. Vandiver a corrigé plus tard une partie de l’argument. |
| 1995 | Wiles, avec Taylor, publie une démonstration par des méthodes modernes. |

La note marginale se termine ainsi : *cuius rei demonstrationem mirabilem sane detexi. Hanc marginis exiguitas non caperet.* Elle ne subsiste que dans l’édition imprimée de 1670.

L’unique démonstration que contiennent les écrits conservés de Fermat établit qu’aucun triangle rectangle à côtés entiers n’a pour aire un carré. Cet énoncé entraîne le cas de l’exposant 4.

Sources de ce tableau : [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/), [St John’s College](https://www.joh.cam.ac.uk/node/2312), [MathPages](https://mathpages.com/home/kmath195/kmath195.htm), [Wikipédia, sur les exposants particuliers](https://en.wikipedia.org/wiki/Proof_of_Fermat%27s_Last_Theorem_for_specific_exponents), [Corry](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf), [Encyclopedia of Mathematics](https://encyclopediaofmath.org/wiki/Fermat_last_theorem).

## Premières réductions : ce que toute démonstration doit affronter

Seuls l’exposant 4 et les exposants premiers impairs demandent une démonstration. **\[Mathématiques\]** Si n = km, une solution pour n fournit la solution (xᵏ, yᵏ, zᵏ) pour m. Tout n > 2 est divisible par 4 ou par un nombre premier impair.

On peut aussi supposer que x, y, z sont premiers entre eux deux à deux. Un nombre premier qui divise deux d’entre eux divise le troisième et peut être éliminé.

Pour un nombre premier impair p, faisons tout passer dans un même membre, xᵖ + yᵖ + zᵖ = 0, et isolons un facteur linéaire :

```latex
-z^p = x^p+y^p = (x+y)\,\Phi(x,y),\qquad \Phi(x,y)=x^{p-1}-x^{p-2}y+\cdots+y^{p-1}
```

**Lemme 1 \[Mathématiques ; Barlow 1810, Abel 1823\].** Si x et y sont premiers entre eux, le seul nombre premier qui puisse diviser à la fois x + y et Φ(x, y) est p.

*Démonstration.* Modulo x + y, on a x ≡ −y, et chacun des p termes de Φ devient yᵖ⁻¹. Donc Φ ≡ p·yᵖ⁻¹. Un facteur premier commun ne peut pas diviser y ; il divise donc p. ∎

Depuis l’époque de Germain, on scinde le problème en deux. **\[Fait\]** Dans le *premier cas*, p ne divise aucun des nombres x, y, z. Dans le *second cas*, p divise exactement l’un d’entre eux.

Dans le premier cas, les deux facteurs sont premiers entre eux, donc chacun est une puissance p-ième. Il en va de même pour les deux autres paires :

```latex
x+y=c^p,\qquad y+z=a^p,\qquad z+x=b^p,\qquad \Phi(x,y)=\gamma^p,\qquad z=-c\gamma
```

**\[Reconstruction\]** Ces relations étaient à la portée de Fermat, et elles paraissent décisives. Elles ne le sont pas. Elles contraignent une solution sans la contredire, et la section sur les congruences montre pourquoi un raisonnement de ce type ne peut pas combler l’écart.

## La descente là où elle fonctionne : l’exposant 4

L’équation x⁴ + y⁴ = z² n’a aucune solution en entiers strictement positifs, ce qui règle le cas n = 4. **\[Mathématiques\]** La démonstration utilise trois outils : la formule d’Euclide pour les triplets pythagoriciens, la règle selon laquelle des facteurs premiers entre eux dont le produit est un carré sont eux-mêmes des carrés, et la descente.

1. Prenons une solution où z est le plus petit possible. Alors x et y sont premiers entre eux : un facteur premier commun d donnerait la solution plus petite (x/d, y/d, z/d²).
2. Les entiers x et y ne sont pas tous deux impairs, car on aurait alors z² ≡ 2 (mod 4). Disons que y est pair. Alors x², y², z forment un triplet pythagoricien primitif.
3. La formule d’Euclide fournit des entiers m > n > 0 premiers entre eux, l’un pair et l’autre impair, tels que x² = m² − n², y² = 2mn, z = m² + n².
4. Dans x² + n² = m², le nombre x est impair, donc n est pair et m est impair. La formule d’Euclide fournit de nouveau des entiers r, s premiers entre eux tels que n = 2rs et m = r² + s².
5. Or (y/2)² = rs(r² + s²). Les trois facteurs sont premiers entre eux deux à deux, donc chacun est un carré : r = a², s = b², r² + s² = c².
6. D’où a⁴ + b⁴ = c² avec c ≤ c² = m < z. Cela contredit le choix de z. ∎

**\[Fait\]** La version de Fermat lui-même démontre un énoncé voisin : aucun triangle rectangle à côtés entiers n’a pour aire un carré. Frénicle (1676) et Euler (1738) ont publié des démonstrations ultérieures. La version ci-dessus est la forme moderne usuelle.

**Pourquoi la descente se referme. \[Reconstruction\]** En lisant les étapes à rebours, on obtient des formules fixes :

```latex
x=a^4-b^4,\qquad y=2abc,\qquad z=c^4+4a^4b^4
```

Toute solution serait l’image d’une solution plus petite par une même application polynomiale de degré 4. La descente dit que cette application peut toujours être parcourue à rebours. Ce fait structurel reparaît dans la section sur l’impossibilité.

## Le cas des cubes : une descente complète, la lacune d’Euler comblée

L’équation x³ + y³ = z³ n’a aucune solution en entiers non nuls, et la démonstration ne requiert que des outils que Fermat a utilisés ou énoncés. **\[Mathématiques\]**

**\[Fait\]** Fermat a cité ce résultat en 1659 sans en laisser de démonstration. La démonstration imprimée d’Euler (1770) présente une lacune au niveau du lemme sur les cubes ci-dessous. Ses propres résultats de 1759–1763 sur la forme a² + 3b² la comblent.

Le symbole √−3 n’est qu’une commodité d’écriture. Le produit (c + d√−3)(e + f√−3) abrège le couple (ce − 3df, cf + de). Le fait sous-jacent est une identité entre entiers :

```latex
(c^2+3d^2)(e^2+3f^2)=(ce-3df)^2+3(cf+de)^2
```

**Lemme 2 (division) \[Mathématiques ; Euler\].** Soit P = c² + 3d² un nombre premier, ou bien P = 4. Soient a, b premiers entre eux, tels que P divise a² + 3b². Alors, après un choix convenable du signe de d, il existe e, f premiers entre eux tels que

```latex
a+b\sqrt{-3}=(c+d\sqrt{-3})(e+f\sqrt{-3}),\qquad a^2+3b^2=P\,(e^2+3f^2)
```

*Démonstration.* Le nombre P divise (ad − bc)(ad + bc), car ce produit est égal à d²(a² + 3b²) − b²(c² + 3d²). Choisissons le signe de d de sorte que P divise ad − bc. (Pour P = 4, a et b sont impairs, donc 4 divise a − b ou a + b.) Dans l’identité (ac + 3bd)² + 3(ad − bc)² = P(a² + 3b²), le second membre et le deuxième terme sont divisibles par P². Donc P divise ac + 3bd. Posons e = (ac + 3bd)/P et f = (bc − ad)/P. Une substitution directe donne les deux égalités affichées. Un facteur commun à e et f diviserait a et b. ∎

**Lemme 3 (diviseurs) \[Mathématiques ; Euler 1759–1763\].** Si a et b sont premiers entre eux, tout facteur premier impair de a² + 3b² est de la forme c² + 3d².

*Démonstration par descente.* Soit P le plus petit nombre premier impair qui divise un tel nombre sans être de cette forme. Remplaçons a et b par leurs plus petits restes en valeur absolue modulo P. Alors a² + 3b² = PQ avec Q < P, car a² + 3b² < P². Divisons par le carré de pgcd(a, b), qui est premier avec P ; le cofacteur Q ne peut que diminuer. Si Q est pair, alors a et b sont impairs, il y a exactement un facteur 4, et le lemme 2 l’élimine. Tout facteur premier impair de Q est plus petit que P, donc de la forme c² + 3d², et le lemme 2 l’élimine aussi. Il reste P = e² + 3f², ce qui est une contradiction. ∎

**Lemme 4 (cubes) \[Mathématiques\].** Soient a, b premiers entre eux, avec a² + 3b² = s³ et s impair. Alors a + b√−3 = (e + f√−3)³ pour certains e, f premiers entre eux. Explicitement :

```latex
a=e(e-3f)(e+3f),\qquad b=3f(e-f)(e+f),\qquad s=e^2+3f^2
```

*Démonstration.* Écrivons s comme produit de nombres premiers impairs Pᵢ = cᵢ² + 3dᵢ², grâce au lemme 3. Appliquons le lemme 2 trois fois pour chaque nombre premier. On obtient a + b√−3 = ±∏(cᵢ ± dᵢ√−3), avec trois facteurs par nombre premier. Pour des nombres premiers égaux, tous les signes coïncident. Sinon, le produit contiendrait (c + d√−3)(c − d√−3) = P, et P diviserait à la fois a et b. Le produit est donc un cube, et −1 est lui aussi un cube. ∎

**Théorème \[Mathématiques\].** L’équation x³ + y³ + z³ = 0 n’a aucune solution avec xyz ≠ 0.

1. Prenons une solution dont les termes sont premiers entre eux deux à deux. Exactement un des trois termes est pair. Appelons-le z, et choisissons |z| le plus petit possible.
2. Posons x = u + v et y = u − v. Alors u et v sont premiers entre eux, l’un pair et l’autre impair, et −z³ = 2u(u² + 3v²). Aucun des deux n’est nul : u = 0 donne z = 0, et v = 0 donne 2x³ = −z³.
3. Le nombre u² + 3v² est impair et 8 divise z³, donc u est pair et v est impair. Le seul nombre premier qui puisse diviser à la fois 2u et u² + 3v² est 3.
4. **Si 3 ne divise pas u,** les deux facteurs sont des cubes premiers entre eux : 2u = r³ et u² + 3v² = s³. Le lemme 4 donne u = e(e − 3f)(e + 3f) et v = 3f(e − f)(e + f), avec e pair et f impair.
5. Alors 2e, e − 3f, e + 3f sont premiers entre eux deux à deux, car e divise u et est donc premier avec 3f, et e ± 3f sont impairs. Leur produit est r³ ; ce sont donc des cubes k³, l³, m³, et l³ + m³ = k³.
6. Ici k est pair et non nul, et |z|³ = |k|³·|e² − 9f²|·(u² + 3v²) ≥ 3|k|³. Donc |k| < |z|, ce qui contredit l’étape 1.
7. **Si 3 divise u,** écrivons u = 3w. Alors −z³ = 18w(3w² + v²), avec des facteurs premiers entre eux, donc 18w = r³ et v² + 3w² = s³. Le lemme 4 donne v = e(e − 3f)(e + 3f) et w = 3f(e − f)(e + f), avec e impair et f pair.
8. Or 18w = 27·2f(e − f)(e + f). Donc 2f, e − f, e + f sont des cubes premiers entre eux k³, l³, m³, avec k³ + l³ = m³. De nouveau k est pair et non nul, et |z|³ ≥ 27|k|³. Contradiction. ∎

**Pourquoi la descente se referme. \[Reconstruction\]** Deux faits concernant a² + 3b² ont fait tout le travail. Ses diviseurs premiers sont de la même forme, et ses cubes ne s’obtiennent que par composition. En remontant les étapes, on écrit x, y, z comme des polynômes fixes de degré 9 en k, l, m.

## Pourquoi le schéma s’essouffle aux exposants 5 et 7

Pour p = 5 et p = 7, une descente existe encore, mais chaque exposant a exigé un outillage nouveau, et la méthode directe n’est pas allée plus loin. **\[Fait\]**

Gauss a montré en 1801 que 4Φ est toujours une expression quadratique Y² ± pZ² en deux formes auxiliaires Y et Z de degré (p − 1)/2. **\[Mathématiques\]** Les trois premiers cas, vérifiés par calcul formel pour cet article :

```latex
4\Phi_3=(2x-y)^2+3y^2
```

```latex
4\Phi_5=(2x^2-xy+2y^2)^2-5(xy)^2
```

```latex
4\Phi_7=(2x^3-x^2y-xy^2+2y^3)^2+7\,\bigl(xy(x-y)\bigr)^2
```

**Exposant 3. \[Reconstruction\]** Y et Z sont linéaires en x et y. Savoir que Y + Z√−3 est un cube redonne donc x et y eux-mêmes, et la descente se referme à l’intérieur d’une seule équation.

**Exposant 5. \[Fait\]** Y et Z sont quadratiques, de sorte qu’un énoncé de puissance cinquième portant sur Y² − 5Z² ne redonne pas directement x et y. Dirichlet et Legendre (1825) ont scindé le second cas en deux et ont mené la descente à travers des équations auxiliaires. Il leur a fallu l’arithmétique de a² − 5b², où l’équation de Pell-Fermat fournit une infinité de facteurs unités.

**Exposant 7. \[Fait\]** Les démonstrations classiques (Lamé 1839, simplifiée par Lebesgue en 1840) reposent sur une identité propre aux puissances septièmes :

```latex
(x+y+z)^7-(x^7+y^7+z^7)=7(x+y)(y+z)(z+x)\left[(x^2+y^2+z^2+xy+yz+zx)^2+xyz(x+y+z)\right]
```

L’historique de MacTutor voit dans la démonstration de Lamé le signe que les exposants plus grands réclamaient une idée entièrement nouvelle. Les exposants 11, 13, 17 et 19 ont d’abord été atteints par la théorie de Kummer, non par une descente directe.

**La leçon. \[Reconstruction\]** Chaque nouveau nombre premier a exigé l’arithmétique d’un système de nombres plus vaste : a² + 3b² pour 3, a² − 5b² pour 5, une identité ad hoc pour 7. Le schéma ne se prolonge pas avec les seuls entiers ordinaires.

## Congruences : le théorème de Germain et pourquoi son plan échoue

Les arguments de congruence démontrent de véritables restrictions sur une solution, mais, pour chaque exposant, ils s’arrêtent à un unique énoncé de divisibilité, fixé une fois pour toutes. **\[Mathématiques\]**

**Théorème de Germain \[Mathématiques ; Germain au plus tard en 1819, imprimé en 1823–1827\].** Soient p un nombre premier impair et θ un nombre premier possédant deux propriétés :

- (i) deux résidus de puissances p-ièmes non nuls modulo θ ne diffèrent jamais de 1 ;
- (ii) p n’est pas un résidu de puissance p-ième modulo θ.

Alors, dans toute solution de xᵖ + yᵖ + zᵖ = 0, p divise xyz.

1. La condition (i) dit : si xᵖ + yᵖ + zᵖ ≡ 0 (mod θ), alors θ divise xyz. Sinon, (x/z)ᵖ et (−y/z)ᵖ différeraient de 1.
2. Supposons une solution, à termes premiers entre eux deux à deux, où p ne divise pas xyz. Les relations entre facteurs donnent y + z = aᵖ, z + x = bᵖ, x + y = cᵖ, Φ(y, z) = αᵖ, Φ(x, y) = γᵖ.
3. D’après l’étape 1, θ divise l’un des nombres x, y, z ; disons x. Alors bᵖ + cᵖ + (−a)ᵖ = 2x ≡ 0 (mod θ), donc θ divise abc, de nouveau d’après l’étape 1.
4. Le nombre θ ne peut diviser ni b ni c : de θ | b on tirerait θ | z + x, puis θ | z. Donc θ divise a, c’est-à-dire y ≡ −z (mod θ).
5. Alors αᵖ = Φ(y, z) ≡ p·yᵖ⁻¹ et γᵖ = Φ(x, y) ≡ yᵖ⁻¹ (mod θ). Donc p ≡ (α/γ)ᵖ, ce qui contredit (ii). ∎

**Exemple. \[Mathématiques\]** Pour p = 5, prenons θ = 11. Les résidus de puissances cinquièmes sont 1 et 10, donc (i) et (ii) sont toutes deux vérifiées. Le premier cas est impossible pour p = 5.

**\[Fait\]** Germain a trouvé un tel θ pour chaque nombre premier inférieur à 100, et Legendre a prolongé la table jusqu’aux nombres premiers inférieurs à 197. **\[Mathématiques ; calculé\]** Un nouveau calcul le confirme. Pour tout nombre premier impair p < 197, un θ = 2Np + 1 avec N ≤ 8 convient, tandis que p = 197 exige N = 19, θ = 7487.

**Le grand plan. \[Fait\]** Germain espérait montrer que, pour chaque p, une infinité de nombres premiers θ vérifient (i). Chacun d’eux diviserait xyz, de sorte qu’aucune solution non nulle ne pourrait exister.

**Pourquoi il échoue. \[Mathématiques\]** Seuls comptent les nombres premiers θ ≡ 1 (mod p), car sinon tout résidu est une puissance p-ième. Pour ceux-là, les sommes de Jacobi (1837) dénombrent les solutions de Xᵖ + Yᵖ = 1 modulo θ :

```latex
N=\theta-(p-1)+E,\qquad |E|\le (p-1)(p-2)\sqrt{\theta}
```

Seules 2p de ces solutions vérifient XY = 0. Toute autre solution fournit deux résidus consécutifs, (−X)ᵖ et Yᵖ. La condition (i) est donc nécessairement en défaut dès que

```latex
\theta\ \ge\ (p-1)^2(p-2)^2+6p-2
```

**\[Fait\]** Libri a affirmé cette finitude en 1829. Pépin et Pellet l’ont confirmée plus tard dans le siècle, et Dickson a publié des bornes explicites en 1909.

En testant chaque nombre premier inférieur à la borne, on obtient les listes complètes. **\[Mathématiques ; calculé\]**

| p | Borne | Tous les nombres premiers impairs θ vérifiant (i) |
| --- | --- | --- |
| 3 | 20 | 7, 13 |
| 5 | 172 | 11, 41, 71, 101 |
| 7 | 940 | 29, 71, 113, 491 |
| 11 | 8 164 | 23, 89, 947, 1409 |
| 13 | 17 500 | 53, 131, 443, 521 |
| 17 | 57 700 | 137, 239, 443, 1667, 4013 |

**\[Fait\]** Germain a démontré elle-même la première ligne, et Legendre a présumé la deuxième.

**Le plafond. \[Mathématiques\]** Disons qu’un nombre premier est *forcé* si des congruences modulo ses puissances montrent qu’il divise xyz. Les nombres premiers forcés sont 2, les nombres premiers du tableau, et p lui-même lorsque le premier cas est impossible modulo p². Soit M leur produit.

| p | Nombres premiers forcés | M |
| --- | --- | --- |
| 3 | 2, 3, 7, 13 | 546 |
| 5 | 2, 5, 11, 41, 71, 101 | 32 341 210 |
| 7 | 2, 29, 71, 113, 491 | 228 478 994 |

Alors M divise xyz dans toute solution. Réciproquement, pour tout module m, la congruence xᵖ + yᵖ ≡ zᵖ (mod m) admet une solution dans laquelle pgcd(xyz, m) divise M. Aucune congruence, quel qu’en soit le module, ne peut donc démontrer davantage que « M divise xyz ».

*Démonstration de la réciproque.* Pour un nombre premier forcé θ, le triplet (1, θ, z) avec zᵖ = 1 + θᵖ existe modulo toute puissance de θ, et θ divise le produit xyz correspondant exactement une fois. Pour tout autre nombre premier, une solution dont le produit xyz est premier avec lui existe modulo ce nombre premier (modulo p² dans le cas du nombre premier p) et se relève à toute puissance supérieure par approximations successives. Le théorème des restes chinois les combine. ∎

Sources : [Laubenbacher et Pengelley](https://ar5iv.arxiv.org/html/0801.1809) pour Germain, Libri, Pellet et Dickson ; [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/) pour le prolongement dû à Legendre.

## Factorisation : l’erreur de Lamé et la réparation de Kummer

Factoriser complètement xᵖ + yᵖ est l’idée la plus puissante dont on disposait avant 1900. Elle démontre le théorème pour tout nombre premier régulier, et rien d’uniforme au-delà. **\[Mathématiques\]**

Avec ζ une racine primitive p-ième de l’unité :

```latex
x^p+y^p=\prod_{k=0}^{p-1}\bigl(x+\zeta^k y\bigr)
```

**La tentative de Lamé. \[Fait\]** Le 1ᵉʳ mars 1847, Lamé a traité les nombres a₀ + a₁ζ + a₂ζ² + … comme des entiers ordinaires. Des facteurs premiers entre eux d’une puissance p-ième seraient alors des puissances p-ièmes, et une descente s’ensuivrait. Liouville a objecté que l’unicité de la factorisation n’était pas démontrée. Kummer avait déjà montré en 1844 qu’elle est en défaut.

**Où elle est en défaut. \[Mathématiques\]** L’unicité de la factorisation vaut pour p ≤ 19 et tombe en défaut à p = 23. On en voit une trace avec les outils de 1801. Les formes x² + xy + 6y² et 2x² ± xy + 3y² ont toutes pour discriminant −23 et ne sont pas équivalentes. Corrélativement, le nombre 6 admet deux factorisations différentes en nombres irréductibles :

```latex
6 = 2\cdot 3=\frac{1+\sqrt{-23}}{2}\cdot\frac{1-\sqrt{-23}}{2}
```

Toutes deux se situent dans les entiers cyclotomiques formés avec les racines 23-ièmes de l’unité.

**La réparation de Kummer. \[Fait\]** En 1846–1847, il a introduit les nombres idéaux, pour lesquels l’unicité de la factorisation est rétablie. Le nombre de classes h mesure l’écart entre les nombres idéaux et les nombres véritables. Un nombre premier p est dit *régulier* si p ne divise pas h.

**Théorème \[Mathématiques ; Kummer 1847–1850\].** Le dernier théorème de Fermat est vrai pour tout nombre premier régulier.

*Premier cas, p ≥ 5.* Supposons xᵖ + yᵖ = zᵖ, avec x, y, z premiers entre eux deux à deux et p ne divisant pas xyz. Posons λ = 1 − ζ.

1. Les facteurs x + ζᵏy sont premiers entre eux deux à deux. Un facteur premier idéal commun diviserait λx et λy, donc λ. Alors p diviserait x + y, et donc z, contrairement à l’hypothèse.
2. Chaque facteur est donc une puissance p-ième idéale. Par régularité, celle-ci provient d’un nombre véritable : x + ζy = ε·αᵖ, où ε est une unité.
3. Kummer fournit deux faits. L’unité ε est le produit d’une puissance ζʳ par une unité réelle, et αᵖ est congru à un entier ordinaire modulo p. En comparant x + ζy à son conjugué complexe, on obtient la congruence affichée sous la liste.
4. Les puissances 1, ζ, …, ζᵖ⁻² sont indépendantes modulo p. À moins que deux des quatre exposants ne coïncident, p divise x et y. Les coïncidences ne laissent que x ≡ y (mod p).
5. Le même argument appliqué à xᵖ + (−z)ᵖ = (−y)ᵖ donne x ≡ −z. Alors 0 = xᵖ + yᵖ − zᵖ ≡ 3x (mod p), d’après le petit théorème de Fermat. Donc p divise x, ce qui est une contradiction. ∎

```latex
x+\zeta y-\zeta^{2r}x-\zeta^{2r-1}y\equiv 0 \pmod p
```

*Second cas.* Il requiert le lemme de Kummer sur les unités : une unité congrue à un entier modulo p est une puissance p-ième. On procède ensuite par descente sur la puissance de λ qui divise z. Les deux étapes exigent la régularité. La démonstration n’est pas reproduite ici.

**Le critère. \[Mathématiques ; Kummer\]** Un nombre premier p est régulier si et seulement s’il ne divise aucun des numérateurs des nombres de Bernoulli B₂, B₄, … jusqu’à l’indice p − 3.

**\[Mathématiques ; calculé\]** Recalculé pour cet article : les nombres premiers irréguliers inférieurs à 100 sont 37, 59 et 67. Par exemple, 37 divise le numérateur de B₃₂ = −7709321041217/510. En dessous de 1000, 64 des 167 nombres premiers impairs sont irréguliers.

**Le plafond en 1900. \[Fait\]** Les critères supplémentaires de Kummer (1857) ont traité 37, 59 et 67 un nombre premier à la fois. Il n’existait aucun argument uniforme pour les nombres premiers irréguliers.

**Toujours ouvert. \[Fait\]** Il existe une infinité de nombres premiers irréguliers (Jensen 1915). Personne n’a démontré qu’il existe une infinité de nombres premiers réguliers.

Sources : [MacTutor](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/) pour 1844–1847 ; [Conrad](https://kconrad.math.uconn.edu/blurbs/gradnumthy/fltreg.pdf) pour les nombres de classes et l’argument du premier cas ; [Corry](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf) pour 1857.

## Une reconstruction : la meilleure démonstration d’avant 1900, étape par étape

Assemblés en un seul argument, les outils classiques démontrent le théorème pour tout exposant divisible par 4 ou par un nombre premier régulier. Pour les autres, l’argument se rompt en deux étapes bien identifiées. **\[Reconstruction\]**

| Étape | Énoncé | Outil et date | Statut |
| --- | --- | --- | --- |
| 1 | Se ramener à n = 4 et aux nombres premiers impairs p | Euclide | Démontré |
| 2 | Régler n = 4 par descente | Fermat | Démontré |
| 3 | Décomposer xᵖ + yᵖ = (x + y)·Φ et borner le facteur commun | Barlow 1810, Abel 1823 | Démontré |
| 4 | Décomposer Φ en facteurs linéaires x + ζᵏy | Gauss 1801, Lamé 1847 | Démontré |
| 5 | Des facteurs premiers entre eux d’une puissance p-ième sont des puissances p-ièmes | Nombres idéaux de Kummer, 1847 | Vrai pour les nombres idéaux seulement |
| 6 | Un nombre qui est une puissance p-ième idéale est le produit d’une unité par une puissance p-ième | Nombre de classes, 1847 | Exige p ∤ h ; faux comme règle générale pour 37, 59, 67, … |
| 7 | L’unité restante ne gêne pas | Lemme de Kummer sur les unités, 1850 | Exige de nouveau la régularité |
| 8 | Produire une solution plus petite | Descente de Fermat | S’ensuit dès que 5–7 sont acquises |

**À quoi ressemblerait la version de Fermat lui-même. \[Reconstruction\]** En 1637, les étapes 4 à 7 devaient être menées avec des entiers ordinaires et des formes. Pour p = 3, la forme est a² + 3b², et la section sur les cubes montre que la chaîne se referme. Pour un p général, il lui aurait fallu le principe suivant :

*Si Φ(x, y) est une puissance p-ième et si x, y sont premiers entre eux, alors x et y proviennent, par une composition répétée p fois, d’entiers plus petits.*

Pour p = 3, c’est le lemme 4. Pour p = 5 et 7, il a fallu Dirichlet, Legendre et Lamé. En général, c’est le contenu des étapes 5 à 7.

**Bilan. \[Mathématiques\]** La reconstruction est une démonstration complète pour n = 4 et pour p = 3, 5, 7, 11, 13, 17, 19, 23, 29, 31 et tout autre nombre premier régulier. Il suffit à un exposant d’avoir un seul bon facteur ; les premiers exposants laissés ouverts sont donc 37, 59, 67 et 74.

Elle ne peut pas être complétée pour tout n. Dans les entiers cyclotomiques formés avec les racines 37-ièmes de l’unité, l’étape 6 est fausse en tant que règle générale. Il y existe des classes d’idéaux d’ordre 37, de sorte que certains nombres sont des puissances 37-ièmes idéales sans être le produit d’une unité par une puissance 37-ième.

Que l’étape 6 soit ou non en défaut pour les nombres particuliers x + ζy d’une solution de Fermat, cette méthode ne permet pas de le voir. C’est exactement là que se situe la lacune.

**Un mathématicien du XIXᵉ siècle aurait-il pu la contourner ? \[Spéculation\]** Kummer, Kronecker, Dedekind et Hilbert connaissaient tous l’obstacle, et aucun ne l’a levé. La démonstration de 1995 passe par les courbes elliptiques et les formes modulaires. Leur lien avec l’équation de Fermat n’a été remarqué qu’au milieu des années 1980.

## Peut-on démontrer l’impossibilité ?

Non. Il n’existe aucun argument rigoureux établissant qu’une démonstration d’avant 1900 ne peut pas exister, et la logique laisse penser qu’on n’en trouvera pas. Ce que l’on peut démontrer, ce sont des limites propres à chaque méthode. **\[Mathématiques\]**

**Ce qu’exigerait une démonstration d’impossibilité. \[Mathématiques\]** « Les mathématiques d’avant 1900 » ne constituent pas un système formel. Le substitut précis le plus proche est l’arithmétique du premier ordre : les entiers naturels, l’addition, la multiplication et la récurrence. La descente infinie est la récurrence sous un autre habit, et toutes les démonstrations ci-dessus peuvent s’écrire dans ce système.

**\[Fait\]** Le dernier théorème de Fermat est un énoncé de cette arithmétique. La synthèse de McLarty sur la logique de la question rapporte que la démonstration de 1995 ne requiert probablement, en principe, rien de plus que l’arithmétique du premier ordre. Friedman conjecture qu’un système beaucoup plus faible suffit. Aucune de ces deux affirmations n’a été rédigée intégralement.

**\[Mathématiques\]** Si cette attente est fondée, une démonstration élémentaire existe au sens logique, et l’impossibilité n’est pas seulement non démontrée : elle est fausse. Une telle démonstration pourrait être d’une longueur astronomique. Aucun théorème connu ne minore sa longueur.

**Un précédent. \[Fait\]** Le théorème des nombres premiers a été démontré en 1896 au moyen de l’analyse complexe. Hardy doutait qu’une démonstration élémentaire puisse exister. Selberg et Erdős en ont trouvé une en 1948.

**Cinq limites démontrées. \[Mathématiques\]**

| Méthode | Ce qui est démontré sur sa portée | Établi par |
| --- | --- | --- |
| Congruences modulo un module quelconque | Elles montrent que M divise xyz, et rien de plus | Sommes de Jacobi et relèvement ; calculé ci-dessus |
| Plan de Germain | Chaque p n’admet qu’un nombre fini de nombres premiers auxiliaires | Libri 1829, Pellet 1887, Dickson 1909 |
| Factorisation unique des entiers cyclotomiques | En défaut à partir de p = 23 | Kummer 1844 |
| Méthode de Kummer | Ne couvre que les nombres premiers réguliers ; il existe une infinité de nombres premiers irréguliers | Kummer 1850, Jensen 1915 |
| Descente par une formule fixe sur la courbe de Fermat | Impossible pour n ≥ 4 | Hurwitz 1891 |

**La dernière ligne, expliquée. \[Mathématiques\]** Dans les sections sur les exposants 4 et 3, toute solution est l’image d’une solution plus petite par une application polynomiale fixe de degré strictement supérieur à 1. Ces deux applications vivent sur des courbes de genre 1. La courbe xⁿ + yⁿ = zⁿ est de genre (n − 1)(n − 2)/2, qui vaut au moins 3 dès que n ≥ 4. La formule de Hurwitz dit qu’une application de degré d d’une courbe de genre g dans elle-même vérifie

```latex
2g-2\ \ge\ d\,(2g-2)
```

Donc d = 1 dès que g ≥ 2. Aucune formule ne peut envoyer les solutions de l’équation de Fermat sur d’autres solutions, en dehors de ses symétries évidentes.

Cela n’exclut pas les descentes qui passent par d’autres équations, comme celles de Dirichlet et de Kummer. Cela explique en revanche pourquoi la démonstration pour l’exposant 4 opère sur x⁴ + y⁴ = z², courbe de genre 1, et non sur la quartique elle-même.

**La méthode classique de la corde. \[Mathématiques\]** Diophante et Fermat trouvaient de nouvelles solutions rationnelles par des substitutions qui reviennent à tracer une droite passant par des solutions connues. Sur une conique, une telle droite recoupe la courbe en un point supplémentaire, et sur une cubique, une droite passant par deux points connus la recoupe en exactement un autre point. Sur xⁿ + yⁿ = 1 avec n ≥ 4, elle recoupe la courbe en au moins deux autres points, qui n’ont aucune raison d’être rationnels. La méthode n’offre alors aucune prise pour grimper.

**Là où une démonstration merveilleuse existe bel et bien. \[Mathématiques\]** Pour les polynômes à une indéterminée, le théorème est attribué à Liouville (1879), et une démonstration par dérivation tient en quelques lignes. Soient x, y, z des polynômes premiers entre eux, non tous constants, tels que xⁿ + yⁿ = zⁿ. Dérivons, puis éliminons zⁿ :

```latex
x^{n-1}\,(xz'-x'z)=y^{n-1}\,(y'z-yz')
```

Comme x et y sont premiers entre eux, xⁿ⁻¹ divise y′z − yz′, qui n’est pas nul. D’où (n − 1)·deg x ≤ deg y + deg z − 1. En additionnant les trois inégalités symétriques, on obtient (n − 3)(deg x + deg y + deg z) ≤ −3, ce qui est impossible pour n ≥ 3. ∎

**\[Spéculation\]** Cette démonstration repose sur un seul outil, la dérivée. On ne lui connaît aucun équivalent pour les entiers. Une démonstration merveilleuse pour les entiers devrait en fournir un, et rien, au XVIIᵉ comme au XIXᵉ siècle, ne laisse entrevoir un tel outil.

Sources : [McLarty](https://www.cs.umd.edu/users/gasarch/BLOGPAPERS/fltlargecard.pdf) pour la logique ; [Wikipédia, « Elementary proof »](https://en.wikipedia.org/wiki/Elementary_proof) pour le théorème des nombres premiers ; [Laeng](https://parabola.unsw.edu.au/sites/default/files/2024-03/vol35_no1_1.pdf) pour les polynômes.

## Ce que Fermat avait probablement

Le scénario le plus vraisemblable est que Fermat a cru un moment que sa descente pour les carrés et les cubes s’étendait à toutes les puissances, puis a vu qu’il n’en était rien. **\[Spéculation\]**

**Les indices. \[Fait\]**

- La note était privée. Il ne l’a jamais publiée, et il n’a jamais répété l’affirmation générale dans ses lettres.
- Il n’a cessé de proposer n = 3 et n = 4 comme des défis distincts, et n’a rédigé de démonstration que pour 4. Une démonstration générale aurait rendu l’un et l’autre superflus.
- Sa synthèse de 1659 des résultats obtenus par descente revendique les cubes, non toutes les puissances.
- La même lettre range la primalité de tous les nombres 2^(2^n) + 1 parmi les propositions traitées par descente. Cette affirmation est fausse. Au moins une fois, sa confiance dans la descente a devancé ses démonstrations.

**Trois mécanismes possibles. \[Spéculation\]**

1. *Une loi de composition étendue à l’excès.* Il disposait de la formule des triplets pythagoriciens, et il a énoncé la propriété des diviseurs de a² + 3b². Il a pu supposer qu’une loi analogue vaut pour chaque exposant. Ce sont les étapes 5 et 6 de la reconstruction : l’erreur de Lamé, avec deux siècles d’avance.
2. *Une démonstration pour les petits exposants, énoncée en toute généralité.* Une note marginale n’est pas une publication, et son « en général » peut n’exprimer qu’un espoir.
3. *Un argument tiré des relations entre facteurs.* Les relations de la section sur les premières réductions paraissent décisives sans l’être.

**Ce qu’aurait exigé une démonstration correcte. \[Reconstruction\]** Avec ses méthodes attestées, Fermat aurait dû résoudre en 1637 le problème qui a arrêté Kummer en 1850. Ses lettres ne portent aucune trace des idées nécessaires.

**La lecture des historiens. \[Fait\]** L’historique de MacTutor suggère qu’il a pu s’apercevoir que sa démonstration était fausse, puisqu’il a reformulé ses autres théorèmes sous forme de défis, et jamais celui-ci. L’Encyclopedia of Mathematics qualifie de « tout à fait absurde » l’idée qu’il ait possédé une démonstration. Le verdict de Weil, tel qu’on le cite habituellement, est que Fermat s’est brièvement fait illusion avec une idée qu’il est impossible de retrouver.

**Ce qu’il possédait très vraisemblablement. \[Spéculation\]** Une descente correcte pour les cubes, dans l’esprit de la section sur les cubes, est à la portée de l’outillage qu’il a lui-même décrit.

## Conclusions : réponses aux sept exigences

Une démonstration complète avec les outils d’avant 1900 n’est pas connue, ne peut pas être démontrée impossible, et était, de façon réaliste, hors de portée.

1. **Aucun concept postérieur.** Toutes les démonstrations ci-dessus utilisent des outils datés d’avant 1900. Les résultats postérieurs à 1900 n’apparaissent que comme des commentaires signalés sur les méthodes.
2. **Outils identifiés.** Le tableau de la boîte à outils date chacun d’eux, d’Euclide à Hurwitz.
3. **Approches connues analysées.** La descente, les congruences et la factorisation ont chacune leur section, et la méthode classique de la corde est évaluée avec les limites. Des démonstrations complètes sont données pour les exposants 4 et 3, pour le théorème de Germain et pour le premier cas de Kummer.
4. **Une démonstration complète aurait-elle pu exister ?** Pas de façon réaliste. La méthode d’époque la plus puissante laisse de côté une infinité d’exposants premiers, et ceux qui l’ont bâtie savaient pourquoi.
5. **Est-ce impossible ?** Cela ne peut pas être démontré, et c’est probablement faux au sens logique. Ce qui est démontré, ce sont cinq limites, une par méthode.
6. **La voie plausible.** La descente à travers la factorisation cyclotomique est développée étape par étape. Elle démontre le théorème pour les exposants divisibles par 4 ou par un nombre premier régulier, non pour tout n > 2.
7. **Étiquettes.** Fait, Mathématiques, Reconstruction et Spéculation sont indiqués tout au long du texte.

**\[Spéculation\]** La meilleure reconstruction de la « démonstration merveilleuse » est une descente correcte pour les puissances quatrièmes et les cubes, enveloppée dans une généralisation que les outils de Fermat ne pouvaient pas soutenir au-delà.

## Sources

Pages consultées et vérifiées pour cet article le 22 novembre 2026 :

- [MacTutor, « Fermat’s last theorem »](https://mathshistory.st-andrews.ac.uk/HistTopics/Fermat%27s_last_theorem/) : la chronologie de Fermat à Kummer
- [Laubenbacher et Pengelley, « Voici ce que j’ai trouvé: Sophie Germain’s grand plan to prove Fermat’s Last Theorem »](https://ar5iv.arxiv.org/html/0801.1809) : Germain, Libri, Pellet, Dickson
- [McLarty, « What does it take to prove Fermat’s Last Theorem? », Bulletin of Symbolic Logic 16 (2010)](https://www.cs.umd.edu/users/gasarch/BLOGPAPERS/fltlargecard.pdf) : la logique de la démonstration de 1995
- [Conrad, « Fermat’s Last Theorem for regular primes »](https://kconrad.math.uconn.edu/blurbs/gradnumthy/fltreg.pdf) : nombres de classes et premier cas de Kummer
- [Corry, sur Kummer, Vandiver et le calcul](https://www.tau.ac.il/~corry/publications/articles/pdf/FLT%20-%20SWAC.pdf) : les critères de 1857 et leur correction ultérieure
- [MathPages, « Fermat’s Fallibility »](https://mathpages.com/home/kmath195/kmath195.htm) : l’affirmation sur 2^(2^n) + 1
- [MAA, sur la lettre de 1659 à Carcavi](https://old.maa.org/node/3575258) : la descente décrite par Fermat lui-même
- [Wikipédia, « Proof of Fermat’s Last Theorem for specific exponents »](https://en.wikipedia.org/wiki/Proof_of_Fermat%27s_Last_Theorem_for_specific_exponents) : qui a démontré quel exposant, et quand
- [Wikipédia, « Elementary proof »](https://en.wikipedia.org/wiki/Elementary_proof) : le théorème des nombres premiers et la conjecture de Friedman
- [Encyclopedia of Mathematics, « Fermat last theorem »](https://encyclopediaofmath.org/wiki/Fermat_last_theorem) : Vandiver, et l’enchaînement des années 1980 menant à Wiles
- [Laeng, « Fermat’s Last Theorem for polynomials », Parabola 35 (1999)](https://parabola.unsw.edu.au/sites/default/files/2024-03/vol35_no1_1.pdf) : l’attribution à Liouville
- [St John’s College, Cambridge, sur le Diophante de 1670](https://www.joh.cam.ac.uk/node/2312) : l’original perdu

Ouvrages imprimés de référence, utilisés de mémoire et non consultés ici : H. M. Edwards, *Fermat’s Last Theorem: A Genetic Introduction* (1977) ; P. Ribenboim, *13 Lectures on Fermat’s Last Theorem* (1979) ; A. Weil, *Number Theory: An Approach through History* (1984). C’est sur eux que reposent la réparation du lemme d’Euler, l’identité pour l’exposant 7, les dates de Barlow et d’Abel, et le verdict de Weil.

Tous les énoncés calculés sont reproduits intégralement dans l’annexe [Journal des calculs](#journal-des-calculs) ci-dessous.

---

## Journal des calculs

Tout énoncé marqué « calculé » dans l’article provient des vérifications ci-dessous. Elles utilisent l’arithmétique exacte sur les entiers et le calcul formel, en Python 3 avec SymPy, et ont été exécutées le 22 novembre 2026. Le script est disponible sur demande.

### Identités algébriques

Chacune a été confirmée par développement en calcul formel.

- (u + v)³ + (u − v)³ = 2u(u² + 3v²)
- a = e³ − 9ef² et b = 3e²f − 3f³ donnent a² + 3b² = (e² + 3f²)³
- (ce − 3df)² + 3(cf + de)² = (c² + 3d²)(e² + 3f²), dans les deux conventions de signe
- (ad − bc)(ad + bc) = d²(a² + 3b²) − b²(c² + 3d²)
- Les deux emplois de la formule d’Euclide pour les triplets dans le cas de l’exposant 4, et l’application (a, b, c) → (a⁴ − b⁴, 2abc, c⁴ + 4a⁴b⁴)
- Les expressions de 4Φ pour p = 3, 5, 7 figurant dans l’article
- L’identité des puissances septièmes
- Φ(−y, y) = p·yᵖ⁻¹ pour p = 3, 5, 7, 11, 13

### Nombres premiers sans résidus de puissances p-ièmes consécutifs

Chaque nombre premier inférieur à la borne (p − 1)²(p − 2)² + 6p − 2 a été testé. Pour contrôler la borne, les nombres premiers jusqu’à trois fois la borne ont été testés également, et aucun ne convenait.

| p | Borne | Nombre | Liste complète |
| --- | --- | --- | --- |
| 3 | 20 | 2 | 7, 13 |
| 5 | 172 | 4 | 11, 41, 71, 101 |
| 7 | 940 | 4 | 29, 71, 113, 491 |
| 11 | 8 164 | 4 | 23, 89, 947, 1409 |
| 13 | 17 500 | 4 | 53, 131, 443, 521 |
| 17 | 57 700 | 5 | 137, 239, 443, 1667, 4013 |
| 19 | 93 748 | 7 | 191, 419, 647, 761, 1217, 1901, 2129 |
| 23 | 213 580 | 12 | 47, 461, 599, 1289, 1427, 1979, 3083, 3221, 3911, 4049, 4877, 6947 |

Une seule entrée ne vérifie pas la seconde condition de Germain : 443 pour p = 13.

### Plus petit nombre premier auxiliaire vérifiant les deux conditions

| p | θ = 2Np + 1 | N |
| --- | --- | --- |
| 3 | 7 | 1 |
| 5 | 11 | 1 |
| 7 | 29 | 2 |
| 11 | 23 | 1 |
| 13 | 53 | 2 |
| 17 | 137 | 4 |
| 19 | 191 | 5 |
| 23 | 47 | 1 |
| 29 | 59 | 1 |
| 31 | 311 | 5 |
| 37 | 149 | 2 |
| 41 | 83 | 1 |
| 43 | 173 | 2 |
| 47 | 659 | 7 |
| 53 | 107 | 1 |
| 59 | 827 | 7 |
| 61 | 977 | 8 |
| 67 | 269 | 2 |
| 71 | 569 | 4 |
| 73 | 293 | 2 |
| 79 | 317 | 2 |
| 83 | 167 | 1 |
| 89 | 179 | 1 |
| 97 | 389 | 2 |

Pour chaque nombre premier compris entre 100 et 197, un N ≤ 8 convient également. Pour p = 197, les seuls nombres premiers de la forme 2N·197 + 1 avec N < 19 sont 3547 et 4729, et tous deux possèdent des résidus consécutifs. N = 19 donne 7487, qui vérifie les deux conditions.

### Premier cas modulo p²

Les solutions de la congruence xᵖ + yᵖ ≡ zᵖ (mod p²), avec p ne divisant aucun des nombres x, y, z, ont été recherchées pour chaque nombre premier impair inférieur à 100.

- Aucune solution : p = 3, 5, 11, 17, 23, 29, 41, 47, 53, 71, 89.
- Une solution existe : p = 7, 13, 19, 31, 37, 43, 59, 61, 67, 73, 79, 83, 97. Exemple : 1⁷ + 2⁷ ≡ 3⁷ (mod 49).

### Nombres premiers forcés et leur produit M

| p | Nombres premiers forcés | M |
| --- | --- | --- |
| 3 | 2, 3, 7, 13 | 546 |
| 5 | 2, 5, 11, 41, 71, 101 | 32 341 210 |
| 7 | 2, 29, 71, 113, 491 | 228 478 994 |
| 11 | 2, 11, 23, 89, 947, 1409 | 60 089 901 982 |
| 13 | 2, 53, 131, 443, 521 | 3 204 930 458 |

Les solutions locales utilisées dans la réciproque ont été confirmées par recherche exhaustive pour p = 3 et p = 5, en chaque nombre premier de 2 à 31 que l’argument fait intervenir.

### Nombres premiers irréguliers

Un nombre premier p est irrégulier lorsqu’il divise le numérateur d’un nombre de Bernoulli d’indice pair compris entre 2 et p − 3.

| Nombre premier irrégulier | Indice du nombre de Bernoulli |
| --- | --- |
| 37 | 32 |
| 59 | 44 |
| 67 | 58 |
| 101 | 68 |
| 103 | 24 |
| 131 | 22 |
| 149 | 130 |
| 157 | 62 et 110 |

En dessous de 1000, il y a 167 nombres premiers impairs, dont 64 sont irréguliers (38,3 %). Le numérateur de B₃₂ est −7709321041217 = −37 × 208360028141, et son dénominateur est 510.

### Faits annexes

- 2³² + 1 = 4294967297 = 641 × 6700417.
- Les formes réduites de discriminant −23 sont (1, 1, 6), (2, 1, 3) et (2, −1, 3). Les discriminants −3, −7, −11, −19 et −43 n’ont chacun qu’une seule forme réduite.
- La forme x² + xy + 6y² prend la valeur 6, mais jamais 2 ni 3.
- Des recherches de contrôle n’ont trouvé aucune solution de x⁴ + y⁴ = z² avec 1 ≤ x ≤ y < 400, ni aucune de x³ + y³ = z³ avec 1 ≤ x ≤ y < 1500. Les démonstrations ne dépendent pas de ces recherches.
