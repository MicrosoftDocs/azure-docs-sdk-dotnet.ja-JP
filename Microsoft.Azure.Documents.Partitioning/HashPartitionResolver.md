<Type Name="HashPartitionResolver" FullName="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver">
  <TypeSignature Language="C#" Value="public class HashPartitionResolver : IDisposable, Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HashPartitionResolver extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class HashPartitionResolver&#xA;Implements IDisposable, IPartitionResolver" />
  <TypeSignature Language="F#" Value="type HashPartitionResolver = class&#xA;    interface IPartitionResolver&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HashPartitionResolver は、要求およびデータを Azure Cosmos DB サービスのパーティションの数の間で均等に分散することができます、ハッシュ関数の値に基づくパーティション分割を実装します。 
            </summary>
    <remarks>
      <para>
            IPartitionResolver ベース クラスのサポートは廃止されました。 使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。
            </para>
      <para>
            HashPartitionResolver クラスでは、経由で指定されたハッシュ関数で、一貫したハッシュ リングを内部的に実装、<see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />インターフェイスです。 既定では、HashPartitionResolver が MD5 ハッシュ関数には、このことができますにスワップ アウトする別のハッシュ実装。 一貫したハッシュ リングは、コレクション間でドキュメントのより均一な分布を実現するためにコレクションごとに 16 のレプリカを作成します。
            </para>
      <para>
            ハッシュ パーティション分割は、コレクション間でデータを均等に割り当てがあるために、パーティション キーは基数の大きな時にパーティション分割に最も適しています。 通常ハッシュ パーティション分割は、id プロパティを使用しています。 ハッシュ パーティション分割の一般的なユース ケースは、生成またはから多数の個別のクライアントまたはユーザー プロファイル、カタログ アイテム、および遠隔測定データを格納するために使用されたデータです。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (Func&lt;object,string&gt; partitionKeyExtractor, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, string&gt; partitionKeyExtractor, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.Func{System.Object,System.String},System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, String), collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : Func&lt;obj, string&gt; * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyExtractor, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.String&gt;" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor">ドキュメントからの partitionKey を抽出する関数</param>
        <param name="collectionLinks">ハッシュに使用されるコレクションへのリンクの一覧。</param>
        <param name="numberOfVirtualNodesPerCollection">Conisistent ハッシュ リング内のコレクションあたりの仮想ノードの数。</param>
        <param name="hashGenerator"><see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />一貫したハッシュで使用します。 Null の場合は、既定の MD5 ハッシュ ジェネレーターが使用されます。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyExtractor" />値。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : string * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyPropertyName, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName">上のハッシュを実行するドキュメントのプロパティの名前です。</param>
        <param name="collectionLinks">ハッシュに使用されるコレクションへのリンクの一覧。</param>
        <param name="numberOfVirtualNodesPerCollection">Conisistent ハッシュ リング内のコレクションあたりの仮想ノードの数。</param>
        <param name="hashGenerator"><see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />一貫したハッシュで使用します。 Null の場合は、既定の MD5 ハッシュ ジェネレーターが使用されます。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyPropertyName" />値。
            </summary>
        <remarks>
            1 つのプロパティ名に基づくパーティションを作成するときに使用します。 その他のパーティション分割スキームの場合、代わりに partitionKeyExtractor でコンス トラクターを使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; CollectionLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; CollectionLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionLinks As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.CollectionLinks : seq&lt;string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのハッシュに使用されるコレクションへのリンクの IEnumerable を取得します。
            </summary>
        <value>ハッシュに使用されるコレクションへのリンクの IEnumerable です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="hashPartitionResolver.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでの競合回避モジュールを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~HashPartitionResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="hashPartitionResolver.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            クラスのデストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="hashPartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document">ドキュメント オブジェクト</param>
        <summary>
            パーティション キーを指定して、指定されたドキュメントから抽出<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />プロパティまたは<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />Cosmos DB の Azure サービスでの優先順位で機能します。
            </summary>
        <returns>パーティション キーとして使用されるオブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">パーティション キーを抽出できない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="HashGenerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HashGenerator As IHashGenerator" />
      <MemberSignature Language="F#" Value="member this.HashGenerator : Microsoft.Azure.Documents.Partitioning.IHashGenerator" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberType>Property</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Partitioning.IHashGenerator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一貫したハッシュで使用される HashGenerator を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfVirtualNodesPerCollection">
      <MemberSignature Language="C#" Value="public int NumberOfVirtualNodesPerCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfVirtualNodesPerCollection As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfVirtualNodesPerCollection : int" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberType>Property</MemberType>
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
            Conisistent ハッシュにコレクションごとの仮想ノードの数は、Azure Cosmos DB サービス リングします。 これは、ドキュメントの歪み度のセキュリティ侵害で制御コレクション vs 一貫したハッシュ遅延します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,string&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, string&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービス内のオブジェクトから、パーティション キーを抽出する関数を取得します。
            </summary>
        <value>オブジェクトから、パーティション キーを抽出する関数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberType>Property</MemberType>
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
            Cosmos DB の Azure サービスでのハッシュを実行するドキュメントでプロパティの名前を取得します。
            </summary>
        <value>上のハッシュを実行するドキュメントのプロパティの名前です。</value>
        <remarks>
            HashPartitionResolver - 2 つのモードをサポートしている 1 つを使用して PartitionKeyPropertyName と、その他の PartitionKeyExtractor を使用しています。
            PartitionKeyPropertyName がリフレクションでは、c# を使用してプロパティ名では、JSON 表現ではありませんを使用して抽出されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="hashPartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">ターゲット コレクションを決定するために使用するパーティション キーを作成します。</param>
        <summary>
            パーティション キーを返しますが、コレクションの自己リンク指定 Cosmos DB の Azure サービスでドキュメントを作成します。
            </summary>
        <returns>ドキュメントの作成に使用するターゲット コレクションのリンクです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">スローされた場合、指定した<paramref name="partitionKey" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="hashPartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">読み取り対象のコレクションを決定するために使用するパーティション キーです。 文字列である必要があります。</param>
        <summary>
            パーティション キーを返します Cosmos DB の Azure サービスでそのハッシュを使用してから参照するコレクションにリンクの一覧を指定します。
            </summary>
        <returns>ターゲット コレクションのリンクの一覧。</returns>
        <remarks>
            PartitionKey が null の場合は、すべてのコレクションが返されます。 HashPartitionResolver partitionKeys として文字列のみをサポートします。
            その他の種類には、文字列に変換する ToString() または JsonConvert.SerializeObject() を使用します。
            </remarks>
        <exception cref="T:System.InvalidOperationException">パーティション キーが文字列ではない場合にスローされます。</exception>
      </Docs>
    </Member>
  </Members>
</Type>