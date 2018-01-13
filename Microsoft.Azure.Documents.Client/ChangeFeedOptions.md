<Type Name="ChangeFeedOptions" FullName="Microsoft.Azure.Documents.Client.ChangeFeedOptions">
  <TypeSignature Language="C#" Value="public sealed class ChangeFeedOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ChangeFeedOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ChangeFeedOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChangeFeedOptions" />
  <TypeSignature Language="F#" Value="type ChangeFeedOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            関連付けられているオプションを変更する Azure Cosmos DB サービス内のフィード メソッド (列挙操作) を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ChangeFeedOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.MaxItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxItemCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxItemCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.MaxItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービス内の列挙操作で返される項目の最大数を設定します。
            </summary>
        <value>
            列挙操作で返される項目の最大数。
            </value>
        <remarks>
            クエリの改ページを使用します。
            動的なページ サイズの '-1' 使用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyRangeId">
      <MemberSignature Language="C#" Value="public string PartitionKeyRangeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyRangeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.PartitionKeyRangeId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyRangeId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyRangeId : string with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.PartitionKeyRangeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの現在の要求のパーティション キーの範囲の id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ChangeFeed 要求は、特定のパーティション キーの範囲に対して実行できます。 これを使用するには、変更を並列で複数のコンシューマー間でのフィードを処理します。
            PartitionKeyRangeId は、PartitionKey と共に指定することはできません。
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.PartitionKeyRange" />
        <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadPartitionKeyRangeFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      </Docs>
    </Member>
    <Member MemberName="RequestContinuation">
      <MemberSignature Language="C#" Value="public string RequestContinuation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.RequestContinuation" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestContinuation As String" />
      <MemberSignature Language="F#" Value="member this.RequestContinuation : string with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.RequestContinuation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの継続トークンの要求を設定します。
            </summary>
        <value>
            要求の継続トークンです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのセッションの整合性を使用するためのセッション トークンを設定します。
            </summary>
        <value>
            セッションで使用するためのセッション トークンです。
            </value>
        <remarks>
            複数 Microsoft.Azure.Documents.Client.DocumentClient インスタンス間で負荷分散するアプリケーション向けに便利です。 これで大文字と小文字、ラウンドト リップをアプリケーションには、エンド ユーザーからのトークンと Azure Cosmos DB にできるように、サーバー間でセッションを保持できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartFromBeginning">
      <MemberSignature Language="C#" Value="public bool StartFromBeginning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StartFromBeginning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.StartFromBeginning" />
      <MemberSignature Language="VB.NET" Value="Public Property StartFromBeginning As Boolean" />
      <MemberSignature Language="F#" Value="member this.StartFromBeginning : bool with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.StartFromBeginning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または変更 Cosmos DB の Azure サービスでのフィードは、(true) を開始または現在 (false) からを起動する必要があるかどうかを設定します。
            既定では現在 (false) から開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ChangeFeedOptions.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.ChangeFeedOptions.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または検索後に変更を開始するには、(排他) の時間を設定します。
            これを指定すると、StartFromBeginning は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>