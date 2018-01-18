<Type Name="VerificationIPFlowResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowResultInner" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fff19-101">ターゲット リソースで IP フロー検証の結果。</span><span class="sxs-lookup"><span data-stu-id="fff19-101">Results of IP flow verification on the target resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fff19-102">VerificationIPFlowResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fff19-102">Initializes a new instance of the VerificationIPFlowResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResultInner (string access = null, string ruleName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string access, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional access As String = null, Optional ruleName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner (access, ruleName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="access"><span data-ttu-id="fff19-103">トラフィックが許可または拒否するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fff19-103">Indicates whether the traffic is allowed or denied.</span></span> <span data-ttu-id="fff19-104">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="fff19-104">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="ruleName"><span data-ttu-id="fff19-105">ルールの名前です。</span><span class="sxs-lookup"><span data-stu-id="fff19-105">Name of the rule.</span></span> <span data-ttu-id="fff19-106">入力が一致しない場合、セキュリティの規則に対しては表示されません。</span><span class="sxs-lookup"><span data-stu-id="fff19-106">If input is not matched against any security rule, it is not displayed.</span></span></param>
        <summary>
            <span data-ttu-id="fff19-107">VerificationIPFlowResultInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fff19-107">Initializes a new instance of the VerificationIPFlowResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="fff19-108">取得または設定は、トラフィックが許可または拒否するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fff19-108">Gets or sets indicates whether the traffic is allowed or denied.</span></span>
            <span data-ttu-id="fff19-109">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="fff19-109">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleName">
      <MemberSignature Language="C#" Value="public string RuleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.RuleName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleName As String" />
      <MemberSignature Language="F#" Value="member this.RuleName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VerificationIPFlowResultInner.RuleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="fff19-110">取得またはルールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="fff19-110">Gets or sets name of the rule.</span></span> <span data-ttu-id="fff19-111">入力が一致しない場合、セキュリティの規則に対しては表示されません。</span><span class="sxs-lookup"><span data-stu-id="fff19-111">If input is not matched against any security rule, it is not displayed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>