<Type Name="UnprovisionApplicationTypeDescription" FullName="System.Fabric.Description.UnprovisionApplicationTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UnprovisionApplicationTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="F#" Value="type UnprovisionApplicationTypeDescription = class" />
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
      <para><span data-ttu-id="21624-101">使用して準備を解除するアプリケーションの種類について説明します<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="21624-101">Describes an application type to be unprovisioned by using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnprovisionApplicationTypeDescription (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UnprovisionApplicationTypeDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationTypeName As String, applicationTypeVersion As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UnprovisionApplicationTypeDescription : string * string -&gt; System.Fabric.Description.UnprovisionApplicationTypeDescription" Usage="new System.Fabric.Description.UnprovisionApplicationTypeDescription (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="21624-102">アプリケーションの種類名のプロビジョニングを解除</span><span class="sxs-lookup"><span data-stu-id="21624-102">The application type name to unprovision</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="21624-103">アプリケーション タイプのバージョンのプロビジョニングを解除</span><span class="sxs-lookup"><span data-stu-id="21624-103">The application type version to unprovision</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="21624-104">インスタンスをインスタンス化<see cref="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="21624-104">Instantiates an instance of <see cref="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
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
          <para><span data-ttu-id="21624-105">プロビジョニングを解除するアプリケーションの種類の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="21624-105">Gets the application type name to unprovision.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21624-106">アプリケーションの種類名です。</span><span class="sxs-lookup"><span data-stu-id="21624-106">The application type name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
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
          <para><span data-ttu-id="21624-107">プロビジョニングを解除アプリケーション タイプのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="21624-107">Gets the application type version to unprovision.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21624-108">アプリケーションの種類のバージョン。</span><span class="sxs-lookup"><span data-stu-id="21624-108">The application type version.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Async">
      <MemberSignature Language="C#" Value="public bool Async { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Async" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
      <MemberSignature Language="VB.NET" Value="Public Property Async As Boolean" />
      <MemberSignature Language="F#" Value="member this.Async : bool with get, set" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
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
          <para><span data-ttu-id="21624-109">取得または設定するかどうかを非同期的に発生する必要がありますプロビジョニング解除を示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="21624-109">Gets or sets the flag indicating whether unprovisioning should occur asynchronously.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="21624-110">かどうかは、このフラグが false の場合、動作は呼び出すことと同じ<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="21624-110">If this flag is false, then the behavior is equivalent to calling <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="21624-111">Timeout 引数は、サービスの提供解除操作自体に適用され、システムで、サービスの提供解除操作が完了した場合にのみ、返されるタスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="21624-111">The timeout argument is applied to the unprovision operation itself and the returned task completes only when the unprovision operation completes in the system.</span></span></para>
          <para><span data-ttu-id="21624-112">このフラグが true、timeout 引数は、メッセージの配信にだけ適用し、返されるタスクが 1 回が完了した場合、システムに要求が許可しました。</span><span class="sxs-lookup"><span data-stu-id="21624-112">If this flag is true, then the timeout argument is only applied to message delivery and the returned task completes once the system has accepted the request.</span></span> <span data-ttu-id="21624-113">システムは、タイムアウトの制限がないサービスの提供解除操作を処理しを使用して、状態を照会できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="21624-113">The system will process the unprovision operation without any timeout limit and its state can be queried using <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>