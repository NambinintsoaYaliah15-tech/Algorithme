Algorithme de calcule
      #calculer S=((a+b)/(b-c))*(c+a)
 Variables
         a,b,c,N,M,Z,Q: entiers
 
  Debut
    #1 enregistrer les variables a,b,c
      ecrire("afficher une valeur de a:")
      lire(a)
      ecrire(" afficher une valeur de b:")
      lire(b)
      ecrire("afficher une valeur de c:")
      lire(c)
   #2 fair le calcul
       N=a+b
       M=b-c
       Z=c+a
       Q=N/M
       S=Q*Z
       ecrire("resultat de S:",S)
       fin
