<Type Name="DataSource" FullName="Microsoft.Azure.Search.Models.DataSource">
  <TypeSignature Language="C#" Value="public class DataSource : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSource extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSource&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type DataSource = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            インデクサーの構成に使用できる Azure search データソース定義を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource (string name, Microsoft.Azure.Search.Models.DataSourceType type, Microsoft.Azure.Search.Models.DataSourceCredentials credentials, Microsoft.Azure.Search.Models.DataContainer container, string description = null, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataSourceType type, class Microsoft.Azure.Search.Models.DataSourceCredentials credentials, class Microsoft.Azure.Search.Models.DataContainer container, string description, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor(System.String,Microsoft.Azure.Search.Models.DataSourceType,Microsoft.Azure.Search.Models.DataSourceCredentials,Microsoft.Azure.Search.Models.DataContainer,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataSource : string * Microsoft.Azure.Search.Models.DataSourceType * Microsoft.Azure.Search.Models.DataSourceCredentials * Microsoft.Azure.Search.Models.DataContainer * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="new Microsoft.Azure.Search.Models.DataSource (name, type, credentials, container, description, dataChangeDetectionPolicy, dataDeletionDetectionPolicy, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Search.Models.DataSourceType" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.Models.DataSourceCredentials" />
        <Parameter Name="container" Type="Microsoft.Azure.Search.Models.DataContainer" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dataChangeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="dataDeletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="type">データ ソースの種類。</param>
        <param name="credentials">データ ソースの資格情報。</param>
        <param name="container">データ ソースのデータ コンテナーです。</param>
        <param name="description">データ ソースの説明です。</param>
        <param name="dataChangeDetectionPolicy">データは、データ ソースの検出ポリシーを変更します。</param>
        <param name="dataDeletionDetectionPolicy">データ ソースのデータ削除検出ポリシー。</param>
        <param name="eTag">データ ソースの ETag です。</param>
        <summary>
            DataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureBlobStorage (string name, string storageConnectionString, string containerName, string pathPrefix = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureBlobStorage(string name, string storageConnectionString, string containerName, string pathPrefix, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureBlobStorage (name As String, storageConnectionString As String, containerName As String, Optional pathPrefix As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureBlobStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage (name, storageConnectionString, containerName, pathPrefix, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="storageConnectionString">Azure ストレージ アカウントの接続文字列。 この形式に従う必要があります:"DefaultEndpointsProtocol = https;AccountName [ストレージ アカウント] を = です。AccountKey [アカウント キー] を = です"。HTTPS が必要なことに注意してください。</param>
        <param name="containerName">Blob の読み取り元のコンテナーの名前。</param>
        <param name="pathPrefix">省略可能。 指定した場合、データ ソースはこのプレフィックスで始まる blob のみが含まれます。 これは、機能は、blob はフォルダーで整理"仮想"、たとえばときに便利です。</param>
        <param name="deletionDetectionPolicy">省略可能。 データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            Azure Blob コンテナーへの接続に新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">Azure SQL データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="changeDetectionPolicy">データ ソースの変更検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            変更の検出を有効になっていると、Azure SQL データベースに接続する新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">Azure SQL データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="deletionDetectionPolicy">省略可能。 データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            Azure SQL データベースへの接続に新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">Azure SQL データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="changeDetectionPolicy">データ ソースの変更検出ポリシー。 削除の検出が有効になっている場合は、そののみ高基準値変更検出を Azure SQL の許可します。</param>
        <param name="deletionDetectionPolicy">データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            変更の検出と削除の検出が有効な Azure SQL データベースへの接続に新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureTableStorage (string name, string storageConnectionString, string tableName, string query = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureTableStorage(string name, string storageConnectionString, string tableName, string query, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureTableStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureTableStorage (name As String, storageConnectionString As String, tableName As String, Optional query As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureTableStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureTableStorage (name, storageConnectionString, tableName, query, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="storageConnectionString">Azure ストレージ アカウントの接続文字列。 この形式に従う必要があります:"DefaultEndpointsProtocol = https;AccountName [ストレージ アカウント] を = です。AccountKey [アカウント キー] を = です"。HTTPS が必要なことに注意してください。</param>
        <param name="tableName">行の読み込み元のテーブルの名前。</param>
        <param name="query">省略可能。 行を読み取るときに、テーブルに適用されるクエリ。</param>
        <param name="deletionDetectionPolicy">省略可能。 データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            Azure テーブルへの接続に新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataContainer Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As DataContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Search.Models.DataContainer with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースのデータ コンテナーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As DataSourceCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Search.Models.DataSourceCredentials with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースの資格情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataChangeDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataChangeDetectionPolicy As DataChangeDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataChangeDetectionPolicy : Microsoft.Azure.Search.Models.DataChangeDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataChangeDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataChangeDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースのデータ変更検出ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDeletionDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDeletionDetectionPolicy As DataDeletionDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataDeletionDetectionPolicy : Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDeletionDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースのデータ削除検出ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースの説明を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentDb">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource DocumentDb (string name, string documentDbConnectionString, string collectionName, string query = null, bool useChangeDetection = true, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource DocumentDb(string name, string documentDbConnectionString, string collectionName, string query, bool useChangeDetection, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.DocumentDb(System.String,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DocumentDb (name As String, documentDbConnectionString As String, collectionName As String, Optional query As String = null, Optional useChangeDetection As Boolean = true, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member DocumentDb : string * string * string * string * bool * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.DocumentDb (name, documentDbConnectionString, collectionName, query, useChangeDetection, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="documentDbConnectionString" Type="System.String" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="useChangeDetection" Type="System.Boolean" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="documentDbConnectionString">DocumentDb データベースの接続文字列。 この形式に従う必要があります:"AccountName |AccountEndpoint [アカウント名またはエンドポイント] を = です。AccountKey [アカウント キー] を =; Database = [データベース名]"</param>
        <param name="collectionName">ドキュメントを読み取り元のコレクションの名前。</param>
        <param name="query">省略可能。 ドキュメントを読み取るときに、コレクションに適用されるクエリ。</param>
        <param name="useChangeDetection">省略可能。 インデックスを作成するときに、変更の検出を使用するかどうかを示します。 既定値は true です。</param>
        <param name="deletionDetectionPolicy">省略可能。 データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            DocumentDb データベースへの接続に新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースの ETag を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            取得またはデータ ソースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">SQL Server データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="changeDetectionPolicy">データ ソースの変更検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            変更の検出を有効になっていると、VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">SQL Server データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="deletionDetectionPolicy">省略可能。 データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ ソースの名前。</param>
        <param name="sqlConnectionString">SQL Server データベースの接続文字列。</param>
        <param name="tableOrViewName">テーブルまたはビューの行を読み取り元の名前。</param>
        <param name="changeDetectionPolicy">データ ソースの変更検出ポリシー。 削除の検出が有効になっている場合は、そののみ高基準値変更検出を SQL Server の許可します。</param>
        <param name="deletionDetectionPolicy">データ ソースのデータ削除検出ポリシー。</param>
        <param name="description">省略可能。 データ ソースの説明です。</param>
        <summary>
            変更の検出と削除の検出を有効になっている VM でホストされる SQL Server データベースに接続する新しいデータ ソースを作成します。
            </summary>
        <returns>新しいデータ ソース インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataSourceType with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>