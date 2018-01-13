<Type Name="FileGetPropertiesFromTaskHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders">
  <TypeSignature Language="C#" Value="public class FileGetPropertiesFromTaskHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetPropertiesFromTaskHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetPropertiesFromTaskHeaders" />
  <TypeSignature Language="F#" Value="type FileGetPropertiesFromTaskHeaders = class&#xA;    interface IProtocolNodeFile" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            GetPropertiesFromTask 操作のヘッダーを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromTaskHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.#ctor" />
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
            FileGetPropertiesFromTaskHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromTaskHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; ocpCreationTime = null, Nullable&lt;bool&gt; ocpBatchFileIsdirectory = null, string ocpBatchFileUrl = null, string ocpBatchFileMode = null, string contentType = null, Nullable&lt;long&gt; contentLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpCreationTime, valuetype System.Nullable`1&lt;bool&gt; ocpBatchFileIsdirectory, string ocpBatchFileUrl, string ocpBatchFileMode, string contentType, valuetype System.Nullable`1&lt;int64&gt; contentLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional ocpCreationTime As Nullable(Of DateTime) = null, Optional ocpBatchFileIsdirectory As Nullable(Of Boolean) = null, Optional ocpBatchFileUrl As String = null, Optional ocpBatchFileMode As String = null, Optional contentType As String = null, Optional contentLength As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders (clientRequestId, requestId, eTag, lastModified, ocpCreationTime, ocpBatchFileIsdirectory, ocpBatchFileUrl, ocpBatchFileMode, contentType, contentLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpCreationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpBatchFileIsdirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpBatchFileUrl" Type="System.String" />
        <Parameter Name="ocpBatchFileMode" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="contentLength" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="clientRequestId">クライアント要求 id 要求時にクライアントによって指定します。 これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</param>
        <param name="requestId">バッチ サービスに対して行った要求に対して一意の識別子。 要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。 レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</param>
        <param name="eTag">ETag HTTP 応答ヘッダー。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</param>
        <param name="lastModified">リソースの最終更新日時。</param>
        <param name="ocpCreationTime">ファイルの作成時刻。</param>
        <param name="ocpBatchFileIsdirectory">かどうか、オブジェクトは、ディレクトリを表します。</param>
        <param name="ocpBatchFileUrl">ファイルの URL です。</param>
        <param name="ocpBatchFileMode">8 進数形式でファイル モード属性です。</param>
        <param name="contentType">ファイルのコンテンツの種類。</param>
        <param name="contentLength">ファイルの長さ。</param>
        <summary>
            FileGetPropertiesFromTaskHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="client-request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。 これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContentLength : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ContentLength" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentLength</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルの長さを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ContentType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentType</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルのコンテンツの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ETag HTTP 応答ヘッダーを設定します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.LastModified" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.LastModified</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Last-Modified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースが最後に変更された時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileIsdirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OcpBatchFileIsdirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OcpBatchFileIsdirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileIsdirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileIsdirectory : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileIsdirectory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-isdirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオブジェクトがディレクトリを表すかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileMode">
      <MemberSignature Language="C#" Value="public string OcpBatchFileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileMode As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 8 進数形式でファイル モード属性を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileUrl">
      <MemberSignature Language="C#" Value="public string OcpBatchFileUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileUrl As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpBatchFileUrl" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileUrl</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpCreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpCreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpCreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpCreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpCreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpCreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.OcpCreationTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpCreationTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-creation-time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル作成時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromTaskHeaders.RequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.RequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が、バッチ サービスに行われた要求の一意の識別子。 要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。 レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>