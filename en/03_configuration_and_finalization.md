# Configuration and Final Adjustments

1. Now download the earliest available version of Hytale (for example, from [here](https://lbx.zone/f/GCbzkCJ)). Locate the `Assets.zip` archive and extract all of its contents into the `latest` folder.

2. Download the latest version of HytaleServer (link coming soon) and extract it with replacement into:
   `release\package\game\latest\Server`

3. This version of Hytale includes two genders. Therefore, you need to add the `DefaultFor` parameter to both `Eyes.json` and `Eyebrows.json` to specify the gender. For example:

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

Make sure that each file contains at least one `Feminine` and one `Masculine` entry. You have to add to EACH element!

Everything is ready! Launch `HytaleClient.exe` and enjoy the game!
**If you encounter any issues, don’t worry — just contact us on our [Telegram](https://t.me/hytalefans) and we’ll be happy to help!**
