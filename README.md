# cpp_raylib

C++ と [raylib](https://www.raylib.com/) を使ったシンプルなウィンドウアプリケーションのサンプルです。

## 必要なもの

| ツール | バージョン |
|--------|-----------|
| CMake  | 3.16 以上 |
| C++ コンパイラ | C++17 対応 (GCC / Clang / MSVC) |
| Git    | （FetchContent が raylib を自動取得するため） |

## ビルド手順

```bash
# リポジトリをクローン
git clone https://github.com/croissantoon/cpp_raylib.git
cd cpp_raylib

# ビルドディレクトリを作成して移動
cmake -S . -B build
cmake --build build

# 実行
./build/cpp_raylib   # Windows の場合: build\cpp_raylib.exe
```

## プロジェクト構成

```
cpp_raylib/
├── CMakeLists.txt   # CMake ビルド設定（raylib を自動取得）
├── src/
│   └── main.cpp     # エントリポイント（raylib サンプル）
└── README.md
```
