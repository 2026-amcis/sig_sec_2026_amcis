Este campo de pesquisa, fortemente caracterizado pela intersecção entre **Sistemas de Informação (SI), segurança comportamental, governança de Inteligência Artificial e fatores humanos**, está sendo ativamente construído por uma rede global de acadêmicos de diversas instituições renomadas. 

Abaixo, apresento um panorama detalhado de quem são os pesquisadores, as principais ideias em debate e as perspectivas teóricas que sustentam essa discussão.

---

### 1. Quem está construindo o campo (Autores e Instituições Influentes)

Os principais grupos e autores que moldam este ecossistema de pesquisa podem ser divididos em quatro grandes frentes temáticas com base nos seus estudos:

*   **Uso de Shadow AI e Comportamento Organizacional:**
    *   **Hsieh-Hong Huang** (*National Taitung University*, Taiwan): Pioneiro em enquadrar o uso de GenAI não autorizada como um **Comportamento Pró-Organizacional Antiético (UPB)**, analisando o conflito entre o desempenho profissional e a conformidade com as políticas de segurança.
*   **Fatores Cognitivos, Carga Mental e Vigilância (O "Efeito Guarda-Baixa" da IA):**
    *   **Mohamed Abouzahra** (*California State University, Monterey Bay*): Formulou o conceito de **"AI Guard-Down Effect"** (Efeito Guarda-Baixa da IA), investigando como interfaces fluidas de IA geram overtrust (excesso de confiança) e desviam a atenção humana dos sinais de perigo.
    *   **Lakshika Vaishnav e Sanjay Goel** (*University at Albany, SUNY*): Conduzem experimentos com rastreamento ocular (*gaze tracking*) para provar que a carga cognitiva e o estresse afetam diretamente a resposta dos funcionários a alertas de segurança.
    *   **Frederick Adrah e Arindam Ray** (*University of North Carolina Greensboro*): Estudam o impacto do trabalho remoto e do *cyberslacking* (uso pessoal da internet no trabalho) sob a ótica da sobrecarga mental.
    *   **Akanksha Shukla** (*Wipro Technologies*) e pesquisadores da *East Texas A&M University*: Pesquisam como o uso substitutivo da IA (automação) em comparação com o uso complementar (aumento) reduz a vigilância cognitiva diante de deepfakes e phishing.
*   **Segurança Socio-Técnica e Prevenção "na Concepção":**
    *   **Jonas Fegert** (*Karlsruhe Institute of Technology - KIT*): Desenvolveu a lente de **Context-Aware Cybersecurity (CAC)**, que defende que a segurança não é um fator meramente técnico, mas emerge do alinhamento entre os contextos geopolítico, organizacional e de interação.
    *   **Raghvendra Singh, Kevin Cleary e Sanjukta Das Smith** (*University at Buffalo*): Investigam o "estágio de concepção" do ataque, introduzindo o construto de **"role-intent"** (intenção baseada no papel organizacional) para discernir entre experimentação legítima e sondagem maliciosa.
*   **Governança de IA, Transparência e Regulamentação:**
    *   **Edna Dias Canedo e Andressa Girotto Vargas** (*Universidade de Brasília - UnB*): Propõem modelos práticos de governança para equilibrar as demandas de **explicabilidade da IA (XAI)** com as restrições de privacidade (LGPD e GDPR).
    *   **Daniel Juan Sivizaca Conde** (*Freie Universität Berlin*): Lidera pesquisas empíricas sobre a auditabilidade de dados de treinamento à luz do **EU AI Act**.
    *   **Arunabha Mukhopadhyay** (*IIM Lucknow*): Um dos autores mais produtivos presentes nas fontes, atuando na modelagem matemática de riscos de segurança e na implementação de identidades descentralizadas (Self-Sovereign Identity - SSI) no setor público.

---

### 2. Ideias que aparecem com mais frequência (Temas Centrais)

A literatura orbita em torno de três paradoxos e tensões recorrentes:

1.  **O Paradoxo da Produtividade vs. Segurança (Shadow AI):** Knowledge workers utilizam ferramentas de IA sem aprovação não por malícia, mas para suprir a falta de recursos internos e alcançar metas de desempenho. Isso cria uma grande vulnerabilidade, pois a entrada de dados confidenciais alimenta o aprendizado contínuo dos modelos públicos de linguagem.
2.  **A Desativação da Vigilância Humana (Efeito Guarda-Baixa):** À medida que a IA assume tarefas de interpretação de dados (por exemplo, resumindo e-mails ou filtrando mensagens), ocorre um fenômeno chamado de **Cognitive Offloading** (descarregamento cognitivo). A linguagem persuasiva, gramaticalmente fluida e confiante das ferramentas de IA gera um "Reliability Halo" (auréola de confiabilidade), fazendo com que as pessoas verifiquem menos a veracidade de informações sensíveis e fiquem vulneráveis a ataques sem necessidade de invasão técnica do sistema.
3.  **Governança Baseada em Evidências e Auditoria:** Os documentos destacam que a transparência puramente narrativa (textos livres e voluntários nas plataformas) não é suficiente para o cumprimento de novas leis como o *EU AI Act*. Há um forte apelo para a transição para sistemas de **Policy-as-Code** (políticas codificadas executáveis em tempo real por agentes de segurança de IA) e auditoria rigorosa de proveniência de dados.

---

### 3. Perspectivas Teóricas que Sustentam a Discussão

Para além das tecnologias, o campo está fortemente ancorado em bases teóricas robustas importadas da psicologia, economia e gestão:

*   **Teoria dos Sistemas Socio-Técnicos (STS):** Teoria que serve de guarda-chuva para a maioria das discussões de segurança da informação. Ela assume que a segurança não se resolve apenas com ferramentas técnicas, mas sim com a coordenação entre tecnologia, processos organizacionais e pessoas.
*   **Teoria da Motivação de Proteção (Protection Motivation Theory - PMT):** Essencial para compreender as reações dos utilizadores aos riscos. Avalia-se como os indivíduos percebem a **gravidade** e a **vulnerabilidade** a uma ameaça, contrastando com as suas capacidades individuais de lidar com esse risco (Autoeficácia).
*   **Teoria dos Escalões Superiores (Upper Echelons Theory - UET) e Visão Baseada em Atenção:** Utilizada para entender como a diversidade e a profundidade de envolvimento dos executivos (TMT - Top Management Team) influenciam a resiliência e as decisões de segurança nas organizações, provando que a governança no topo modela os resultados de prevenção e recuperação técnica.
*   **Teoria do Processamento de Informação Organizacional (OIPT):** Explica o risco de violação de dados através do desalinhamento entre a complexidade de processamento de dados demandada por diferentes áreas da IA e a capacidade real de monitorização da equipe de segurança.
*   **Teoria do Comportamento Pró-Organizacional Antiético (UPB):** Aplicada especificamente para desmistificar o uso de Shadow AI, demonstrando que funcionários bem-intencionados podem violar regras de conformidade se acreditarem que isso beneficiará os objetivos gerais da organização.
*   **Teoria de Sinalização (Signaling Theory):** Mobilizada para decodificar como investidores e parceiros externos interpretam as comunicações de desculpas, conformidade e transparência das empresas logo após incidentes de segurança.
*   **Teoria da Carga Cognitiva:** Usada para modelar os gargalos da memória operacional humana frente à proliferação de alertas de segurança e e-mails no dia a dia.

