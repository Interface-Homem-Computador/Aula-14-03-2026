# Atividade: Arquitetura de Modelagem do "CodeMentor AI"

**Cenário e Desafio Técnico:**
Você foi designado como engenheiro de software líder para projetar o motor de personalização do "CodeMentor AI", um plugin corporativo para IDEs criado para treinar desenvolvedores recém-contratados. A diretoria exige que a ferramenta forneça valor desde o primeiro minuto do funcionário na empresa (antes mesmo de ele digitar muito código), mapeie continuamente sua evolução técnica em relação aos padrões arquiteturais exigidos pelos engenheiros especialistas da casa e utilize *Deep Learning* para sugerir bibliotecas adequadas ao seu contexto. O time de UX, contudo, alertou sobre os riscos de o sistema alterar o código sozinho de forma imprevisível e de o funcionário rejeitar as sugestões da IA por não entender a origem delas.

Escreva uma proposta de arquitetura de Modelagem de Usuário para o plugin resolvendo este cenário. Sua proposta deve descrever um fluxo único de funcionamento que incorpore obrigatoriamente as seguintes soluções embasadas na teoria de IHC:

1. A técnica exata que será usada no momento do login inicial para contornar o problema do "Cold Start" e como ela será implementada.
2. A aplicação do **Modelo Overlay (Sobreposição)** para processar o código que o usuário está digitando e calcular dinamicamente o que precisa ser ensinado a ele.
3. A definição do paradigma de **Iniciativa Mista**, detalhando qual comportamento do plugin será puramente **Adaptativo** (sob controle da máquina) e qual será **Adaptável** (sob controle do usuário).
4. O mecanismo de **Transparência e Controle** projetado na interface para mitigar o efeito "Caixa Preta" gerado pelo uso do *Deep Learning* nas recomendações.

---

### Gabarito / Critérios de Avaliação Esperados

O aluno deve apresentar um texto coeso interligando os quatro pontos. A avaliação deve focar em:

* **Item 1:** O aluno deve propor o uso de **Estereótipos**. Exemplo aceitável: O sistema faz 2 ou 3 perguntas iniciais (ex: "Qual sua senioridade e área?") e o coloca em um "cesto" pré-definido para fazer as primeiras sugestões.
* **Item 2:** O aluno deve explicar que o sistema vai comparar o conhecimento atual do usuário (o código que ele acabou de escrever) com o "Modelo Especialista" (o padrão de código da empresa)[. A divergência (área vazia/bugs) ditará o tutorial ou dica que aparecerá na tela.
* **Item 3:** O aluno precisa exemplificar corretamente. **Adaptativo**: O plugin infere o erro e destaca a linha de código sozinho. **Adaptável**: O usuário possui um painel de configurações para desligar as dicas visuais ou ajustar o nível de interferência da IA.
* **Item 4:** Para resolver a "Caixa Preta", o aluno deve propor ferramentas de explicabilidade na interface. Exemplo aceitável: Um botão "Por que estou vendo isso?" ao lado de cada recomendação, ou rótulos que digam "Sugerido porque você costuma errar tipagem de variáveis".

* ### 📧 Instruções de Envio

> **Enviar para o professor:** `karan.luciano@afya.com.br`
> 
> **Assunto do E-mail:** [IHC] Nome do Aluno - Arquitetura de Modelagem
