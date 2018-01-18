<Type Name="StatelessServiceContext" FullName="System.Fabric.StatelessServiceContext">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceContext : System.Fabric.ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceContext extends System.Fabric.ServiceContext" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.StatelessServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceContext&#xA;Inherits ServiceContext" />
  <TypeSignature Language="F#" Value="type StatelessServiceContext = class&#xA;    inherit ServiceContext" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServiceContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d9b5f-101">下にある、ステートレスなサービスが動作しているサービス コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-101">The service context that the stateless service is operating under.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatelessServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.StatelessServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.StatelessServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.StatelessServiceContext" Usage="new System.Fabric.StatelessServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, instanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeContext" Type="System.Fabric.NodeContext" />
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.ICodePackageActivationContext" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="instanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext"><span data-ttu-id="d9b5f-102">ステートレス サービス インスタンスが実行されているノードに関する情報を含むノードのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-102">The node context, which contains information about the node where the stateless service instance is running.</span></span></param>
        <param name="codePackageActivationContext"><span data-ttu-id="d9b5f-103">コード パッケージのアクティベーション コンテキスト サービス マニフェストと現在アクティブ化されたコード パッケージからの情報を格納しているコンテキスト ID など、like の作業ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-103">The code package activation context, which contains information from the service manifest and the currently activated code package, like work directory, context ID etc.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="d9b5f-104">サービス型の名前。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-104">The service type name.</span></span></param>
        <param name="serviceName"><span data-ttu-id="d9b5f-105">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-105">The service name.</span></span></param>
        <param name="initializationData"><span data-ttu-id="d9b5f-106">サービスの初期化データ、サービスの作成者によって提供されるカスタムの初期化データを表します。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-106">The service initialization data, which represents custom initialization data provided by the creator of the service.</span></span></param>
        <param name="partitionId"><span data-ttu-id="d9b5f-107">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-107">The partition ID.</span></span></param>
        <param name="instanceId"><span data-ttu-id="d9b5f-108">インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-108">The instance ID.</span></span></param>
        <summary>
            <span data-ttu-id="d9b5f-109"><see cref="T:System.Fabric.StatelessServiceContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-109">Initializes a new instance of the <see cref="T:System.Fabric.StatelessServiceContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public long InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 InstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.StatelessServiceContext.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.InstanceId : int64" Usage="System.Fabric.StatelessServiceContext.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9b5f-110">ステートレス サービス インスタンス ID を取得します</span><span class="sxs-lookup"><span data-stu-id="d9b5f-110">Gets the stateless service instance ID.</span></span>
            </summary>
        <value><span data-ttu-id="d9b5f-111">ステートレス サービス インスタンス id。</span><span class="sxs-lookup"><span data-stu-id="d9b5f-111">The stateless service instance ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>