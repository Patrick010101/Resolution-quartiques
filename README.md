Posons l'équation réduite liée à az^4 + bz^3 + cz^2 + dz + e = 0 (x = z - b / 4a)

x^4 + px^2 + qx + r = (x² + fx + g)(x² - fx + h) = 0

si on avait posé (x² + fx + g)(x² + ix + h), on trouvait "facilement" que i = -f

on continue avec f différent de 0 sinon on a une équation bicarrée que l'on sait résoudre

on trouve :

g = (f^3 + pf - q) / 2f

h = (f^3 + pf + q) / 2f

f^6 + 2pf^4 + (p^2-4r) f² - q² = 0

on pose F = f² donc F^3 + 2pF² + (p^2-4r)F - q² = 0 que l'on sait résoudre (Cardan)

soit F une solution de cette équation cubique (et donc f = sqrt(F))

en "simplifiant", on obtient les 4 solutions dans C de notre équation réduite

xi = (± f ± sqrt(-f² - 2p ± 2q/f)) / 2

et zi = xi - b/4a

pour mettre les signes + et - au bon endroit :

x1 = (- f + sqrt(-f² - 2p + 2q/f)) / 2

x2 = (- f - sqrt(-f² - 2p + 2q/f)) / 2

x3 = (  f + sqrt(-f² - 2p - 2q/f)) / 2

x4 = (  f - sqrt(-f² - 2p - 2q/f)) / 2

Le fichier html joint implémente en javascritpt cette méthode



