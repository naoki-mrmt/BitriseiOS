# BitriseiOS
[![Build Status](https://app.bitrise.io/app/ff873f31dae2cdb6/status.svg?token=TQfyNkNbesusylrkJfJCrw&branch=develop)](https://app.bitrise.io/app/ff873f31dae2cdb6)
## 環境構築
### 事前準備
- Bundlerをインストール
    - ```gem install bundler```
        - [rbenv](https://github.com/rbenv/rbenv) 
- CocoaPodsのインストール
    - ```bundle install```
 
### xcworkspaceの生成
- ```make```
    - 中身 
        - ```bundle exec pod install```
        - ```open ./TechCurationApp.xcworkspace```

