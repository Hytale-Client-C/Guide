# Environment Setup and Project Structure

1. Скачайте и установите Visual Studio 2019 или более позднюю версию.
2. Скачайте и установите .NET Framework 4.7.
3. Создайте следующую структуру *(вы можете ее изменить, но в нашем случае это было так)*:

<pre>
release/
├── package/
│   ├── sig
│   ├── jre
│   ├── game
│   │   └── latest
│   └── config.json
└── HytaleClient/
    └── Graphics
        └── Shaders
</pre>

4. Добавьте `HytaleClient.exe` в папку `latest`.

NEXT: [02_dependencies_and_assets.md](02_dependencies_and_assets.md)