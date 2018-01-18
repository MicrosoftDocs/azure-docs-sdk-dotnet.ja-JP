<Type Name="VirtualNetworkRule" FullName="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule">
  <TypeSignature Language="C#" Value="public class VirtualNetworkRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9ee86-101">仮想ネットワーク ルール。</span><span class="sxs-lookup"><span data-stu-id="9ee86-101">A virtual network rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ee86-102">VirtualNetworkRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-102">Initializes a new instance of the VirtualNetworkRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkRule (string virtualNetworkSubnetId, string id = null, string name = null, string type = null, Nullable&lt;bool&gt; ignoreMissingVnetServiceEndpoint = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string virtualNetworkSubnetId, string id, string name, string type, valuetype System.Nullable`1&lt;bool&gt; ignoreMissingVnetServiceEndpoint, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualNetworkSubnetId As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional ignoreMissingVnetServiceEndpoint As Nullable(Of Boolean) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule : string * string * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" Usage="new Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule (virtualNetworkSubnetId, id, name, type, ignoreMissingVnetServiceEndpoint, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualNetworkSubnetId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="ignoreMissingVnetServiceEndpoint" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualNetworkSubnetId"><span data-ttu-id="9ee86-103">仮想ネットワーク サブネットの ARM リソース id です。</span><span class="sxs-lookup"><span data-stu-id="9ee86-103">The ARM resource id of the virtual network subnet.</span></span></param>
        <param name="id"><span data-ttu-id="9ee86-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="9ee86-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="9ee86-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="9ee86-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="9ee86-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="9ee86-106">Resource type.</span></span></param>
        <param name="ignoreMissingVnetServiceEndpoint"><span data-ttu-id="9ee86-107">仮想ネットワークがある vnet サービス エンドポイントが有効にする前に、ファイアウォール規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-107">Create firewall rule before the virtual network has vnet service endpoint enabled.</span></span></param>
        <param name="state"><span data-ttu-id="9ee86-108">仮想ネットワーク ルールの状態。</span><span class="sxs-lookup"><span data-stu-id="9ee86-108">Virtual Network Rule State.</span></span> <span data-ttu-id="9ee86-109">使用可能な値が含まれます: '初期化'、'処理中'、'準備完了'、'削除'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="9ee86-109">Possible values include: 'Initializing', 'InProgress', 'Ready', 'Deleting', 'Unknown'</span></span></param>
        <summary>
            <span data-ttu-id="9ee86-110">VirtualNetworkRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-110">Initializes a new instance of the VirtualNetworkRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreMissingVnetServiceEndpoint">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreMissingVnetServiceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreMissingVnetServiceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.IgnoreMissingVnetServiceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreMissingVnetServiceEndpoint As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreMissingVnetServiceEndpoint : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.IgnoreMissingVnetServiceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreMissingVnetServiceEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ee86-111">取得または設定は、仮想ネットワークがある vnet サービス エンドポイントが有効にする前に、ファイアウォール規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-111">Gets or sets create firewall rule before the virtual network has vnet service endpoint enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ee86-112">仮想ネットワーク ルールの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-112">Gets virtual Network Rule State.</span></span> <span data-ttu-id="9ee86-113">使用可能な値が含まれます: '初期化'、'処理中'、'準備完了'、'削除'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="9ee86-113">Possible values include: 'Initializing', 'InProgress', 'Ready', 'Deleting', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualNetworkRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ee86-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9ee86-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9ee86-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkSubnetId">
      <MemberSignature Language="C#" Value="public string VirtualNetworkSubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkSubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.VirtualNetworkSubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkSubnetId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkSubnetId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule.VirtualNetworkSubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkSubnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ee86-116">取得または仮想ネットワーク サブネットの ARM リソース id を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ee86-116">Gets or sets the ARM resource id of the virtual network subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>