<Type Name="ConnectionStringDictionary" FullName="Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary">
  <TypeSignature Language="C#" Value="public class ConnectionStringDictionary : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionStringDictionary extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionStringDictionary&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ConnectionStringDictionary = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            文字列ディクショナリ リソース。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStringDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ConnectionStringDictionary クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStringDictionary (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional properties As IDictionary(Of String, ConnStringValueTypePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary" Usage="new Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary (id, name, kind, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="properties">接続文字列です。</param>
        <summary>
            ConnectionStringDictionary クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, ConnStringValueTypePair)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または接続文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>