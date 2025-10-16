Guia Turístico Colaborativo de Bagé
===================================

Uma plataforma web interativa e colaborativa para descobrir, avaliar e compartilhar os melhores pontos turísticos, restaurantes e locais de lazer em Bagé, RS.

📜 Sobre o Projeto
------------------

Este projeto foi desenvolvido como uma solução moderna e dinâmica para a exploração turística e local. Diferente de guias impressos ou sites desatualizados, nossa plataforma é alimentada pela própria comunidade. Moradores e visitantes podem compartilhar suas experiências, garantindo que as informações sejam sempre relevantes e autênticas.

O objetivo principal é valorizar a cultura e a economia local, dando visibilidade a estabelecimentos e pontos de interesse de forma democrática e acessível a todos.

Este projeto foi concebido e desenvolvido como trabalho final para a disciplina de **Gestão de Projetos**.

✨ Funcionalidades Principais
----------------------------

*   **Visualização em Mapa Interativo:** Todos os pontos são exibidos em um mapa dinâmico (Leaflet.js).
    
*   **Acesso Público:** Visitantes podem visualizar todos os pontos, filtrar por categorias e buscar locais sem a necessidade de login.
    
*   **Autenticação Segura:** Sistema de login com Google, gerenciado pelo Firebase Authentication.
    
*   **Conteúdo Colaborativo (Apenas para usuários logados):**
    
    *   **Adicionar Pontos:** Usuários logados podem cadastrar novos locais, definindo nome, endereço, descrição, categoria e localização no mapa.
        
    *   **Editar e Excluir:** Total controle sobre os pontos cadastrados.
        
    *   **Sistema de Avaliação:** Dê notas de 1 a 5 estrelas para os locais. A média é calculada e exibida em tempo real.
        
*   **Busca Inteligente:**
    
    *   Busca geral por endereço para navegar pelo mapa.
        
    *   Busca com autocomplete ao cadastrar um novo endereço.
        
    *   Botão "Minha Localização" para centralizar o mapa na posição atual do usuário.
        

🛠️ Tecnologias Utilizadas
--------------------------

*   **Frontend:** HTML5, CSS3, JavaScript (ES6 Modules)
    
*   **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
    
*   **Mapa:** [Leaflet.js](https://leafletjs.com/)
    
*   **Ícones:** [Font Awesome](https://fontawesome.com/)
    
*   **Backend & Banco de Dados:** [Google Firebase](https://firebase.google.com/)
    
    *   **Firestore:** Banco de dados NoSQL em tempo real.
        
    *   **Authentication:** Sistema de autenticação de usuários.
        
*   **APIs Externas:** [Nominatim (OpenStreetMap)](https://nominatim.org/) para geocodificação e busca de endereços.
    

🚀 Como Executar o Projeto
--------------------------

A aplicação foi desenvolvida em um único arquivo, o que simplifica sua execução.

1.  **Clone ou baixe** este repositório.
    
2.  **Abra o arquivo index.html** em qualquer navegador de internet moderno (Google Chrome, Firefox, etc.).
    
3.  const firebaseConfig = { apiKey: "SUA\_API\_KEY", authDomain: "SEU\_AUTH\_DOMAIN", projectId: "SEU\_PROJECT\_ID", // ...e as outras chaves};
    
    *   Para que a aplicação se conecte ao banco de dados, é crucial substituir o objeto firebaseConfig no código pelas suas próprias credenciais do Firebase.
        
    *   Encontre a seção no final do arquivo index.html e cole sua configuração:</div></li></ul></li></ol><h2 class="slate-h2">👥 Autores</h2><ul class="slate-ul"><li class="slate-li"><div style="position:relative">Matheus Fagundes de Oliveira</div></li><li class="slate-li"><div style="position:relative">Vitor \[Sobrenome\]</div></li><li class="slate-li"><div style="position:relative">Andre \[Sobrenome\]</div></li></ul></x-turndown>