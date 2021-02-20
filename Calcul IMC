def calcul_imc(masse, taille):
    return masse/(taille**2)
 
masse_utilisateur = int(input("Entrez votre poids en kg:"))
taille_utilisateur = float(input("Entrez votre taille en m:"))
imc = calcul_imc(masse_utilisateur, taille_utilisateur)
 
if imc < 16.5:
    print("Vous êtes trop dénutris!")
elif 16.5<imc<18.5:
    print("Vous êtes maigre!")
elif 18.5<imc<25.0:
    print("Vous êtes de corpulence normal")
elif 25.0<imc<30.0:
    print("Vous êtes en surpoids")
elif 30.0<imc<35.0:
    print("Vous êtes en obesité modérée")
elif 35.0<imc<40.0:
    print("Vous êtes en obesité sévère")
elif imc > 40.0:
    print("Vous êtes en obésité morbide")
