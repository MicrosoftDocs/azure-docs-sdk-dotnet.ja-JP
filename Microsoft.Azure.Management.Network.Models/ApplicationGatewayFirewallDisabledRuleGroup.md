<Type Name="ApplicationGatewayFirewallDisabledRuleGroup" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFirewallDisabledRuleGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFirewallDisabledRuleGroup" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFirewallDisabledRuleGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ルール グループまたは全体のルール グループ内のルールを無効にできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallDisabledRuleGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ApplicationGatewayFirewallDisabledRuleGroup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallDisabledRuleGroup (string ruleGroupName, System.Collections.Generic.IList&lt;int&gt; rules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ruleGroupName, class System.Collections.Generic.IList`1&lt;int32&gt; rules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.#ctor(System.String,System.Collections.Generic.IList{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ruleGroupName As String, Optional rules As IList(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup : string * System.Collections.Generic.IList&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup (ruleGroupName, rules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ruleGroupName" Type="System.String" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="ruleGroupName">無効になるルール グループの名前。</param>
        <param name="rules">無効になる規則の一覧。 Null の場合、ルール グループのすべてのルールが無効になります。</param>
        <summary>
            ApplicationGatewayFirewallDisabledRuleGroup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleGroupName">
      <MemberSignature Language="C#" Value="public string RuleGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.RuleGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleGroupName As String" />
      <MemberSignature Language="F#" Value="member this.RuleGroupName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.RuleGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または無効になるルール グループの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;int&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;int32&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または無効になるルールの一覧を設定します。 Null の場合、ルール グループのすべてのルールが無効になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayFirewallDisabledRuleGroup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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