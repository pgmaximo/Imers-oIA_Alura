# Chatbot de Recomendação de Treinamentos do Google Cloud Platform
Este projeto apresenta um chatbot inteligente desenvolvido para auxiliar na seleção de treinamentos do Google Cloud Platform (GCP) da Matza, ideal para profissionais que buscam aprimorar suas habilidades na nuvem. 
Tive o intuido de proceder com o projeto por causa da Imersão IA da Alura, onde ensinaram muito sobre o Gemini e sua API. O desafio final era entregar um projeto funcional e este é o meu!
# Funcionalidades:
Compreensão de linguagem natural: O chatbot interpreta as necessidades de treinamento descritas pelo usuário em linguagem natural.
Análise de similaridade semântica: Utiliza embeddings de texto para comparar a descrição do usuário com o conteúdo dos materiais de treinamento.
Recomendação personalizada: Sugere o treinamento mais adequado com base na análise de similaridade, levando em consideração o nível de experiência, tópicos de interesse e pré-requisitos.
Geração de resumos informativos: Fornece um resumo conciso e informativo do treinamento recomendado, incluindo nome, descrição, duração, formato, nível de experiência, módulos, pré-requisitos, laboratórios, tópicos abordados e tópicos não abordados.
Interface conversacional: Permite uma interação natural e intuitiva com o usuário através de um chatbot.
# Tecnologias:
Google Generative AI: Potencializado pelos modelos de linguagem avançados do Google, incluindo Gemini para geração de texto e embeddings para análise semântica.
PyPDF2: Extração de texto de arquivos PDF contendo informações sobre os treinamentos.
Pandas: Estruturar e manipular os dados dos treinamentos.
NumPy: Cálculo de similaridade entre embeddings.
# Utilização:
1. Configuração:
Instale as bibliotecas necessárias: google-generativeai, pypdf2, gdown.
Configure a chave API do Google Generative AI.
Defina o caminho da pasta contendo os PDFs dos treinamentos.
2. Execução:
Execute o script Python.
Interaja com o chatbot através do prompt, descrevendo suas necessidades de treinamento.
Receba a recomendação do treinamento mais adequado.
Avalie a recomendação fornecendo feedback (útil/não útil).
# Próximos Passos:
Implementar um sistema de feedback mais robusto, permitindo aos usuários fornecer avaliações detalhadas sobre as recomendações.
Integrar o chatbot a outras plataformas de comunicação, como Slack ou Microsoft Teams.
Expandir a base de dados de treinamentos para incluir outras áreas de conhecimento do GCP.
# Contribuições:
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com sugestões de melhorias, correções de bugs ou novas funcionalidades.
# Contato:
Em caso de dúvidas ou sugestões, entre em contato com pedrogmaximo@gmail.com.
# Observação:
Este projeto foi desenvolvido com fins educacionais e demonstrativos. Pode ser adaptado e expandido para atender às necessidades específicas de outras organizações.
