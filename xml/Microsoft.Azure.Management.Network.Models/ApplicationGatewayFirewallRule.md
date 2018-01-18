<Type Name="ApplicationGatewayFirewallRule" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFirewallRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFirewallRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFirewallRule" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFirewallRule = class" />
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
            <span data-ttu-id="0e0bb-101">Web アプリケーション ファイアウォール ルール。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-101">A web application firewall rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.#ctor" />
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
            <span data-ttu-id="0e0bb-102">ApplicationGatewayFirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-102">Initializes a new instance of the ApplicationGatewayFirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRule (int ruleId, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 ruleId, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.#ctor(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ruleId As Integer, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule : int * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule (ruleId, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ruleId" Type="System.Int32" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleId"><span data-ttu-id="0e0bb-103">Web アプリケーション ファイアウォール ルールの識別子。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-103">The identifier of the web application firewall rule.</span></span></param>
        <param name="description"><span data-ttu-id="0e0bb-104">Web アプリケーション ファイアウォール規則の説明です。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-104">The description of the web application firewall rule.</span></span></param>
        <summary>
            <span data-ttu-id="0e0bb-105">ApplicationGatewayFirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-105">Initializes a new instance of the ApplicationGatewayFirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0e0bb-106">取得または web アプリケーション ファイアウォール規則の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-106">Gets or sets the description of the web application firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleId">
      <MemberSignature Language="C#" Value="public int RuleId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.RuleId" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleId As Integer" />
      <MemberSignature Language="F#" Value="member this.RuleId : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.RuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0e0bb-107">取得または web アプリケーション ファイアウォール ルールの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-107">Gets or sets the identifier of the web application firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayFirewallRule.Validate " />
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
            <span data-ttu-id="0e0bb-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0e0bb-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0e0bb-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>