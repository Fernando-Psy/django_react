# django_react

## Sobre React

Props (propriedades) e state (estado) são dois conceitos fundamentais no React e representam maneiras diferentes de lidar com dados em um componente React.

### Props:
- Props são dados que são passados de um componente pai para um componente filho.
- Elas são imutáveis, ou seja, o componente filho não pode modificar as props que recebe.
- Props são usadas para configurar e personalizar a aparência e o comportamento de um componente filho.
- Exemplos de props: título, tamanho, cor, etc.

### State:
- State representa o estado interno de um componente.
- O state é gerenciado dentro do próprio componente e pode ser modificado ao longo do tempo.
- Quando o state de um componente é atualizado, o React irá re-renderizar o componente e atualizar a interface do usuário.
- State é usado para armazenar e gerenciar dados que mudam ao longo do tempo, como entradas de usuário, resultados de API, etc.

### Principais diferenças:
- Props são passadas de cima para baixo (do componente pai para o componente filho), enquanto o state é gerenciado internamente por cada componente.
- Props são imutáveis, enquanto o state pode ser atualizado ao longo do tempo.
- Props são usadas para configurar e personalizar componentes, enquanto o state é usado para gerenciar o estado interno de um componente.

Em resumo, props são usadas para passar dados entre componentes, enquanto state é usado para gerenciar o estado interno de um componente React.