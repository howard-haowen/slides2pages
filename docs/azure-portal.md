---
marp: true
theme: uncover
class:
    - lead
paginate: true
_paginate: false
color: white
backgroundImage: url('https://www.cloud4c.com/ksa/sites/ksa/files/2023-10/microsoft-azure-expert-msp-logo-badge-d.webp')
---

<!-- _backgroundImage: "" -->
<!-- _color: navy -->

# Azure 平台入口網站基本操作

[江豪文](https://howard-haowen.github.io/) + Bing Chat

![bg fit right](https://rovertech.com.hk/wp-content/uploads/2024/01/Rectangle-192671.png)

---

## 大綱

-   Azure 平台主要功能
-   資源群組與資源
-   新增或刪除使用者
-   存取控制

---

## Azure 平台

-   Azure 是微軟的雲端平台，可提供建立雲端裝載應用程式所需的運算、儲存和網路資源。
-   [Azure 入口網站](https://azure.microsoft.com/zh-tw/get-started/azure-portal)可讓你建立及管理所有 Azure 資源。

---

## Azure 平台主要功能(1/2)

-   **計算服務**：提供虛擬機器、容器、伺服器減少運算等多種計算服務。
-   **儲存服務**：提供 Blob 儲存、隊列儲存、檔案儲存和磁碟儲存等多種儲存服務。
-   **網路服務**：提供虛擬網路、負載平衡器、VPN、CDN 等網路服務。
-   **Web + Mobile**：提供 Web Apps、Mobile Apps、API Apps 等服務。

---

## Azure 平台主要功能(2/2)

-   **資料庫服務**：提供 SQL Database、Cosmos DB 等資料庫服務。
-   **AI + Machine Learning**：提供 Cognitive Services、Machine Learning、Bot Service 等 AI 和機器學習服務。
-   **IoT**：提供 IoT Hub、IoT Central 等物聯網服務。
-   **安全性 + 身份識別**：提供 Azure Active Directory、Key Vault 等安全性和身份識別服務。

---

![bg](https://theflyingmaverick.com/wp-content/uploads/2018/03/image4.png)

---

## [Azure OpenAI 服務](https://learn.microsoft.com/zh-tw/azure/ai-services/openai/)

-   Azure OpenAI 服務可讓你存取 OpenAI 的模型，包括 GPT-4、GPT-4 Turbo with Vision、GPT-3.5-Turbo、DALLE-3 和 Embeddings 模型系列，其中包含 Azure 的安全性和企業功能。

---

## [Azure AI 文件智慧服務](https://learn.microsoft.com/zh-tw/azure/ai-services/document-intelligence/?view=doc-intel-4.0.0)

-   Azure AI 文件智慧服務 (先前稱為 Azure 表格辨識器) 是雲端式 Azure AI 服務，其使用機器學習模型將應用程式和工作流程中的資料處理自動化。
-   文件智慧服務對於增強資料驅動策略和擴充文件搜尋功能至關重要。

---

## <!-- fit --> Azure 平台入口網站

-   可使用任何網頁瀏覽器來存取的公用網站。
-   [登入](https://portal.azure.com/)後，即可以建立、管理和監視 Azure 服務和資源。

![bg right:60% fit](https://learn.microsoft.com/zh-tw/training/modules/tour-azure-portal/media/2-azure-portal.png)

---

## 入口網站功能表

-   入口網站的左側邊欄是入口網站功能表，其列出不同的 Azure 服務和資源類型。
-   此處列出的服務是`我的最愛`中的服務。
-   可將`我的最愛`自訂為最常建立或管理的特定資源類型。

![bg left fit](https://learn.microsoft.com/zh-tw/training/modules/tour-azure-portal/media/5-show-portal-menu.png)

---

## Azure 平台的主要概念

-   **訂閱(Subscription)**：Azure 訂閱是一種組織與 Microsoft 之間的協議，允許組織在 Azure 上建立和使用資源。訂閱提供了對 Azure 資源使用情況的詳細賬單和付款方式。
-   **資源群組(Resource Group)**：Azure 資源群組是一種將相關資源組織在一起的方式，以便更輕鬆地管理和組織這些資源。
-   **資源(Resources)**：Azure 資源是在 Azure 上建立的實例，例如虛擬機器、儲存帳戶、SQL 資料庫或各種 AI 服務等。

---

![bg fit](https://images.ctfassets.net/xxmwcynv5jdx/5lbtoW200BnS1fm15DiOVy/d47c0613e3057e35456bdd26e72a641c/resource-groups.png?w=1600&h=650&q=50&fit=fill&f=center)

---

## 新增[資源群組](https://learn.microsoft.com/zh-tw/azure/azure-resource-manager/management/manage-resource-groups-portal)

1. 登入 Azure 平台入口網站。
2. 在左側導航欄中，點擊`資源群組`。
3. 點擊`新增`按鈕。
4. 在`新增資源群組`頁面中，輸入群組名稱和選擇訂閱。
5. 點擊`建立`按鈕。

![bg right fit](https://learn.microsoft.com/zh-tw/azure/azure-resource-manager/management/media/manage-resource-groups-portal/manage-resource-groups-add-group.png#lightbox)

---

## <!-- fit --> 新增 [OpenAI 服務](https://learn.microsoft.com/zh-tw/azure/ai-services/openai/overview)

1. 登入 Azure 平台入口網站。
2. 在首頁，點擊`建立資源`按鈕。
3. 在`新建資源`頁面中，搜尋並選擇`OpenAI`。
4. 在`建立OpenAI服務`頁面中，填寫相關資訊。
5. 點擊`建立`按鈕。

![bg right fit](https://media.licdn.com/dms/image/D4D12AQG6zZzypa59lw/article-cover_image-shrink_600_2000/0/1707813316698?e=2147483647&v=beta&t=Ttgm2WxCNB1saeGNSSUnO0NgBAHDvLhB6M_C8AS-khM)

---

## <!-- fit --> 啟動 GPT-3.5 Turbo

1. 在 Azure 平台入口網站的首頁，點擊`所有服務`。
2. 在`所有服務`頁面中，搜尋並選擇你剛剛建立的 OpenAI 服務。
3. 在 OpenAI 服務的儀表板中，選擇`GPT-3.5 Turbo`。
4. 點擊`啟動`按鈕。

![bg right fit](https://media.licdn.com/dms/image/D4D12AQHJrAQjhkDzmw/article-cover_image-shrink_720_1280/0/1692819396048?e=2147483647&v=beta&t=RLG0RU1LxdBVp9hoYTD0nUGf-l80LvEya5fEih_AW4A)

---

## <!-- fit --> 啟動 Embeddings 模型

1. 在 Azure 平台入口網站的首頁，點擊`所有服務`。
2. 在`所有服務`頁面中，搜尋並選擇你剛剛建立的 OpenAI 服務。
3. 在 OpenAI 服務的儀表板中，選擇`Embeddings`。
4. 點擊`啟動`按鈕。

![bg right fit](https://publish-01.obsidian.md/access/1b0b209d26800640324dbdc7d5b5e5b5/Computing/Intelligence/Pasted%20image%2020230214113109.png)

---

## <!-- fit --> 新增 [文件智慧服務](https://learn.microsoft.com/zh-tw/azure/ai-services/document-intelligence/?view=doc-intel-4.0.0)

1. 在左側選單中，點選`建立資源`，在搜尋欄中輸入`文件智慧服務`。
2. 在新視窗中填寫必要的資訊，如`名稱`、`訂閱`、`資源群組`、`位置`等，並點選`建立`。
3. 返回首頁並在`資源群組`中找到剛剛建立的服務。

![bg right:40% fit](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/media/overview/analyze-id-document.png?view=doc-intel-4.0.0)

---

## [新增使用者](https://learn.microsoft.com/zh-tw/azure/active-directory/fundamentals/add-users)

1. 登入後，在首頁點擊`Microsoft Entra識別碼`。
2. 流覽至 `身分> 識別使用者>所有使用者`。
3. 選取`新增使用者>建立新使用者` 或 `邀請外部使用者`。

![bg right:40% fit](https://getnerdio.com/wp-content/uploads/2023/09/Microsoft-Entra-ID-The-New-Name-for-Azure-Active-Directory1.jpg)

---

![bg](https://learn.microsoft.com/zh-tw/azure/active-directory/fundamentals/media/add-users-azure-active-directory/create-new-user-menu.png)

---

## [刪除使用者](https://learn.microsoft.com/zh-tw/azure/active-directory/fundamentals/add-users)

1. 登入後，在首頁點擊`Microsoft Entra識別碼`。
2. 流覽至 `身分> 識別使用者>所有使用者`。
3. 搜尋並選取想要刪除的使用者。
4. 選取`刪除`。

![bg right fit](https://learn.microsoft.com/zh-tw/azure/active-directory/fundamentals/media/add-users-azure-active-directory/delete-existing-user.png)

---

## 微軟 Azure 平台的 RBAC

#### 什麼是 RBAC？

-   RBAC (Role-Based Access Control) 是一種基於角色的存取控制，它讓我們可以根據用戶的角色來分配存取權限。
-   使用這項功能是免費的，包含在 Azure 訂閱帳戶中。

#### Azure RBAC 的工作原理

-   在 Azure 中，RBAC 的工作方式是將操作權限（例如讀取、寫入和刪除）組合成角色，然後將這些角色分配給用戶、群組、服務主體或管理群組。

---

## Azure RBAC 的角色

Azure RBAC 有許多內建的角色，例如：

-   **Owner**：具有完全存取權限的用戶，並且可以分配角色給其他用戶。
-   **Contributor**：可以創建和管理所有類型的 Azure 資源，但不能分配角色給其他用戶。
-   **Reader**：只能查看 Azure 資源。

---

## <!-- fit --> 設定 RBAC 三步驟

1. WHO: 安全性主體
2. WHAT: 角色定義
3. WHERE: 範圍

![bg right:70% fit](https://learn.microsoft.com/zh-tw/azure/role-based-access-control/media/overview/rbac-overview.png)

---

## RBAC 的好處

-   **最小權限原則**：可以僅授予用戶完成工作所需的最小權限。
-   **靈活性**：可以根據需要分配不同的角色給不同的用戶。

![bg right fit](https://assets.website-files.com/5ff66329429d880392f6cba2/60a2467ccc346830c07f2325_RBAC%20preview.jpg)

---

## <!-- fit --> 訪問控制 （IAM）

在 Azure 入口網站 中，使用 Azure RBAC 的角色指派會出現在訪問控制 （IAM） 頁面上。

![bg right fit](https://learn.microsoft.com/zh-tw/azure/role-based-access-control/media/shared/sub-role-assignments.png)

---

## 內建角色清單

![h:500](https://learn.microsoft.com/zh-tw/azure/role-based-access-control/media/shared/roles-list.png)

---

## 參考資料

-   [使用 Azure 入口網站管理服務](https://learn.microsoft.com/zh-tw/training/modules/tour-azure-portal/)
-   [Azure 官方文件](https://docs.microsoft.com/zh-tw/azure/)
