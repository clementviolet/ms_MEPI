---
authors:
- Kevyn Raynal
- Clément Violet
documentclass: article
classoption: oneside
mainlang: french
geometry:
  - left = 2cm
  - right = 2cm
  - top = 2cm
  - bottom = 2cm
mainfont: Lato
fontsize: 12pt
toc: false
---

# Objectif du modèle

L’objectif de ce modèle est d’observer la dynamique de la transmission de la dengue par le moustique *Aedes albopictus*. Cette maladie infectieuse menace chaque année près de 40% de la population mondiale et infecte chaque année entre 50 et 100 milions de personnes selon l’OMS. L’originalité de ce modèle est qu’il ne s’intéresse pas à la principale espèce de moustique vecteur de la dingue qui est *Aedes aegypti*. Si les auteurs préfères s’intéresser à *Aedes albopictus*, c’est parce que cette espèce a été la cause de plusieurs épidémie de dengue, cette espèce est plus difficile à contrôler, elle a un taux de morsure supérieur et est plus compétitivz qu’*A. aegypti*.

Les auteurs ont créé un premier modèle en couplant un modèle classique SEIR pour modéliser la dynamique de l'infection chez l'Homme avec un modèle SEI pour modéliser la dynamique de la maladie chez le vecteur. 

Le modèle de dynamique chez l'Homme est le suivant :

$$ \frac{dH_s}{dt} = \lambda H_t - H_s \left(\frac{cV_i}{H_t} + \mu_h\right)$$ {#eq:eq1}
$$ \frac{dH_e}{dt} = H_s \frac{cV_i}{H_t} - H_e (\tau_{exh} + \mu_h)$$ {#eq:eq2}
$$ \frac{dH_i}{dt} = H_e\tau_{exh} - H_i\left(\tau_{ih} + \alpha + \mu_h\right)$$ {#eq:eq3}
$$ \frac{dH_r}{dt} = H_i\left(\tau_{ih}\right) - \mu_h H_r$$ {#eq:eq4}

Le modèle de dynamique épidémiologique pour le moustique est celui-ci :

$$ \frac{dV_s}{dt} = \mu_aV_t - V_s \left(\frac{cH_i}{H_t} + mu_a\right)$$ {#eq:eq5}
$$ \frac{dV_e}{dt} = V_s \frac{cH_i}{H_t} - V_e \left(\tau_{ex\nu} + \mu_a\right)$$ {#eq:eq6}
$$ \frac{dV_i}{dt} = V_e\tau_{ex\nu} - \mu_aV_i $$ {#eq:eq7}

# Reproductibilité de l'article

Ut a risus placerat, tempor magna in, efficitur leo. Nunc et tristique diam, vitae commodo nisi. In eu lorem et odio vehicula sagittis malesuada eu dolor. Aenean venenatis dui eget justo suscipit, eu mattis neque rutrum. In finibus suscipit eros, ac bibendum massa iaculis et. Duis sit amet hendrerit lorem, sit amet hendrerit eros. Proin cursus cursus ipsum, et feugiat augue suscipit vitae. Phasellus vitae neque nec lectus viverra pulvinar. Sed eget orci non nunc tempor rutrum ut sagittis nunc. Quisque auctor metus nec leo fermentum, non tincidunt nisl imperdiet.

# Modélisation complémentaire

Pellentesque ac porta purus. Phasellus et pellentesque lacus, pulvinar vulputate dui. Pellentesque posuere pellentesque nisi vel ultricies. Vivamus at neque convallis, dignissim magna eget, aliquet ante. Maecenas venenatis, diam in maximus varius, felis ligula faucibus tellus, at tincidunt ligula ex eu mi. Nunc volutpat leo a nunc laoreet commodo. In hac habitasse platea dictumst. Aenean pellentesque arcu ut lacus pulvinar semper. Etiam convallis, magna maximus congue gravida, urna leo porttitor felis, ut luctus turpis lacus in enim. Vestibulum volutpat nulla libero, id cursus lacus faucibus sed. Quisque finibus metus quis lorem iaculis, a scelerisque diam tincidunt. Nulla placerat blandit quam, eu posuere augue. Cras sem ligula, sodales non sem at, interdum pretium quam. Cras eget justo blandit, lobortis diam sit amet, eleifend lorem.

# Interprétations

Pellentesque bibendum libero metus, sed laoreet nisl ornare eget. Interdum et malesuada fames ac ante ipsum primis in faucibus. Morbi varius mauris eu ipsum pellentesque accumsan a vitae turpis. Sed laoreet finibus purus, venenatis facilisis mi. Curabitur molestie dui nibh, non condimentum metus efficitur nec. Fusce nisl eros, bibendum et fermentum vel, commodo eu est. Sed tristique eleifend felis, sed porttitor tellus luctus non. Mauris eros metus, rhoncus viverra imperdiet eget, tempor in odio. Aliquam dapibus pharetra tortor sit amet fermentum.

# Synthèse

Proin eleifend eros eget ante porta, at hendrerit urna pharetra. Duis a lacus condimentum, dignissim lacus et, tincidunt enim. Quisque ac efficitur velit. Sed semper ligula id lacus venenatis hendrerit. Phasellus a nisl id sapien porttitor cursus sed sit amet orci. Praesent blandit feugiat neque ac feugiat. Quisque dictum enim sed velit sodales pellentesque. In sapien ligula, bibendum ac purus vitae, luctus venenatis nisl. Nulla nec posuere velit. Suspendisse ex ex, laoreet ac ante eu, scelerisque tincidunt ipsum. Pellentesque hendrerit vestibulum mollis. Aliquam et neque hendrerit risus sagittis placerat.

# References
