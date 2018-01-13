<Type Name="DatabaseAccount" FullName="Microsoft.Azure.Documents.DatabaseAccount">
  <TypeSignature Language="C#" Value="public class DatabaseAccount : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseAccount extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DatabaseAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseAccount = class&#xA;    inherit Resource" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> 
            DatabaseAccount を表します。 DatabaseAccount は、Azure Cosmos DB サービス内のデータベースのコンテナーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConsistencyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ConsistencyPolicy ConsistencyPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.ConsistencyPolicy ConsistencyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyPolicy As ConsistencyPolicy" />
      <MemberSignature Language="F#" Value="member this.ConsistencyPolicy : Microsoft.Azure.Documents.ConsistencyPolicy" Usage="Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" />
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
        <ReturnType>Microsoft.Azure.Documents.ConsistencyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="P:Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" /> Cosmos DB の Azure サービスから設定します。
            </summary>
        <value>
            ConsistencyPolicy 設定します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabasesLink">
      <MemberSignature Language="C#" Value="public string DatabasesLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabasesLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.DatabasesLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabasesLink As String" />
      <MemberSignature Language="F#" Value="member this.DatabasesLink : string" Usage="Microsoft.Azure.Documents.DatabaseAccount.DatabasesLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_dbs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自己リンクのデータベース、databaseAccount でサービスから取得 Azure Cosmos DB します。
            </summary>
        <value>
            自己リンクのデータベース、databaseAccount にします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long MaxMediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MaxMediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxMediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.DatabaseAccount.MaxMediaStorageUsageInMB" />
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
            Azure Cosmos DB サービスからメディアの記憶域、databaseAccount の記憶域のクォータを取得します。
            </summary>
        <value>
            測定 Mb の記憶域のクォータ。
            </value>
        <remarks>
            この値は、ゲートウェイから取得されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaLink">
      <MemberSignature Language="C#" Value="public string MediaLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MediaLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MediaLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MediaLink As String" />
      <MemberSignature Language="F#" Value="member this.MediaLink : string" Usage="Microsoft.Azure.Documents.DatabaseAccount.MediaLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="media")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自己リンクのメディア、databaseAccount でサービスから取得 Azure Cosmos DB します。
            </summary>
        <value>
            自己リンクのメディア、databaseAccount にします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long MediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.DatabaseAccount.MediaStorageUsageInMB" />
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
            現在の添付ファイル コンテンツ (メディア) の使用量を mb 単位 Azure Cosmos DB サービスから取得します。
            </summary>
        <value>
            Mb で添付ファイルのコンテンツ (メディア) 使用率。
            </value>
        <remarks>
            値は、ゲートウェイから取得されます。 値は、定期的に更新情報をキャッシュから返され、リアルタイムであるとは限りません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadableLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt; ReadableLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.DatabaseAccountLocation&gt; ReadableLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.ReadableLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadableLocations As IEnumerable(Of DatabaseAccountLocation)" />
      <MemberSignature Language="F#" Value="member this.ReadableLocations : seq&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;" Usage="Microsoft.Azure.Documents.DatabaseAccount.ReadableLocations" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからこのデータベース アカウントの読み取り可能な領域場所 reprsenting の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritableLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt; WritableLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.DatabaseAccountLocation&gt; WritableLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.WritableLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WritableLocations As IEnumerable(Of DatabaseAccountLocation)" />
      <MemberSignature Language="F#" Value="member this.WritableLocations : seq&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;" Usage="Microsoft.Azure.Documents.DatabaseAccount.WritableLocations" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからこのデータベース アカウントの書き込み可能な領域場所 reprsenting の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>