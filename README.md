# submodule-test
`git submodule`を利用したことが無かったので試してみた

1. CloneからSubmoduleのAddまで
    1. git clone git@github.com:qushot/submodule-test.git
    1. cd submodule-test
    1. git submodule add git@github.com:qushot/submodule-test-foo-api.git
    1. git submodule add git@github.com:qushot/submodule-test-foo-front.git

1. Submoduleが更新された場合
    1. git add submodule-test-foo-api
    1. git commit -m "Update submodule: submodule-test-foo-api"

参考
- [Qiita: Git submodule の基礎](https://qiita.com/sotarok/items/0d525e568a6088f6f6bb)
- [Qiita: Git submoduleの押さえておきたい理解ポイントのまとめ](https://qiita.com/kinpira/items/3309eb2e5a9a422199e9#submodule-%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99%E3%82%8B)
