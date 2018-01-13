<Type Name="ODATADetailLevel" FullName="Microsoft.Azure.Batch.ODATADetailLevel">
  <TypeSignature Language="C#" Value="public class ODATADetailLevel : Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODATADetailLevel extends Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ODATADetailLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class ODATADetailLevel&#xA;Inherits DetailLevel" />
  <TypeSignature Language="F#" Value="type ODATADetailLevel = class&#xA;    inherit DetailLevel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.DetailLevel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             一覧表示するか、OData のクエリ句を使用して、リソースを取得するときに Azure Batch のサービスから要求される詳細情報の量を制御します。
             </summary>
    <remarks>
      <para>Azure Batch は、一覧操作で返されるどのリソースを制御することでクエリのパフォーマンスをより細かく制御を取得するためにクライアントを許可するは、OData クエリをサポートしています (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />)、リスト、Get または更新の各リソースのプロパティが返されます操作 (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />と<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />)。</para>
      <para>既定を渡さない場合、<see cref="T:Microsoft.Azure.Batch.DetailLevel" />の一覧を取得または更新操作、バッチ クライアント フィルターを指定されません (すべてのレコードが返されます)、展開句の select 句のない (すべての単純なプロパティが返されます) と いいえ (関連付けられているエンティティは返されません)。  その結果、既定では、関連付けられているエンティティ プロパティは、その他のプロパティと同様に登録されているのではなく、null の場合。  個々 のクラスのマニュアルを参照するプロパティが関連付けられているエンティティと見なされ、展開すると、設定する必要がありますを参照してください。</para>
      <para>OData クエリは、REST API に直接渡されるため句文字列では JSON 属性の名前から、REST API ではない常に .NET プロパティの名前と同じを使用する必要があります。  たとえば、.NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see>プロパティは、REST API の vmSize 属性に対応していますそのため、VM のサイズによってプールの一覧操作をフィルターするにはする必要 VirtualMachineSize ではなく vmSize 記述。で、フィルター文字列。  .NET プロパティに対応する JSON 属性名を見つけるに REST API のドキュメントを参照してください。</para>
      <para>OData を使用して、Azure Batch サービスを効率的にクエリする方法の詳細については、次を参照してください。<a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">効率的なリスト クエリ</a>msdn です。</para>
    </remarks>
    <example>
             このサンプルは、唯一アクティブを一覧表示する ODataDetailLevel を指定する方法を示します<see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>、のみを取得し、 <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />、<see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" />プールごとに (たとえば、レポート ユーザーに表示インターフェイス) です。
             <code>
             var detailLevel = new ODATADetailLevel(
             filterClause: "state eq 'active'",
             selectClause: "id,displayName,stats",
                 expandClause: "stats"
                 );
                 
             var pools = batchClient.PoolOperations.ListPools(detailLevel);
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" />空句を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel (string filterClause = null, string selectClause = null, string expandClause = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filterClause, string selectClause, string expandClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filterClause As String = null, Optional selectClause As String = null, Optional expandClause As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ODATADetailLevel : string * string * string -&gt; Microsoft.Azure.Batch.ODATADetailLevel" Usage="new Microsoft.Azure.Batch.ODATADetailLevel (filterClause, selectClause, expandClause)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filterClause" Type="System.String" />
        <Parameter Name="selectClause" Type="System.String" />
        <Parameter Name="expandClause" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterClause">フィルター句。</param>
        <param name="selectClause">select 句。</param>
        <param name="expandClause">展開句。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" />指定した句を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandClause">
      <MemberSignature Language="C#" Value="public string ExpandClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpandClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandClause As String" />
      <MemberSignature Language="F#" Value="member this.ExpandClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、OData は、句を展開します。 取得するメインのエンティティの関連付けられているエンティティを取得するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これは省略可能な OData $ 式の文字列を展開して<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(OData の仕様を参照してください)</a>です。
            関連付けられているエンティティを含むプロパティは、ExpandClause に含まれている場合を除き、null になります。
            具体的には、一覧に、実行する場合を取得または更新を指定しないと、ExpandClause 関連付けられているエンティティのすべてのプロパティは null になります。  たとえばを実行する場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />せず、ExpandClause 操作、<see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" />プロパティは null になります。  Statistics プロパティを設定するには、ExpandClause を指定する必要があります<c>stats</c>です。個々 のクラスのマニュアルを参照するプロパティが関連付けられているエンティティと見なされますを参照してください。</para>
          <para>両方、ExpandClause を指定する場合、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />、ExpandClause に表示されるプロパティは、(サービスの応答、SelectClause に示したプロパティのみが含まれている) ために、SelectClause で繰り返す必要があります。  (この要件はありません、SelectClause が指定されていない場合ことを意味 'が含まれるためすべてのプロパティで応答します ')</para>
          <para>展開は、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</para>
          <para>既定ではない式、つまり、関連付けられているオブジェクトは返されませんを展開して (および対応するプロパティが null)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterClause">
      <MemberSignature Language="C#" Value="public string FilterClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterClause As String" />
      <MemberSignature Language="F#" Value="member this.FilterClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OData フィルター句を設定します。 指定した条件に一致する項目を一覧表示操作を制限するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これは省略可能な OData $filter 式の文字列<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(OData の仕様を参照してください)</a>です。
            たとえば、制限することができます、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />を式にアクティブなプールのみを返す操作<c>状態 eq 'アクティブ'</c>です。</para>
          <para>フィルターは、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</para>
          <para>既定値には、フィルター式は、すべてのリソースが返されることを意味はありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectClause">
      <MemberSignature Language="C#" Value="public string SelectClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelectClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectClause As String" />
      <MemberSignature Language="F#" Value="member this.SelectClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OData select 句を設定します。 すべてのオブジェクトのプロパティではなく特定のプロパティだけを取得するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これは省略可能な OData $select 式の文字列<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(OData の仕様を参照してください)</a>です。
            SelectClause を提供する場合<b>のみ</b>その句のリストにプロパティが設定されてです。 その他のプロパティに既定値 (通常 null)。  実行する場合など、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />の SelectClause で操作<c>id、displayName</c>、し、各<see cref="T:Microsoft.Azure.Batch.CloudPool" />がその<see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />が作成されますが、プロパティ、などその他のプロパティ<see cref="P:Microsoft.Azure.Batch.CloudPool.State" />は取得されませんし、その結果、既定値 (通常 null) が与えられます。</para>
          <para>含まれていませんまたは複数のプロパティを一意になる SelectClause を指定したオブジェクトの識別、ときに、エンティティが取得された場合は (一覧を取得または更新) 経由で (通常、Id プロパティが、<see cref="T:Microsoft.Azure.Batch.Certificate" />サムプリントと ThumbprintAlgorithm次に データの取得や操作を実行するバッチ サービスにアクセスするすべてのメソッドは失敗します。
            これには、オブジェクトのほとんどのメソッドが含まれますなど<see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />と<see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。
            (ただし、SelectClause に含まれているプロパティのみが設定されます) プロパティにアクセスすることができます。</para>
          <para>選択内容は、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</para>
          <para>既定値には、select 式は、すべてのプロパティが返されることを意味はありません。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>