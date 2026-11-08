# WasHere Garmin Connect 数据隐私说明 / Garmin Connect Data Privacy Notice

生效日期 / Effective: 2026-11-08

Garmin Connect 自动同步功能正在开发中。以下说明适用于用户主动连接 Garmin Connect 并授权 WasHere 访问活动数据之后；在连接功能上线前，WasHere 不会接收 Garmin Connect 数据。WasHere 的[一般隐私政策](https://qiuxin.github.io/washere-privacy/)也适用。

## 中文

### 1. 收集的数据与用途

只有在你主动连接 Garmin Connect 并授权 Activity API 后，WasHere 才会接收你授权的运动活动数据，包括活动类型、时间、距离、运动指标及 GPS 轨迹，以及完成同步所需的 Garmin 用户标识和 OAuth 凭据。我们仅用于把你的跑步、徒步等活动导入你自己的 WasHere 记录，让你查看地图、回顾运动及导出记录。Garmin 数据不会用于广告、用户画像，也不会用于训练、评估或改进 AI 模型。

### 2. 数据流向与处理方

- **Garmin Connect**：在你授权并将设备活动同步到 Garmin Connect 后，Garmin 按你的授权向 WasHere 发送活动数据。
- **腾讯云（Tencent Cloud）**：由 WasHere 开发者控制的腾讯云服务器接收 Garmin 推送，暂存并处理活动文件，以及保存完成授权和同步所需的 Garmin 用户标识与 OAuth 凭据。腾讯云作为基础设施提供方可能处理这些数据。API 密钥不会交给其他第三方使用。
- **你的 iPhone**：导入完成后，活动及轨迹保存在 WasHere 的本机记录中。只有你主动开启 WasHere 的 iCloud 同步时，相关记录才会按该功能的设置保存到你自己的 Apple iCloud 云盘，并由 Apple 按其条款处理。
- **地图服务**：当你在应用中查看导入的路线时，设备会向 Mapbox 请求所查看区域的地图图块；地图请求可能包含地图范围、IP 地址和设备信息，但我们不会把原始 Garmin 活动文件交给 Mapbox。详情见一般隐私政策。

我们不出售 Garmin 数据，不向广告商、数据经纪商或 AI 服务提供商提供 Garmin 数据。除上述提供功能所必需的处理方和你主动选择的 iCloud 同步外，不与其他第三方共享 Garmin 数据。

### 3. 保留、安全与删除

Garmin 原始活动文件在成功导入你的 iPhone 后从 WasHere 服务器删除；导入失败的文件最多保留 7 天，以便重试，之后删除。完成连接所需的 Garmin 用户标识和 OAuth 凭据仅在你保持连接期间保存，并在断开连接或撤回授权后删除。传输使用 HTTPS；服务器限制对凭据和活动数据的访问。

你可以在 WasHere 中查看、导出或删除已导入的记录。你可以在 Garmin Connect 的授权设置中撤回 WasHere 的访问权限，停止后续同步；如需删除服务器上尚未交付的数据或凭据，或请求访问、更正、导出数据，请联系 **qiuxincsuhk@hotmail.com**。撤回授权不会自动删除已导入 iPhone 的本地记录；你可在 WasHere 中自行删除。若你曾主动开启 iCloud 同步，也可在自己的 iCloud 云盘中删除相应文件。

### 4. 政策变更

如果实际实现、处理方或保留期限发生变化，我们会在启用相关处理前更新本页面。

---

## English

Garmin Connect automatic sync is in development. This notice applies only after you choose to connect Garmin Connect and authorize WasHere to access activity data. Before that feature launches, WasHere does not receive Garmin Connect data. Our [general privacy policy](https://qiuxin.github.io/washere-privacy/) also applies.

### 1. Data and purposes

Only after you connect Garmin Connect and authorize the Activity API will WasHere receive the activity data you permit, including activity type, time, distance, workout metrics and GPS routes, plus the Garmin user identifier and OAuth credentials needed for syncing. We use it only to import your runs, hikes and other activities into your own WasHere history, display routes, review workouts and let you export records. Garmin data is not used for advertising or profiling, or to train, evaluate or improve AI models.

### 2. Data flow and processors

- **Garmin Connect:** after your authorization and device sync, Garmin sends activity data to WasHere under the permissions you granted.
- **Tencent Cloud:** a server controlled by the WasHere developer receives Garmin pushes, temporarily stores and processes activity files, and stores the Garmin user identifier and OAuth credentials needed for authorization and syncing. Tencent Cloud may process this data as the infrastructure provider. API keys are not given to other third parties for use.
- **Your iPhone:** imported activities and routes are stored in WasHere's local records. Only if you choose to enable WasHere's iCloud sync may those records be stored in your own Apple iCloud Drive and processed by Apple under its terms.
- **Map service:** when you view an imported route, your device requests map tiles for the viewed area from Mapbox. Those requests may include the map area, IP address and device information, but we do not provide raw Garmin activity files to Mapbox. See our general privacy policy for details.

We do not sell Garmin data or provide it to advertisers, data brokers or AI service providers. We do not share it with other third parties beyond the processors needed to provide this feature and the optional iCloud sync you choose.

### 3. Retention, security and deletion

Raw Garmin activity files are deleted from the WasHere server after successful import to your iPhone. Failed imports are retained for retry for no more than seven days and then deleted. The Garmin user identifier and OAuth credentials needed for the connection are retained only while you remain connected and are deleted when you disconnect or withdraw authorization. Data is transmitted over HTTPS, and server access to credentials and activity data is restricted.

You can view, export or delete imported records in WasHere. You can revoke WasHere's access in Garmin Connect authorization settings to stop future syncing. To request deletion of undelivered server data or credentials, or to request access, correction or export, contact **qiuxincsuhk@hotmail.com**. Revoking access does not automatically delete records already imported to your iPhone; you can delete those in WasHere. If you enabled iCloud sync, you can also remove the corresponding files from your own iCloud Drive.

### 4. Changes

If the implementation, processors or retention periods change, we will update this page before the related processing begins.
