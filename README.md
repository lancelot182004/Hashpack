# Hashpack
O Hashpack consegue criar Hashs com qualquer texto colocado pelo usuario
Esse projeto faz parte de uma série futura de sistemas que conseguem explorar a criptografia gerando segurança em meio ao caos da era cibernetica. 
É uma pesquisa pessoal para o desenvolvimento de ferramentas ainda mais avançadas na area de segurança cibernetica. 

# Por dentro das Linhas 

O usuario tera 4 opçoes de hashs para escolher

1º MD5
  
  O MD5 (Message Digest Algorithm 5) é uma função de hash criptográfica que transforma uma entrada de dados em uma sequência de caracteres de tamanho fixo geralmente representada por uma sequência hexadecimal de 
  32 caracteres12. Essa sequência é conhecida como “hash” ou “digest”.

2º SHA256
  SHA-256 (Secure Hash Algorithm 256) é uma função de hash criptográfica que gera um valor de hash de tamanho fixo de 256 bits (32 bytes). Este algoritmo faz parte da família SHA-2, desenvolvida pela NSA (Agência 
 de Segurança Nacional dos EUA) e é amplamente utilizado para garantir a integridade e a segurança dos dados
  
3º SHA1 
  SHA-1 é mais frequentemente usado para verificar se um arquivo não foi alterado. Isso é feito produzindo uma soma de verificação antes de o arquivo ser transmitido e, novamente, quando ele atinge seu destino.
  
4º SHA512
  SHA-512 (Secure Hash Algorithm 512) é uma função de hash criptográfica que gera um valor de hash de 512 bits (64 bytes). Este algoritmo faz parte da família SHA-2, desenvolvida pela NSA (Agência de Segurança Nacional dos EUA), e é amplamente utilizado para garantir a integridade e a segurança dos dados.

Vamos usar como exemplo SHA512. Logo com o auxilio da importação da biblioteca hashlib onde:

    import hashlib 

Temos: 

kcode = hashlib.sha512 ((v4).encode ('utf-8')).hexdigest()

sendo 'v4' a variavel que recebe o valor do usuario. 

Por fim:

print ('O valor criado é de: ',kcode)
