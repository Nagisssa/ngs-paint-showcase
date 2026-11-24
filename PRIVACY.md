# 隐私说明 / Privacy

**Ngs Paint 不收集、不上传任何用户数据。**

- 不联网：应用没有 `INTERNET` 权限，不包含账号、统计、广告或第三方 SDK。
- 不申请系统权限：APK 中只有 AndroidX 自动生成的 `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`（应用内广播保护），不会访问通讯录、相册、位置、麦克风或摄像头。
- 文档保存在应用私有目录：`.ngs` 草稿、恢复点、缩略图和崩溃日志都存放在 `/Android/data/com.ngspaint.app/` 下，其他应用无法读取。
- 崩溃日志仅在本地：下次启动时提示，可在应用内查看；不会自动发送。
- 卸载即删除：卸载应用会删除应用私有目录中的数据。你主动导出到公共目录的文件需要自行删除。
- 下载平台：通过 GitHub 或 Q 群下载时，平台自身可能记录下载行为；这与本应用无关。

如果你在 Issues 或 Q 群反馈问题时主动附上截图、日志或画作，这些内容会由你公开或发送给作者；请先确认其中没有你不希望公开的信息。

---

**English summary**

Ngs Paint does not collect or upload any user data. It has no `INTERNET` permission, no analytics, no ads, no accounts, and no third-party SDKs. Documents, recovery points and crash logs are stored in the app's private directory and are not transmitted. Uninstalling the app deletes its private data. Download platforms (GitHub, Q group) may log downloads independently.
