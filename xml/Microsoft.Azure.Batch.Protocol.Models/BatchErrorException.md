<Type Name="BatchErrorException" FullName="Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
  <TypeSignature Language="C#" Value="public class BatchErrorException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchErrorException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchErrorException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type BatchErrorException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33fd6-101">BatchError 情報で無効な応答にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="33fd6-101">Exception thrown for an invalid response with BatchError information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchErrorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.#ctor" />
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
            <span data-ttu-id="33fd6-102">BatchErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-102">Initializes a new instance of the BatchErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchErrorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorException : string -&gt; Microsoft.Azure.Batch.Protocol.Models.BatchErrorException" Usage="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="33fd6-103">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="33fd6-103">The exception message.</span></span></param>
        <summary>
            <span data-ttu-id="33fd6-104">BatchErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-104">Initializes a new instance of the BatchErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchErrorException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorException : string * Exception -&gt; Microsoft.Azure.Batch.Protocol.Models.BatchErrorException" Usage="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="33fd6-105">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="33fd6-105">The exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="33fd6-106">内部例外。</span><span class="sxs-lookup"><span data-stu-id="33fd6-106">Inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="33fd6-107">BatchErrorException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-107">Initializes a new instance of the BatchErrorException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.BatchError Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.BatchError Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As BatchError" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.Batch.Protocol.Models.BatchError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.BatchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33fd6-108">取得または body オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-108">Gets or sets the body object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpRequestMessageWrapper Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpRequestMessageWrapper Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpRequestMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33fd6-109">関連付けられている HTTP 要求に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-109">Gets information about the associated HTTP request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpResponseMessageWrapper Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpResponseMessageWrapper Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchErrorException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpResponseMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33fd6-110">関連付けられている HTTP 応答に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="33fd6-110">Gets information about the associated HTTP response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>