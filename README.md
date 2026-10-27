# Lista de Compras — Android Studio

Aplicativo acadêmico desenvolvido em **Java + XML**, com persistência local em SQLite.

## Funcionalidades
- Cadastrar item com descrição, quantidade e valor unitário.
- Calcular automaticamente o valor total do item (`quantidade × valor unitário`).
- Listar itens e mostrar o total geral da compra.
- Abrir detalhes de um item ao tocar nele.
- Editar e excluir itens com confirmação.
- Manter os dados salvos ao fechar e abrir o aplicativo.

## Como abrir
1. Extraia o arquivo ZIP.
2. No Android Studio, escolha **Open** e selecione a pasta `ListaDeComprasAndroid`.
3. Aguarde a sincronização do Gradle.
4. Execute em um emulador ou dispositivo Android.

## Estrutura principal
- `MainActivity.java`: lista e ações de edição/exclusão.
- `ItemFormActivity.java`: cadastro e edição com validação.
- `ItemDetailActivity.java`: detalhes do item.
- `DatabaseHelper.java`: banco SQLite local.
- `res/layout`: interfaces XML.

Se o Android Studio solicitar a instalação do Android SDK 35 ou atualização do Gradle, aceite a configuração recomendada pelo próprio Android Studio.
