<Type Name="NetworkInterfaceAssociation" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceAssociation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceAssociation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceAssociation" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceAssociation = class" />
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
            ネットワーク インターフェイス、カスタム セキュリティの規則。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceAssociation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NetworkInterfaceAssociation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceAssociation (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; securityRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; securityRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional securityRules As IList(Of SecurityRuleInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation (id, securityRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="securityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" />
      </Parameters>
      <Docs>
        <param name="id">ネットワーク インターフェイス id です。</param>
        <param name="securityRules">カスタム セキュリティ規則のコレクション。</param>
        <summary>
            NetworkInterfaceAssociation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ネットワーク インターフェイス ID の取得
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; SecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityRules As IList(Of SecurityRuleInner)" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはカスタムのセキュリティ規則のコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>