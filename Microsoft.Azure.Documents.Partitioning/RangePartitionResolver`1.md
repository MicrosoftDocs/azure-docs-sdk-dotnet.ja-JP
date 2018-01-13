<Type Name="RangePartitionResolver&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangePartitionResolver&lt;T&gt; : Microsoft.Azure.Documents.Client.IPartitionResolver where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangePartitionResolver`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangePartitionResolver(Of T)&#xA;Implements IPartitionResolver" />
  <TypeSignature Language="F#" Value="type RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IPartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>System.IComparable&lt;T&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">範囲パーティション分割に使用する値の型。</typeparam>
    <summary>
            RangePartitionResolver では、自己リンクをコレクションに値の範囲のパーティションのマップを使用して Azure Cosmos DB サービスのパーティション分割を実装します。
            これは、動作も、データの自然順序付けし、一般的な時系列データまたは文字列のアルファベット順の範囲をたとえば、値の範囲の使用時にクエリを実行します。
            </summary>
    <remarks>
      <para>
            IPartitionResolver ベース クラスのサポートは廃止されました。 使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。
            </para>
      <para>
            範囲パーティション分割では、パーティション キーが特定の範囲内にあるかどうかに基づいてパーティションが割り当てられます。 RangePartitionResolver クラスには、間のマッピングを維持するのに役立ちます、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />とコレクションの自己リンクします。
            </para>
      <para>
        <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />実装する任意の型の範囲を指定するための単純なクラス<see cref="T:System.IComparable`1" />と<see cref="T:System.IEquatable`1" />などの文字列または数値です。 読み込み、作成しを任意の範囲内に渡すことができ、競合回避モジュールが twith、要求された範囲の交差するパーティションの範囲を識別することによってすべての候補コレクションを識別します。
            </para>
      <para>
            範囲パーティション分割の特殊なケースは、範囲が単一不連続の値だけでルックアップがパーティション分割とも呼ばれます。 これは、地域や種類などの不連続の値によって、パーティション分割や、マルチ テナント アプリケーションで、テナントのパーティション分割のよく使用されます。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (Func&lt;object,object&gt; partitionKeyExtractor, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, object&gt; partitionKeyExtractor, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.Func{System.Object,System.Object},System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, Object), partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : Func&lt;obj, obj&gt; * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyExtractor, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.Object&gt;" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor">上のハッシュを実行するドキュメントのプロパティの名前です。</param>
        <param name="partitionMap">範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyExtractor" />値。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">パラメーターのいずれかが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.String,System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : string * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyPropertyName, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName">上のハッシュを実行するドキュメントのプロパティの名前です。</param>
        <param name="partitionMap">範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />クラスを指定して、Azure Cosmos DB サービス <paramref name="partitionKeyPropertyName" />値。
            </summary>
        <remarks>
            1 つのプロパティ名に基づくパーティションを作成するときに使用します。 その他のパーティション分割スキームの場合、代わりに partitionKeyExtractor でコンス トラクターを使用します。
            </remarks>
        <exception cref="T:System.ArgumentNullException">パラメーターのいずれかが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="rangePartitionResolver.GetPartitionKey document" />
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
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,object&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, object&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, Object)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, obj&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの任意のオブジェクトから、パーティション キーを抽出する関数を取得します。
            </summary>
        <value>
            任意のオブジェクトから、パーティション キーを抽出する関数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyPropertyName" />
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
            Cosmos DB の Azure サービスでのハッシュを実行するドキュメントのプロパティの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; PartitionMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; PartitionMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionMap As IDictionary(Of Range(Of T), String)" />
      <MemberSignature Language="F#" Value="member this.PartitionMap : System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            範囲からの Azure Cosmos DB サービスのパーティション分割の要求で使用されるコレクション リンクへのマップを取得します。
            </summary>
        <value>
            範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="rangePartitionResolver.ResolveForCreate partitionKey" />
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
        <param name="partitionKey">ターゲット コレクションの作成を決定するために使用するパーティション キー</param>
        <summary>
            Azure Cosmos DB サービスの範囲パーティションのマップを使用してドキュメントを作成するためのパーティション キーを返します自己リンク正しいコレクションを指定します。
            </summary>
        <returns>ドキュメントの作成に使用するターゲット コレクションのリンクです。</returns>
        <remarks>
            場合は、複数の範囲には、指定した partitionKey が一致すると、競合回避モジュールを返しますの一致する範囲のいずれか。 一致なしの範囲のかどうかは、メソッドをスロー、<see cref="T:System.InvalidOperationException" />です。 PartitionKey が null の場合は、すべてのコレクションが返されます。
            </remarks>
        <exception cref="T:System.ArgumentNullException">場合にスロー<paramref name="partitionKey" />が null です。</exception>
        <exception cref="T:System.InvalidOperationException">
            場合にスローされます、<paramref name="partitionKey" />は無効な型の範囲の中に、指定されたパーティション キーが一致するものである場合またはします。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="rangePartitionResolver.ResolveForRead partitionKey" />
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
        <param name="partitionKey">クエリのターゲット コレクションを決定するために使用するパーティション キー</param>
        <summary>
            パーティション キーを返します範囲パーティション マップを使用して、Azure Cosmos DB サービスからの読み取りにコレクションへのリンクの一覧を指定します。
            </summary>
        <returns>ターゲット コレクションのリンクの一覧。</returns>
        <remarks>
            <paramref name="partitionKey" />のインスタンスである必要があります<typeparamref name="T" />、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />または<see cref="T:System.Collections.Generic.IEnumerable`1" />"。/&gt;. このメソッドは、指定したと交差する範囲に対応するすべてのコレクションを返します<paramref name="partitionKey" />です。
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            場合にスローされます、<paramref name="partitionKey" />種類が無効です。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>