# NagisinnraLinux‑mist
**NagisinnraLinux の世界観特化版 — 青・霧・静寂をテーマにした軽量 Linux ディストリビューション**

NagisinnraLinux‑mist は、本家 NagisinnraLinux をベースに  
「青霧の世界観」「暗室向け UI」「静寂のデザイン」を OS 全体へ適用した特別版です。

本家の軽量性・高速性を維持しつつ、  
起動直後から Mist の世界に没入できるよう再構築しています。

---

## 🌌 特徴

### ■ Mist 専用テーマ
- LightDM テーマを Mist 用に再設計  
- 壁紙は青霧の世界観に統一  
- GTK / Xfce テーマを Mist 用に最適化  
- 暗室での使用を前提にコントラスト調整

### ■ パネルは Mist 専用構成
`/etc/xdg/xfce4/panel/` に Mist の設定を配置。  
ユーザー初期設定に依存せず、起動直後から Mist の UI が反映されます。

### ■ 壁紙・テーマは skel で完全反映
`/etc/skel/.config/xfce4/`  
`/etc/skel/.config/gtk-3.0/`  
に Mist の初期設定を配置し、  
新規ユーザー環境でも世界観が崩れません。

### ■ 本家と同じ軽量性
- ISO サイズ：約 2.4GB  
- RAM 使用量：約 470MB  
- Debian Trixie ベース  
- fcitx5 + Mozc 事前組み込み

---

## 🔧 技術構成

- **Base**: Debian Trixie  
- **DE**: Xfce4  
- **Theme**: Mist (GTK / Xfce / LightDM)  
- **Panel**: Mist 専用 xdg  
- **Wallpaper**: Mist 専用背景  
- **Initramfs**: Mist 起動テーマ反映済み  
- **Skel**: Mist 初期設定を完全適用

---

## 📦 ISO ダウンロード
（ここに GitHub Releases のリンクを貼る）

---

## 🖼 スクリーンショット
（後で追加）

---

## 📝 ライセンス
Debian ベースのため、各パッケージはそれぞれのライセンスに従います。  
Mist テーマ部分は NagisinnraLinux 開発者によるオリジナルです。

---

## 🌫️ 世界観
NagisinnraLinux‑mist は、  
「霧の中に浮かぶ青銀河」をテーマにした世界観 OS です。

- 冷白の細いライン  
- 霧のような青のグラデーション  
- 暗室向けの静かな UI  
- 余計なノイズを排除したミニマルデザイン  

本家版とは別の “世界観ライン” として開発されています。

---

## 🤝 本家版
NagisinnraLinux（本家）  
https://nagisinnra.github.io

