<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class" />
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
            <span data-ttu-id="10054-101">受信エンドポイントに適用するネットワーク セキュリティ グループ ルール。</span><span class="sxs-lookup"><span data-stu-id="10054-101">A network security group rule to apply to an inbound endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.#ctor" />
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
            <span data-ttu-id="10054-102">NetworkSecurityGroupRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="10054-102">Initializes a new instance of the NetworkSecurityGroupRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule : int * Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="10054-103">このルールの優先度。</span><span class="sxs-lookup"><span data-stu-id="10054-103">The priority for this rule.</span></span></param>
        <param name="access"><span data-ttu-id="10054-104">指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="10054-104">The action that should be taken for a specified IP address, subnet range or tag.</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="10054-105">発信元アドレス プレフィックスまたはルールに一致するタグです。</span><span class="sxs-lookup"><span data-stu-id="10054-105">The source address prefix or tag to match for the rule.</span></span></param>
        <summary>
            <span data-ttu-id="10054-106">NetworkSecurityGroupRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="10054-106">Initializes a new instance of the NetworkSecurityGroupRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10054-107">取得または指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="10054-107">Gets or sets the action that should be taken for a specified IP address, subnet range or tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10054-108">使用可能な値が含まれます 'の allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="10054-108">Possible values include: 'allow', 'deny'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10054-109">取得または、このルールの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="10054-109">Gets or sets the priority for this rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10054-110">プール内の優先度は、一意である必要があり、優先度順に評価されます。</span><span class="sxs-lookup"><span data-stu-id="10054-110">Priorities within a pool must be unique and are evaluated in order of priority.</span></span> <span data-ttu-id="10054-111">数値が低いほど、優先度は高くなります。</span><span class="sxs-lookup"><span data-stu-id="10054-111">The lower the number the higher the priority.</span></span> <span data-ttu-id="10054-112">たとえば、ルールは、150、250、および 350 の順序番号で指定できます。</span><span class="sxs-lookup"><span data-stu-id="10054-112">For example, rules could be specified with order numbers of 150, 250, and 350.</span></span> <span data-ttu-id="10054-113">150 の注文番号のルールを 250 の順序を持つルールよりも優先されます。</span><span class="sxs-lookup"><span data-stu-id="10054-113">The rule with the order number of 150 takes precedence over the rule that has an order of 250.</span></span> <span data-ttu-id="10054-114">許可される優先度は、150 に 3500 です。</span><span class="sxs-lookup"><span data-stu-id="10054-114">Allowed priorities are 150 to 3500.</span></span> <span data-ttu-id="10054-115">予約済みか、重複する値がある場合、要求は HTTP ステータス コード 400 で失敗します。</span><span class="sxs-lookup"><span data-stu-id="10054-115">If any reserved or duplicate values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10054-116">取得または発信元アドレス プレフィックスまたはルールに一致するタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="10054-116">Gets or sets the source address prefix or tag to match for the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="10054-117">有効な値は 1 つの IP アドレス (つまり 10.10.10.10)、IP サブネット (192.168.1.0/24 など)、既定のタグ、または \* (すべてのアドレス)。</span><span class="sxs-lookup"><span data-stu-id="10054-117">Valid values are a single IP address (i.e. 10.10.10.10), IP subnet (i.e. 192.168.1.0/24), default tag, or \* (for all addresses).</span></span>  <span data-ttu-id="10054-118">その他の場合、HTTP ステータス コード 400 で失敗した要求値が提供されます。</span><span class="sxs-lookup"><span data-stu-id="10054-118">If any other values are provided the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSecurityGroupRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10054-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="10054-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="10054-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="10054-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>