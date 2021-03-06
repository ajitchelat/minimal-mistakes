---
layout: leftnav
title: 在 Desktop Viewer 中顯示您的裝置
menu: subnav
---

Citrix Receiver for Windows 偵測到已連線到電腦的裝置，並允許您選擇要與主控桌面和應用程式搭配使用的裝置。

* 您可以使用 **[喜好設定]** > **[連線]** 中的設定來自訂是否想要將裝置 (例如麥克風和網路攝影機) 連線到您的虛擬工作階段。
* 已連線到本機電腦的裝置將顯示在 **[喜好設定]** > **[裝置]** 的 [裝置] 清單中。
* 如果您已連線裝置，但無法在 [裝置] 清單中看到該裝置，請按一下 **[重新整理]**。
* 連線後，裝置將顯示為 **[最佳化]**、**[受到原則限制]** 或 **[一般]**。

| 裝置 | 描述 |
| --- | --- |
| 最佳化 | 裝置具有 Citrix 虛擬通道，並且可同時在遠端工作階段和本機電腦中自動提供使用。 最佳化裝置的 [目前連線] 欄顯示在本機電腦和**遠端工作階段**中均處於已連線狀態的裝置。 [重新導向] 核取方塊已選取，且無法編輯。 您可以在 [虛擬通道] 欄中使用 [切換至] 按鈕在 [最佳化] 和 [一般] 之間切換。 例如，如果虛擬通道不支援裝置的完整功能，則選取 [切換為一般]。 |
| 一般 | 裝置沒有 Citrix 虛擬通道且無法同時在本機電腦和遠端工作階段上使用。 選取 [重新導向] 核取方塊，以在遠端工作階段和本機電腦之間切換裝置的可用性。 您可以在 [目前連線] 欄中看到目前連線狀態。 |
| 受到原則限制 | 管理員已設定原則來限制此類型的裝置。 例如，依預設，USB 滑鼠和鍵盤通常會受到原則限制，因為可在沒有 USB 支援的情況下在遠端工作階段中自動處理其行為。 出於安全性原因，可能會限制其他裝置 (如網路裝置)。 受到原則限制之裝置的 [目前連線] 欄僅顯示**本機電腦**。 您無法在受到原則限制的裝置上選取 [重新導向] 核取方塊。 |

