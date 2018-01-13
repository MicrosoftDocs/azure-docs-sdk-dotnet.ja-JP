<Type Name="PagedApplicationTypeQueryDescription" FullName="System.Fabric.Description.PagedApplicationTypeQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedApplicationTypeQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="F#" Value="type PagedApplicationTypeQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クエリを実行するときに使用されるフィルターのセットを示す<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。</para>
    </summary>
    <remarks>
      <para>このクエリの説明の既定値は、結果が最初のページから返され、フィルターは適用されませんを確認します。
            このクエリの説明は、個々 のプロパティを設定してカスタマイズできます。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedApplicationTypeQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeDefinitionKindFilter As ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKindFilter : System.Fabric.Description.ApplicationTypeDefinitionKindFilter with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定の定義の種類が返されるアプリケーションの種類をフィルター処理するために使用します。
            </para>
        </summary>
        <value>
          <para>定義の種類をアプリケーションの種類をフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para>ApplicationTypeDefinitionKindFilter が指定されていない場合、結果は定義の種類によってフィルターされません。</para>
          <para>ApplicationTypeNameFilter と ApplicationTypeDefinitionKindFilter を同時に指定するはありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定の詳細を取得するアプリケーションの種類。</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            既定値は null の場合、すべてのアプリケーションの種類と一致しています。
            </para>
          <para>
            このパラメーターは、プロビジョニングまたはプロビジョニングのアプリケーションのすべての種類のアプリケーション マニフェストで定義されている大文字小文字を区別の正確なアプリケーションの種類名と一致します。 たとえば、"Test"の値と一致しません"TestApp"部分的な一致しかになっているためです。
            この値は、アプリケーションの種類のバージョンを含めることはできません、同じアプリケーションの種類名のすべてのバージョンと一致します。
            すべてのアプリケーションの種類がないを要求するには、この値を設定します。
            </para>
          <para>
            ApplicationTypeNameFilter と ApplicationTypeDefinitionKindFilter を同時に指定するはありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersionFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersionFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersionFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersionFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersionFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            取得または設定のアプリケーション タイプ バージョンの詳細を取得します。
            </para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            既定値は null の場合、すべてのアプリケーションに一致するバージョンの特定のアプリケーションの種類名を入力します。 アプリケーションの種類の名前フィルターも含まれている場合にのみ、このフィルターを指定する必要があります。
            </para>
          <para>
            このパラメーターは、すべてのアプリケーションのプロビジョニングまたはプロビジョニングの種類のアプリケーション マニフェストで定義されている大文字小文字を区別の正確なアプリケーション タイプ バージョンに対してと一致します。
            たとえば、"v1"バージョンと一致しませんバージョン"v1.0"部分的な一致しかになっているためです。
            アプリケーションの種類名のすべてのアプリケーション タイプ バージョンを要求するには、この値を設定しないでください。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または次のページを取得するために使用する継続トークンを設定します。</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            既定値は null の場合、クエリ結果のいずれかのページが返されます。
            </para>
          <para>
            フィルターを適用する結果が多すぎる場合、1 つのメッセージに収まらない可能性があります。
            コレクションを分割してこの問題に対応するページングが使用される<see cref="T:System.Fabric.Query.ApplicationType" />別のページにします。
            継続トークンが、前のページ、中断場所を知るため、クエリ自体にのみ意味を実行します。
            この値は、このクエリを実行してから生成するか、後続のページを取得するために、次のクエリ要求に渡すことができます。
            Null 以外の継続トークンの値は、後続のページがある場合にのみ、結果の一部として返されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアプリケーションのパラメーターをクエリ結果から除外するかどうかを設定します。</para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            既定値は false。
            </para>
          <para>
            この場合は true。 リーフに設定、<see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" />空白。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の数が最大<see cref="T:System.Fabric.Query.ApplicationType" />のページごとに返されることができます。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            既定値は long 型の最大値です。
            </para>
          <para>これは、アプリケーションの種類が返される、最小値ではない数の上限の境界のみを定義します。
            たとえば、ページが収まる最大で 1000 が返される場合構成では、最大メッセージ サイズの制限に従って項目が定義されてし、MaxResults 値に設定されている 2000 では、1000 を超える結果が返されます場合でも、2000 のアプリケーションの種類、クエリの説明に一致します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pagedApplicationTypeQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            クエリの説明のすべてのコンテンツを印刷する ToString() メソッドをオーバーライドします。
            </summary>
        <returns>
            クエリの説明のすべてのプロパティを含む文字列を返します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>