<Type Name="SearchCredentials" FullName="Microsoft.Azure.Search.SearchCredentials">
  <TypeSignature Language="C#" Value="public class SearchCredentials : Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchCredentials extends Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SearchCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchCredentials&#xA;Inherits ServiceClientCredentials" />
  <TypeSignature Language="F#" Value="type SearchCredentials = class&#xA;    inherit ServiceClientCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClientCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Search サービスへの認証に使用する資格情報。
            <see href="https://docs.microsoft.com/rest/api/searchservice/" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchCredentials (string apiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string apiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (apiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchCredentials : string -&gt; Microsoft.Azure.Search.SearchCredentials" Usage="new Microsoft.Azure.Search.SearchCredentials apiKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="apiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiKey">api キーを Azure Search サービスを認証するために使用します。</param>
        <summary>
            クエリまたは管理者キーで SearchCredentials クラスの新しいインスタンスを初期化します。 アプリケーションに検索サービスまたはインデックスへの書き込みアクセスが必要としない場合は、クエリ キーを使用します。
            </summary>
        <remarks>
            クエリ キーを渡すことをお勧め、アプリケーションでは、インデックスに対してのみクエリ操作を実行する場合、<paramref name="apiKey" />パラメーター。 これにより、インデックスには、最低限の特権の原則を一貫性のある読み取り専用のアクセスを使用しています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchCredentials.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string" Usage="Microsoft.Azure.Search.SearchCredentials.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            api キーを Azure Search サービスを認証するために使用します。 のみ、クエリを実行するためのクエリ キーまたはインデックスとドキュメント管理機能もできるように管理者キーのいずれかを指定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessHttpRequestAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task ProcessHttpRequestAsync (System.Net.Http.HttpRequestMessage request, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task ProcessHttpRequestAsync(class System.Net.Http.HttpRequestMessage request, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchCredentials.ProcessHttpRequestAsync(System.Net.Http.HttpRequestMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ProcessHttpRequestAsync : System.Net.Http.HttpRequestMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="searchCredentials.ProcessHttpRequestAsync (request, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="request">HTTP 要求</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            指定された HTTP 要求に資格情報を追加します。
            </summary>
        <returns>非同期操作の進行状況を追跡するタスクです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>