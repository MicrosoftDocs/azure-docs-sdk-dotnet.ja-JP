<Type Name="MigrateMySqlRequest" FullName="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest">
  <TypeSignature Language="C#" Value="public class MigrateMySqlRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrateMySqlRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrateMySqlRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MigrateMySqlRequest = class&#xA;    inherit ProxyOnlyResource" />
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
            MySQL の移行要求。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrateMySqlRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MigrateMySqlRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrateMySqlRequest (string id = null, string name = null, string kind = null, string type = null, string connectionString = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; migrationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string connectionString, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; migrationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional connectionString As String = null, Optional migrationType As Nullable(Of MySqlMigrationType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest (id, name, kind, type, connectionString, migrationType)" />
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
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="migrationType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="connectionString">リモートの MySQL データベースへの接続文字列。</param>
        <param name="migrationType">実行する移行操作の種類。 使用可能な値が含まれます: 'LocalToRemote'、'RemoteToLocal'</param>
        <summary>
            MigrateMySqlRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリモートの MySQL データベースへの接続文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; MigrationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; MigrationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.MigrationType" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationType As Nullable(Of MySqlMigrationType)" />
      <MemberSignature Language="F#" Value="member this.MigrationType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MigrateMySqlRequest.MigrationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.migrationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MySqlMigrationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または実行する移行操作の種類を設定します。 使用可能な値が含まれます: 'LocalToRemote'、'RemoteToLocal'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>