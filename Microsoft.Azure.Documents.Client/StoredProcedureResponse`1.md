<Type Name="StoredProcedureResponse&lt;TValue&gt;" FullName="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public class StoredProcedureResponse&lt;TValue&gt; : Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StoredProcedureResponse`1&lt;TValue&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1&lt;!TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Class StoredProcedureResponse(Of TValue)&#xA;Implements IStoredProcedureResponse(Of TValue)" />
  <TypeSignature Language="F#" Value="type StoredProcedureResponse&lt;'Value&gt; = class&#xA;    interface IStoredProcedureResponse&lt;'Value&gt;" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IStoredProcedureResponse&lt;TValue&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
    <summary>
            Azure Cosmos DB サービスのデータベースのストアド プロシージャから返された応答を表します。 応答本文とヘッダーをラップします。
            </summary>
    <remarks>
            ストアド プロシージャは、getContext().getResponse().setBody() メソッドを使用して、文字列の出力を返すことができます。
            この応答本文には、シリアル化された JSON オブジェクトでは、またはその他の種類があります。
            .NET SDK 内には、TValue、対応する型に、応答を逆シリアル化できます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoredProcedureResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            Cosmos DB の Azure サービスで目的のモックに公開されているコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public string ActivityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityId : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ActivityId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ActivityId</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスからの要求のアクティビティ ID を取得します。
            </summary>
        <value>
            要求のアクティビティ ID。
            </value>
        <remarks>グローバルに一意の ID を持つすべての要求をトレースします。 アプリケーション エラーのトレースに、および Azure Cosmos DB サポートに問い合わせて、アクティビティ ID を含める</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentResourceQuotaUsage">
      <MemberSignature Language="C#" Value="public string CurrentResourceQuotaUsage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentResourceQuotaUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.CurrentResourceQuotaUsage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentResourceQuotaUsage As String" />
      <MemberSignature Language="F#" Value="member this.CurrentResourceQuotaUsage : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.CurrentResourceQuotaUsage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.CurrentResourceQuotaUsage</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスから、コレクション内で各リソースの種類の使用法を含んでいる区切られた文字列を取得します。
            </summary>
        <value>コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRUPerMinuteUsed">
      <MemberSignature Language="C#" Value="public bool IsRUPerMinuteUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRUPerMinuteUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.IsRUPerMinuteUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRUPerMinuteUsed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRUPerMinuteUsed : bool" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.IsRUPerMinuteUsed" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB からの応答に関連付けられているフラグの要求単位 (Ru) からこのストアド プロシージャ要求が処理されるかどうかをサービス/か、容量を分単位を取得します。
            </summary>
        <value>
            この要求が 1 分あたりの RUs 容量から提供された場合は true。 それ以外の場合は false です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResourceQuota">
      <MemberSignature Language="C#" Value="public string MaxResourceQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxResourceQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.MaxResourceQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResourceQuota As String" />
      <MemberSignature Language="F#" Value="member this.MaxResourceQuota : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.MaxResourceQuota" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.MaxResourceQuota</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスから、コレクション内で各リソースの種類のクォータを含んでいる区切られた文字列を取得します。
            </summary>
        <value>コレクション内のリソースの種類ごとに使用される単位数を含んでいる区切られた文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator TValue (Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt; source);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname !TValue op_Implicit(class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!TValue&gt; source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.op_Implicit(Microsoft.Azure.Documents.Client.StoredProcedureResponse{`0})~`0" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (source As StoredProcedureResponse(Of TValue)) As TValue" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt; -&gt; 'Value" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.op_Implicit source" />
      <MemberType>Method</MemberType>
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
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="source">ストアド プロシージャの応答です。</param>
        <summary>
            Azure Cosmos DB サービスから暗黙的にリソースを取得します。
            </summary>
        <returns>返されたリソースです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCharge">
      <MemberSignature Language="C#" Value="public double RequestCharge { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 RequestCharge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.RequestCharge" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestCharge As Double" />
      <MemberSignature Language="F#" Value="member this.RequestCharge : double" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.RequestCharge" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.RequestCharge</InterfaceMember>
      </Implements>
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
            正規化された Azure Cosmos DB 要求ユニット (Ru) Azure Cosmos DB サービスからの課金の数を取得します。
            </summary>
        <value>
            正規化された Azure Cosmos DB 要求ユニット (Ru) の数が課金されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public TValue Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As TValue" />
      <MemberSignature Language="F#" Value="member this.Response : 'Value" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.Response" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.Response</InterfaceMember>
      </Implements>
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
            ストアド プロシージャは、Azure Cosmos DB サービスから指定された型にシリアル化の応答を取得します。
            </summary>
        <value>指定された型にシリアル化し、ストアド プロシージャの応答です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ResponseHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ResponseHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ResponseHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaders As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaders : System.Collections.Specialized.NameValueCollection" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ResponseHeaders" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ResponseHeaders</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスからの応答に関連付けられたヘッダーを取得します。
            </summary>
        <value>
            応答に関連付けられたヘッダー。
            </value>
        <remarks>
            Azure Cosmos DB API から返されたすべての HTTP 応答ヘッダーへのアクセスを提供します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLog">
      <MemberSignature Language="C#" Value="public string ScriptLog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ScriptLog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScriptLog As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLog : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.ScriptLog" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.ScriptLog</InterfaceMember>
      </Implements>
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
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.SessionToken" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.SessionToken</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスから、トークンを整合性要求セッションで使用するために取得します。
            </summary>
        <value>
            セッションの整合性の要求で使用するためのトークンです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode" Usage="Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;.StatusCode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IStoredProcedureResponse`1.StatusCode</InterfaceMember>
      </Implements>
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
            Azure Cosmos DB サービスからの要求の完了ステータス コードを取得します。
            </summary>
        <value>要求の完了ステータス コード</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>