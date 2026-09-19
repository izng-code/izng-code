# Matthias Waiss | Software Development Portfolio

**日本在住｜ソフトウェアエンジニア職へのキャリアチェンジを目指しています**  
**Based in Japan | Seeking a junior software development role**

国際経営・人事管理を学び、現在は英語講師として働きながら、ソフトウェア開発とゲーム関連ツールの個人制作に取り組んでいます。CS50、C、Web開発を基礎に、既存コードベースの調査、機能設計、UI実装、デバッグ、移植プロトタイプまで制作範囲を広げてきました。

My background is in International Business Administration with a focus on HR management. Alongside full-time work as an English instructor, I study software engineering and build independent projects spanning game systems, UI integration, emulator tooling, and platform-porting prototypes.

## 注目プロジェクト / Featured Projects

| Project | What it demonstrates | Stack / Tools |
| --- | --- | --- |
| [**mGBA Dual-Screen Pokémon Companion**](https://github.com/izng-code/mgba-dual-screen-companion) | mGBAのライブ状態とROMデータを読み取り、現在地に応じた情報を表示するデュアルスクリーン向け機能プロトタイプ。Linux版は動作し、Android表示シェルまで実装。**AI支援開発であることを明示しています。** | C, C++, Qt, Java, Android, CMake |
| [**Focus Battle System**](https://github.com/izng-code/focus-battle-system) | 既存のElite Battle: DXとFocus Meter Systemを解析し、プレイスタイル型メカニクスとして再設計・統合。UI、AI、保存データ、バトルロジックを横断する拡張。 | Ruby, Pokémon Essentials, EBDX |
| [**System Main Protocol**](https://github.com/izng-code/pokemon-essentials-pause-menu) | After Effectsをプロジェクトのために学び、Blender素材とRuby実装を組み合わせて約1週末で制作したプリレンダリング式ポーズメニュー。 | Ruby, After Effects, Blender, Photoshop |

### 1. mGBA Dual-Screen Pokémon Companion

デュアルスクリーンAndroid端末「AYN Thor」を想定したNuzlocke補助機能です。エミュレーター内部の状態を読み取り、手動でルートを選択せずに現在地とROM内のエンカウント情報を対応付けます。

- 約10 Hzの読み取り専用ライブ状態取得
- FireRed / LeafGreenの移動するSaveBlock1を毎回解決
- ROMからエンカウントテーブルと種族名を構造的に探索
- エミュレーター、解析ロジック、UI間を正規化データで分離
- Androidの第二画面検出、`Presentation`、単画面フォールバック
- 無効なポインターや非互換ROMに対するfail-closed設計
- 現状を正確に記載：Linux版は機能、AndroidのJNI/コア接続とAYN Thor実機検証は未完了

> **AI-assisted development:** プロダクトコンセプト、要件、対象端末のUX、設計制約、テスト、採否判断は私が担当しました。AIはコードベース調査、実装、デバッグ、ビルド設定、ドキュメント作成を支援しました。すべてを手作業で書いたコードとは主張していません。

[ケーススタディを見る →](https://github.com/izng-code/mgba-dual-screen-companion)

### 2. Focus Battle System

既存システム上で制作した仕事を、自作部分と上流部分を明確に分けて公開したケーススタディです。

- 5種類のFocus Styleと7種類の特殊処理を設計
- 約3,200行の実装・適応コード（上流由来の適応部分を含む）
- 技威力、能力変化、相性、急所、状態異常などを評価するメーター計算
- プレイヤーUIだけでなく、敵AIと技評価にも統合
- Mega Evolution、Dynamax系処理、EBDXバトルフローとの互換調整
- `CONTRIBUTION_MAP.md`で自作・改変・上流の境界を明示

[ケーススタディを見る →](https://github.com/izng-code/focus-battle-system)

### 3. System Main Protocol

UIデザイン、モーション制作、3D素材、コード統合を一人で担当した短期プロトタイプです。

- 6項目の循環選択、決定・キャンセル、既存メニュー接続をRubyで実装
- After Effectsで選択状態別の背景とトランジションを制作
- Blenderで3Dワイヤーフレーム素材を制作
- プリレンダリング映像と操作入力のタイミングを反復調整
- 約1週末で、未経験ツールの学習から動作プロトタイプまで完成

[デモとソースを見る →](https://github.com/izng-code/pokemon-essentials-pause-menu)

## 技術・強み / Skills

- **Programming:** C, C++, Ruby, JavaScript, HTML, CSS
- **Platforms and tooling:** Qt, Android / Java, CMake, Gradle, Git, GitHub
- **Creative tooling:** Adobe After Effects, Blender, Adobe Photoshop
- **Engineering approach:** unfamiliar-codebase investigation, feature integration, debugging, scope management, technical documentation
- **AI-assisted development:** requirements and constraints defined by me; generated work reviewed, tested, and documented with explicit disclosure

## 学習プロジェクト / Earlier Web Projects

| Project | Focus |
| --- | --- |
| [IPPO — Task Manager](https://github.com/izng-code/to-do-list) | JavaScript modules, DOM interaction, localStorage |
| [Admin Dashboard](https://github.com/izng-code/admin-dashboard) | Responsive interface layout with CSS Grid and Flexbox |
| [Calculator](https://github.com/izng-code/calculator) | JavaScript event handling and application state |

## Background

- B.A. in International Business Administration, HR management focus
- Professional English-teaching experience in Japan
- TOEFL iBT: 116
- Programming study and independent development alongside full-time work
- English, German, Japanese, and Russian communication experience

日本でのジュニアソフトウェアエンジニア職、特に既存システムの理解、機能統合、ツール開発、ゲーム関連技術に携われる機会を希望しています。国際的な環境や、英語と日本語を活用できるチームにも関心があります。

I am seeking a junior software development opportunity in Japan, particularly work involving existing-system integration, tools, game-related technology, or cross-platform development. I am also interested in international teams where English and Japanese communication are valuable.
