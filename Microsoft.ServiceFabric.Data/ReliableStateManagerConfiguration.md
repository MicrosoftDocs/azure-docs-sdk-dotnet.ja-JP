<Type Name="ReliableStateManagerConfiguration" FullName="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration">
  <TypeSignature Language="C#" Value="public class ReliableStateManagerConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReliableStateManagerConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManagerConfiguration" />
  <TypeSignature Language="F#" Value="type ReliableStateManagerConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b5fa-101">構成オブジェクトが ReliableStateManager を作成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-101">Configuration object used to create ReliableStateManager.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManagerConfiguration (Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings replicatorSettings, Func&lt;System.Threading.Tasks.Task&gt; onInitializeStateSerializersEvent = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings replicatorSettings, class System.Func`1&lt;class System.Threading.Tasks.Task&gt; onInitializeStateSerializersEvent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.#ctor(Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings,System.Func{System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (replicatorSettings As ReliableStateManagerReplicatorSettings, Optional onInitializeStateSerializersEvent As Func(Of Task) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration : Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings * Func&lt;System.Threading.Tasks.Task&gt; -&gt; Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration (replicatorSettings, onInitializeStateSerializersEvent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings" />
        <Parameter Name="onInitializeStateSerializersEvent" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings"><span data-ttu-id="2b5fa-102">レプリケーターの設定、ReliableStateManager を初期化するために使用します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-102">Replicator settings used to initialize the ReliableStateManager.</span></span></param>
        <param name="onInitializeStateSerializersEvent">
            <span data-ttu-id="2b5fa-103">カスタムのシリアライザーを追加する必要があるときにも発生する省略可能なコールバックです。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-103">Optional callback which will fire when custom serializers should be added.</span></span>
            <span data-ttu-id="2b5fa-104">設定するため、<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-104">Used to set the <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" /> property.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b5fa-105">新しい ReliableStateManagerConfiguration を作成します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-105">Create a new ReliableStateManagerConfiguration.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManagerConfiguration (string configPackageName = &quot;Config&quot;, string replicatorSecuritySectionName = &quot;ReplicatorSecurityConfig&quot;, string replicatorSettingsSectionName = &quot;ReplicatorConfig&quot;, Func&lt;System.Threading.Tasks.Task&gt; onInitializeStateSerializersEvent = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configPackageName, string replicatorSecuritySectionName, string replicatorSettingsSectionName, class System.Func`1&lt;class System.Threading.Tasks.Task&gt; onInitializeStateSerializersEvent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.#ctor(System.String,System.String,System.String,System.Func{System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional configPackageName As String = &quot;Config&quot;, Optional replicatorSecuritySectionName As String = &quot;ReplicatorSecurityConfig&quot;, Optional replicatorSettingsSectionName As String = &quot;ReplicatorConfig&quot;, Optional onInitializeStateSerializersEvent As Func(Of Task) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration : string * string * string * Func&lt;System.Threading.Tasks.Task&gt; -&gt; Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration (configPackageName, replicatorSecuritySectionName, replicatorSettingsSectionName, onInitializeStateSerializersEvent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="replicatorSecuritySectionName" Type="System.String" />
        <Parameter Name="replicatorSettingsSectionName" Type="System.String" />
        <Parameter Name="onInitializeStateSerializersEvent" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="configPackageName"><span data-ttu-id="2b5fa-106">レプリケーター/セキュリティの設定の読み込み元のオプションの構成パッケージ名です。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-106">Optional config package name from which to load replicator security/settings.</span></span></param>
        <param name="replicatorSecuritySectionName"><span data-ttu-id="2b5fa-107">レプリケーターのセキュリティ設定の読み込み元のオプションの構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-107">Optional config section name from which to load replicator security settings.</span></span></param>
        <param name="replicatorSettingsSectionName"><span data-ttu-id="2b5fa-108">レプリケーターの設定の読み込み元のオプションの構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-108">Optional config section name from which to load replicator settings.</span></span></param>
        <param name="onInitializeStateSerializersEvent">
            <span data-ttu-id="2b5fa-109">カスタムのシリアライザーを追加する必要があるときにも発生する省略可能なコールバックです。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-109">Optional callback which will fire when custom serializers should be added.</span></span>
            <span data-ttu-id="2b5fa-110">設定するため、<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-110">Used to set the <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" /> property.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b5fa-111">新しい ReliableStateManagerConfiguration を作成します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-111">Create a new ReliableStateManagerConfiguration.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigPackageName">
      <MemberSignature Language="C#" Value="public string ConfigPackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigPackageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConfigPackageName As String" />
      <MemberSignature Language="F#" Value="member this.ConfigPackageName : string" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b5fa-112">レプリケーター設定および複製物作成会社のセキュリティ設定の読み込み元の Settings.xml 内には、構成パッケージの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-112">Gets the name of the config package in Settings.xml from which to load replicator settings and replicator security settings.</span></span>
            </summary>
        <value><span data-ttu-id="2b5fa-113">構成パッケージ名です。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-113">The config package name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitializeStateSerializersEvent">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.Tasks.Task&gt; OnInitializeStateSerializersEvent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`1&lt;class System.Threading.Tasks.Task&gt; OnInitializeStateSerializersEvent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OnInitializeStateSerializersEvent As Func(Of Task)" />
      <MemberSignature Language="F#" Value="member this.OnInitializeStateSerializersEvent : Func&lt;System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.OnInitializeStateSerializersEvent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b5fa-114">カスタムのシリアライザーを追加するときに呼び出されるデリゲートを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-114">Gets the delegate which will be called when custom serializers can be added.</span></span>  
            <span data-ttu-id="2b5fa-115">呼び出されると、指定を使用してカスタムのシリアライザー<see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" /></span><span class="sxs-lookup"><span data-stu-id="2b5fa-115">When called, specify custom serializers via <see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" /></span></span></summary>
        <value><span data-ttu-id="2b5fa-116">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-116">Task that represents the asynchronous operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSecuritySectionName">
      <MemberSignature Language="C#" Value="public string ReplicatorSecuritySectionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorSecuritySectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSecuritySectionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSecuritySectionName As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSecuritySectionName : string" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSecuritySectionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b5fa-117">レプリケーターのセキュリティ設定を取得セクション名。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-117">Gets the replicator security settings section name.</span></span>
            </summary>
        <value><span data-ttu-id="2b5fa-118">セクション名。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-118">The section name.</span></span></value>
        <remarks><span data-ttu-id="2b5fa-119">によって指定された構成パッケージに存在する場合<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" />Settings.xml で複製物作成会社のセキュリティ設定を構成するこのセクションが使用されます。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-119">If present in the config package specified by <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" /> in Settings.xml, this section will be used to configure replicator security settings.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings ReplicatorSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings ReplicatorSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettings As ReliableStateManagerReplicatorSettings" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettings : Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ReliableStateManagerReplicatorSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b5fa-120">取得または複製物作成会社の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-120">Gets or sets the replicator settings.</span></span>
            </summary>
        <value><span data-ttu-id="2b5fa-121">レプリケーターの設定。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-121">The replicator settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettingsSectionName">
      <MemberSignature Language="C#" Value="public string ReplicatorSettingsSectionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorSettingsSectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSettingsSectionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettingsSectionName As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettingsSectionName : string" Usage="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ReplicatorSettingsSectionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b5fa-122">レプリケーターの取得の設定セクションの名前。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-122">Gets the replicator settings section name.</span></span>
            </summary>
        <value><span data-ttu-id="2b5fa-123">セクション名。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-123">The section name.</span></span></value>
        <remarks><span data-ttu-id="2b5fa-124">によって指定された構成パッケージに存在する場合<see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" />Settings.xml で複製物作成会社の設定を構成するこのセクションが使用されます。</span><span class="sxs-lookup"><span data-stu-id="2b5fa-124">If present in the config package specified by <see cref="P:Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration.ConfigPackageName" /> in Settings.xml, this section will be used to configure replicator settings.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>