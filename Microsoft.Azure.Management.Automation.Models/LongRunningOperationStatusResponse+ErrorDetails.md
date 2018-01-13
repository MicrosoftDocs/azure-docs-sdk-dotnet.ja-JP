<Type Name="LongRunningOperationStatusResponse+ErrorDetails" FullName="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse+ErrorDetails">
  <TypeSignature Language="C#" Value="public class LongRunningOperationStatusResponse.ErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit LongRunningOperationStatusResponse/ErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class LongRunningOperationStatusResponse.ErrorDetails" />
  <TypeSignature Language="F#" Value="type LongRunningOperationStatusResponse.ErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2798a-101">非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="2798a-101">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request, and also includes error information regarding the failure.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2798a-102">ErrorDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2798a-102">Initializes a new instance of the ErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2798a-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2798a-103">Optional.</span></span> <span data-ttu-id="2798a-104">非同期要求が失敗したかどうか、管理サービス エラー コードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2798a-104">The management service error code returned if the asynchronous request failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse.ErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2798a-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2798a-105">Optional.</span></span> <span data-ttu-id="2798a-106">非同期要求が失敗したかどうか、管理サービスのエラー メッセージが返されます。</span><span class="sxs-lookup"><span data-stu-id="2798a-106">The management service error message returned if the asynchronous request failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>