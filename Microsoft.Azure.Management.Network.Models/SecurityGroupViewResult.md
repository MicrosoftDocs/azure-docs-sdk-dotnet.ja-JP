<Type Name="SecurityGroupViewResult" FullName="Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult">
  <TypeSignature Language="C#" Value="public class SecurityGroupViewResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityGroupViewResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityGroupViewResult" />
  <TypeSignature Language="F#" Value="type SecurityGroupViewResult = class" />
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
            指定した VM に適用されるセキュリティ規則に関する情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.#ctor" />
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
            SecurityGroupViewResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; networkInterfaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; networkInterfaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaces As IList(Of SecurityGroupNetworkInterface) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="new Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult networkInterfaces" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaces">指定した VM 上のネットワーク インターフェイスの一覧です。</param>
        <summary>
            SecurityGroupViewResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaces As IList(Of SecurityGroupNetworkInterface)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定した VM のネットワーク インターフェイスの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>