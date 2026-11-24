# 第三方组件声明 / Third-Party Notices

Ngs Paint 的发布包包含以下第三方组件。除特别注明外，运行时组件均以 **Apache License 2.0** 授权。

The Ngs Paint release includes the third-party components listed below. Unless noted otherwise, runtime components are licensed under the **Apache License 2.0**.

完整 Apache-2.0 文本见 [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt)。
The full Apache-2.0 text is available at [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt).

---

## 运行时组件 / Runtime components

| 组件 / Component | 版本 / Version | 许可 / License |
| --- | --- | --- |
| AndroidX Core KTX (`androidx.core:core-ktx`) | 1.17.0 | Apache-2.0 |
| AndroidX Lifecycle (`androidx.lifecycle:*`) | 2.9.4 | Apache-2.0 |
| AndroidX Activity Compose (`androidx.activity:activity-compose`) | 1.12.4 | Apache-2.0 |
| Jetpack Compose BOM (`androidx.compose:compose-bom`) | 2026.05.00 | Apache-2.0 |
| Compose UI / Graphics / Foundation / Material3 (`androidx.compose.ui:ui`, `ui-graphics`, `foundation`, `material3`) | BOM 2026.05.00 | Apache-2.0 |
| Compose Tooling Preview (`androidx.compose.ui:ui-tooling-preview`) | BOM 2026.05.00 | Apache-2.0 |
| Kotlin Standard Library (`org.jetbrains.kotlin:kotlin-stdlib`) | 2.4.10 | Apache-2.0 |
| Guava `listenablefuture` (`com.google.guava:listenablefuture`) | 1.0 | Apache-2.0（POM 未声明许可，按 Guava 项目许可列入 / POM omits license; listed under the Guava project license） |

AndroidX / Compose 的传递依赖（`androidx.annotation`、`androidx.collection`、`androidx.concurrent`、`androidx.savedstate`、`androidx.startup`、`androidx.tracing`、`androidx.versionedparcelable` 等）同样以 Apache-2.0 授权。完整依赖树可在构建时通过 `./gradlew :app:dependencies --configuration releaseRuntimeClasspath` 查看。
Transitive AndroidX / Compose dependencies (e.g. `androidx.annotation`, `androidx.collection`, `androidx.concurrent`, `androidx.savedstate`, `androidx.startup`, `androidx.tracing`, `androidx.versionedparcelable`) are also Apache-2.0. The full tree can be inspected with `./gradlew :app:dependencies --configuration releaseRuntimeClasspath`.

## 仅测试期组件 / Test-only components

以下组件不进入发布 APK：
The following components are not included in the release APK:

| 组件 / Component | 版本 / Version | 许可 / License |
| --- | --- | --- |
| JUnit (`junit:junit`) | 4.13.2 | Eclipse Public License 1.0 (EPL-1.0) |
| Hamcrest (`org.hamcrest:hamcrest-core`) | 1.3 | BSD-3-Clause |

## 无 copyleft 运行时组件 / No copyleft runtime components

发布包中不包含 GPL、LGPL、AGPL、MPL 或 EPL 授权的运行时组件。
The release APK contains no GPL, LGPL, AGPL, MPL or EPL-licensed runtime components.

## 素材 / Assets

- 应用图标由作者本人画作生成；音效 `save_beep.wav`、`merge_soft.wav` 为作者原创录音/合成，不含第三方采样。
- App icon is generated from the author's own artwork; `save_beep.wav` and `merge_soft.wav` are original recordings/synthesis by the author, with no third-party samples.

## 联系方式 / Contact

如对第三方组件或许可有疑问，请联系：1798514750@qq.com
For questions about third-party components or licensing, contact: 1798514750@qq.com
