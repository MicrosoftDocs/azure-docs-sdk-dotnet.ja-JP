<Type Name="ITableEntity" FullName="Microsoft.Azure.CosmosDB.Table.ITableEntity">
  <TypeSignature Language="C#" Value="public interface ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableEntity" />
  <TypeSignature Language="F#" Value="type ITableEntity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            テーブルのエンティティ型に必要なインターフェイスです。 <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />インターフェイスが、必須のエンティティのプロパティの getter および setter メソッドを宣言および<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />シリアル化と逆シリアル化、プロパティ ディクショナリを使用してすべてのエンティティのプロパティのメソッドです。 実装するクラスを作成する<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />プロパティの格納、取得、シリアル化および逆シリアル化をカスタマイズして、テーブル エンティティの追加のカスタム ロジックを指定します。
            </summary>
    <remarks>
      <para>ストレージ クライアント ライブラリには 2 つの実装が含まれています<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />単純なプロパティ アクセスとシリアル化を提供します。</para>
      <para>
        <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />実装する<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />し格納およびプロパティを取得する単純なプロパティ ディクショナリを提供します。 使用して、<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />簡単なアクセス プロパティのサブセットのみを返す場合 (たとえば、クエリの select 句) をエンティティのプロパティまたはシナリオは、クエリが異なるプロパティを持つ複数のエンティティ型を返すことができます。 また、この種類を使用する、プロパティ情報を失うことがなく異種エンティティの一括テーブルの更新を実行することができます。</para>
      <para>
        <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />実装は、<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />でシリアル化と逆シリアル化をリフレクション ベースで動作を使用するその<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドです。 
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />派生クラスの型と名前付けをシリアル化して自動的に逆シリアル化の規則に従っているメソッドを使用します。 <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />-も、派生クラスは、Microsoft Azure テーブル サービスでサポートされている型の get と set に対応のパブリック プロパティを指定する可能性があります。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティの現在の ETag を設定します。  この値を ' *'、更新操作の一部としてエンティティを無条件で上書きするためにします。
            </summary>
        <value>エンティティのタイムスタンプ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティのパーティション キーを設定します。
            </summary>
        <value>エンティティのパーティション キーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="iTableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">文字列プロパティ名の辞書<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            エンティティのプロパティを設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />のデータ値が、<paramref name="properties" />ディクショナリ。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティの行キーを設定します。
            </summary>
        <value>エンティティの行キーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティのタイムスタンプを設定します。
            </summary>
        <value>エンティティのタイムスタンプ。 プロパティは、Microsoft Azure テーブル サービスで設定されます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="iTableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />エンティティ インスタンスからのデータ値。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />オブジェクトにプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データは、このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>