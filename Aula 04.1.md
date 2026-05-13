<img width="1059" height="578" alt="image" src="https://github.com/user-attachments/assets/14b47b3e-398c-4a0f-8edf-3aba5d214709" />

media1 = float (input ("Digite a sua primeira nota"))

media2 = float (input ("Digite a sua segunda nota"))

media3 = float (input ("Digite a sua terceira nota"))

mediageral = (media1 + media2 + media3)/3

if mediageral >= 7.0:

  print ("Aprovado")
  
else:

  print ("Reprovado")

---

<img width="905" height="486" alt="image" src="https://github.com/user-attachments/assets/345db6ef-a32e-417a-818d-c4d49817e031" />


media1 = float (input ("Digite a sua primeira nota"))

media2 = float (input ("Digite a sua segunda nota"))

media3 = float (input ("Digite a sua terceira nota"))

mediageral = (media1 + media2 + media3)/3

if mediageral >= 7.0:

    print ("Aprovado, sua nota foi de {:.2f}".format (mediageral))

elif mediageral >= 5.0 and mediageral <= 6.9:

    print ("Recuperação, sua nota foi de {:.2f}".format(mediageral))

else:

    print ("Reprovado, sua nota foi de {:.2f}".format(mediageral))
