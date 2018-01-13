<Type Name="ServiceNotificationFilterDescription" FullName="System.Fabric.Description.ServiceNotificationFilterDescription">
  <TypeSignature Language="C#" Value="public class ServiceNotificationFilterDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceNotificationFilterDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceNotificationFilterDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNotificationFilterDescription" />
  <TypeSignature Language="F#" Value="type ServiceNotificationFilterDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="53349-101">によって登録されたサービスの通知の配信用のフィルターの記述に使用されるクラスを表します<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="53349-101">Represents a class that is used to describe a filter for service notification delivery, registered via <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="53349-102"><see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53349-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription (Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor(System.Uri,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As Uri, matchNamePrefix As Boolean, matchPrimaryChangeOnly As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceNotificationFilterDescription : Uri * bool * bool -&gt; System.Fabric.Description.ServiceNotificationFilterDescription" Usage="new System.Fabric.Description.ServiceNotificationFilterDescription (name, matchNamePrefix, matchPrimaryChangeOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="matchNamePrefix" Type="System.Boolean" />
        <Parameter Name="matchPrimaryChangeOnly" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="53349-103">通知の配信サービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="53349-103">The name for which service notifications should be delivered.</span></span></para>
        </param>
        <param name="matchNamePrefix">
          <para><span data-ttu-id="53349-104">すべての service 通知名は、プレフィックスかどうかを示すフラグが配信されます。</span><span class="sxs-lookup"><span data-stu-id="53349-104">Flag that indicates whether all service notifications for which Name is a prefix will be delivered.</span></span></para>
        </param>
        <param name="matchPrimaryChangeOnly">
          <para><span data-ttu-id="53349-105">プライマリ レプリカのエンドポイントが変更されていない通知をフィルターしてサービス通知の配信に一致するかどうかを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="53349-105">Flag that indicates whether to match the service notification delivery by filtering out notifications in which the primary replica endpoint has not changed.</span></span> <span data-ttu-id="53349-106">このフラグには、ステートレスなサービスの効果はありません。</span><span class="sxs-lookup"><span data-stu-id="53349-106">This flag has no effect for stateless services.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="53349-107"><see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53349-107">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchNamePrefix">
      <MemberSignature Language="C#" Value="public bool MatchNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchNamePrefix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchNamePrefix As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchNamePrefix : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="53349-108">名前のプレフィックスすべてのサービスの通知を配信するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="53349-108">Gets a value that indicates whether all service notifications for which Name is a prefix will be delivered.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="53349-109"><languageKeyword>true</languageKeyword>名のプレフィックスすべてのサービス通知は配信された、それ以外になる場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="53349-109"><languageKeyword>true</languageKeyword> if all service notification for which Name is a prefix will be delivered; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="53349-110">既定値は <languageKeyword>false</languageKeyword> です。</span><span class="sxs-lookup"><span data-stu-id="53349-110">The default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
            <span data-ttu-id="53349-111">文字列プレフィックスではなく、URI セグメントのプレフィックスの一致項目がサービス名と一致するので、プレフィックスの一致が発生します。</span><span class="sxs-lookup"><span data-stu-id="53349-111">The prefix match occurs as a URI segment prefix match rather than a string prefix match against service names.</span></span> <span data-ttu-id="53349-112">名前のフィルター"ファブリック:/abc"という名前の一致するサービスをプレフィックス"ファブリック:/abc"と"fabric:/abc def"、という名前のサービスされませんが、"ファブリック:/abc_def"です。</span><span class="sxs-lookup"><span data-stu-id="53349-112">A filter with the name "fabric:/abc" will prefix match services named "fabric:/abc" and "fabric:/abc/def", but not a service named "fabric:/abc_def".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchPrimaryChangeOnly">
      <MemberSignature Language="C#" Value="public bool MatchPrimaryChangeOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchPrimaryChangeOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchPrimaryChangeOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchPrimaryChangeOnly : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="53349-113">プライマリ レプリカのエンドポイントが変更されていない通知をフィルターしてサービス通知の配信に一致するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="53349-113">Gets a value that indicates whether to match the service notification delivery by filtering out notifications in which the primary replica endpoint has not changed.</span></span> <span data-ttu-id="53349-114">このフラグには、ステートレスなサービスの効果はありません。</span><span class="sxs-lookup"><span data-stu-id="53349-114">This flag has no effect for stateless services.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="53349-115"><languageKeyword>true</languageKeyword>のみです。 それ以外の場合には、主な変更をと一致するフィルター場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="53349-115"><languageKeyword>true</languageKeyword> if the filtering matches primary change only; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="53349-116">既定値は <languageKeyword>false</languageKeyword> です。</span><span class="sxs-lookup"><span data-stu-id="53349-116">The default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Uri Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Uri" />
      <MemberSignature Language="F#" Value="member this.Name : Uri with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="53349-117">通知の配信サービスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="53349-117">Gets the name for which service notifications should be delivered.</span></span> <span data-ttu-id="53349-118">名前は、ファブリックにする必要があります。 スキームです。</span><span class="sxs-lookup"><span data-stu-id="53349-118">The name must be in the fabric: scheme.</span></span> <span data-ttu-id="53349-119">ルートの名前 ("fabric:") は許可されています。</span><span class="sxs-lookup"><span data-stu-id="53349-119">The root name ("fabric:") is allowed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="53349-120">通知の配信サービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="53349-120">The name for which service notifications should be delivered.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>