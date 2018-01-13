<Type Name="TopLevelDomain" FullName="Microsoft.Azure.Management.WebSites.Models.TopLevelDomain">
  <TypeSignature Language="C#" Value="public class TopLevelDomain : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopLevelDomain extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TopLevelDomain" />
  <TypeSignature Language="VB.NET" Value="Public Class TopLevelDomain&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type TopLevelDomain = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            トップ レベルのドメイン オブジェクトです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TopLevelDomain クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomain (string id = null, string name = null, string kind = null, string type = null, string domainName = null, Nullable&lt;bool&gt; privacy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string domainName, valuetype System.Nullable`1&lt;bool&gt; privacy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional domainName As String = null, Optional privacy As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomain : string * string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.TopLevelDomain" Usage="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomain (id, name, kind, type, domainName, privacy)" />
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
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="privacy" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="domainName">最上位ドメインの名前です。</param>
        <param name="privacy">場合&lt;コード&gt;true&lt;/code&gt;、トップ レベルのドメインがドメイン プライバシ; をサポートし、それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <summary>
            TopLevelDomain クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.DomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最上位ドメインの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Privacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public Property Privacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Privacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomain.Privacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt;、トップ レベルのドメインがドメイン プライバシ; をサポートし、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code。&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>