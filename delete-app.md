# 删除 WasHere 后的数据 / Your data after deleting WasHere

更新日期 / Updated: 2026-10-03

[隐私政策 / Privacy Policy](index.md) · [技术支持 / Support](support.md)

## 中文

### 这里的“删除 App”指什么？

长按 WasHere 图标，点击 **Remove App（移除 App）**，再选择 **Delete App（删除 App）** 并确认。本文说明完成这个系统删除操作后的数据变化。

如果你只选择 **Remove from Home Screen（从主屏幕移除）**，只是移除桌面图标，WasHere 仍在 App 资源库中，App 和数据都不会因此被删除。

### 哪些数据会被删除？

删除 WasHere 会清除这台 iPhone 上属于 WasHere 的本地数据，包括：

- 本机保存的历史活动及其轨迹、时间、距离、海拔等信息。已经同步到 iCloud 的记录，其本机副本也会清除，但云端副本保留。
- 正在记录、尚未保存为历史活动的内容。这类内容只保存在本机，不会通过 WasHere 的活动同步功能上传到 iCloud。
- App 设置，例如语言、距离单位、里程提醒和 WasHere 内的 iCloud 同步开关。
- App 内部的缓存和临时导出文件。仅生成文件或打开分享面板，并不代表已经把备份保存到 App 外部。

**如果记录只在本机、没有成功同步到 iCloud，也没有另行保存备份，删除 App 后无法通过 WasHere 恢复这些记录。**

### 哪些数据不会因删除 App 自动删除？

- **已经成功同步到你自己的 iCloud 云盘中的 WasHere 活动记录。** 删除 App 不等于删除 iCloud 数据，WasHere 不会因为这个系统操作向 iCloud 发出删除记录的指令。
- **已经另行保存到 App 外部的 JSON 备份或 GPX 文件**，例如保存在 iCloud Drive、Google Drive、Dropbox、OneDrive 或电脑上的文件，以及发给其他人的副本。这些文件需要在各自的保存位置单独管理和删除。
- **其他设备上的数据。** 删除这台 iPhone 上的 WasHere 不会直接清空其他设备的 WasHere 本地记录。

备份是否保留取决于保存位置：不要把 WasHere 自身的本地文件夹或临时文件当作独立备份。如果保存到“我的 iPhone”，请确认文件位于不会随 WasHere 删除的独立位置。

### 重新安装后能恢复吗？

对于已经成功同步到 iCloud、且没有被另行删除的历史活动：

1. 重新安装 WasHere，并登录原来保存这些记录的 Apple 账号。
2. 确保系统的 iCloud 云盘及 WasHere 的 iCloud 访问可用。
3. 在 WasHere 的“设置与备份”中重新打开“使用 iCloud 存储”。全新安装时，这个开关默认关闭。
4. 联网并等待同步和下载完成；必要时点击“立即同步”。

如果你另行保存了 JSON 备份，也可以使用“从 JSON 备份恢复”。恢复范围取决于备份中包含的历史活动；未保存的当前活动不在这类备份中。

### 删除 App 前应检查什么？

先结束并保存需要保留的活动，然后检查 iCloud 同步是否可用并等待同步。开启开关或看到“上次同步”不应当作所有文件已上传到 Apple 云端的绝对保证：上传由系统继续处理。重要记录建议额外导出 JSON 备份，并确认文件已实际保存到 App 外部、可以找到并打开。

### 与 App 内“删除记录”的区别

系统删除 App 与 WasHere 内删除活动是不同操作。App 内的活动删除可以同步到 iCloud，并影响其他同步设备。

当前已发布版本中的“删除全部本地记录”按钮也会排队删除对应的 iCloud 记录；同步开启时，或以后重新开启同步时，删除可能上传到云端。**如果要保留云端记录，不要用这个按钮作为删除 App 前的清理步骤。** 本文不将下一版本尚未发布的修复作为当前版本功能。

关闭 WasHere 的 iCloud 同步只会停止同步，不会自动清除已有云端记录。若要删除云端数据，需要另外删除 iCloud 中的 WasHere 文件；另行导出的备份也需要单独删除。WasHere 没有开发者运营的轨迹存储服务器，开发者不能代你恢复或清除私人 iCloud 文件。

本文讨论的是 WasHere 活动同步，不是整个 iPhone 的 iCloud 设备备份。既有设备备份中的内容需要通过 Apple 的备份管理功能另行管理。

## English

### What does “delete the app” mean here?

Touch and hold the WasHere icon, tap **Remove App**, then choose **Delete App** and confirm. This guide describes what happens after you complete that system deletion process.

If you choose **Remove from Home Screen** only, you hide the icon. WasHere remains in App Library, and neither the app nor its data is deleted by that action.

### What is deleted?

Deleting WasHere removes its local data from this iPhone, including:

- Locally saved activities and their tracks, times, distances and elevation. For activities synced to iCloud, the local copy is removed while the cloud copy remains.
- An activity being recorded that has not yet been saved to history. This information is stored locally and is not uploaded by WasHere’s activity sync feature.
- App preferences, such as language, distance units, distance reminders and the in-app iCloud sync switch.
- Internal caches and temporary export files. Generating an export or opening the share sheet does not mean you have saved a backup outside the app.

**If a record exists only locally, has not successfully synced to iCloud and has no separately saved backup, WasHere cannot restore it after you delete the app.**

### What is not automatically deleted?

- **WasHere activities that have successfully synced to your own iCloud Drive.** Deleting the app is not the same as deleting iCloud data. WasHere does not send activity deletion requests to iCloud because of this system action.
- **JSON backups or GPX files already saved separately outside the app**, for example in iCloud Drive, Google Drive, Dropbox, OneDrive or on a computer, and copies shared with other people. Manage and delete these files separately where they were saved.
- **Data on other devices.** Deleting WasHere on this iPhone does not directly clear local WasHere activities on your other devices.

Whether a backup survives depends on its location. Do not treat WasHere’s own local folder or a temporary file as an independent backup. If you save to “On My iPhone,” confirm that the file is in a separate location that will not be removed with WasHere.

### Can I restore my activities after reinstalling?

For historical activities successfully synced to iCloud and not separately deleted:

1. Reinstall WasHere and sign in to the Apple Account that holds those activities.
2. Make sure iCloud Drive and WasHere’s system iCloud access are available.
3. In WasHere’s Settings & backup, turn on “Store in iCloud” again. This switch is off by default in a fresh installation.
4. Connect to the internet and allow sync and downloads to finish. Tap “Sync now” if needed.

If you separately saved a JSON backup, you can also use “Restore from JSON backup.” Only the historical activities included in that backup can be restored; an unsaved current activity is not included.

### What should I check before deleting?

Finish and save any activity you want to keep, check that iCloud sync is available, and allow time for syncing. Turning the switch on or seeing “Last synced” is not an absolute guarantee that every file has reached Apple’s cloud: the system continues handling uploads. For important records, also export a JSON backup and confirm that it was actually saved outside the app and that you can find and open it.

### How is this different from deleting activities inside WasHere?

Deleting the app through iOS and deleting activities inside WasHere are separate actions. In-app activity deletions can sync to iCloud and affect other devices using sync.

In the currently released version, “Delete all local activities” also queues deletion of the corresponding iCloud records. Those deletions may reach the cloud while sync is enabled or when it is enabled later. **Do not use this button as a cleanup step before deleting the app if you want to keep your cloud records.** This guide does not describe the next version’s unreleased fix as a feature of the current release.

Turning off WasHere’s iCloud sync stops syncing but does not automatically erase existing cloud records. To remove cloud data, separately delete the WasHere files in iCloud; separately exported backups must also be deleted individually. WasHere has no developer-operated track storage server, and the developer cannot restore or erase your private iCloud files for you.

This guide covers WasHere’s activity sync, not a whole-iPhone iCloud device backup. Manage any existing device backups separately using Apple’s backup management features.

## Apple 官方说明 / Apple documentation

[Remove or delete apps from iPhone](https://support.apple.com/guide/iphone/iph248b543ca/ios)
