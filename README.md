# Explicação do código

# Pré-requisito
1- Comandos básicos de linux
2- Programação em python (recomendado - porém é possível executar o teste sem o prévio conhecimento)

## Disclaimers:
1- O código foi criado pelo instrutor Cassiano Peres {DIO  Tech Education Analyst}
2- O projeto original encontra-se em: https://github.com/cassiano-dio/cibersecurity-desafio-ransomware![image](https://github.com/alexsansantos/cibersecurity-desafio-ransomware/assets/142915856/86403d14-1ae7-4bb4-9fd1-ab187690dbac)
3- O objetivo aqui é explicar algumas dificuldades que você pode encontrar na execução do código e algumas dicas do que pode melhorar
4-Como premissa está sendo utilizado o sistema operacional kali-linux (apenas por ser Recomendado)

## Detalhes

a- Crie uma pasta para que fique mais organizado os testes, você pode criá-la dentro do diretório de usuário, 
exemplo: ~/projetos/projeto_ransoware_py
b- crie um arquivo com o nome teste.txt e digite algum conteúdo dentro dele e salve.
importante (esse arquivo, juntamente com os arquivos python estão no repositório para download)
c- baixe os arquivos encrypter.py e descrypter.py e salve-os no diretório de projeto criado no passa (a)
d- execute o arquivo encrypter.py com o comando "python encrypter.py" (importante ressaltar que você deve executar o comando dentro do diretório onde estão salvos os arquivos)
c- com o comando "ls -l" voce ira verificar que o arquivo teste.txt passou a se chamar texte.txt.rensowaretroll; isso porque agora ele está criptografado!
e- se você abrir esse arquivo, {pelo terminal pode usar o comando "nano teste.txt.ransowaretroll}, você ira verificar que o conteúdo está todo criptrografado.
f- para descriptrografar, use o program decrypter com o comando "python decrypter.py".
g- com o comando "ls -l" voce ira verificar que o arquivo de teste voltou a ter o seu nome/extensão normal -> texte.txt
h- lendo novamente o arquivo, com o comando "nano teste.txt", você vai verificar que o arquivo está legível.

## Considerações finais

I - o nome do arquivo "teste.txt" está destacado dentro dos códigos python (arquivos encrypter.py e decrypter.py), desta forma, você pode ajustar o código conforme a sua necessidade.
II - a chave de criptografia de 16bits está dentro dos arquivos, salvo pela variável "key", você pode mudá-la, porem deve manter o total de caracteres
III - o .ranswaretroll que é colocado ao final do arquivo após a criptografia, também é definido nos códigos, e você pode mudá-lo.

## Dica 

Considere estudar python e enteder todo o código, aqui foi apenas explanado o básico para algum ajustes que possam ser feitos.
Espero que tenha curtido o conteúdo e a explicação.

"Conhecimento é pode, e onde usá-lo é o que diferencia as pessoas"

Abraços
Alex Sandro


