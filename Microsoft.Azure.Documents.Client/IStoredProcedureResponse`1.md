<Type Name="IStoredProcedureResponse&lt;TValue&gt;" FullName="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IStoredProcedureResponse&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStoredProcedureResponse`1&lt;TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStoredProcedureResponse(Of TValue)" />
  <TypeSignature Language="F#" Value="type IStoredProcedureResponse&lt;'Value&gt; = interface" />
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
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
    <summary>
            Azure Cosmos DB サービスの目的をモックに公開されるインターフェイス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ActivityId" />
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
        <remarks>グローバルに一意の ID を持つすべての要求をトレースします。 アプリケーション エラーのトレースに、および Azure Cosmos DB サポートに問い合わせて、アクティビティ ID が含まれます。
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.CurrentResourceQuotaUsage" />
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
            コレクション内で各リソースの種類の使用法を含んでいる区切られた文字列を取得します。
            </summary>
        <value>コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.MaxResourceQuota" />
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
            コレクション内で各リソースの種類のクォータを含んでいる区切られた文字列を取得します。
            </summary>
        <value>コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.RequestCharge" />
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
            課金正規化された要求ユニット (Ru) の数を取得します。
            </summary>
        <value>
            正規化された要求ユニット (Ru) の数が課金されます。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public TValue Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As TValue" />
      <MemberSignature Language="F#" Value="member this.Response : 'Value" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.Response" />
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
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定された型にシリアル化し、ストアド プロシージャの応答を取得します。
            </summary>
        <value>指定された型にシリアル化し、ストアド プロシージャの応答です。</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ResponseHeaders" />
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
            応答に関連付けられたヘッダーを取得します。
            </summary>
        <value>
            応答に関連付けられたヘッダー。
            </value>
        <remarks>
            Azure Cosmos DB API から返されたすべての HTTP 応答ヘッダーへのアクセスを提供します。
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLog">
      <MemberSignature Language="C#" Value="public string ScriptLog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ScriptLog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScriptLog As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLog : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.ScriptLog" />
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
            ストアド プロシージャから console.log() ステートメントの出力を取得します。
            </summary>
        <value>
            ストアド プロシージャで console.log() ステートメントからの出力。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.SessionToken" />
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
            セッションの整合性の要求で使用するためには、トークンを取得します。
            </summary>
        <value>
            セッションの整合性の要求で使用するためのトークンです。
            </value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;'Value&gt;.StatusCode" />
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
            要求の完了ステータス コードを取得します。
            </summary>
        <value>要求の完了ステータス コード</value>
        <remarks>
            これは、Azure Cosmos DB サービスの目的をモックに公開されます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>