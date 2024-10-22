# 编译ntfy Android App

为了方便自建服务器的小伙伴，利用 action 自动编译适配自己的app。

1. 需要在 [Google Firebase Console](https://console.firebase.google.com) 创建应用，名需要设置为 `io.heckel.ntfy`。
2. 在 **项目设置** 页面下方 **Android 应用** tab页，下载 `google-services.json` 文件。
3. 在该 GitHub 仓库中设置变量 `APP_BASE_URL`、`GOOGLE_APPLICATION_CREDENTIALS` 和 `TOKEN`。
4. `APP_BASE_URL` 为你的 ntfy 服务端域名。
5. `GOOGLE_APPLICATION_CREDENTIALS` 为 `google-services.json` 的文件内容。
6. `TOKEN` 随意。


## Translations
We're using [Weblate](https://hosted.weblate.org/projects/ntfy/) to translate the ntfy Android app. We'd love your participation.

<a href="https://hosted.weblate.org/engage/ntfy/">
<img src="https://hosted.weblate.org/widgets/ntfy/-/multi-blue.svg" alt="Translation status" />
</a>

## License
Made with ❤️ by [Philipp C. Heckel](https://heckel.io), distributed under the [Apache License 2.0](LICENSE).
