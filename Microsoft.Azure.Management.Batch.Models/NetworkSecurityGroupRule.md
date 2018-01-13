<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            受信エンドポイントに適用するネットワーク セキュリティ グループ ルール。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NetworkSecurityGroupRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule : int * Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority">このルールの優先度。</param>
        <param name="access">指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクション。</param>
        <param name="sourceAddressPrefix">発信元アドレス プレフィックスまたはルールに一致するタグです。</param>
        <summary>
            NetworkSecurityGroupRule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定された IP アドレス、サブネットの範囲またはタグに対して実行されるアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます 'の Allow'、'拒否'。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            取得または、このルールの優先順位を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プール内の優先度は、一意である必要があり、優先度順に評価されます。 数値が低いほど、優先度は高くなります。 たとえば、ルールは、150、250、および 350 の順序番号で指定できます。 150 の注文番号のルールを 250 の順序を持つルールよりも優先されます。 許可される優先度は、150 に 3500 です。 予約済みか、重複する値がある場合、要求は HTTP ステータス コード 400 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            取得または発信元アドレス プレフィックスまたはルールに一致するタグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            有効な値は 1 つの IP アドレス (つまり 10.10.10.10)、IP サブネット (192.168.1.0/24 など)、既定のタグ、または * (すべてのアドレス)。  その他の場合、HTTP ステータス コード 400 で失敗した要求値が提供されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkSecurityGroupRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSecurityGroupRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>