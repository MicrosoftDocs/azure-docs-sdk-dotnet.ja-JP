<Type Name="RecoverableDatabase" FullName="Microsoft.Azure.Management.Sql.Models.RecoverableDatabase">
  <TypeSignature Language="C#" Value="public class RecoverableDatabase : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecoverableDatabase extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Class RecoverableDatabase&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RecoverableDatabase = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="206f9-101">回復可能なデータベース</span><span class="sxs-lookup"><span data-stu-id="206f9-101">A recoverable database</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoverableDatabase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="206f9-102">RecoverableDatabase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="206f9-102">Initializes a new instance of the RecoverableDatabase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoverableDatabase (string id = null, string name = null, string type = null, string edition = null, string serviceLevelObjective = null, string elasticPoolName = null, Nullable&lt;DateTime&gt; lastAvailableBackupDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string edition, string serviceLevelObjective, string elasticPoolName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastAvailableBackupDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional edition As String = null, Optional serviceLevelObjective As String = null, Optional elasticPoolName As String = null, Optional lastAvailableBackupDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RecoverableDatabase : string * string * string * string * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RecoverableDatabase" Usage="new Microsoft.Azure.Management.Sql.Models.RecoverableDatabase (id, name, type, edition, serviceLevelObjective, elasticPoolName, lastAvailableBackupDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="lastAvailableBackupDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="206f9-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="206f9-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="206f9-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="206f9-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="206f9-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="206f9-105">Resource type.</span></span></param>
        <param name="edition"><span data-ttu-id="206f9-106">データベースのエディション</span><span class="sxs-lookup"><span data-stu-id="206f9-106">The edition of the database</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="206f9-107">データベースのサービス レベル目標の名前</span><span class="sxs-lookup"><span data-stu-id="206f9-107">The service level objective name of the database</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="206f9-108">データベースの弾力性プールの名前</span><span class="sxs-lookup"><span data-stu-id="206f9-108">The elastic pool name of the database</span></span></param>
        <param name="lastAvailableBackupDate"><span data-ttu-id="206f9-109">最後にバックアップして利用可能なデータベース (ISO8601 形式) の日付</span><span class="sxs-lookup"><span data-stu-id="206f9-109">The last available backup date of the database (ISO8601 format)</span></span></param>
        <summary>
            <span data-ttu-id="206f9-110">RecoverableDatabase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="206f9-110">Initializes a new instance of the RecoverableDatabase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.Edition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string" Usage="Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="206f9-111">データベースのエディションを取得します。</span><span class="sxs-lookup"><span data-stu-id="206f9-111">Gets the edition of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="206f9-112">データベースの弾力性プールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="206f9-112">Gets the elastic pool name of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAvailableBackupDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastAvailableBackupDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastAvailableBackupDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.LastAvailableBackupDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAvailableBackupDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastAvailableBackupDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.LastAvailableBackupDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastAvailableBackupDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="206f9-113">最後にバックアップして利用可能なデータベース (ISO8601 形式) の日付を取得します。</span><span class="sxs-lookup"><span data-stu-id="206f9-113">Gets the last available backup date of the database (ISO8601 format)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.RecoverableDatabase.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="206f9-114">データベースのサービス レベル目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="206f9-114">Gets the service level objective name of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>