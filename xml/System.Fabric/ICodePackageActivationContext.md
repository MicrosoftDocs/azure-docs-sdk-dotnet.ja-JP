<Type Name="ICodePackageActivationContext" FullName="System.Fabric.ICodePackageActivationContext">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1a60c-101">Service Fabric のアクティベーション コンテキストを表しますには、サービスがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="1a60c-101">Represents activation context for the Service Fabric activated service.</span></span>
            </summary>
    <remarks><span data-ttu-id="1a60c-102">サービス マニフェストからの情報と作業のように、現在アクティブ化されたコード パッケージに関する情報を含むディレクトリ、コンテキスト id などです。</span><span class="sxs-lookup"><span data-stu-id="1a60c-102">Includes information from the service manifest as well as information about the currently activated code package like work directory, context id etc.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="System.Fabric.ICodePackageActivationContext.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-103">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-103">Gets the application name.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-104">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a60c-104">The name of the application.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.ICodePackageActivationContext.ApplicationTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-105">アプリケーションの種類名を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-105">Gets the application type name.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-106">アプリケーションの種類名。</span><span class="sxs-lookup"><span data-stu-id="1a60c-106">The name of the application type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-107">イベント発生時に新しい<see cref="T:System.Fabric.CodePackage" />サービス マニフェストに追加します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-107">Event raised when new <see cref="T:System.Fabric.CodePackage" /> is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-108">いつ発生するイベント、<see cref="T:System.Fabric.CodePackage" />サービスではマニフェストを変更します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-108">Event raised when a <see cref="T:System.Fabric.CodePackage" /> in the service manifest is modified.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.ICodePackageActivationContext.CodePackageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-109">アクティブ化されてファブリック コード パッケージの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-109">Gets the name of the fabric activated code package.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-110">ファブリックの名前には、コード パッケージがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="1a60c-110">The name of the fabric activated code package.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.CodePackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event CodePackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-111">いつ発生するイベント、<see cref="T:System.Fabric.CodePackage" />サービス マニフェストから削除されます。</span><span class="sxs-lookup"><span data-stu-id="1a60c-111">Event raised when a <see cref="T:System.Fabric.CodePackage" /> is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.ICodePackageActivationContext.CodePackageVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-112">アクティブ化されてファブリック コード パッケージのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-112">Gets the version of the fabric activated code package.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-113">ファブリックのバージョンでは、コード パッケージがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="1a60c-113">The version of the fabric activated code package.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-114">イベント発生時に新しい<see cref="T:System.Fabric.ConfigurationPackage" />サービス マニフェストに追加します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-114">Event raised when new <see cref="T:System.Fabric.ConfigurationPackage" /> is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-115">いつ発生するイベント、<see cref="T:System.Fabric.ConfigurationPackage" />サービスではマニフェストを変更します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-115">Event raised when a <see cref="T:System.Fabric.ConfigurationPackage" /> in the service manifest is modified.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event ConfigurationPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-116">いつ発生するイベント、<see cref="T:System.Fabric.ConfigurationPackage" />サービス マニフェストから削除されます。</span><span class="sxs-lookup"><span data-stu-id="1a60c-116">Event raised when a <see cref="T:System.Fabric.ConfigurationPackage" /> is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContextId">
      <MemberSignature Language="C#" Value="public string ContextId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContextId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.ContextId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContextId As String" />
      <MemberSignature Language="F#" Value="member this.ContextId : string" Usage="System.Fabric.ICodePackageActivationContext.ContextId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-117">コンテキスト ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-117">Gets the context id.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-118">コンテキスト id です。</span><span class="sxs-lookup"><span data-stu-id="1a60c-118">The context id.</span></span></value>
        <remarks><span data-ttu-id="1a60c-119">コンテキスト id は、1 つのサービス マニフェスト内のすべてのコード パッケージに同じです。</span><span class="sxs-lookup"><span data-stu-id="1a60c-119">The context id is the same for all code packages in the same service manifest.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAddedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-120">イベント発生時に新しい<see cref="T:System.Fabric.DataPackage" />サービス マニフェストに追加します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-120">Event raised when new <see cref="T:System.Fabric.DataPackage" /> is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModifiedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-121">いつ発生するイベント、<see cref="T:System.Fabric.DataPackage" />サービスではマニフェストを変更します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-121">Event raised when a <see cref="T:System.Fabric.DataPackage" /> in the service manifest is modified.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemovedEvent">
      <MemberSignature Language="C#" Value="event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.ICodePackageActivationContext.DataPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Event DataPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-122">いつ発生するイベント、<see cref="T:System.Fabric.DataPackage" />サービス マニフェストから削除されます。</span><span class="sxs-lookup"><span data-stu-id="1a60c-122">Event raised when a <see cref="T:System.Fabric.DataPackage" /> is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPrincipals">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetApplicationPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationPrincipals () As ApplicationPrincipalsDescription" />
      <MemberSignature Language="F#" Value="abstract member GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription" Usage="iCodePackageActivationContext.GetApplicationPrincipals " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationPrincipalsDescription</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-123">アプリケーション マニフェストで定義されているプリンシパルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-123">Retrieves the principals defined in the application manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-124">アプリケーション マニフェストで定義されているプリンシパル。</span><span class="sxs-lookup"><span data-stu-id="1a60c-124">The principals defined in the application manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetCodePackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetCodePackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetCodePackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetCodePackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-125">サービス マニフェスト内のコード パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-125">Retrieves the list of code package names in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-126">サービス マニフェスト内のコード パッケージ名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="1a60c-126">The list of code package names in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackage GetCodePackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.CodePackage GetCodePackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetCodePackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageObject (packageName As String) As CodePackage" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageObject : string -&gt; System.Fabric.CodePackage" Usage="iCodePackageActivationContext.GetCodePackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName"><span data-ttu-id="1a60c-127">コード パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="1a60c-127">The name of the code package.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-128">返します、<see cref="T:System.Fabric.CodePackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-128">Returns the <see cref="T:System.Fabric.CodePackage" /> object from Service Package that matches the desired package name.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-129"><see cref="T:System.Fabric.CodePackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-129">The <see cref="T:System.Fabric.CodePackage" /> object from Service Package that matches the desired package name.</span></span></returns>
        <remarks><span data-ttu-id="1a60c-130">パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="1a60c-130">Throws KeyNotFoundException exception if the package is not found.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetConfigurationPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetConfigurationPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetConfigurationPackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-131">サービス マニフェストの構成パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-131">Retrieves the list of configuration package names in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-132">サービス マニフェスト内の構成パッケージ名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="1a60c-132">The list of configuration package names in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.ConfigurationPackage GetConfigurationPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.ConfigurationPackage GetConfigurationPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageObject (packageName As String) As ConfigurationPackage" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage" Usage="iCodePackageActivationContext.GetConfigurationPackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ConfigurationPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName"><span data-ttu-id="1a60c-133">構成パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="1a60c-133">The name of the configuration package.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-134">返します、<see cref="T:System.Fabric.ConfigurationPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-134">Returns the <see cref="T:System.Fabric.ConfigurationPackage" /> object from Service Package that matches the desired package name.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-135"><see cref="T:System.Fabric.ConfigurationPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-135">The <see cref="T:System.Fabric.ConfigurationPackage" /> object from Service Package that matches the desired package name.</span></span></returns>
        <remarks><span data-ttu-id="1a60c-136">パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="1a60c-136">Throws KeyNotFoundException exception if the package is not found.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetDataPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetDataPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetDataPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="iCodePackageActivationContext.GetDataPackageNames " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-137">サービス マニフェスト内のデータ パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-137">Retrieves the list of data package names in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-138">データの一覧には、サービス マニフェストの名前がパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-138">The list of data package names in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.DataPackage GetDataPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.DataPackage GetDataPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetDataPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageObject (packageName As String) As DataPackage" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageObject : string -&gt; System.Fabric.DataPackage" Usage="iCodePackageActivationContext.GetDataPackageObject packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName"><span data-ttu-id="1a60c-139">データ パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="1a60c-139">The name of the data package.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-140">返します、<see cref="T:System.Fabric.DataPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-140">Returns the <see cref="T:System.Fabric.DataPackage" /> object from Service Package that matches the desired package name.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-141"><see cref="T:System.Fabric.DataPackage" />必要なパッケージ名に一致するサービス パッケージからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1a60c-141">The <see cref="T:System.Fabric.DataPackage" /> object from Service Package that matches the desired package name.</span></span></returns>
        <remarks><span data-ttu-id="1a60c-142">パッケージが見つからない場合は、KeyNotFoundException 例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="1a60c-142">Throws KeyNotFoundException exception if the package is not found.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointResourceDescription GetEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.EndpointResourceDescription GetEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint (endpointName As String) As EndpointResourceDescription" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription" Usage="iCodePackageActivationContext.GetEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EndpointResourceDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName"><span data-ttu-id="1a60c-143">エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="1a60c-143">The name of the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-144">サービス マニフェストから名前が指定されたエンドポイントのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-144">Retrieves the endpoint resource with a given name from the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-145">指定した名前のエンドポイント リソースです。</span><span class="sxs-lookup"><span data-stu-id="1a60c-145">The endpoint resource with the specified name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoints () As KeyedCollection(Of String, EndpointResourceDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;" Usage="iCodePackageActivationContext.GetEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.EndpointResourceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-146">サービス マニフェスト内のエンドポイントのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-146">Retrieves the endpoint resources in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-147">サービス マニフェスト内のエンドポイント リソース。</span><span class="sxs-lookup"><span data-stu-id="1a60c-147">The endpoint resources in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceGroupTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupTypes () As KeyedCollection(Of String, ServiceGroupTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;" Usage="iCodePackageActivationContext.GetServiceGroupTypes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceGroupTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-148">サービス マニフェスト内のサービス グループの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-148">Retrieves the list of Service Group types in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-149">サービス マニフェスト内のサービス グループの種類の一覧。</span><span class="sxs-lookup"><span data-stu-id="1a60c-149">The list of Service Group types in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestName">
      <MemberSignature Language="C#" Value="public string GetServiceManifestName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestName() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestName () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestName : unit -&gt; string" Usage="iCodePackageActivationContext.GetServiceManifestName " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-150">サービス マニフェストの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-150">Retrieves the name of the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-151">サービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="1a60c-151">The name of the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string GetServiceManifestVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestVersion () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestVersion : unit -&gt; string" Usage="iCodePackageActivationContext.GetServiceManifestVersion " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-152">サービス マニフェストのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-152">Retrieves the version of the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-153">サービス マニフェストのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1a60c-153">The version of the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.GetServiceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypes () As KeyedCollection(Of String, ServiceTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;" Usage="iCodePackageActivationContext.GetServiceTypes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-154">サービス マニフェスト内のサービスの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-154">Retrieves the list of Service types in the service manifest.</span></span>
            </summary>
        <returns><span data-ttu-id="1a60c-155">サービス マニフェスト内のサービス型の一覧。</span><span class="sxs-lookup"><span data-stu-id="1a60c-155">The list of service types in the service manifest.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.LogDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-156">アプリケーションを使用してログ ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-156">Gets the path to the Log directory that the application can use.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-157">コード パッケージのログ ディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="1a60c-157">The path to the code package Log directory.</span></span></value>
        <remarks><span data-ttu-id="1a60c-158">パラメーター名のログインに ClusterManifest の LogicalDirectories セクションし、返されるパスを指定した場合は、パラメーター値にシンボリック リンクです。</span><span class="sxs-lookup"><span data-stu-id="1a60c-158">If you have specified a parameter name Log in LogicalDirectories section of ClusterManifest then the returned path is a symbolic link to the parameter value.</span></span>
            <span data-ttu-id="1a60c-159">ex: 場合<LogicalDirectory LogicalDirectoryName="Log" MappedTo="F:\Log" />が指定されている LogDirectory に返されるパスは F:\Log\NodeId\ApplicationType_ApplicationVersion へのシンボリック リンクになります</span><span class="sxs-lookup"><span data-stu-id="1a60c-159">for ex: if <LogicalDirectory LogicalDirectoryName="Log" MappedTo="F:\Log" /> is specified then the returned path to LogDirectory will be a symbolic link to F:\Log\NodeId\ApplicationType_ApplicationVersion</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-160"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-160">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-161">現在のアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-161">Reports health for current application.</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-162"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-162">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="1a60c-163"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-163">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="1a60c-164">現在のアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-164">Reports health for current application.</span></span> <span data-ttu-id="1a60c-165">レポートを送信する方法を制御するオプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-165">Specifies options to control how the report is sent.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-166">ヘルス情報をレポートします。</span><span class="sxs-lookup"><span data-stu-id="1a60c-166">Health information that is to be reported.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-167">現在展開済みのアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-167">Reports health for current deployed application.</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-168"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-168">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="1a60c-169"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-169">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="1a60c-170">現在展開済みのアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-170">Reports health for current deployed application.</span></span> <span data-ttu-id="1a60c-171">レポートを送信する方法を制御するオプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-171">Specifies options to control how the report is sent.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedServicePackageHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-172">ヘルス情報をレポートします。</span><span class="sxs-lookup"><span data-stu-id="1a60c-172">Health information that is to be reported.</span></span></param>
        <summary>
            <span data-ttu-id="1a60c-173">現在の展開済みサービス パッケージの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-173">Reports health for current deployed service package.</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iCodePackageActivationContext.ReportDeployedServicePackageHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="1a60c-174"><see cref="T:System.Fabric.Health.HealthInformation" />正常性レポートの情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-174">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="1a60c-175"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-175">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="1a60c-176">現在の展開済みサービス パッケージの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-176">Reports health for current deployed service package.</span></span> <span data-ttu-id="1a60c-177">正常性ストアに、レポートを送信する方法を制御する送信オプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-177">Specifies send options that control how the report is sent to the health store.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.TempDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-178">アプリケーションを使用して Temp ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-178">Gets the path to the Temp directory that the application can use.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-179">コード パッケージの Temp ディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="1a60c-179">The path to the code package Temp directory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.ICodePackageActivationContext.WorkDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a60c-180">アプリケーションを使用して作業ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a60c-180">Gets the path to the Work directory that the application can use.</span></span>
            </summary>
        <value><span data-ttu-id="1a60c-181">コード パッケージの作業ディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="1a60c-181">The path to the code package Work directory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>