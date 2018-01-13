<Type Name="OperationWorkerResponse" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse">
  <TypeSignature Language="C#" Value="public class OperationWorkerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationWorkerResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationWorkerResponse" />
  <TypeSignature Language="F#" Value="type OperationWorkerResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、結果の操作応答の基本クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationWorkerResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationWorkerResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationWorkerResponse (Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; headers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; headers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.#ctor(System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional statusCode As Nullable(Of HttpStatusCode) = null, Optional headers As IDictionary(Of String, IList(Of String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse (statusCode, headers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statusCode" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="statusCode">操作の HTTP ステータス コード。
            使用可能な値が含まれます: 'Continue'、'SwitchingProtocols'、'OK'、'を作成'、'許可'、'NonAuthoritativeInformation'、'NoContent'、'ResetContent'、'PartialContent'、'MultipleChoices'、'あいまいな'、'MovedPermanently'、'移動' は、'が見つかりました'、'リダイレクト '、'SeeOther'、'RedirectMethod'、'NotModified'、'UseProxy'、'未使用'、'TemporaryRedirect'、'RedirectKeepVerb'、'BadRequest'、'承認されていない'、'PaymentRequired'、'は許可されていません'、'NotFound'、'MethodNotAllowed'、'NotAcceptable'、'ProxyAuthenticationRequired'、'RequestTimeout'、'競合'、'なくなり'、'LengthRequired'、'PreconditionFailed'、'RequestEntityTooLarge'、'RequestUriTooLong'、'UnsupportedMediaType'、'RequestedRangeNotSatisfiable'、'ExpectationFailed'、'UpgradeRequired'、'InternalServerError'、'NotImplemented'、'BadGateway'、'ServiceUnavailable'、'GatewayTimeout'、'HttpVersionNotSupported'</param>
        <param name="headers">この操作に関連付けられている HTTP ヘッダー。</param>
        <summary>
            OperationWorkerResponse クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, IList(Of String))" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの操作に関連付けられている HTTP ヘッダーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Nullable(Of HttpStatusCode)" />
      <MemberSignature Language="F#" Value="member this.StatusCode : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作の HTTP ステータス コード。 使用可能な値が含まれます: 'Continue'、'SwitchingProtocols'、'OK'、'を作成'、'許可'、'NonAuthoritativeInformation'、'NoContent'、'ResetContent'、'PartialContent'、'MultipleChoices'、'あいまいな'、'MovedPermanently'、'移動' は、'が見つかりました'、'リダイレクト '、'SeeOther'、'RedirectMethod'、'NotModified'、'UseProxy'、'未使用'、'TemporaryRedirect'、'RedirectKeepVerb'、'BadRequest'、'承認されていない'、'PaymentRequired'、'は許可されていません'、'NotFound'、'MethodNotAllowed'、'NotAcceptable'、'ProxyAuthenticationRequired'、'RequestTimeout'、'競合'、'なくなり'、'LengthRequired'、'PreconditionFailed'、'RequestEntityTooLarge'、'RequestUriTooLong'、'UnsupportedMediaType'、'RequestedRangeNotSatisfiable'、'ExpectationFailed'、'UpgradeRequired'、'InternalServerError'、'NotImplemented'、'BadGateway'、'ServiceUnavailable'、'GatewayTimeout'、'HttpVersionNotSupported'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>