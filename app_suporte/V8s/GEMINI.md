# Contexto do Diretório: `app_suporte/V8s`

Este diretório contém o histórico de versões e variações do projeto **"Meu Apoio Diário"**, uma aplicação web estática de suporte terapêutico para neurodivergentes (Foco em Autismo, TDAH e perfil PDA).

## 📂 Visão Geral

Os arquivos aqui são **Single Page Applications (SPAs)** completas, onde HTML, CSS e JavaScript estão todos contidos em um único arquivo. Isso permite que a aplicação seja executada offline e sem necessidade de servidor, bastando abrir o arquivo no navegador.

### Arquivos Principais

*   **`VV_BEST.html`**:
    *   **Descrição:** Atualmente a versão mais completa e robusta neste diretório.
    *   **Destaques:** Inclui todas as ferramentas de regulação (Respiração, Mindfulness, Hiperfoco), o Check-in de Autoconsciência, Quizzes educativos (PDA, Autismo) e, notavelmente, a **Escala HAD (Hospital Anxiety and Depression Scale)** para auto-reflexão.
    *   **Uso Recomendado:** Base para novas funcionalidades experimentais ou para uso quando se deseja o conjunto completo de ferramentas.

*   **`V8_light12.html`**:
    *   **Descrição:** Uma versão "Super Leve" (Light).
    *   **Destaques:** Otimizada para simplicidade visual e performance. Mantém as funcionalidades nucleares (Check-in, Estratégias PDA, Ferramentas de Regulação) mas com menos peso visual e scripts simplificados.
    *   **Uso Recomendado:** Para dispositivos mais antigos, conexões lentas ou momentos de sobrecarga sensorial onde uma interface minimalista é preferível.

*   **Outros Arquivos (`V8_CRÚ.html`, `v8 semi final...`)**:
    *   São versões de desenvolvimento anteriores ou "snapshots" de momentos específicos do projeto. Úteis apenas para referência histórica ou recuperação de código antigo.

## 🛠️ Instruções Técnica

### Como Executar
1.  Não há necessidade de `npm`, `build` ou servidores locais.
2.  Simplesmente clique duas vezes no arquivo `.html` desejado ou arraste-o para o seu navegador (Chrome, Edge, Firefox).

### Diretrizes de Edição
*   **Arquitetura Monolítica:** Todo o código (Estrutura, Estilo, Lógica) reside no mesmo arquivo.
    *   `<style>`: CSS (Variáveis de cores no `:root`).
    *   `<body>`: Estrutura HTML semântica (Abas, Conteineres).
    *   `<script>`: Lógica JS (Funções globais anexadas a `window` para handlers de eventos).
*   **Convenções:**
    *   Mantenha o código "Vanilla" (sem frameworks).
    *   Ao editar, verifique se as alterações em um arquivo (ex: correção de bug no Check-in) devem ser replicadas nos outros (ex: `VV_BEST` e `V8_light12`).
    *   **Neuro-Afirmativo:** Mantenha a linguagem validante e o design acessível (cores suaves, sem animações bruscas).

## 🧠 Contexto do Usuário (Rodrigo)
*   **Perfil:** AuDHD (Autismo + TDAH) com perfil PDA (Evitação de Demandas).
*   **Objetivo do App:** Funcionar como um "Cérebro Externo" para regulação emocional e suporte à função executiva.
*   **Atenção:** O conteúdo sobre a **Escala HAD** e **PDA** é sensível e deve sempre vir acompanhado dos *disclaimers* de que **não são diagnósticos médicos**.
