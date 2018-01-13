<Type Name="FileDeleteFromTaskHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders">
  <TypeSignature Language="C#" Value="public class FileDeleteFromTaskHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileDeleteFromTaskHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class FileDeleteFromTaskHeaders" />
  <TypeSignature Language="F#" Value="type FileDeleteFromTaskHeaders = class" />
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
            DeleteFromTask 操作のヘッダーを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDeleteFromTaskHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.#ctor" />
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
            FileDeleteFromTaskHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDeleteFromTaskHeaders (string clientRequestId = null, string requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientRequestId, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As String = null, Optional requestId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders (clientRequestId, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.String" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientRequestId">クライアント要求 id 要求時にクライアントによって指定します。 これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</param>
        <param name="requestId">バッチ サービスに対して行った要求に対して一意の識別子。 要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。 レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</param>
        <summary>
            FileDeleteFromTaskHeaders クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。 これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders.RequestId" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
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