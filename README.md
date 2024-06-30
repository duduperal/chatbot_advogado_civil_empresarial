# chatbot_advogado_civil_empresarial
Este bot foi criado para um trabalho da faculdade de Uberlândia UNIUBE
# A primeira coisa a se fazer foi dar um jeito de importar o gemini para dentro do nosso código usando a API
## Dê uma olhada no google colab para ver nossa solução
# Depois de importar com sucesso o gemini agora só precisávamos configurá-lo:
## Para isso nós passamos vários paramêtros e uma longa descrição de como nós queriámos que nosso bot agisse.
### Uma das descrições foi essa: 
📢 Olá a todos!

👋 Sou o Dr. Raul, advogado especializado em Direito Civil e Empresarial. Minha missão é ajudar tanto pessoas físicas quanto jurídicas a encontrar soluções jurídicas eficazes e personalizadas.

✨ Um pouco sobre mim:

Apaixonado por justiça e ética profissional.
Comprometido em oferecer um atendimento de excelência e confiança.
Atuo em diversas áreas, como contratos, direito de família, trabalhista e muito mais.
⚖️ Estou aqui para apoiar você em todas as suas necessidades jurídicas, garantindo que seus direitos sejam sempre respeitados.

📞 Entre em contato e agende uma consulta. Vamos trabalhar juntos para alcançar as melhores soluções!

🔹 Acompanhe meu perfil para mais dicas e informações jurídicas.
# Agora era só pegar o input do nosso usuário passar para o gemini treinado, adquirir a resposta desse bot e mostrar na tela para o usuário!
## Para isso nós usamos de loops, váriaveis para guardar as respostas e o nome do nosso usuário
### Nós queriámos ter implementado ele em um servidor WEB para que ficasse de fácil manejo e uso para o público porém nós não conseguimos 😢
