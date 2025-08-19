# bakin-vrm-blender
**A Blender Addon that adds RPG Developer Bakin specific features for VRoid VRM models. VRM 0.0 & 1.0 compatible.**

**VRoidのVRMモデルにRPG開発者Bakin固有の機能を追加するBlenderアドオンです。 VRM 0.0と1.0に対応しています。**

![blenderaddon](https://github.com/user-attachments/assets/27eef35b-fd36-421b-98c1-0c42c68d56f5)

> [!TIP]
> [Full tutorial on how to use the add-on](https://meringue-rouge.itch.io/guide-rpg-developer-bakin-vrm-models-animations-rigging-and-more)
> 
> [アドオンの使い方の完全なチュートリアル](https://meringue-rouge.itch.io/guide-rpg-developer-bakin-vrm-models-animations-rigging-and-more)

> [!IMPORTANT]
> You'll need the VRM Addon for Blender. (BlenderのVRMアドオンが必要です。) https://vrm-addon-for-blender.info/en/
> 
> We strongly recommend you use VRM 1.0 models. Some features aren't supported for models with materials reduced set to 2. (VRM 1.0モデルの使用を強くお勧めします。 マテリアルを2に減らしたモデルでは、一部の機能がサポートされません。)


- *If you wish to import general models for BAKIN using PBR, use this Blender add-on instead: https://github.com/Ingenoire/bakin-blender-exporter*
- *If you wish to animate the VRM models with baked-in hair/bust/outfit physics for your Bakin game, check out this add-on I made: https://github.com/Ingenoire/VRM-Spacing-Animation-Baking*

## Features / 特徴
EN
- Automated Item Hook Bones
- Eye Look Blend Shaoes
- Add Alternative Iris Textures (swap through Blend Shapes)
- Add Alternative Blush Textures (swap through Blend Shapes)
- Turn model's head in game with Head Tilt Blend Shapes (adds significant filesize weight)
- Export in VRM or FBX format
- Animation Exporter Utility, make your custom animations work properly by importing the generated rig, retargetting the animation, setting the name and then pressing the animation export button.
  
JP
- 自動化アイテム フックボーン
- アイ・ルック・ブレンド・シャオ
- 代替アイリステクスチャの追加（ブレンドシェイプで入れ替え）
- 代替チークテクスチャの追加（ブレンドシェイプでスワップ）
- Head Tilt Blend Shapes（ヘッドチルトブレンドシェイプ）を使って、ゲーム内でモデルの頭を回転させる（ファイルサイズが大幅に重くなります）。
- VRMまたはFBXフォーマットで書き出し
- Animation Exporter Utilityは、生成されたリグをインポートし、アニメーションをリターゲットし、名前を設定してからアニメーションエクスポートボタンを押すことで、カスタムアニメーションを適切に動作させます。

## Installation / インストール
EN
- Download the latest release.
- Open Blender, and under "Edit" -> "Preferences", select "Add-ons". Then go to "Install..." and find your downloaded zip file. It should then be installed.
- The addon is set to the right side panel. Press the N key to open the side panel and find the VRoid for Bakin tab.

JP
- 最新リリースをダウンロード
- Blenderを開き、"Edit" -> "Preferences "で "Add-ons "を選択します。 そして "Install... "に進み、ダウンロードしたzipファイルを見つけます。 するとインストールされるはずです。
- アドオンは右サイドパネルに設定されている。 Nキーを押してサイドパネルを開き、VRoid for Bakinタブを見つけます。

### Credits
The addon was made through Microsoft Copilot and ChatGPT (using the Blender scripting GPT), after a lot of trial and error and a few tweaks. Grok as well.
