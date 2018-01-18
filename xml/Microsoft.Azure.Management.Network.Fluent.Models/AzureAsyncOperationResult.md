<Type Name="AzureAsyncOperationResult" FullName="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult">
  <TypeSignature Language="C#" Value="public class AzureAsyncOperationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureAsyncOperationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureAsyncOperationResult" />
  <TypeSignature Language="F#" Value="type AzureAsyncOperationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="91b60-101">応答本文には、かどうかそれが成功したが進行中、または失敗を示すが、指定した非同期操作の状態が含まれています。</span><span class="sxs-lookup"><span data-stu-id="91b60-101">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is in progress, or has failed.</span></span> <span data-ttu-id="91b60-102">この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="91b60-102">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span> <span data-ttu-id="91b60-103">非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="91b60-103">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span> <span data-ttu-id="91b60-104">非同期操作に失敗した場合、応答本文には、失敗した要求とエラーに関する情報、エラーの HTTP ステータス コードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="91b60-104">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request and error information regarding the failure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="91b60-105">AzureAsyncOperationResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="91b60-105">Initializes a new instance of the AzureAsyncOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureAsyncOperationResult (string status = null, Microsoft.Azure.Management.Network.Fluent.Models.Error error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.Network.Fluent.Models.Error error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.#ctor(System.String,Microsoft.Azure.Management.Network.Fluent.Models.Error)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult : string * Microsoft.Azure.Management.Network.Fluent.Models.Error -&gt; Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Network.Fluent.Models.Error" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="91b60-106">Azure の非同期操作の状態です。</span><span class="sxs-lookup"><span data-stu-id="91b60-106">Status of the Azure async operation.</span></span> <span data-ttu-id="91b60-107">使用可能な値が: '処理中'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="91b60-107">Possible values are: 'InProgress', 'Succeeded', and 'Failed'.</span></span> <span data-ttu-id="91b60-108">使用可能な値が含まれます: '処理中'、'成功', '失敗'</span><span class="sxs-lookup"><span data-stu-id="91b60-108">Possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span></param>
        <param name="error">To be added.</param>
        <summary>
            <span data-ttu-id="91b60-109">AzureAsyncOperationResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="91b60-109">Initializes a new instance of the AzureAsyncOperationResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.Error Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.Error Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Error" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Network.Fluent.Models.Error with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AzureAsyncOperationResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91b60-110">取得または Azure の非同期操作の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="91b60-110">Gets or sets status of the Azure async operation.</span></span> <span data-ttu-id="91b60-111">使用可能な値が: '処理中'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="91b60-111">Possible values are: 'InProgress', 'Succeeded', and 'Failed'.</span></span> <span data-ttu-id="91b60-112">使用可能な値が含まれます: '処理中'、'成功', '失敗'</span><span class="sxs-lookup"><span data-stu-id="91b60-112">Possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>