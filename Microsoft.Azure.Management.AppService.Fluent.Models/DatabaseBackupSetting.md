<Type Name="DatabaseBackupSetting" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting">
  <TypeSignature Language="C#" Value="public class DatabaseBackupSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseBackupSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseBackupSetting" />
  <TypeSignature Language="F#" Value="type DatabaseBackupSetting = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9cda1-101">データベース バックアップの設定。</span><span class="sxs-lookup"><span data-stu-id="9cda1-101">Database backup settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBackupSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9cda1-102">DatabaseBackupSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9cda1-102">Initializes a new instance of the DatabaseBackupSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBackupSetting (string databaseType, string name = null, string connectionStringName = null, string connectionString = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string databaseType, string name, string connectionStringName, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (databaseType As String, Optional name As String = null, Optional connectionStringName As String = null, Optional connectionString As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting : string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting (databaseType, name, connectionStringName, connectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="databaseType" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="connectionStringName" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseType"><span data-ttu-id="9cda1-103">データベースの種類 (例: SqlAzure/MySql)。</span><span class="sxs-lookup"><span data-stu-id="9cda1-103">Database type (e.g. SqlAzure / MySql).</span></span>
            <span data-ttu-id="9cda1-104">使用可能な値が含まれます: 'SqlAzure'、'MySql'、'LocalMySql'</span><span class="sxs-lookup"><span data-stu-id="9cda1-104">Possible values include: 'SqlAzure', 'MySql', 'LocalMySql'</span></span></param>
        <param name="name">To be added.</param>
        <param name="connectionStringName"><span data-ttu-id="9cda1-105">SiteConfig.ConnectionStrings にリンクされている接続文字列名が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9cda1-105">Contains a connection string name that is linked to the SiteConfig.ConnectionStrings.</span></span>
            <span data-ttu-id="9cda1-106">これは、復元中に使用では、接続文字列オプションを上書きします。</span><span class="sxs-lookup"><span data-stu-id="9cda1-106">This is used during restore with overwrite connection strings options.</span></span></param>
        <param name="connectionString"><span data-ttu-id="9cda1-107">バックアップがあるデータベースへの接続文字列を含むまたは復元します。</span><span class="sxs-lookup"><span data-stu-id="9cda1-107">Contains a connection string to a database which is being backed up or restored.</span></span> <span data-ttu-id="9cda1-108">場合、復元する必要がありますの新しいデータベースに、内部データベース名は新しいです。</span><span class="sxs-lookup"><span data-stu-id="9cda1-108">If the restore should happen to a new database, the database name inside is the new one.</span></span></param>
        <summary>
            <span data-ttu-id="9cda1-109">DatabaseBackupSetting クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9cda1-109">Initializes a new instance of the DatabaseBackupSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9cda1-110">取得または設定がバックアップされているデータベースへの接続文字列が含まれています。 または復元します。</span><span class="sxs-lookup"><span data-stu-id="9cda1-110">Gets or sets contains a connection string to a database which is being backed up or restored.</span></span> <span data-ttu-id="9cda1-111">場合、復元する必要がありますの新しいデータベースに、内部データベース名は新しいです。</span><span class="sxs-lookup"><span data-stu-id="9cda1-111">If the restore should happen to a new database, the database name inside is the new one.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStringName">
      <MemberSignature Language="C#" Value="public string ConnectionStringName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStringName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionStringName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionStringName As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStringName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionStringName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionStringName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9cda1-112">取得または設定、SiteConfig.ConnectionStrings にリンクされている接続文字列名が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9cda1-112">Gets or sets contains a connection string name that is linked to the SiteConfig.ConnectionStrings.</span></span>
            <span data-ttu-id="9cda1-113">これは、復元中に使用では、接続文字列オプションを上書きします。</span><span class="sxs-lookup"><span data-stu-id="9cda1-113">This is used during restore with overwrite connection strings options.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseType">
      <MemberSignature Language="C#" Value="public string DatabaseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.DatabaseType" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseType As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.DatabaseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9cda1-114">取得または設定データベースの種類 (例: SqlAzure/MySql)。</span><span class="sxs-lookup"><span data-stu-id="9cda1-114">Gets or sets database type (e.g. SqlAzure / MySql).</span></span> <span data-ttu-id="9cda1-115">使用可能な値が含まれます: 'SqlAzure'、'MySql'、'LocalMySql'</span><span class="sxs-lookup"><span data-stu-id="9cda1-115">Possible values include: 'SqlAzure', 'MySql', 'LocalMySql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="databaseBackupSetting.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9cda1-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9cda1-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9cda1-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9cda1-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>