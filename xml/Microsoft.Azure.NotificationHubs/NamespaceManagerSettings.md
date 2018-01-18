<Type Name="NamespaceManagerSettings" FullName="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManagerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManagerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManagerSettings" />
  <TypeSignature Language="F#" Value="type NamespaceManagerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6e875-101">名前空間マネージャーの設定が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6e875-101">Contains the settings for the namespace manager.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManagerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6e875-102"><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e875-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e875-103">取得または GetQueue CreateQueue、やなど、すべてのサービス名前空間の管理操作の操作のタイムアウト期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e875-103">Gets or sets the operation timeout period for all service namespace management operations, such as GetQueue, CreateQueue, and so on.</span></span></summary>
        <value><span data-ttu-id="6e875-104">A<see cref="T:System.TimeSpan" />タイムアウト期間を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6e875-104">A <see cref="T:System.TimeSpan" /> object that represents the timeout period.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6e875-105">null 値設定されている場合の例: null 許容 TimeSpan をスローします。</span><span class="sxs-lookup"><span data-stu-id="6e875-105">throws if a null is set - e.g. a nullable TimeSpan.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="6e875-106">TimeSpan が設定されている、ゼロまたは負の値とスローされます。</span><span class="sxs-lookup"><span data-stu-id="6e875-106">throws when a zero or negative TimeSpan is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.NotificationHubs.RetryPolicy with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e875-107">取得または信頼性の低いアクションおよび一時的な状態の名前空間マネージャーに関連付けられている場合は、この再試行メカニズムの基本実装を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e875-107">Gets or sets the base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></summary>
        <value><span data-ttu-id="6e875-108">この再試行メカニズムで信頼性の低いアクションおよび名前空間マネージャーに関連付けられている一時的な問題の基本実装。</span><span class="sxs-lookup"><span data-stu-id="6e875-108">The base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e875-109">取得またはセキュリティ トークン プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6e875-109">Gets or sets the security token provider.</span></span></summary>
        <value><span data-ttu-id="6e875-110">セキュリティ トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="6e875-110">The security token provider.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>