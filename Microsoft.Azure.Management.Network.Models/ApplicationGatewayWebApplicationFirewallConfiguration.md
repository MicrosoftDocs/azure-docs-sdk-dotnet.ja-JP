<Type Name="ApplicationGatewayWebApplicationFirewallConfiguration" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayWebApplicationFirewallConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayWebApplicationFirewallConfiguration = class" />
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
            アプリケーション ゲートウェイの web アプリケーション ファイアウォール構成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayWebApplicationFirewallConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.#ctor" />
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
            ApplicationGatewayWebApplicationFirewallConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayWebApplicationFirewallConfiguration (bool enabled, string firewallMode, string ruleSetType, string ruleSetVersion, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; disabledRuleGroups = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, string firewallMode, string ruleSetType, string ruleSetVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; disabledRuleGroups) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.#ctor(System.Boolean,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enabled As Boolean, firewallMode As String, ruleSetType As String, ruleSetVersion As String, Optional disabledRuleGroups As IList(Of ApplicationGatewayFirewallDisabledRuleGroup) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration : bool * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration (enabled, firewallMode, ruleSetType, ruleSetVersion, disabledRuleGroups)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="firewallMode" Type="System.String" />
        <Parameter Name="ruleSetType" Type="System.String" />
        <Parameter Name="ruleSetVersion" Type="System.String" />
        <Parameter Name="disabledRuleGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="enabled">Web アプリケーション ファイアウォールが有効かどうかされません。</param>
        <param name="firewallMode">Web アプリケーション ファイアウォール モードです。 使用可能な値が含まれます: '検出'、'防止'</param>
        <param name="ruleSetType">Web アプリケーション ファイアウォール規則の種類を設定します。 使用可能な値が: 'OWASP' です。</param>
        <param name="ruleSetVersion">ルールのバージョンでは、種類を設定します。</param>
        <param name="disabledRuleGroups">無効になっているルール グループです。</param>
        <summary>
            ApplicationGatewayWebApplicationFirewallConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledRuleGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; DisabledRuleGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; DisabledRuleGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.DisabledRuleGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledRuleGroups As IList(Of ApplicationGatewayFirewallDisabledRuleGroup)" />
      <MemberSignature Language="F#" Value="member this.DisabledRuleGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.DisabledRuleGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledRuleGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または無効になっているルール グループを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または web アプリケーション ファイアウォールが有効かどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallMode">
      <MemberSignature Language="C#" Value="public string FirewallMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FirewallMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.FirewallMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallMode As String" />
      <MemberSignature Language="F#" Value="member this.FirewallMode : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.FirewallMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="firewallMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または web アプリケーション ファイアウォール モードを設定します。 使用可能な値が含まれます: '検出'、'防止'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetType">
      <MemberSignature Language="C#" Value="public string RuleSetType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetType" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetType As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleSetType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または web アプリケーション ファイアウォール ルールのセットの種類を設定します。
            使用可能な値が: 'OWASP' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetVersion">
      <MemberSignature Language="C#" Value="public string RuleSetVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleSetVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または規則セットの種類のバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayWebApplicationFirewallConfiguration.Validate " />
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