<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Batch.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class&#xA;    interface ITransportObjectProvider&lt;NetworkSecurityGroupRule&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="aa712-101">受信エンドポイントに適用するネットワーク セキュリティ グループ ルール。</span><span class="sxs-lookup"><span data-stu-id="aa712-101">A network security group rule to apply to an inbound endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.NetworkSecurityGroupRule : int * Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Batch.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Batch.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="aa712-102">このルールの優先度。</span><span class="sxs-lookup"><span data-stu-id="aa712-102">The priority for this rule.</span></span></param>
        <param name="access"><span data-ttu-id="aa712-103">指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="aa712-103">The action that should be taken for a specified IP address, subnet range or tag.</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="aa712-104">発信元アドレス プレフィックスまたはルールに一致するタグです。</span><span class="sxs-lookup"><span data-stu-id="aa712-104">The source address prefix or tag to match for the rule.</span></span></param>
        <summary>
            <span data-ttu-id="aa712-105"><see cref="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aa712-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa712-106">指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="aa712-106">Gets the action that should be taken for a specified IP address, subnet range or tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa712-107">このルールの優先順位を取得します。</span><span class="sxs-lookup"><span data-stu-id="aa712-107">Gets the priority for this rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="aa712-108">プール内の優先度は、一意である必要があり、優先度順に評価されます。</span><span class="sxs-lookup"><span data-stu-id="aa712-108">Priorities within a pool must be unique and are evaluated in order of priority.</span></span> <span data-ttu-id="aa712-109">数値が低いほど、優先度は高くなります。</span><span class="sxs-lookup"><span data-stu-id="aa712-109">The lower the number the higher the priority.</span></span> <span data-ttu-id="aa712-110">たとえば、ルールは、150、250、および 350 の順序番号で指定できます。</span><span class="sxs-lookup"><span data-stu-id="aa712-110">For example, rules could be specified with order numbers of 150, 250, and 350.</span></span> <span data-ttu-id="aa712-111">150 の注文番号のルールを 250 の順序を持つルールよりも優先されます。</span><span class="sxs-lookup"><span data-stu-id="aa712-111">The rule with the order number of 150 takes precedence over the rule that has an order of 250.</span></span> <span data-ttu-id="aa712-112">許可される優先度は、150 に 3500 です。</span><span class="sxs-lookup"><span data-stu-id="aa712-112">Allowed priorities are 150 to 3500.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa712-113">発信元アドレス プレフィックスまたはルールに一致するタグを取得します。</span><span class="sxs-lookup"><span data-stu-id="aa712-113">Gets the source address prefix or tag to match for the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="aa712-114">有効な値は 1 つの IP アドレス (つまり 10.10.10.10)、IP サブネット (192.168.1.0/24 など)、既定のタグ、または \* (すべてのアドレス)。</span><span class="sxs-lookup"><span data-stu-id="aa712-114">Valid values are a single IP address (i.e. 10.10.10.10), IP subnet (i.e. 192.168.1.0/24), default tag, or \* (for all addresses).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>