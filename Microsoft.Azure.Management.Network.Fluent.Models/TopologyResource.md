<Type Name="TopologyResource" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource">
  <TypeSignature Language="C#" Value="public class TopologyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopologyResource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource" />
  <TypeSignature Language="VB.NET" Value="Public Class TopologyResource" />
  <TypeSignature Language="F#" Value="type TopologyResource = class" />
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
            指定されたリソース グループのネットワーク リソースのトポロジ情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TopologyResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopologyResource (string name = null, string id = null, string location = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; associations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string location, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; associations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional location As String = null, Optional associations As IList(Of TopologyAssociation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource (name, id, location, associations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="associations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt;" />
      </Parameters>
      <Docs>
        <param name="name">リソースの名前。</param>
        <param name="id">リソースの ID です。</param>
        <param name="location">リソースの場所。</param>
        <param name="associations">その他のリソース、リソース グループは、リソースはアソシエーションを保持します。</param>
        <summary>
            TopologyResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Associations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; Associations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; Associations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Associations" />
      <MemberSignature Language="VB.NET" Value="Public Property Associations As IList(Of TopologyAssociation)" />
      <MemberSignature Language="F#" Value="member this.Associations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Associations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="associations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TopologyAssociation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、その他のリソース、リソース グループは、リソースはアソシエーションを保持します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Id" />
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
            取得またはリソースの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TopologyResource.Name" />
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
            取得またはリソースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>