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
            ターゲット リソースで IP フロー検証の結果。
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
            VerificationIPFlowResult クラスの新しいインスタンスを初期化します。
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
        <param name="access">トラフィックが許可または拒否するかどうかを示します。 使用可能な値が含まれます 'の Allow'、'拒否'。</param>
        <param name="ruleName">ルールの名前です。 入力が一致しない場合、セキュリティの規則に対しては表示されません。</param>
        <summary>
            VerificationIPFlowResult クラスの新しいインスタンスを初期化します。
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
            取得または設定は、トラフィックが許可または拒否するかどうかを示します。
            使用可能な値が含まれます 'の Allow'、'拒否'。
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
            取得またはルールの名前を設定します。 入力が一致しない場合、セキュリティの規則に対しては表示されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>