# 1.Como usuário quero adicionar os dados do animal a ser entregue para adoção no sistema
## Inicial: O cliente coloca imagem, nome, peso, tamanho, idade, raça, genêro e outras observações necessárias dentro do sistema para serem vísiveis aos outros usuários
## Normal: O pet fica vísivel para todos exceto quem o cadastrou para adoção, alguém se interessa pela adoção e contata o usuário
## O que pode dar errado: Dados não serem válidos(impossíveis ou erro de informação)
## Outros: Falta de moderação nos conteúdos(ambos de pet e de conversas) pode ser problemático
## Conclusão: Após conversa com o possível adotante, e aceitação do pet ser adotado se deleta do banco de dados os dados do pet para adoção

# 2.Como usuário quero modificar os dados do animal cadastrado no sistema
## Inicial: O cliente seleciona o pet a se mudar os dados
## Normal: O pet tem de ser removido e readicionado com os dados certos
## O que pode dar errado: Dados não serem válidos(impossíveis ou erro de informação)
## Outros: Falta de moderação nos conteúdos pode ser problemático
## Conclusão: O pet reaparece no banco de dados com os dados modificados

# 3.Como usuário quero adotar um pet
## Inicial: Vendo os animais disponíveis para adoção, clico em algum deles
## Normal: Leva a tela de contato com quem pôs o pet para adoção, e eles começam a se comunicar sobre a possível adoção
## O que pode dar errado: 
## Outros: Possível não se executar a adoção e manter os status do pet
## Conclusão: Um pet é adotado e removido do banco de dados

# 4.Como administrador quero enviar mensagem à um usuário que colocou um pet para adoção
## Inicial: O administrador clica no usuário e aparece a tela de chat
## Normal: Ele manda a mensagem desejada e talvez remova o pet colocado para adoção tmeporariamente
## O que pode dar errado: 
## Outros: Os dados de presença do usuário podem ser vísiveis para o administrador
## Conclusão: O administrador se resolveu com o usuário
