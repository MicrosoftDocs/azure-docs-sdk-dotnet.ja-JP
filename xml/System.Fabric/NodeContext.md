<Type Name="NodeContext" FullName="System.Fabric.NodeContext">
  <TypeSignature Language="C#" Value="public class NodeContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeContext" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeContext" />
  <TypeSignature Language="F#" Value="type NodeContext = class" />
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
      <para><span data-ttu-id="ff155-101">ノードの名前、ID、ノード型などなどの Service Fabric ノードについてのコンテキスト情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="ff155-101">Specifies contextual information about a Service Fabric node such as node name, ID, node type etc.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeContext (string nodeName, System.Fabric.NodeId nodeId, System.Numerics.BigInteger nodeInstanceId, string nodeType, string ipAddressOrFQDN);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, class System.Fabric.NodeId nodeId, valuetype System.Numerics.BigInteger nodeInstanceId, string nodeType, string ipAddressOrFQDN) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeContext.#ctor(System.String,System.Fabric.NodeId,System.Numerics.BigInteger,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.NodeContext : string * System.Fabric.NodeId * System.Numerics.BigInteger * string * string -&gt; System.Fabric.NodeContext" Usage="new System.Fabric.NodeContext (nodeName, nodeId, nodeInstanceId, nodeType, ipAddressOrFQDN)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Fabric.NodeId" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
        <Parameter Name="nodeType" Type="System.String" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="ff155-102">ノード名。</span><span class="sxs-lookup"><span data-stu-id="ff155-102">The node name.</span></span></param>
        <param name="nodeId"><span data-ttu-id="ff155-103">ノード id。</span><span class="sxs-lookup"><span data-stu-id="ff155-103">The node id.</span></span></param>
        <param name="nodeInstanceId"><span data-ttu-id="ff155-104">ノード インスタンスの id です。</span><span class="sxs-lookup"><span data-stu-id="ff155-104">The node instance id.</span></span></param>
        <param name="nodeType"><span data-ttu-id="ff155-105">ノード型。</span><span class="sxs-lookup"><span data-stu-id="ff155-105">The node type.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="ff155-106">IP アドレスまたはノードの FQDN です。</span><span class="sxs-lookup"><span data-stu-id="ff155-106">The IP address or FQDN of the node.</span></span></param>
        <summary>
            <span data-ttu-id="ff155-107"><see cref="T:System.Fabric.NodeContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff155-107">Initializes a new instance of the <see cref="T:System.Fabric.NodeContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeContext.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetDirectory : string -&gt; string" Usage="nodeContext.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="ff155-108">ノード レベルでディレクトリのディレクトリ パスを取得します。</span><span class="sxs-lookup"><span data-stu-id="ff155-108">Retrieves the directory path for the directory at node level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrFQDN">
      <MemberSignature Language="C#" Value="public string IPAddressOrFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddressOrFQDN" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.IPAddressOrFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IPAddressOrFQDN As String" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrFQDN : string" Usage="System.Fabric.NodeContext.IPAddressOrFQDN" />
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
          <para><span data-ttu-id="ff155-109">IP アドレスまたはノードの完全修飾ドメイン名を取得します。</span><span class="sxs-lookup"><span data-stu-id="ff155-109">Gets the IP address or the fully qualified domain name of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ff155-110">IP アドレスまたはノードの完全修飾ドメイン名を返します。</span><span class="sxs-lookup"><span data-stu-id="ff155-110">Returns the IP address or the fully qualified domain name of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.NodeContext.NodeId" />
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
          <para><span data-ttu-id="ff155-111">ノード ID を取得します</span><span class="sxs-lookup"><span data-stu-id="ff155-111">Gets the node ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ff155-112"><see cref="T:System.Fabric.NodeId" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ff155-112">Returns <see cref="T:System.Fabric.NodeId" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.NodeContext.NodeInstanceId" />
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
          <para><span data-ttu-id="ff155-113">ノードを一意に識別するノードのインスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="ff155-113">Gets the node instance ID, which uniquely identifies the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ff155-114"><see cref="T:System.Numerics.BigInteger" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ff155-114">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.NodeContext.NodeName" />
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
          <para><span data-ttu-id="ff155-115">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="ff155-115">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ff155-116">ノード名を返します。</span><span class="sxs-lookup"><span data-stu-id="ff155-116">Returns the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeType">
      <MemberSignature Language="C#" Value="public string NodeType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeType As String" />
      <MemberSignature Language="F#" Value="member this.NodeType : string" Usage="System.Fabric.NodeContext.NodeType" />
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
          <para><span data-ttu-id="ff155-117">ノードの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="ff155-117">Gets the node type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ff155-118">ノード型の文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="ff155-118">Returns the node type string.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>