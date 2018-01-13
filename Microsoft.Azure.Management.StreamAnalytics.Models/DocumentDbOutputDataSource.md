<Type Name="DocumentDbOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource">
  <TypeSignature Language="C#" Value="public class DocumentDbOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentDbOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentDbOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type DocumentDbOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/DocumentDB")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            DocumentDB 出力のデータ ソースをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DocumentDbOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbOutputDataSource (string accountId = null, string accountKey = null, string database = null, string collectionNamePattern = null, string partitionKey = null, string documentId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountId, string accountKey, string database, string collectionNamePattern, string partitionKey, string documentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountId As String = null, Optional accountKey As String = null, Optional database As String = null, Optional collectionNamePattern As String = null, Optional partitionKey As String = null, Optional documentId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource (accountId, accountKey, database, collectionNamePattern, partitionKey, documentId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountId" Type="System.String" />
        <Parameter Name="accountKey" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="collectionNamePattern" Type="System.String" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountId">DocumentDB アカウントの名前または id。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="accountKey">DocumentDB アカウントのアカウント キー。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="database">DocumentDB データベースの名前。
            PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="collectionNamePattern">使用するコレクションのコレクション名のパターン。 コレクション名の形式は、オプションの {partition} トークンを使用して構成できます。この場合、パーティションは 0 から開始します。 詳細については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output の DocumentDB セクションを参照してください。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="partitionKey">コレクション全体で出力をパーティション分割するためのキーを指定するために使用される、出力イベント内のフィールドの名前。
            'CollectionNamePattern' {partition} トークンが含まれている場合、このプロパティを指定する必要です。</param>
        <param name="documentId">挿入または更新操作の基準となるプライマリ キーを指定するために使用される、出力イベント内のフィールドの名前。</param>
        <summary>
            DocumentDbOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public string AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As String" />
      <MemberSignature Language="F#" Value="member this.AccountId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            DocumentDB アカウントの名前または id。 取得または設定 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DocumentDB アカウントのアカウント キーを設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionNamePattern">
      <MemberSignature Language="C#" Value="public string CollectionNamePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionNamePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.CollectionNamePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property CollectionNamePattern As String" />
      <MemberSignature Language="F#" Value="member this.CollectionNamePattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.CollectionNamePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.collectionNamePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用するコレクションのコレクション名のパターンを設定します。 コレクション名の形式は、オプションの {partition} トークンを使用して構成できます。この場合、パーティションは 0 から開始します。 詳細については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output の DocumentDB セクションを参照してください。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.database")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DocumentDB データベースの名前を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentId">
      <MemberSignature Language="C#" Value="public string DocumentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.DocumentId" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentId As String" />
      <MemberSignature Language="F#" Value="member this.DocumentId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.DocumentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.documentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力を挿入または更新操作を主キーを指定するために使用イベントがに基づいて、フィールドの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または出力をパーティション分割コレクション間でのキーを指定するために使用する出力イベント内のフィールドの名前を設定します。 'CollectionNamePattern' {partition} トークンが含まれている場合、このプロパティを指定する必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>