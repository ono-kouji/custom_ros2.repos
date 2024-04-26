# custom_ros2.repos# カスタムROS 2リポジトリ

このリポジトリには、カスタムのROS 2リポジトリセットを設定するための`custom_ros2.repos`ファイルが含まれています。`.repos`ファイルフォーマットは、一連のリポジトリをクローンするための`vcs`ツールで使用されます。

## 前提条件

- [ROS 2](https://index.ros.org/doc/ros2/Installation/)のインストール（Foxy Fitzroy推奨）
- `vcs`ツールのインストール（[vcstool](https://github.com/dirk-thomas/vcstool)）

## ワークスペースの設定

`custom_ros2.repos`ファイルを使用してワークスペースを設定するには、次の手順に従ってください。

1. 新しいワークスペースディレクトリを作成します：
   ```bash
   mkdir -p ~/ros2_custom_ws/src
   cd ~/ros2_custom_ws
