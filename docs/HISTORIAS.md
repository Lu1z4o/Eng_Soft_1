# Histórias de usuário

# Persona: Pedro Martins (Fã de corridas de automobilismo)

## 1.1. Funcionalidade: Receber Alertas de Eventos Estratégicos Durante a Corrida

**História:**  
Como Pedro Martins, quero receber alertas sobre eventos estratégicos importantes (como pit stops, ultrapassagens e safety car) durante a corrida, para acompanhar melhor as mudanças táticas em tempo real.

**Tarefas:**
- Integrar sistema de alertas com os eventos em tempo real da corrida
- Criar lógica de gatilhos para eventos relevantes (pit stop, bandeiras, ultrapassagens)
- Exibir notificações não intrusivas dentro da interface da corrida
- Permitir ativar ou desativar tipos específicos de alerta nas configurações

**Critérios de Aceite:**
- O sistema deve enviar alertas durante a corrida em tempo real com base em dados recebidos da API.
- Os alertas devem ser discretos, mas visíveis, e personalizáveis por tipo de evento.
- O recurso deve funcionar tanto em mobile quanto em desktop.

---

## 1.2. Funcionalidade: Classificação Geral
**História:**  
Como Pedro Martins, quero ver a classificação atualizada do campeonato para acompanhar o desempenho acumulado dos pilotos e equipes.

**Tarefas:**
- Criar tela de classificação com pilotos e equipes
- Integrar dados de pontuação por corrida
- Adicionar filtros por categoria

**Critérios de Aceite:**
- A tela deve mostrar ranking, pontos e variação de posição.
- A classificação deve ser atualizada automaticamente após cada corrida.
- Deve ser possível alternar entre diferentes categorias.

---

## 1.3. Funcionalidade: Comparar Estatísticas de Temporada entre Pilotos

**História:**  
Como Pedro Martins, quero comparar estatísticas como pontos, poles e vitórias entre dois pilotos ao longo da temporada, para avaliar quem está tendo o melhor desempenho geral.

**Tarefas:**
- Criar interface de comparação entre pilotos por temporada
- Permitir seleção de dois pilotos para comparação
- Exibir gráficos comparativos de pontos, vitórias, poles e média de classificação
- Adicionar indicadores visuais para destacar quem lidera em cada métrica

**Critérios de Aceite:**
- O sistema deve permitir a comparação de estatísticas acumuladas entre dois pilotos.
- Devem ser apresentados pelo menos: total de pontos, número de vitórias, poles e pódios.
- A comparação deve estar disponível em versão responsiva para desktop e mobile.
- Os dados devem ser atualizados automaticamente após cada corrida.

---

# Persona: Juliana Santana (Fã Casual)

## 2.1. Funcionalidade: Receber Notificações e Resumo Pós-Corrida
**História:**  
Como Juliana Santana, quero receber uma notificação e um resumo visual após cada corrida para entender rapidamente o que aconteceu e poder compartilhar.

**Tarefas:**
- Configurar sistema de push notification pós-corrida
- Criar componente de resumo com imagens e destaques
- Adicionar botão de compartilhamento direto

**Critérios de Aceite:**
- O usuário deve ser notificado automaticamente após o fim da corrida.
- O resumo deve conter principais eventos, vencedores e destaques visuais.
- O botão de compartilhamento deve estar presente e funcional.

---

## 2.2. Funcionalidade: Selecionar Favoritos
**História:**  
Como Juliana Santana, quero escolher minhas equipes e pilotos favoritos para receber notificações personalizadas.

**Tarefas:**
- Criar tela de seleção de favoritos
- Salvar preferências do usuário no perfil
- Integrar favoritos com o sistema de notificações

**Critérios de Aceite:**
- O usuário deve conseguir selecionar e editar seus favoritos facilmente.
- O app deve usar essas informações para enviar alertas personalizados.
- As preferências devem ser persistidas na conta do usuário.

---

## 2.3. Funcionalidade: Resumo Rápido da Corrida

**História:**  
Como Juliana Santana, quero ler um artigo curto com os principais acontecimentos da corrida para me atualizar rapidamente.

**Tarefas:**  
- Criar um painel com resumos escritos de cada corrida  
- Redigir artigos objetivos com leitura estimada de até 2 minutos  
- Destacar os principais eventos da corrida (ultrapassagens, acidentes, vencedor, etc.)  
- Otimizar o layout para leitura fluida em dispositivos móveis  

**Critérios de Aceite:**  
- O artigo deve estar disponível até 1 hora após o término da corrida  
- O conteúdo deve ser de fácil leitura e escaneabilidade (títulos, tópicos, destaques)  
- Deve conter informações claras, organizadas e sem jargões técnicos excessivos



---

# Persona: Ricardo Lemos (Criador de Conteúdo)

## 3.1. Funcionalidade: Exportar Dados da Corrida
**História:**  
Como Ricardo Lemos, quero exportar os dados da corrida em um formato estruturado para utilizar durante minhas transmissões e vídeos.

**Tarefas:**
- Criar botão “Exportar Dados”
- Permitir exportação em formato CSV e imagem
- Incluir classificação final, voltas, tempo total e eventos

**Critérios de Aceite:**
- Os dados devem ser exportáveis em formatos CSV e imagem.
- Os arquivos devem ser compatíveis com Excel, Sheets, editores de imagem.
- A funcionalidade deve estar disponível até 10 minutos após o fim da corrida.

---

## 3.2. Funcionalidade: Acompanhar Dados ao Vivo
**História:**  
Como Ricardo Lemos, quero acompanhar os dados da corrida ao vivo em uma tela dedicada para comentar durante transmissões.

**Tarefas:**
- Criar “modo comentarista” com foco em dados ao vivo
- Exibir posição por volta, pit stops e tempo por setor
- Destacar eventos importantes em tempo real

**Critérios de Aceite:**
- Os dados devem ser atualizados em tempo real sem recarregar a página.
- A visualização deve ser otimizada para tela grande (desktop ou tablet).
- Os eventos devem estar destacados visualmente.

---

## 3.3. Funcionalidade: Agenda Completa por Categoria
**História:**  
Como Ricardo Lemos, quero acessar a agenda de todas as categorias que sigo, para organizar minha produção de conteúdo.

**Tarefas:**
- Criar tela com calendário filtrável por categoria
- Permitir marcação de datas importantes
- Integrar com calendário externo (Google/Outlook)

**Critérios de Aceite:**
- Deve ser possível filtrar e buscar corridas por data e categoria.
- O app deve permitir exportar a agenda para serviços externos.
- A navegação do calendário deve ser fluida e responsiva.

