# Projeto PlantSelect

## Descrição
O **PlantSelect** é um aplicativo desenvolvido em React Native que ajuda os usuários a selecionar pratos de diferentes restaurantes de forma intuitiva. O app possui uma interface amigável e interativa, permitindo que os usuários explorem uma variedade de opções de refeições.

## Tecnologias Utilizadas
- **React Native**: Biblioteca para construção de interfaces de usuário móveis.
- **TypeScript**: Linguagem que traz tipagem estática para JavaScript, ajudando na manutenção do código.
- **React Navigation**: Para gerenciamento de navegação entre as diferentes telas do aplicativo.


### Componentes
- **EnviromentButton**: Componente que representa um botão para selecionar um ambiente (tipo de comida).
- **Header**: Componente que representa o cabeçalho do aplicativo.
- **RestaurantCard**: Componente que representa os detalhes de um restaurante, incluindo nome, nota, tipo, distância e imagem.

### Páginas
- **PlanSelect**: Página principal onde os usuários podem selecionar um prato e visualizar os restaurantes disponíveis.

## Funcionalidades
- **Seleção de Ambientes**: O usuário pode clicar nos botões de ambiente (como "Italiana", "Japonesa", etc.) para selecionar o tipo de prato que deseja.
- **Exibição de Restaurantes**: Após selecionar um ambiente, o aplicativo mostra uma lista de restaurantes fictícios, incluindo informações como:
  - Nome do restaurante
  - Nota (rating)
  - Tipo de cozinha
  - Distância em km
  - Descrição
  - Imagem do restaurante (carregada a partir de uma URL)

## Como Executar o Projeto
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu_usuario/plantselect.git
   cd plantselect
   npm install
   npx expo start




