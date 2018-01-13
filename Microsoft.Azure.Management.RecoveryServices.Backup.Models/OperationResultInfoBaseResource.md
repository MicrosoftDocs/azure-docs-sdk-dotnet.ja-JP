<Type Name="OperationResultInfoBaseResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource">
  <TypeSignature Language="C#" Value="public class OperationResultInfoBaseResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationResultInfoBaseResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationResultInfoBaseResource&#xA;Inherits OperationWorkerResponse" />
  <TypeSignature Language="F#" Value="type OperationResultInfoBaseResource = class&#xA;    inherit OperationWorkerResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            情報を結果の操作の基本クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResultInfoBaseResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationResultInfoBaseResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResultInfoBaseResource (Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; headers = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase operation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; headers, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.#ctor(System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional statusCode As Nullable(Of HttpStatusCode) = null, Optional headers As IDictionary(Of String, IList(Of String)) = null, Optional operation As OperationResultInfoBase = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource (statusCode, headers, operation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statusCode" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
        <Parameter Name="operation" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase" />
      </Parameters>
      <Docs>
        <param name="statusCode">操作の HTTP ステータス コード。
            使用可能な値が含まれます: 'Continue'、'SwitchingProtocols'、'OK'、'を作成'、'許可'、'NonAuthoritativeInformation'、'NoContent'、'ResetContent'、'PartialContent'、'MultipleChoices'、'あいまいな'、'MovedPermanently'、'移動' は、'が見つかりました'、'リダイレクト '、'SeeOther'、'RedirectMethod'、'NotModified'、'UseProxy'、'未使用'、'TemporaryRedirect'、'RedirectKeepVerb'、'BadRequest'、'承認されていない'、'PaymentRequired'、'は許可されていません'、'NotFound'、'MethodNotAllowed'、'NotAcceptable'、'ProxyAuthenticationRequired'、'RequestTimeout'、'競合'、'なくなり'、'LengthRequired'、'PreconditionFailed'、'RequestEntityTooLarge'、'RequestUriTooLong'、'UnsupportedMediaType'、'RequestedRangeNotSatisfiable'、'ExpectationFailed'、'UpgradeRequired'、'InternalServerError'、'NotImplemented'、'BadGateway'、'ServiceUnavailable'、'GatewayTimeout'、'HttpVersionNotSupported'</param>
        <param name="headers">この操作に関連付けられている HTTP ヘッダー。</param>
        <param name="operation">OperationResultInfoBaseResource 操作</param>
        <summary>
            OperationResultInfoBaseResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As OperationResultInfoBase" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 operationResultInfoBaseResource 操作
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>