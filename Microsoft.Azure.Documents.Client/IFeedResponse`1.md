<Type Name="IFeedResponse&lt;T&gt;" FullName="Microsoft.Azure.Documents.Client.IFeedResponse&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IFeedResponse&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFeedResponse`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IFeedResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFeedResponse(Of T)" />
  <TypeSignature Language="F#" Value="type IFeedResponse&lt;'T&gt; = interface" />
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
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">フィードの種類。</typeparam>
    <summary>
            Cosmos DB の Azure サービス内のフィード メソッド (列挙操作) に関連付けられている応答の Api をキャプチャします。
            目的のモックに公開されるインターフェイス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ActivityId" />
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
            Azure Cosmos DB サービスの要求のアクティビティ ID を取得します。
            </summary>
        <value>
            要求のアクティビティ ID。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB データベース アカウント内のコレクション リソースの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionSizeQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キロバイト単位で Azure Cosmos DB データベースでのコレクションの最大サイズ。
            </summary>
        <value>
            クォータ (キロバイト単位)。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionSizeUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キロバイト単位で Azure Cosmos DB データベースでのコレクションの現在のサイズ。 
            </summary>
        <value>
            現在コレクション サイズ。
            </value>
        <remarks>To be added.</remarks>
        <vallue>
            現在コレクション サイズ。
            </vallue>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CollectionUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在、Azure Cosmos DB データベース アカウント内でコレクションのリソースの数。
            </summary>
        <value>
            コレクションの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ContentLocation" />
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
            コンテンツの親の Azure Cosmos DB データベースの場所を db、foo、colls/バー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.Count" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのフィードの操作に関連付けられた応答で返される項目数を取得します。
            </summary>
        <value>
            応答内の項目の数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.CurrentResourceQuotaUsage" />
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
            Cosmos DB の Azure サービスでは、このエンティティの現在のサイズを取得します。
            </summary>
        <value>
            このエンティティの現在のサイズ。 その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.DatabaseQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB データベース アカウント内のデータベース リソースの最大クォータを取得します。 
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.DatabaseUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在 Azure Cosmos DB データベース アカウント内のデータベース リソースの数。
            </summary>
        <value>
            データベースの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IFeedResponse`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;" Usage="iFeedResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure Cosmos DB サービスのコレクションを反復処理する列挙子を返します。
            </summary>
        <returns>コレクションを反復処理に使用できる IEnumerator オブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.MaxResourceQuota" />
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
            このサービスのエンティティに Azure Cosmos DB のサイズの上限を取得します。
            </summary>
        <value>
            このエンティティの最大サイズの制限。 その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.PermissionQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB データベース アカウント内のアクセス許可リソースの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.PermissionUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在 Azure Cosmos DB データベース アカウント内のアクセス許可リソースの数。 
            </summary>
        <value>
            アクセス許可の数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.RequestCharge" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この要求に対して Azure Cosmos DB データベース アカウントの要求の料金を取得します。
            </summary>
        <value>
            要求の料金は、reqest 単位で測定されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuation">
      <MemberSignature Language="C#" Value="public string ResponseContinuation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ResponseContinuation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseContinuation As String" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuation : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ResponseContinuation" />
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
            Azure Cosmos DB サービスの列挙を継続するために使用する継続トークンを取得します。
            </summary>
        <value>
            列挙体を継続するために使用する継続トークンです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.ResponseHeaders" />
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
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答ヘッダーを取得します。
            </summary>
        <value>
            応答ヘッダー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.SessionToken" />
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
            Azure Cosmos DB サービスのセッションの整合性の読み取りに使用するため、セッション トークンを取得します。
            </summary>
        <value>
            セッションで使用するためのセッション トークンです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.StoredProceduresQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのコレクションのストアド プロシージャの最大クォータを取得します。
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.StoredProceduresUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在では、Azure Cosmos DB サービスのコレクション用のストアド プロシージャの数。
            </summary>
        <value>
            現在のストアド プロシージャの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.TriggersQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのコレクションのトリガーの最大クォータを取得します。 
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.TriggersUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在では、Azure Cosmos DB サービスのコレクションのトリガーの数。
            </summary>
        <value>
            現在のトリガーの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserDefinedFunctionsQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのコレクションのユーザー定義関数の最大クォータを取得します。 
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserDefinedFunctionsUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ユーザーの現在の数は、Azure Cosmos DB サービスでコレクションの機能を定義します。
            </summary>
        <value>
            ユーザーの現在の数は、関数を定義します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserQuota" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB データベース アカウント内のユーザー リソースの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IFeedResponse`1.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.IFeedResponse&lt;'T&gt;.UserUsage" />
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
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在 Azure Cosmos DB データベース アカウント内のユーザー リソースの数。
            </summary>
        <value>
            ユーザーの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>