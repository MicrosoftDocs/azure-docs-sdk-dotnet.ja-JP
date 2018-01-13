<Type Name="LogRecord" FullName="Microsoft.WindowsAzure.Storage.Analytics.LogRecord">
  <TypeSignature Language="C#" Value="public class LogRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit LogRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class LogRecord" />
  <TypeSignature Language="F#" Value="type LogRecord = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Storage Analytics のログ エントリを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求が共有キーまたは共有アクセス署名 (SAS)、によって認証されたかが匿名かどうかを示します。
            </summary>
        <value>A<see cref="T:System.String" />認証スキームを示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列として要求に含まれる、x ms-クライアントの要求 id ヘッダーの値。
            </summary>
        <value>A<see cref="T:System.String" />を含むクライアント要求 id です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConditionsUsed">
      <MemberSignature Language="C#" Value="public string ConditionsUsed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConditionsUsed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ConditionsUsed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConditionsUsed As String" />
      <MemberSignature Language="F#" Value="member this.ConditionsUsed : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ConditionsUsed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            セミコロンで区切られた一覧は、ConditionName の形式でエンコードされた文字列としての値を =。
            </summary>
        <value>A<see cref="T:System.String" />要求に対して使用される条件を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndToEndLatency">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; EndToEndLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; EndToEndLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.EndToEndLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndToEndLatency As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.EndToEndLatency : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.EndToEndLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            読み取り要求を受信し、要求元に応答を送信するために必要な時間も含めて、要求された操作を実行するミリ秒単位の時間の合計。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />エンド ツー エンドの待機時間、操作を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETagIdentifier">
      <MemberSignature Language="C#" Value="public string ETagIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETagIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ETagIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETagIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.ETagIdentifier : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ETagIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列として返されるオブジェクトの ETag 識別子。
            </summary>
        <value>A<see cref="T:System.String" />リソースの ETag が含まれています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public string HttpStatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatusCode As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の HTTP ステータス コード。 要求が中断された場合は、"不明"にこの値を設定することがあります。
            </summary>
        <value>A <see cref="T:System.String" /> HTTP ステータス コードを含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最終更新日時 (LMT) でエンコードされた文字列として返されるオブジェクトの。 このフィールドは<c>null</c>を複数のオブジェクトを返す操作。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />最終更新時刻を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; OperationCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; OperationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.OperationCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス 0 から始まる、要求のログ記録操作の数。 いくつかの要求に Copy Blob など、複数の操作が必要なは、ほとんどが 1 つの操作を実行します。
            </summary>
        <value>操作数を格納する整数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public string OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As String" />
      <MemberSignature Language="F#" Value="member this.OperationType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            REST 操作の種類を実行します。 
            </summary>
        <value>A<see cref="T:System.String" />操作の種類を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OwnerAccountName">
      <MemberSignature Language="C#" Value="public string OwnerAccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OwnerAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OwnerAccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OwnerAccountName As String" />
      <MemberSignature Language="F#" Value="member this.OwnerAccountName : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.OwnerAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスの所有者のアカウント名。
            </summary>
        <value>A<see cref="T:System.String" />ストレージ アカウントの名前を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReferrerHeader">
      <MemberSignature Language="C#" Value="public string ReferrerHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReferrerHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ReferrerHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReferrerHeader As String" />
      <MemberSignature Language="F#" Value="member this.ReferrerHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ReferrerHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列として参照元のヘッダーの値。
            </summary>
        <value>A <see cref="T:System.String" /> Referrer ヘッダーの値を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestContentLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestContentLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestContentLength : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ サービスに送信される要求のコンテンツ長のヘッダーの値。 要求が成功した、この値は要求パケット サイズに等しくなります。 要求が成功した、この値を要求パケットのサイズと同じにすることができないか可能性がある場合<c>null</c>です。
            </summary>
        <value>要求のコンテンツ長 (バイト単位) を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedObjectKey">
      <MemberSignature Language="C#" Value="public string RequestedObjectKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedObjectKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestedObjectKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedObjectKey As String" />
      <MemberSignature Language="F#" Value="member this.RequestedObjectKey : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestedObjectKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列として、要求されたオブジェクトのキー。 このフィールドでは、カスタム ドメイン名が構成されている場合でも、アカウント名は常に使用します。
            </summary>
        <value><see cref="T:System.String" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequesterAccountName">
      <MemberSignature Language="C#" Value="public string RequesterAccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequesterAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterAccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequesterAccountName As String" />
      <MemberSignature Language="F#" Value="member this.RequesterAccountName : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求元である、共有キーを使用して、要求が認証されている場合、ストレージ アカウントの名前。 このフィールドは<c>null</c>匿名の要求および共有アクセス署名 (SAS) を使用して行われた要求。
            </summary>
        <value>A<see cref="T:System.String" />ストレージ アカウントの名前を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequesterIPAddress">
      <MemberSignature Language="C#" Value="public string RequesterIPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequesterIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequesterIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RequesterIPAddress : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequesterIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ポート番号を含む、要求者の IP アドレス。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestHeaderSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestHeaderSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestHeaderSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestHeaderSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestHeaderSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestHeaderSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestHeaderSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            (バイト単位)、要求ヘッダーのサイズ。 この値は、要求が成功した場合は、 <c>null</c>です。
            </summary>
        <value>要求ヘッダーのサイズを表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestIdHeader">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestIdHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestIdHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestIdHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestIdHeader As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestIdHeader : Nullable&lt;Guid&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestIdHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ サービスによって割り当てられている要求 ID。 これは、x ms 要求 id ヘッダーの値に相当します。
            </summary>
        <value>A<see cref="T:System.Guid" />要求 ID を含む</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestMD5">
      <MemberSignature Language="C#" Value="public string RequestMD5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestMD5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestMD5 As String" />
      <MemberSignature Language="F#" Value="member this.RequestMD5 : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Content-md5 ヘッダーまたはエンコードされた文字列として要求に x ms-content-md5 ヘッダーのいずれかの値。
            このフィールドで指定された MD5 ハッシュ値は、要求のコンテンツを表します。 このフィールドは、 <c>null</c>です。
            </summary>
        <value>A<see cref="T:System.String" />要求 MD5 値を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestPacketSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestPacketSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestPacketSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestPacketSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestPacketSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestPacketSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestPacketSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            (バイト単位)、ストレージ サービスによって読み取られた要求パケットのサイズ。 この値は、要求が成功した場合は、 <c>null</c>です。
            </summary>
        <value>要求のパケット サイズを表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; RequestStartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; RequestStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.RequestStartTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            UTC 形式では、サービスで要求を受信した時刻。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />開始時刻を要求を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestStatus">
      <MemberSignature Language="C#" Value="public string RequestStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestStatus As String" />
      <MemberSignature Language="F#" Value="member this.RequestStatus : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求された操作の状態。
            </summary>
        <value>A<see cref="T:System.String" />要求の状態を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestUrl">
      <MemberSignature Language="C#" Value="public Uri RequestUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri RequestUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestUrl As Uri" />
      <MemberSignature Language="F#" Value="member this.RequestUrl : Uri" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の完全な URL。
            </summary>
        <value><see cref="T:System.Uri" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestVersionHeader">
      <MemberSignature Language="C#" Value="public string RequestVersionHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestVersionHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestVersionHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestVersionHeader As String" />
      <MemberSignature Language="F#" Value="member this.RequestVersionHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.RequestVersionHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            記憶域サービスのバージョンでは、要求が行われたときを指定します。 これは、x-ms-version ヘッダーの値と等価です。
            </summary>
        <value>A<see cref="T:System.String" />要求バージョン ヘッダーを含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseHeaderSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ResponseHeaderSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ResponseHeaderSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponseHeaderSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseHeaderSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ResponseHeaderSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponseHeaderSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バイト単位で、応答ヘッダーのサイズ。 この値は、要求が成功した場合は、 <c>null</c>です。
            </summary>
        <value>バイト単位で、応答ヘッダーのサイズを表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponsePacketSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ResponsePacketSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ResponsePacketSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponsePacketSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponsePacketSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ResponsePacketSize : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ResponsePacketSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            (バイト単位)、ストレージ サービスによって書き込まれた応答パケットのサイズ。 この値は、要求が成功した場合は、 <c>null</c>です。
            </summary>
        <value>応答のヘッダー、バイトのパケット サイズを表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerLatency">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerLatency As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerLatency : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求された操作を実行するミリ秒単位の時間の合計。 この値は、ネットワーク待機時間 (読み取り要求を受信し、要求元に応答を送信するために必要な時間) には含まれません。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />操作のサーバー待機時間を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerMD5">
      <MemberSignature Language="C#" Value="public string ServerMD5 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerMD5" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerMD5 As String" />
      <MemberSignature Language="F#" Value="member this.ServerMD5 : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServerMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列として、ストレージ サービスによって計算された MD5 ハッシュの値。
            </summary>
        <value>A <see cref="T:System.String" /> server MD5 ハッシュを含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceType">
      <MemberSignature Language="C#" Value="public string ServiceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServiceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceType As String" />
      <MemberSignature Language="F#" Value="member this.ServiceType : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.ServiceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求の作成対象となる記憶域サービス: blob、テーブル、またはキュー。
            </summary>
        <value>A<see cref="T:System.String" />どのサービスに対する要求が行われたことを示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentHeader">
      <MemberSignature Language="C#" Value="public string UserAgentHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.UserAgentHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserAgentHeader As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentHeader : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.UserAgentHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンコードされた文字列としてユーザー エージェントのヘッダーの値。
            </summary>
        <value>A <see cref="T:System.String" /> User-agent ヘッダーの値を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionNumber">
      <MemberSignature Language="C#" Value="public string VersionNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.LogRecord.VersionNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionNumber As String" />
      <MemberSignature Language="F#" Value="member this.VersionNumber : string" Usage="Microsoft.WindowsAzure.Storage.Analytics.LogRecord.VersionNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Storage Analytics Logging のバージョンは、エントリの記録を使用します。
            </summary>
        <value>A<see cref="T:System.String" />バージョン番号を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>