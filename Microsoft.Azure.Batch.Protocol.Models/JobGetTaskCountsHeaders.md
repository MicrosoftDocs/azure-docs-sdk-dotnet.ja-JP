<Type Name="JobGetTaskCountsHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders">
  <TypeSignature Language="C#" Value="public class JobGetTaskCountsHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobGetTaskCountsHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class JobGetTaskCountsHeaders" />
  <TypeSignature Language="F#" Value="type JobGetTaskCountsHeaders = class" />
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
            <span data-ttu-id="d3a5f-101">GetTaskCounts 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-101">Defines headers for GetTaskCounts operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobGetTaskCountsHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.#ctor" />
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
            <span data-ttu-id="d3a5f-102">JobGetTaskCountsHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-102">Initializes a new instance of the JobGetTaskCountsHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobGetTaskCountsHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders (clientRequestId, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="d3a5f-103">クライアント要求 id 要求時にクライアントによって指定します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-103">The client-request-id provided by the client during the request.</span></span> <span data-ttu-id="d3a5f-104">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-104">This will be returned only if the return-client-request-id parameter was set to true.</span></span></param>
        <param name="requestId"><span data-ttu-id="d3a5f-105">バッチ サービスに対して行った要求に対して一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-105">A unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="d3a5f-106">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-106">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="d3a5f-107">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-107">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span></param>
        <summary>
            <span data-ttu-id="d3a5f-108">JobGetTaskCountsHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-108">Initializes a new instance of the JobGetTaskCountsHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.ClientRequestId" />
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
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3a5f-109">取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-109">Gets or sets the client-request-id provided by the client during the request.</span></span> <span data-ttu-id="d3a5f-110">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-110">This will be returned only if the return-client-request-id parameter was set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders.RequestId" />
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
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3a5f-111">取得または設定が、バッチ サービスに行われた要求の一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-111">Gets or sets a unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="d3a5f-112">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-112">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="d3a5f-113">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="d3a5f-113">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>