<Type Name="TopologyAssociation" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation">
  <TypeSignature Language="C#" Value="public class TopologyAssociation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopologyAssociation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation" />
  <TypeSignature Language="VB.NET" Value="Public Class TopologyAssociation" />
  <TypeSignature Language="F#" Value="type TopologyAssociation = class" />
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
            親リソースとの関連付けのあるリソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyAssociation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TopologyAssociation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyAssociation (string name = null, string resourceId = null, string associationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string resourceId, string associationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional resourceId As String = null, Optional associationType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation (name, resourceId, associationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="associationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">親のリソースに関連付けられているリソースの名前。</param>
        <param name="resourceId">親のリソースに関連付けられているリソースの ID。</param>
        <param name="associationType">親リソースへの子リソースの関連付けの種類。 使用可能な値が含まれます: '関連付けられている'、'Contains'</param>
        <summary>
            TopologyAssociation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AssociationType">
      <MemberSignature Language="C#" Value="public string AssociationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AssociationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.AssociationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AssociationType As String" />
      <MemberSignature Language="F#" Value="member this.AssociationType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.AssociationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="associationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または親のリソースに子リソースの関連付けの種類を設定します。 使用可能な値が含まれます: '関連付けられている'、'Contains'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または親のリソースに関連付けられているリソースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または親のリソースに関連付けられているリソースの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>