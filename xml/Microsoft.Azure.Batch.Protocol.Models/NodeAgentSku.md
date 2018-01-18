<Type Name="NodeAgentSku" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku">
  <TypeSignature Language="C#" Value="public class NodeAgentSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeAgentSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeAgentSku" />
  <TypeSignature Language="F#" Value="type NodeAgentSku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1a5ee-101">ノード エージェント SKU は、バッチ サービスによってサポートされます。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-101">A node agent SKU supported by the Batch service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="1a5ee-102">Batch ノード エージェントは、プール内の各ノード上で実行され、ノードと、バッチ サービスの間のコマンドとコントロール インターフェイスを提供するプログラムです。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-102">The Batch node agent is a program that runs on each node in the pool, and provides the command-and-control interface between the node and the Batch service.</span></span> <span data-ttu-id="1a5ee-103">オペレーティング システムに応じてさまざまなノード エージェントの実装 (SKU と呼ばれます) があります。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-103">There are different implementations of the node agent, known as SKUs, for different operating systems.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1a5ee-104">NodeAgentSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-104">Initializes a new instance of the NodeAgentSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ImageReference},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OSType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional verifiedImageReferences As IList(Of ImageReference) = null, Optional osType As Nullable(Of OSType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku (id, verifiedImageReferences, osType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="verifiedImageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1a5ee-105">ノード エージェント SKU の ID。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-105">The ID of the node agent SKU.</span></span></param>
        <param name="verifiedImageReferences"><span data-ttu-id="1a5ee-106">このノード エージェント SKU との互換性が確認済みの Azure Marketplace イメージの一覧。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-106">The list of Azure Marketplace images verified to be compatible with this node agent SKU.</span></span></param>
        <param name="osType"><span data-ttu-id="1a5ee-107">ノード エージェント SKU と互換性のオペレーティング システム (Windows または Linux) の型。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-107">The type of operating system (e.g. Windows or Linux) compatible with the node agent SKU.</span></span></param>
        <summary>
            <span data-ttu-id="1a5ee-108">NodeAgentSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-108">Initializes a new instance of the NodeAgentSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a5ee-109">取得またはノード エージェント SKU の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-109">Gets or sets the ID of the node agent SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OSType)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a5ee-110">取得またはノード エージェント SKU と互換性のあるオペレーティング システム (Windows または Linux) の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-110">Gets or sets the type of operating system (e.g. Windows or Linux) compatible with the node agent SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1a5ee-111">使用可能な値が含まれます: 'linux'、'windows'</span><span class="sxs-lookup"><span data-stu-id="1a5ee-111">Possible values include: 'linux', 'windows'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifiedImageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property VerifiedImageReferences As IList(Of ImageReference)" />
      <MemberSignature Language="F#" Value="member this.VerifiedImageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="verifiedImageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a5ee-112">取得またはこのノード エージェント SKU との互換性が確認済みの Azure Marketplace イメージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-112">Gets or sets the list of Azure Marketplace images verified to be compatible with this node agent SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1a5ee-113">このコレクションが完全ではありません (ノードのエージェントは、その他のイメージと互換性のある可能性があります)。</span><span class="sxs-lookup"><span data-stu-id="1a5ee-113">This collection is not exhaustive (the node agent may be compatible with other images).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>