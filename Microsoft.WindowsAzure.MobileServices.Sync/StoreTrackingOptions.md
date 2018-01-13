<Type Name="StoreTrackingOptions" FullName="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions">
  <TypeSignature Language="C#" Value="public enum StoreTrackingOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StoreTrackingOptions extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
  <TypeSignature Language="VB.NET" Value="Public Enum StoreTrackingOptions" />
  <TypeSignature Language="F#" Value="type StoreTrackingOptions = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="aa014-101">追跡オプションを使用できる利用可能なストアのフラグ列挙です。</span><span class="sxs-lookup"><span data-stu-id="aa014-101">A flags enumeration for the available store tracking options available.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllNotifications">
      <MemberSignature Language="C#" Value="AllNotifications" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions AllNotifications = int32(63)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotifications" />
      <MemberSignature Language="VB.NET" Value="AllNotifications" />
      <MemberSignature Language="F#" Value="AllNotifications = 63" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotifications" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>63</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-102">すべての操作を記録してバッチ通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-102">Generates all record operations and batch notifications.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="AllNotificationsAndChangeDetection">
      <MemberSignature Language="C#" Value="AllNotificationsAndChangeDetection" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions AllNotificationsAndChangeDetection = int32(255)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotificationsAndChangeDetection" />
      <MemberSignature Language="VB.NET" Value="AllNotificationsAndChangeDetection" />
      <MemberSignature Language="F#" Value="AllNotificationsAndChangeDetection = 255" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.AllNotificationsAndChangeDetection" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>255</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-103">すべてのレコードの操作の通知が生成され、通知をバッチ処理、挿入の検出とレコードの変更の検出を更新します。</span><span class="sxs-lookup"><span data-stu-id="aa014-103">Generates all record operation notifications, batch notifications, insert and updates detection and record change detection.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DetectInsertsAndUpdates">
      <MemberSignature Language="C#" Value="DetectInsertsAndUpdates" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions DetectInsertsAndUpdates = int32(64)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectInsertsAndUpdates" />
      <MemberSignature Language="VB.NET" Value="DetectInsertsAndUpdates" />
      <MemberSignature Language="F#" Value="DetectInsertsAndUpdates = 64" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectInsertsAndUpdates" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-104">レコードがされているかどうかを検出するために、"upsert"分析を有効にする作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="aa014-104">Enable "upsert" analysis to detect if the record is being created or updated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DetectRecordChanges">
      <MemberSignature Language="C#" Value="DetectRecordChanges" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions DetectRecordChanges = int32(192)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectRecordChanges" />
      <MemberSignature Language="VB.NET" Value="DetectRecordChanges" />
      <MemberSignature Language="F#" Value="DetectRecordChanges = 192" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.DetectRecordChanges" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>192</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-105">更新プログラム、有効にするは変更のレコードを検出し、データの変更が検出された場合のみ通知が生成されます。</span><span class="sxs-lookup"><span data-stu-id="aa014-105">On updates, enable change detection on records and only generates notifications if data changes are detected.</span></span>
            <span data-ttu-id="aa014-106">これは自動的に、挿入を有効にし、分析を更新します。</span><span class="sxs-lookup"><span data-stu-id="aa014-106">This automatically enables inserts and updates analysis.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-107">追跡オプションはありません。</span><span class="sxs-lookup"><span data-stu-id="aa014-107">No tracking options.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalAndServerOperations">
      <MemberSignature Language="C#" Value="NotifyLocalAndServerOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalAndServerOperations = int32(15)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalAndServerOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalAndServerOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalAndServerOperations = 15" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalAndServerOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>15</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-108">(ローカルおよびサーバー プルまたはプッシュ) レコードの操作の通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-108">Generates notifications for local and server (pull or push) record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalConflictResolutionOperations">
      <MemberSignature Language="C#" Value="NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalConflictResolutionOperations = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalConflictResolutionOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalConflictResolutionOperations = 2" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalConflictResolutionOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-109">ローカルの競合の解決操作を記録するための通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-109">Generates notifications for local conflict resolution record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyLocalOperations">
      <MemberSignature Language="C#" Value="NotifyLocalOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyLocalOperations = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyLocalOperations" />
      <MemberSignature Language="F#" Value="NotifyLocalOperations = 1" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyLocalOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-110">ローカルのレコードの操作の通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-110">Generates notifications for local record operations.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerBatch">
      <MemberSignature Language="C#" Value="NotifyServerBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerBatch = int32(48)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerBatch" />
      <MemberSignature Language="F#" Value="NotifyServerBatch = 48" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>48</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-111">サーバーのプル サブスクリプションまたはサーバー プッシュによってトリガー操作バッチの最後に通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-111">Generates a notification at the end of an operation batch triggered by a server pull or a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerOperations">
      <MemberSignature Language="C#" Value="NotifyServerOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerOperations = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerOperations" />
      <MemberSignature Language="F#" Value="NotifyServerOperations = 12" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-112">サーバーのプル サブスクリプションまたはサーバー プッシュでの操作のトリガーされた通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-112">Generates notifications for operations triggerd by a server pull or a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPullBatch">
      <MemberSignature Language="C#" Value="NotifyServerPullBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPullBatch = int32(16)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPullBatch" />
      <MemberSignature Language="F#" Value="NotifyServerPullBatch = 16" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-113">サーバー プルによってトリガー操作バッチの最後に通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-113">Generates a notification at the end of an operation batch triggered by a server pull.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPullOperations">
      <MemberSignature Language="C#" Value="NotifyServerPullOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPullOperations = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPullOperations" />
      <MemberSignature Language="F#" Value="NotifyServerPullOperations = 4" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPullOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-114">サーバー プルによってトリガーされる操作の通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-114">Generates notifications for operations triggered by a server pull.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPushBatch">
      <MemberSignature Language="C#" Value="NotifyServerPushBatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPushBatch = int32(32)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushBatch" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPushBatch" />
      <MemberSignature Language="F#" Value="NotifyServerPushBatch = 32" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushBatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-115">サーバー プッシュによってトリガー操作バッチの最後に通知を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-115">Generates a notification at the end of an operation batch triggered by a server push.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotifyServerPushOperations">
      <MemberSignature Language="C#" Value="NotifyServerPushOperations" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions NotifyServerPushOperations = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushOperations" />
      <MemberSignature Language="VB.NET" Value="NotifyServerPushOperations" />
      <MemberSignature Language="F#" Value="NotifyServerPushOperations = 8" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions.NotifyServerPushOperations" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa014-116">Notifiactions サーバー プッシュによってトリガーされる操作を生成します。</span><span class="sxs-lookup"><span data-stu-id="aa014-116">Generates notifiactions for operations triggered by a server push.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>