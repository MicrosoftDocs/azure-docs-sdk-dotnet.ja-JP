<Type Name="GatewayInformation" FullName="System.Fabric.GatewayInformation">
  <TypeSignature Language="C#" Value="public sealed class GatewayInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GatewayInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GatewayInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GatewayInformation" />
  <TypeSignature Language="F#" Value="type GatewayInformation = class" />
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
      <para><span data-ttu-id="0a4b1-101">クラスター内の Service Fabric ノードを識別する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-101">Contains information identifying a Service Fabric node in the cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeAddress">
      <MemberSignature Language="C#" Value="public string NodeAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeAddress As String" />
      <MemberSignature Language="F#" Value="member this.NodeAddress : string" Usage="System.Fabric.GatewayInformation.NodeAddress" />
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
          <para><span data-ttu-id="0a4b1-102">Service Fabric クライアント (クラスター マニフェストで指定) と同じには、このノードに接続するときに使用するアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-102">Gets the address that Service Fabric clients use when connecting to this node (as specified in the Cluster Manifest).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0a4b1-103">(クラスター マニフェストで指定) と同じには、このノードに接続するときに、Service Fabric クライアントが使用するアドレス。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-103">The address that Service Fabric clients use when connecting to this node (as specified in the Cluster Manifest).</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.GatewayInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0a4b1-104">ノードを識別する、Service Fabric によって内部的に使用する一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-104">The unique identifier used internally by Service Fabric to identify a node.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="0a4b1-105"><see cref="T:System.Fabric.NodeId" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-105">Returns <see cref="T:System.Fabric.NodeId" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.GatewayInformation.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0a4b1-106">Service Fabric ノードのインスタンスは、ノードが再起動されたときに変更します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-106">The instance of a Service Fabric node changes when the node is restarted.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0a4b1-107"><see cref="T:System.Numerics.BigInteger" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-107">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.GatewayInformation.NodeName" />
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
          <para><span data-ttu-id="0a4b1-108">フレンドリ名 (クラスター マニフェストで定義されている)、Service Fabric ノードの NodeId を生成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-108">The friendly name of the Service Fabric node (defined in the Cluster Manifest) used to generate the NodeId.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0a4b1-109"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="0a4b1-109">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>