frase_usuario=input("ENTRE COM SUA FRASE: ")                  
contador=0                                                    
                                                              
vogais="aeiouAEIOU"                                           
                                                              
for palavra in frase_usuario:                                 
    if palavra=='a' or palavra=='e' or palavra== 'i' or\      
       palavra=='o' or palavra=='u' or palavra=='A'or\        
       palavra=='E' or palavra=='I' or palavra=='O'or\        
       palavra=='U':                                          
       contador+=1                                            
print(contador)                                               
