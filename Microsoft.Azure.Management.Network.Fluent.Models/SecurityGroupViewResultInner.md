<Type Name="SecurityGroupViewResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner">
  <TypeSignature Language="C#" Value="public class SecurityGroupViewResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityGroupViewResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityGroupViewResultInner" />
  <TypeSignature Language="F#" Value="type SecurityGroupViewResultInner = class" />
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
            指定した VM に適用されるセキュリティ規則に関する情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SecurityGroupViewResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResultInner (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; networkInterfaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; networkInterfaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaces As IList(Of SecurityGroupNetworkInterface) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner networkInterfaces" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaces">指定した VM 上のネットワーク インターフェイスの一覧です。</param>
        <summary>
            SecurityGroupViewResultInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaces As IList(Of SecurityGroupNetworkInterface)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupViewResultInner.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityGroupNetworkInterface&gt;</ReturnType>
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