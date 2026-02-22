# Configuration and Final Adjustments

1. Теперь скачайте самую ранную версию Hytale (например [отсюда](https://lbx.zone/f/GCbzkCJ)). Найдите там архив Assets.zip и распакуйте всё в папку `latest`.
2. Скачайте последнюю версию HytaleServer (скоро опубликую ссылку) и распакуйте с заменой в папку `release\package\game\latest\Server`.
3. В этой версии Hytale есть два пола. Поэтому нам нужно добавить в `Eyes.json` и `Eyebrows.json` параметр `DefaultFor` для пола. Например:

```json
{
    "Id": "Medium",
    "Name": "avatarCustomization.eyebrows.Medium.name",
    "Model": "Characters/Body_Attachments/Eyebrows/Eyebrows_Medium.blockymodel",
    "IsDefaultAsset": true,
    "GradientSet": "Hair",
    "GreyscaleTexture": "Characters/Body_Attachments/Eyebrows/Medium_Greyscale.png",
	"DefaultFor": "Feminine"
}
```

Обязательно должно быть в каждом файле хотя бы один `Feminine` и один `Masculine`. Вы должны добавить в КАЖДЫЙ элемент!

Всё готово! Запускайте `HytaleClient.exe` и наслаждайтесь игрой! **Если у вас возникли какие-то проблемы, то не отчаивайтесь, а просто напишите в наш [Telegram](t.me/hytalefans) и мы обязательно вам поможем!**