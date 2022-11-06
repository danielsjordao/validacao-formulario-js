# validacao-formulario-js

Acesse o formulário: http://127.0.0.1:5500/cadastro.html

Validações customizadas utilizando técnicas atuais com JavaScript

Preencher campos de endereço automaticamente com requisições à API da ViaCEP

Projeto desenvolvido tendo como parâmetro o curso ministrado pela Alura "JavaScript na Web: validação de Formulários e HTML5

#Apresentação da página principal de cadastro

![image](https://user-images.githubusercontent.com/101356855/200185963-60d135d9-9e7a-415e-821c-6377e11cdcf4.png)

Para completar o cadastro, o usuário deve preencher todos os dados e caso insira alguma informação que esteja fora do padrão definido em JavaScript retornará a mensagem.
Uilização de Regex para elaboração de senha alphanumérica, com condição de não aceitação de caracteres especiais.

![image](https://user-images.githubusercontent.com/101356855/200186155-a1260ae0-6524-4205-8343-b7fc01859309.png)

![image](https://user-images.githubusercontent.com/101356855/200186209-f0bfda8e-e493-4fad-bc6a-958f6371bbc4.png)

Um dos parâmetros definido em JS é que apenas maiores de idade poderão se cadastrar

![image](https://user-images.githubusercontent.com/101356855/200186236-0e6de195-5be6-45ad-b101-e5fd5e3b93e2.png)

Outra condição foi acerca do CPF, como não podemos consumir a API da Receita Federal do Brasil, inserimos condições para não aceitar números sequenciais.

![image](https://user-images.githubusercontent.com/101356855/200186351-017fe72a-d0a1-4299-be6d-cf80d5af9751.png)

Outra condição sendo comsumida por API VIACEP é a busca de endereço após digitar um CEP válido. Caso o usuário digite um CEP inválido o campo informará inválido.

![image](https://user-images.githubusercontent.com/101356855/200186466-cdea7699-3b4f-4d82-8498-659f9d3553c5.png)

Após digitar os dados corretamente, o usuário receberá a informação que a conta já está cadastrada.

![image](https://user-images.githubusercontent.com/101356855/200186528-56338512-51fa-4f0a-ba52-6bd3a1d7a565.png)


