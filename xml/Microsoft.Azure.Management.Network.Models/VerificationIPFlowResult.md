<Type Name="VerificationIPFlowResult" FullName="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowResult" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowResult = class" />
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
            <span data-ttu-id="a69d8-101">ターゲット リソースで IP フロー検証の結果。</span><span class="sxs-lookup"><span data-stu-id="a69d8-101">Results of IP flow verification on the target resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.#ctor" />
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
            <span data-ttu-id="a69d8-102">VerificationIPFlowResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a69d8-102">Initializes a new instance of the VerificationIPFlowResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResult (string access = null, string ruleName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string access, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional access As String = null, Optional ruleName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult : string * string -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult (access, ruleName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="access"><span data-ttu-id="a69d8-103">トラフィックが許可または拒否するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a69d8-103">Indicates whether the traffic is allowed or denied.</span></span> <span data-ttu-id="a69d8-104">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="a69d8-104">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="ruleName"><span data-ttu-id="a69d8-105">ルールの名前です。</span><span class="sxs-lookup"><span data-stu-id="a69d8-105">Name of the rule.</span></span> <span data-ttu-id="a69d8-106">入力が一致しない場合、セキュリティの規則に対しては表示されません。</span><span class="sxs-lookup"><span data-stu-id="a69d8-106">If input is not matched against any security rule, it is not displayed.</span></span></param>
        <summary>
            <span data-ttu-id="a69d8-107">VerificationIPFlowResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a69d8-107">Initializes a new instance of the VerificationIPFlowResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a69d8-108">取得または設定は、トラフィックが許可または拒否するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a69d8-108">Gets or sets indicates whether the traffic is allowed or denied.</span></span>
            <span data-ttu-id="a69d8-109">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="a69d8-109">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleName">
      <MemberSignature Language="C#" Value="public string RuleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.RuleName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleName As String" />
      <MemberSignature Language="F#" Value="member this.RuleName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.RuleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a69d8-110">取得またはルールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a69d8-110">Gets or sets name of the rule.</span></span> <span data-ttu-id="a69d8-111">入力が一致しない場合、セキュリティの規則に対しては表示されません。</span><span class="sxs-lookup"><span data-stu-id="a69d8-111">If input is not matched against any security rule, it is not displayed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>