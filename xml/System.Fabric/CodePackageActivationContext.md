<Type Name="CodePackageActivationContext" FullName="System.Fabric.CodePackageActivationContext">
  <TypeSignature Language="C#" Value="public class CodePackageActivationContext : IDisposable, System.Fabric.ICodePackageActivationContext3" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CodePackageActivationContext extends System.Object implements class System.Fabric.ICodePackageActivationContext, class System.Fabric.ICodePackageActivationContext2, class System.Fabric.ICodePackageActivationContext3, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CodePackageActivationContext" />
  <TypeSignature Language="VB.NET" Value="Public Class CodePackageActivationContext&#xA;Implements ICodePackageActivationContext3, IDisposable" />
  <TypeSignature Language="F#" Value="type CodePackageActivationContext = class&#xA;    interface ICodePackageActivationContext3&#xA;    interface ICodePackageActivationContext2&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext3</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="875bd-101">Service Fabric アプリケーションの実行中のコード パッケージに関する情報を含む、アクティブ化を表します。</span><span class="sxs-lookup"><span data-stu-id="875bd-101">Represents the activation which contains information about a running code package in a Service Fabric application.</span></span></para>
      <para><span data-ttu-id="875bd-102"><see cref="M:System.Fabric.FabricRuntime.GetActivationContext" />と<see cref="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />アクティベーション コンテキストのインスタンスを取得するメソッドを使用できます。</span><span class="sxs-lookup"><span data-stu-id="875bd-102">The <see cref="M:System.Fabric.FabricRuntime.GetActivationContext" /> and <see cref="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" /> methods can be used to get an instance of the activation context.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public string ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : string" Usage="System.Fabric.CodePackageActivationContext.ApplicationName" />
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
          <para><span data-ttu-id="875bd-103">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-103">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-104">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="875bd-104">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.CodePackageActivationContext.ApplicationTypeName" />
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
          <para><span data-ttu-id="875bd-105">アプリケーションの種類の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-105">Gets the name of the application type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-106">アプリケーションの種類名。</span><span class="sxs-lookup"><span data-stu-id="875bd-106">The name of the application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageAdded As EventHandler(Of PackageAddedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-107">サービス マニフェストに新しいコード パッケージが追加されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-107">Raised when a new code package is added to the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-108">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-108">Obsolete.</span></span> <span data-ttu-id="875bd-109">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-109">Use <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-110">サービス マニフェストに新しいコード パッケージが追加されると、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-110">Raised during an application upgrade when a new code package is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageModified As EventHandler(Of PackageModifiedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-111">サービス マニフェストで既存のコード パッケージが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-111">Raised when an existing code package is modified in the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-112">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-112">Obsolete.</span></span> <span data-ttu-id="875bd-113">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageModifiedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-113">Use <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageModifiedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-114">サービス マニフェストで既存のコード パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-114">Raised during an application upgrade when an existing code package is modified in the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.CodePackageActivationContext.CodePackageName" />
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
          <para><span data-ttu-id="875bd-115">アクティブ化されてファブリック コード パッケージの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-115">Gets the name of the fabric activated code package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-116">ファブリックの名前には、コード パッケージがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="875bd-116">The name of the fabric activated code package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.CodePackageDescription&gt;&gt; CodePackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of CodePackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " Usage="member this.CodePackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CodePackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.CodePackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-117">サービス マニフェストからコード パッケージが削除されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-117">Raised when the code package is removed from the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-118">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-118">Obsolete.</span></span> <span data-ttu-id="875bd-119">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-119">Use <see cref="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.CodePackage&gt;&gt; CodePackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.CodePackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event CodePackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of CodePackage)) " />
      <MemberSignature Language="F#" Value="member this.CodePackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " Usage="member this.CodePackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.CodePackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.CodePackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-120">サービス マニフェストからコード パッケージが削除されたときに、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-120">Raised during an application upgrade when a code package is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.CodePackageActivationContext.CodePackageVersion" />
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
          <para><span data-ttu-id="875bd-121">アクティブ化されてファブリック コード パッケージのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-121">Gets the version of the fabric activated code package</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-122">ファブリックのバージョンでは、コード パッケージがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="875bd-122">The version of the fabric activated code package.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageAdded As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-123">サービス マニフェストに新しい構成パッケージが追加されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-123">Raised when a new configuration package is added to the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-124">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-124">Obsolete.</span></span> <span data-ttu-id="875bd-125">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-125">Use <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-126">サービス マニフェストに追加されると、新しい構成パッケージは、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-126">Raised during an application upgrade when a new configuration package is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageModified As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-127">サービス マニフェストで、構成パッケージが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-127">Raised when a configuration package is modified in the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-128">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-128">Obsolete.</span></span> <span data-ttu-id="875bd-129">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModifiedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-129">Use <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModifiedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-130">サービス マニフェストに、構成パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-130">Raised during an application upgrade when a configuration package is modified in the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; ConfigurationPackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " Usage="member this.ConfigurationPackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ConfigurationPackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.ConfigurationPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-131">サービス マニフェストから構成パッケージが削除されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-131">Raised when a configuration package is removed from the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-132">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-132">Obsolete.</span></span> <span data-ttu-id="875bd-133">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-133">Use <see cref="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigurationPackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.ConfigurationPackage&gt;&gt; ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.ConfigurationPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event ConfigurationPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of ConfigurationPackage)) " />
      <MemberSignature Language="F#" Value="member this.ConfigurationPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " Usage="member this.ConfigurationPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.ConfigurationPackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.ConfigurationPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-134">サービス マニフェストから削除されると、構成パッケージは、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-134">Raised during an application upgrade when a configuration package is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContextId">
      <MemberSignature Language="C#" Value="public string ContextId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContextId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ContextId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContextId As String" />
      <MemberSignature Language="F#" Value="member this.ContextId : string" Usage="System.Fabric.CodePackageActivationContext.ContextId" />
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
          <para><span data-ttu-id="875bd-135">アプリケーション パッケージ名を持つには、サービス パッケージ名が修飾を表す ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-135">Gets the ID that represents the service package name qualified with Application package name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-136">コンテキスト id。</span><span class="sxs-lookup"><span data-stu-id="875bd-136">The context ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAdded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageAdded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageAdded" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageAdded" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageAdded As EventHandler(Of PackageAddedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAdded : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageAdded : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageAddedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-137">サービス マニフェストに、データ パッケージが追加されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-137">Raised when a data package is added to the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-138">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-138">Obsolete.</span></span> <span data-ttu-id="875bd-139">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-139">Use <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageAddedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageAddedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageAddedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageAddedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageAddedEvent As EventHandler(Of PackageAddedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageAddedEvent : EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageAddedEvent : System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageAddedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageAddedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-140">サービス マニフェストに追加されると、データ パッケージは、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-140">Raised during an application upgrade when a data package is added to the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModified">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageModified;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageModified" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageModified" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageModified As EventHandler(Of PackageModifiedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModified : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageModified : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageModifiedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-141">サービス マニフェストで、データ パッケージが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-141">Raised when a data package is modified in the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-142">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-142">Obsolete.</span></span> <span data-ttu-id="875bd-143">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageModifiedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-143">Use <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageModifiedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageModifiedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageModifiedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageModifiedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageModifiedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageModifiedEvent As EventHandler(Of PackageModifiedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageModifiedEvent : EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageModifiedEvent : System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageModifiedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageModifiedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-144">サービス マニフェストに、データ パッケージが変更されたときに、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-144">Raised during an application upgrade when a data package is modified in the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemoved">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageRemoved;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.Description.DataPackageDescription&gt;&gt; DataPackageRemoved" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageRemoved" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageRemoved As EventHandler(Of PackageRemovedEventArgs(Of DataPackageDescription)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemoved : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " Usage="member this.DataPackageRemoved : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use DataPackageRemovedEvent event.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.Description.DataPackageDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-145">サービス マニフェストから、データ パッケージが削除されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-145">Raised when a data package is removed from the service manifest.</span></span>
            </summary>
        <remarks><span data-ttu-id="875bd-146">互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-146">Obsolete.</span></span> <span data-ttu-id="875bd-147">代わりに、<see cref="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="875bd-147">Use <see cref="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DataPackageRemovedEvent">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class System.Fabric.PackageRemovedEventArgs`1&lt;class System.Fabric.DataPackage&gt;&gt; DataPackageRemovedEvent" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.CodePackageActivationContext.DataPackageRemovedEvent" />
      <MemberSignature Language="VB.NET" Value="Public Event DataPackageRemovedEvent As EventHandler(Of PackageRemovedEventArgs(Of DataPackage)) " />
      <MemberSignature Language="F#" Value="member this.DataPackageRemovedEvent : EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " Usage="member this.DataPackageRemovedEvent : System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:System.Fabric.ICodePackageActivationContext.DataPackageRemovedEvent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;System.Fabric.PackageRemovedEventArgs&lt;System.Fabric.DataPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875bd-148">サービス マニフェストから、データ パッケージが削除されたときに、アプリケーションのアップグレード中に発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-148">Raised during an application upgrade when a data package is removed from the service manifest.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="codePackageActivationContext.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="875bd-149">コード パッケージのアクティベーション コンテキストを破棄します。</span><span class="sxs-lookup"><span data-stu-id="875bd-149">Disposes of the code package activation context.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~CodePackageActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="codePackageActivationContext.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="875bd-150">オブジェクトが破棄される前に、現在のオブジェクトによって保持されているアンマネージ リソースのクリーンアップ操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="875bd-150">Performs cleanup operations on unmanaged resources held by the current object before the object is destroyed.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPrincipals">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.ApplicationPrincipalsDescription GetApplicationPrincipals() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetApplicationPrincipals" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationPrincipals () As ApplicationPrincipalsDescription" />
      <MemberSignature Language="F#" Value="abstract member GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription&#xA;override this.GetApplicationPrincipals : unit -&gt; System.Fabric.Description.ApplicationPrincipalsDescription" Usage="codePackageActivationContext.GetApplicationPrincipals " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetApplicationPrincipals</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-151">アプリケーション マニフェストで定義されているすべてのプリンシパルを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-151">Retrieves all the principals defined in the application manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-152">アプリケーション マニフェストで定義されているプリンシパル。</span><span class="sxs-lookup"><span data-stu-id="875bd-152">The principals defined in the application manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.CodePackageDescription GetCodePackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.CodePackageDescription GetCodePackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackage (packageName As String) As CodePackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetCodePackage : string -&gt; System.Fabric.Description.CodePackageDescription" Usage="codePackageActivationContext.GetCodePackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetCodePackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.CodePackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para><span data-ttu-id="875bd-153">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-153">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-154">取得、<see cref="T:System.Fabric.Description.CodePackageDescription" />名前のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="875bd-154">Retrieves the <see cref="T:System.Fabric.Description.CodePackageDescription" /> object by name.</span></span></para>
          <para><span data-ttu-id="875bd-155">このメソッドは、互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-155">This method is obsolete.</span></span> <span data-ttu-id="875bd-156"><see cref="M:System.Fabric.CodePackageActivationContext.GetCodePackageObject(System.String)" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-156">Use <see cref="M:System.Fabric.CodePackageActivationContext.GetCodePackageObject(System.String)" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-157"><see cref="T:System.Fabric.Description.CodePackageDescription" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-157">Returns <see cref="T:System.Fabric.Description.CodePackageDescription" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-158">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-158">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetCodePackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetCodePackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetCodePackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetCodePackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetCodePackageNames</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-159">サービス マニフェスト内のコード パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-159">Retrieves the list of code package names in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-160">サービス マニフェスト内のコード パッケージ名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="875bd-160">The list of code package names in the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackage GetCodePackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.CodePackage GetCodePackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetCodePackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCodePackageObject (packageName As String) As CodePackage" />
      <MemberSignature Language="F#" Value="abstract member GetCodePackageObject : string -&gt; System.Fabric.CodePackage&#xA;override this.GetCodePackageObject : string -&gt; System.Fabric.CodePackage" Usage="codePackageActivationContext.GetCodePackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetCodePackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para><span data-ttu-id="875bd-161">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-161">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-162">取得、<see cref="T:System.Fabric.CodePackage" />名前のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="875bd-162">Retrieves the <see cref="T:System.Fabric.CodePackage" /> object by name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-163"><see cref="T:System.Fabric.CodePackage" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-163">Returns <see cref="T:System.Fabric.CodePackage" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-164">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-164">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ConfigurationPackageDescription GetConfigurationPackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.ConfigurationPackageDescription GetConfigurationPackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackage (packageName As String) As ConfigurationPackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetConfigurationPackage : string -&gt; System.Fabric.Description.ConfigurationPackageDescription" Usage="codePackageActivationContext.GetConfigurationPackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetConfigurationPackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ConfigurationPackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para><span data-ttu-id="875bd-165">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-165">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-166">取得、<see cref="T:System.Fabric.Description.ConfigurationPackageDescription" />名前のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="875bd-166">Retrieves the <see cref="T:System.Fabric.Description.ConfigurationPackageDescription" /> object by name.</span></span></para>
          <para><span data-ttu-id="875bd-167">このメソッドは、互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-167">This method is obsolete.</span></span> <span data-ttu-id="875bd-168"><see cref="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageObject(System.String)" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-168">Use <see cref="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageObject(System.String)" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-169"><see cref="T:System.Fabric.Description.ConfigurationPackageDescription" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-169">Returns <see cref="T:System.Fabric.Description.ConfigurationPackageDescription" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-170">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-170">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetConfigurationPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetConfigurationPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetConfigurationPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetConfigurationPackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageNames</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-171">サービス マニフェストの構成パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-171">Retrieves the list of configuration package names in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-172">サービス マニフェスト内の構成パッケージ名の一覧です。</span><span class="sxs-lookup"><span data-stu-id="875bd-172">The list of configuration package names in the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.ConfigurationPackage GetConfigurationPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.ConfigurationPackage GetConfigurationPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetConfigurationPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationPackageObject (packageName As String) As ConfigurationPackage" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage&#xA;override this.GetConfigurationPackageObject : string -&gt; System.Fabric.ConfigurationPackage" Usage="codePackageActivationContext.GetConfigurationPackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetConfigurationPackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para><span data-ttu-id="875bd-173">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-173">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-174">取得、<see cref="T:System.Fabric.ConfigurationPackage" />名前のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="875bd-174">Retrieves the <see cref="T:System.Fabric.ConfigurationPackage" /> object by name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-175"><see cref="T:System.Fabric.ConfigurationPackage" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-175">Returns <see cref="T:System.Fabric.ConfigurationPackage" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-176">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-176">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackage">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.DataPackageDescription GetDataPackage (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Description.DataPackageDescription GetDataPackage(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackage (packageName As String) As DataPackageDescription" />
      <MemberSignature Language="F#" Value="member this.GetDataPackage : string -&gt; System.Fabric.Description.DataPackageDescription" Usage="codePackageActivationContext.GetDataPackage packageName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use GetDataPackageObject method.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.DataPackageDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para><span data-ttu-id="875bd-177">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-177">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-178">取得、<see cref="T:System.Fabric.Description.DataPackageDescription" />名前。</span><span class="sxs-lookup"><span data-stu-id="875bd-178">Retrieves the <see cref="T:System.Fabric.Description.DataPackageDescription" /> by name.</span></span></para>
          <para><span data-ttu-id="875bd-179">このメソッドは、互換性のために残されています。</span><span class="sxs-lookup"><span data-stu-id="875bd-179">This method is obsolete.</span></span> <span data-ttu-id="875bd-180"><see cref="M:System.Fabric.CodePackageActivationContext.GetDataPackageObject(System.String)" />を使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-180">Use <see cref="M:System.Fabric.CodePackageActivationContext.GetDataPackageObject(System.String)" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-181"><see cref="T:System.Fabric.Description.DataPackageDescription" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-181">Returns <see cref="T:System.Fabric.Description.DataPackageDescription" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-182">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-182">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GetDataPackageNames ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;string&gt; GetDataPackageNames() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackageNames" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageNames () As IList(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;&#xA;override this.GetDataPackageNames : unit -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="codePackageActivationContext.GetDataPackageNames " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetDataPackageNames</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-183">サービス マニフェスト内のデータ パッケージ名の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-183">Retrieves the list of data package names in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-184">データの一覧には、サービス マニフェストの名前がパッケージ化します。</span><span class="sxs-lookup"><span data-stu-id="875bd-184">The list of data package names in the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataPackageObject">
      <MemberSignature Language="C#" Value="public System.Fabric.DataPackage GetDataPackageObject (string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.DataPackage GetDataPackageObject(string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDataPackageObject(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDataPackageObject (packageName As String) As DataPackage" />
      <MemberSignature Language="F#" Value="abstract member GetDataPackageObject : string -&gt; System.Fabric.DataPackage&#xA;override this.GetDataPackageObject : string -&gt; System.Fabric.DataPackage" Usage="codePackageActivationContext.GetDataPackageObject packageName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetDataPackageObject(System.String)</InterfaceMember>
      </Implements>
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
        <param name="packageName">
          <para><span data-ttu-id="875bd-185">検索するパッケージの名前</span><span class="sxs-lookup"><span data-stu-id="875bd-185">The name of the package to find</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-186">取得、<see cref="T:System.Fabric.DataPackage" />名前のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="875bd-186">Retrieves the <see cref="T:System.Fabric.DataPackage" /> object by name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-187"><see cref="T:System.Fabric.DataPackage" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="875bd-187">Returns <see cref="T:System.Fabric.DataPackage" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricElementNotFoundException"><span data-ttu-id="875bd-188">サービス マニフェストに、packageName が見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-188">The packageName was not found in the service manifest.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetDirectory : string -&gt; string&#xA;override this.GetDirectory : string -&gt; string" Usage="codePackageActivationContext.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext3.GetDirectory(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            <span data-ttu-id="875bd-189">作業ディレクトリ内のディレクトリのディレクトリ パスを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-189">Retrieves the directory path for the directory inside the work directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EndpointResourceDescription GetEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.Description.EndpointResourceDescription GetEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoint (endpointName As String) As EndpointResourceDescription" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription&#xA;override this.GetEndpoint : string -&gt; System.Fabric.Description.EndpointResourceDescription" Usage="codePackageActivationContext.GetEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetEndpoint(System.String)</InterfaceMember>
      </Implements>
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
        <param name="endpointName">
          <para><span data-ttu-id="875bd-190">エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="875bd-190">The name of the endpoint.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="875bd-191">取得、<see cref="T:System.Fabric.Description.EndpointResourceDescription" />名前。</span><span class="sxs-lookup"><span data-stu-id="875bd-191">Retrieves an <see cref="T:System.Fabric.Description.EndpointResourceDescription" /> by name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-192">指定した名前を持つエンドポイントの説明です。</span><span class="sxs-lookup"><span data-stu-id="875bd-192">The description of the endpoint with a specified name.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-193">endpointName が null または空</span><span class="sxs-lookup"><span data-stu-id="875bd-193">endpointName is null or empty</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="875bd-194">エンドポイントがサービス マニフェストに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="875bd-194">The endpoint was not found in the service manifest.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.EndpointResourceDescription&gt; GetEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEndpoints () As KeyedCollection(Of String, EndpointResourceDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;&#xA;override this.GetEndpoints : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.EndpointResourceDescription&gt;" Usage="codePackageActivationContext.GetEndpoints " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetEndpoints</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-195">サービス マニフェスト内のすべての終了ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-195">Retrieves all the end points in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-196">サービス マニフェストの終点。</span><span class="sxs-lookup"><span data-stu-id="875bd-196">The end points in the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceGroupTypeDescription&gt; GetServiceGroupTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceGroupTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupTypes () As KeyedCollection(Of String, ServiceGroupTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;&#xA;override this.GetServiceGroupTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceGroupTypeDescription&gt;" Usage="codePackageActivationContext.GetServiceGroupTypes " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceGroupTypes</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-197">サービス マニフェスト内のサービス グループの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-197">Retrieves the list of service group types in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-198">サービス マニフェスト内のサービス グループの種類の一覧。</span><span class="sxs-lookup"><span data-stu-id="875bd-198">The list of Service Group types in the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestName">
      <MemberSignature Language="C#" Value="public string GetServiceManifestName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestName() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestName () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestName : unit -&gt; string&#xA;override this.GetServiceManifestName : unit -&gt; string" Usage="codePackageActivationContext.GetServiceManifestName " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceManifestName</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-199">サービス マニフェストの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-199">Retrieves the name of the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-200">サービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="875bd-200">The name of the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string GetServiceManifestVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetServiceManifestVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestVersion () As String" />
      <MemberSignature Language="F#" Value="abstract member GetServiceManifestVersion : unit -&gt; string&#xA;override this.GetServiceManifestVersion : unit -&gt; string" Usage="codePackageActivationContext.GetServiceManifestVersion " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceManifestVersion</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-201">サービス マニフェストのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-201">Retrieves the version of the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-202">サービス マニフェストのバージョン。</span><span class="sxs-lookup"><span data-stu-id="875bd-202">The version of the service manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceTypeDescription&gt; GetServiceTypes() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.GetServiceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypes () As KeyedCollection(Of String, ServiceTypeDescription)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;&#xA;override this.GetServiceTypes : unit -&gt; System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceTypeDescription&gt;" Usage="codePackageActivationContext.GetServiceTypes " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.GetServiceTypes</InterfaceMember>
      </Implements>
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
          <para><span data-ttu-id="875bd-203">サービス マニフェスト内のサービスの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-203">Retrieves the list of service types in the service manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="875bd-204">サービスの種類の一覧。</span><span class="sxs-lookup"><span data-stu-id="875bd-204">The list of service types.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.CodePackageActivationContext.LogDirectory" />
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
          <para><span data-ttu-id="875bd-205">アプリケーションを使用してログ ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-205">Gets the path to the log directory that the application can use.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-206">アプリケーションへのパスは、ディレクトリを記録します。</span><span class="sxs-lookup"><span data-stu-id="875bd-206">The path to the application logs directory.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-207"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-207">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="875bd-208">現在のアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-208">Reports health for current application.</span></span> 
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-209">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-209">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-210">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-210">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-211">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-211">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-212">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="875bd-212">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="875bd-213">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-213">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-214">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-214">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-215">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-215">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-216"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-216"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-217"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-217"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-218"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-218">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="875bd-219"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="875bd-219">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="875bd-220">現在のアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-220">Reports health for current application.</span></span>
            <span data-ttu-id="875bd-221">レポートを送信する方法を制御するオプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="875bd-221">Specifies options to control how the report is sent.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-222">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-222">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-223">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-223">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-224">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-224">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-225">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="875bd-225">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="875bd-226">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-226">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-227">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-227">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-228">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-228">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-229"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-229"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-230"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-230"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportDeployedApplicationHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-231"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-231">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="875bd-232">現在展開済みのアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-232">Reports health for current deployed application.</span></span> 
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-233">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-233">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-234">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-234">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-235">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-235">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-236">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="875bd-236">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="875bd-237">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-237">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-238">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-238">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-239">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-239">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-240"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-240"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-241"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-241"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedApplicationHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedApplicationHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedApplicationHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedApplicationHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportDeployedApplicationHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportDeployedApplicationHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedApplicationHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-242"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-242">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="875bd-243"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="875bd-243">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="875bd-244">現在展開済みのアプリケーションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-244">Reports health for current deployed application.</span></span> 
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-245">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-245">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-246">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-246">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-247">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-247">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-248">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="875bd-248">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="875bd-249">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-249">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-250">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-250">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-251">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-251">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-252"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-252"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-253"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-253"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit&#xA;override this.ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="codePackageActivationContext.ReportDeployedServicePackageHealth healthInfo" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-254"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-254">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="875bd-255">現在の展開済みサービス パッケージの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-255">Reports health for current deployed service package.</span></span> 
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-256">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-256">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-257">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-257">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-258">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-258">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-259">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="875bd-259">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="875bd-260">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-260">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-261">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-261">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-262">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-262">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-263"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-263"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-264"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-264"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportDeployedServicePackageHealth">
      <MemberSignature Language="C#" Value="public void ReportDeployedServicePackageHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportDeployedServicePackageHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportDeployedServicePackageHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit&#xA;override this.ReportDeployedServicePackageHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="codePackageActivationContext.ReportDeployedServicePackageHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.ICodePackageActivationContext.ReportDeployedServicePackageHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)</InterfaceMember>
      </Implements>
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
        <param name="healthInfo"><span data-ttu-id="875bd-265"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-265">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="875bd-266"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="875bd-266">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="875bd-267">現在の展開済みサービス パッケージの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="875bd-267">Reports health for current deployed service package.</span></span> 
            </summary>
        <remarks>
          <para><span data-ttu-id="875bd-268">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="875bd-268">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="875bd-269">コード パッケージのアクティベーション コンテキストは、正常性ストアに、レポートを送信するのに、内部の正常性のクライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="875bd-269">The code package activation context uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="875bd-270">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="875bd-270">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="875bd-271">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="875bd-271">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="875bd-272">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="875bd-272">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="875bd-273">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="875bd-273">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="875bd-274">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="875bd-274">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="875bd-275"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="875bd-275"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="875bd-276"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="875bd-276"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceListenAddress">
      <MemberSignature Language="C#" Value="public string ServiceListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServiceListenAddress : string" Usage="System.Fabric.CodePackageActivationContext.ServiceListenAddress" />
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
          <para><span data-ttu-id="875bd-277">これで、サービスが通信リスナーを開始します。 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="875bd-277">The address at which the service should start the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-278">これで、サービスが通信リスナーを開始します。 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="875bd-278">The address at which the service should start the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePublishAddress">
      <MemberSignature Language="C#" Value="public string ServicePublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServicePublishAddress : string" Usage="System.Fabric.CodePackageActivationContext.ServicePublishAddress" />
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
          <para><span data-ttu-id="875bd-279">リッスン アドレスとして、サービスが公開されるアドレスです。</span><span class="sxs-lookup"><span data-stu-id="875bd-279">The address which the service should publish as the listen address.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-280">リッスン アドレスとして、サービスが公開されるアドレスです。</span><span class="sxs-lookup"><span data-stu-id="875bd-280">The address which the service should publish as the listen address.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.CodePackageActivationContext.TempDirectory" />
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
          <para><span data-ttu-id="875bd-281">アプリケーションがの一時ファイルを Temp ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-281">Gets the path to the Temp directory that the Application can use for temporary files.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-282">Temp ディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="875bd-282">The path to the Temp directory.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CodePackageActivationContext.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.CodePackageActivationContext.WorkDirectory" />
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
          <para><span data-ttu-id="875bd-283">アプリケーションがデータの格納に使用できる作業ディレクトリへのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="875bd-283">Gets the path to the Work directory that the application can use to store data.</span></span> <span data-ttu-id="875bd-284">例: レプリカの状態。</span><span class="sxs-lookup"><span data-stu-id="875bd-284">For example: the state of the replicas.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="875bd-285">作業ディレクトリへのパス。</span><span class="sxs-lookup"><span data-stu-id="875bd-285">The path to the Work directory.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>