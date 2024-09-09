## **Atletas Brasileiros**

### **Aplicação: Busca de Atletas Brasileiros**

**Descrição:**

Esta aplicação web permite a busca por atletas brasileiros, exibindo resultados relevantes com base na pesquisa realizada pelo usuário. A interface simples e intuitiva facilita a navegação e a busca por informações sobre diversos atletas.

**Funcionalidades:**

* **Campo de pesquisa:** O usuário digita o nome do atleta desejado.
* **Resultados dinâmicos:** A lista de resultados é atualizada em tempo real conforme o usuário digita.
* **Detalhes do atleta:** Ao clicar em um resultado, o usuário é direcionado para a página do atleta (link externo).
* **Dados:** Os dados dos atletas são armazenados em um arquivo JavaScript separado (dados.js) para facilitar a manutenção.

**Tecnologias Utilizadas:**

* **HTML:** Estrutura básica da página, definindo os elementos da interface do usuário.
* **CSS:** Estilização da página, definindo as cores, fontes, layout e responsividade.
* **JavaScript:** Lógica da aplicação, responsável por:
    * Capturar a entrada do usuário no campo de pesquisa.
    * Filtrar os dados dos atletas.
    * Atualizar a seção de resultados dinamicamente.
* **JSON:** Formato utilizado para armazenar os dados dos atletas no arquivo dados.js.

**Como funciona:**

1. **Interface:** O usuário interage com a página através do campo de pesquisa e dos resultados exibidos.
2. **Evento de pesquisa:** Ao digitar no campo de pesquisa e clicar no botão "Pesquisar" ou pressionar Enter, a função `pesquisar()` é chamada.
3. **Filtragem dos dados:** A função `pesquisar()` percorre o array de dados dos atletas, comparando a entrada do usuário com os campos "titulo" (nome do atleta), "descricao" e "tags".
4. **Atualização da interface:** Os resultados encontrados são concatenados em uma string HTML e inseridos na seção de resultados, substituindo o conteúdo anterior.
5. **Links externos:** Ao clicar em um resultado, o usuário é direcionado para o link externo associado ao atleta.

**Estrutura de arquivos:**

* **index.html:** Arquivo principal da aplicação, contendo a estrutura HTML da página.
* **style.css:** Arquivo CSS responsável pela estilização da página.
* **dados.js:** Arquivo JavaScript contendo os dados dos atletas em formato JSON.
* **script.js:** Arquivo JavaScript contendo a lógica da aplicação.

**Para executar a aplicação:**

1. **Criar os arquivos:** Crie os arquivos index.html, style.css, dados.js e script.js com o conteúdo fornecido.
2. **Abrir em um navegador:** Abra o arquivo index.html em qualquer navegador web moderno.

**Observações:**

* **Dados dos atletas:** O arquivo dados.js deve ser preenchido com os dados dos atletas que você deseja incluir na aplicação.
* **Personalização:** Você pode personalizar a aparência da página e adicionar novas funcionalidades, como ordenação dos resultados, filtros adicionais ou integração com APIs externas.
* **Otimizações:** Para aplicações maiores, considere otimizar o código JavaScript e utilizar técnicas de pré-renderização para melhorar o desempenho.

**Próximos passos:**

* **Expandir a base de dados:** Adicionar mais atletas e informações detalhadas.
* **Implementar filtros:** Permitir que o usuário filtre os resultados por esporte, nacionalidade ou outros critérios.
* **Melhorar a interface:** Criar uma interface mais visualmente atraente e responsiva.
* **Integrar com APIs:** Utilizar APIs de esportes para obter dados em tempo real sobre os atletas.

**Contribuições:**

Se você deseja contribuir para este projeto, fique à vontade para enviar pull requests.

**Licença:**

Este projeto está licenciado sob a licença MIT.

**Agradecimentos:**

Agradecemos à comunidade open source por fornecer as ferramentas e recursos necessários para a criação desta aplicação.
