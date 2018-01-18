<Type Name="ResolvedServiceEndpoint" FullName="System.Fabric.ResolvedServiceEndpoint">
  <TypeSignature Language="C#" Value="public sealed class ResolvedServiceEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResolvedServiceEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ResolvedServiceEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResolvedServiceEndpoint" />
  <TypeSignature Language="F#" Value="type ResolvedServiceEndpoint = class" />
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
      <para><span data-ttu-id="e2cc9-101">サービス パーティションのレプリカのロールに関する情報が含まれています、解決済みのサービスのエンドポイントとそれをリッスンするアドレスを表します。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-101">Represents a resolved service endpoint, which contains information about service partition replica role and the address it listens to.</span></span></para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="e2cc9-102">解決済みのサービス エンドポイントから返される<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />の一部として<see cref="T:System.Fabric.ResolvedServicePartition" />です。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-102">The resolved service endpoints are returned from <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />, as part of <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.ResolvedServiceEndpoint.Address" />
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
          <para><span data-ttu-id="e2cc9-103">エンドポイントのアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-103">Gets the address for the endpoint.</span></span>
            <span data-ttu-id="e2cc9-104">サービスのレプリカでは、この文字列をアクセスできるユーザーに通知 Service Fabric にできます。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-104">The service replica gives this string to Service Fabric to let users know where it can be reached.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2cc9-105">ここでは、サービス レプリカまたはインスタンスに到達できるエンドポイントのアドレス。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-105">The address for the endpoint where the service replica or instance can be reached.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointRole Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ServiceEndpointRole Role" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As ServiceEndpointRole" />
      <MemberSignature Language="F#" Value="member this.Role : System.Fabric.ServiceEndpointRole" Usage="System.Fabric.ResolvedServiceEndpoint.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e2cc9-106">サービス エンドポイントのロールを取得します。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-106">Gets the role of a service endpoint.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e2cc9-107">サービス エンドポイントのロール。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-107">The role of a service endpoint.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="e2cc9-108"><see cref="T:System.Fabric.ServiceEndpointRole" />クライアントによってサービス インスタンスまたはレプリカを選択しへの接続を判断するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e2cc9-108">The <see cref="T:System.Fabric.ServiceEndpointRole" /> is used by a client to determine which service instance or replica to select and connect to.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>