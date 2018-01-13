<Type Name="ApplicationQueryDescription" FullName="System.Fabric.Description.ApplicationQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationQueryDescription = class" />
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
      <para>使用されるクエリの入力を表す<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationDefinitionKindFilter ApplicationDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationDefinitionKindFilter As ApplicationDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationDefinitionKindFilter : System.Fabric.Description.ApplicationDefinitionKindFilter with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定の定義の種類が返されるアプリケーションをフィルター処理するために使用します。
            </para>
        </summary>
        <value>
          <para>定義の種類をアプリケーションをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para>ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</para>
          <para>フィルターが指定されていない場合に適しているのページのすべてのアプリケーションが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはクエリを実行するアプリケーションの URI 名を設定します。</para>
        </summary>
        <value>
          <para>クエリの実行にアプリケーションの URI 名です。</para>
        </value>
        <remarks>
          <para>ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</para>
          <para>フィルターが指定されていない場合、ページに合わせてすべてのアプリケーションが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ApplicationTypeNameFilter" />
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
          <para>取得またはクエリを実行するアプリケーションをフィルター処理するために使用するアプリケーションの種類名を設定します。
            このアプリケーションの種類は、アプリケーションが返されます。</para>
        </summary>
        <value>
          <para>アプリケーションの種類名はクエリを実行するアプリケーションをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para>ApplicationNameFilter、ApplicationTypeNameFilter、または ApplicationDefinitionKindFilter の 1 つを指定することができます。</para>
          <para>フィルターが指定されていない場合、ページに合わせてすべてのアプリケーションが返されます。</para>
          <para>このフィルターは、大文字小文字を区別します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ContinuationToken" />
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
          <para>取得または次のページを取得するクエリで使用できるトークンを設定します。</para>
        </summary>
        <value>
          <para>次のページを取得するクエリで使用できるトークンです。</para>
        </value>
        <remarks>
          <para>ContinuationToken は、前のクエリによって受信されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.ApplicationQueryDescription.ExcludeApplicationParameters" />
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
          <para>取得またはアプリケーションのパラメーターを結果から除外するかどうかを指定するフラグを設定します。</para>
        </summary>
        <value>
          <para>アプリケーションのパラメーターを結果から除外するかどうかを指定するフラグ。</para>
        </value>
        <remarks>
          <para>このフラグは、パラメーターが大きなサイズの結果を制限するためには、true に設定することができます。
            既定値は false です。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>