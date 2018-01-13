<Type Name="IResourceResponseBase" FullName="Microsoft.Azure.Documents.Client.IResourceResponseBase">
  <TypeSignature Language="C#" Value="public interface IResourceResponseBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceResponseBase" />
  <TypeSignature Language="F#" Value="type IResourceResponseBase = interface" />
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
  <Interfaces />
  <Docs>
    <summary>
            Azure Cosmos DB サービスのすべての要求によって返されるリソース以外の特定のサービスの応答ヘッダーを表します。
            </summary>
    <remarks>
            Azure Cosmos DB サービスの目的をモックに公開されるインターフェイス。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ActivityId" />
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
            要求のアクティビティ ID を取得します。
            </summary>
        <value>
            要求のアクティビティ ID。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionQuota">
      <MemberSignature Language="C#" Value="public long CollectionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionQuota" />
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
            コレクション内のリソース アカウントの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeQuota">
      <MemberSignature Language="C#" Value="public long CollectionSizeQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeQuota As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeQuota" />
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
            (キロバイト単位) のコレクションの最大サイズ。
            </summary>
        <value>
            クォータ (キロバイト単位)。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionSizeUsage">
      <MemberSignature Language="C#" Value="public long CollectionSizeUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionSizeUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionSizeUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionSizeUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionSizeUsage" />
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
            キロバイト単位でのコレクションの現在のサイズ。 
            </summary>
        <value>
            現在コレクション サイズ。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionUsage">
      <MemberSignature Language="C#" Value="public long CollectionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CollectionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.CollectionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CollectionUsage" />
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
            現在、アカウント内でコレクションのリソースの数。
            </summary>
        <value>
            コレクションの数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLocation">
      <MemberSignature Language="C#" Value="public string ContentLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ContentLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentLocation As String" />
      <MemberSignature Language="F#" Value="member this.ContentLocation : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ContentLocation" />
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
            コンテンツの親場所、たとえば、db、foo、colls/バー
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.CurrentResourceQuotaUsage" />
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
            このエンティティの現在のサイズを取得します。
            </summary>
        <value>
            このエンティティの現在のサイズ。 その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseQuota">
      <MemberSignature Language="C#" Value="public long DatabaseQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseQuota" />
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
            アカウント内のデータベース リソースの最大クォータを取得します。 
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsage">
      <MemberSignature Language="C#" Value="public long DatabaseUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DatabaseUsage" />
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
            現在、アカウント内のデータベース リソースの数。
            </summary>
        <value>
            データベースの数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentQuota">
      <MemberSignature Language="C#" Value="public long DocumentQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentQuota As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentQuota" />
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
            (キロバイト単位) のコレクション内のドキュメントの最大サイズ。
            </summary>
        <value>
            クォータ (キロバイト単位)。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentUsage">
      <MemberSignature Language="C#" Value="public long DocumentUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentUsage As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.DocumentUsage" />
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
            (キロバイト単位) のコレクション内のドキュメントの現在のサイズ。 
            </summary>
        <value>
            現在のドキュメント サイズ。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexTransformationProgress">
      <MemberSignature Language="C#" Value="public long IndexTransformationProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IndexTransformationProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.IndexTransformationProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexTransformationProgress As Long" />
      <MemberSignature Language="F#" Value="member this.IndexTransformationProgress : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.IndexTransformationProgress" />
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
            いずれかが行われている場合、インデックスの変換の進行状況を取得します。
            </summary>
        <value>
            0 ~ 100 の整数インデックスの変換処理の完了率を表すです。
            インデックスの変換にはヘッダーが進行状況の場合は-1 を返しますが見つかりませんでした。
            </value>
        <remarks>
            コレクションの IndexPolicy が更新されたときに、インデックスを再構築されます。
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LazyIndexingProgress">
      <MemberSignature Language="C#" Value="public long LazyIndexingProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LazyIndexingProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.LazyIndexingProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LazyIndexingProgress As Long" />
      <MemberSignature Language="F#" Value="member this.LazyIndexingProgress : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.LazyIndexingProgress" />
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
            遅延インデックス作成の進行状況を取得します。
            </summary>
        <value>
            100、限定的なインデックス作成プロセスの完了率を表す 0 から整数。
            限定的なインデックス作成の進行状況ヘッダーが見つからなかった場合は、-1 を返します。
            </value>
        <remarks>
            遅延インデックス作成の進行状況は、インデックス作成モード Lazy を持つコレクションにのみ適用されます。
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.MaxResourceQuota" />
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
            このエンティティの最大サイズの制限を取得します。
            </summary>
        <value>
            このエンティティの最大サイズの制限。 その他のリソースのカウント ドキュメント リソースをキロバイト単位で測定されます。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionQuota">
      <MemberSignature Language="C#" Value="public long PermissionQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionQuota As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionQuota" />
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
            アカウント内のアクセス許可リソースの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionUsage">
      <MemberSignature Language="C#" Value="public long PermissionUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PermissionUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PermissionUsage As Long" />
      <MemberSignature Language="F#" Value="member this.PermissionUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.PermissionUsage" />
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
            現在、アカウント内でのアクセス許可リソースの数。 
            </summary>
        <value>
            アクセス許可の数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.RequestCharge" />
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
            この要求の要求の料金を取得します。
            </summary>
        <value>
            要求の料金は、reqest 単位で測定されます。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseHeaders" />
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
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream ResponseStream { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IO.Stream ResponseStream" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseStream" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseStream As Stream" />
      <MemberSignature Language="F#" Value="member this.ResponseStream : System.IO.Stream" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.ResponseStream" />
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
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答の基になるストリームを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.SessionToken" />
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
            セッションの整合性の読み取りに使用するため、セッション トークンを取得します。
            </summary>
        <value>
            セッションで使用するためのセッション トークンです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StatusCode" />
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
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            応答に関連付けられている HTTP ステータス コードを取得します。
            </summary>
        <value>
            応答に関連付けられている HTTP ステータス コード。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresQuota">
      <MemberSignature Language="C#" Value="public long StoredProceduresQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresQuota As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresQuota" />
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
            コレクションのストアド プロシージャの最大クォータを取得します。
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresUsage">
      <MemberSignature Language="C#" Value="public long StoredProceduresUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StoredProceduresUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresUsage As Long" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.StoredProceduresUsage" />
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
            現在のコレクション用のストアド プロシージャの数。
            </summary>
        <value>
            現在のストアド プロシージャの数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersQuota">
      <MemberSignature Language="C#" Value="public long TriggersQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersQuota As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersQuota" />
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
            コレクションのトリガーの最大クォータを取得します。 
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersUsage">
      <MemberSignature Language="C#" Value="public long TriggersUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TriggersUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersUsage As Long" />
      <MemberSignature Language="F#" Value="member this.TriggersUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.TriggersUsage" />
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
            現在のコレクションのトリガーの数。
            </summary>
        <value>
            現在のトリガーの数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsQuota">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsQuota" />
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
            コレクションのユーザー定義関数の最大クォータを取得します。 
            </summary>
        <value>
            最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsUsage">
      <MemberSignature Language="C#" Value="public long UserDefinedFunctionsUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserDefinedFunctionsUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserDefinedFunctionsUsage" />
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
            現在のユーザー数には、コレクションの機能が定義されています。
            </summary>
        <value>
            ユーザーの現在の数は、関数を定義します。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserQuota">
      <MemberSignature Language="C#" Value="public long UserQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserQuota As Long" />
      <MemberSignature Language="F#" Value="member this.UserQuota : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserQuota" />
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
            アカウント内のユーザー リソースの最大クォータを取得します。
            </summary>
        <value>
            アカウントの最大クォータです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserUsage">
      <MemberSignature Language="C#" Value="public long UserUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 UserUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponseBase.UserUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserUsage As Long" />
      <MemberSignature Language="F#" Value="member this.UserUsage : int64" Usage="Microsoft.Azure.Documents.Client.IResourceResponseBase.UserUsage" />
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
            現在、アカウント内のユーザー リソースの数。
            </summary>
        <value>
            ユーザーの数。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>