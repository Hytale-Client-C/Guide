# Library, Protocol, and Asset Installation

1. Загрузите библиотеки из репозитория [Client](https://github.com/Hytale-Client-C/Client) и распакуйте их в ту же папку (`latest`).

2. В папке `Game` создайте папку `Interface`. Должно получиться так: `release\package\game\latest\Client\Game\Interface`.

3. Скачайте архив из репоризтория [Interface](https://github.com/Hytale-Client-C/Interface/releases) и распакуйте его в эту папку (`Game\Interface`).

4. Скачайте [SDL2-CS](https://github.com/Hytale-Client-C/SDL2-CS). Данный проект являтся оберткой над SDL2 для C#. Скачайте последнюю версию или сделайте сбору проекта, и распакуйте с заменой в папку `latest` с заменой.

5. Скачайте [Wwise_CS](https://github.com/Hytale-Client-C/Wwise_CS). Данный проект являтся оберткой над Wwise для C#. Скачайте последнюю версию или сделайте сбору проекта, и распакуйте с заменой в папку `latest` с заменой.

6. Скачайте [HytaleProtocol](https://github.com/Hytale-Client-C/HytaleProtocol). Данный репозиторий содержит в себе все протоколы, которые использует клиент для общения с сервером. Будет обновляться часто, поэтому скачайте последнюю версию или сделайте сбору проекта, и распакуйте с заменой в папку `latest` с заменой. **Следите за обновлениями и обновляйте его!**

7. Скачайте последнюю версию [Zlib](https://github.com/Hytale-Client-C/Zlib/releases) и добавьте с заменой в папку `Client`.

8. Скачайте последнюю версию [AuthProtocol](https://github.com/Hytale-Client-C/AuthProtocol/releases) и добавьте с заменой в папку `Client`.

9. Скачайте последнюю версию [HytaleAPI](https://github.com/Hytale-Client-C/CommonStub/releases) и добавьте с заменой в папку `Client`.

10. Скачайте шейдеры [Hytale-Shaders](https://github.com/Hytale-Client-C/Hytale-Shaders) и распакуйте их пути `release\HytaleClient\Graphics\Shaders`. **Следите за обновлениями и обновляйте их!**

Почти готово к запуску✨ Осталось пару мелких шагов!

NEXT: [03_configuration_and_finalization.md](03_configuration_and_finalization.md)
