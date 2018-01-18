<Type Name="ClientRequestIdProvider" FullName="Microsoft.Azure.Batch.ClientRequestIdProvider">
  <TypeSignature Language="C#" Value="public class ClientRequestIdProvider : Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientRequestIdProvider extends Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ClientRequestIdProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientRequestIdProvider&#xA;Inherits RequestInterceptor" />
  <TypeSignature Language="F#" Value="type ClientRequestIdProvider = class&#xA;    inherit RequestInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="55c06-101">として設定するクライアント要求 id の生成に使用される関数を含むインターセプター<see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />です。</span><span class="sxs-lookup"><span data-stu-id="55c06-101">Interceptor which contains a function used to generate a client request id to set as <see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />.</span></span>
            <span data-ttu-id="55c06-102">これの複数のインスタンスがある場合、最後は wins を設定します。</span><span class="sxs-lookup"><span data-stu-id="55c06-102">If there are multiple instances of this then the last set wins.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientRequestIdProvider (Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,Guid&gt; generateClientRequestIdFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.Batch.Protocol.IBatchRequest, valuetype System.Guid&gt; generateClientRequestIdFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ClientRequestIdProvider.#ctor(System.Func{Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (generateClientRequestIdFunc As Func(Of IBatchRequest, Guid))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ClientRequestIdProvider : Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest, Guid&gt; -&gt; Microsoft.Azure.Batch.ClientRequestIdProvider" Usage="new Microsoft.Azure.Batch.ClientRequestIdProvider generateClientRequestIdFunc" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="generateClientRequestIdFunc" Type="System.Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="generateClientRequestIdFunc">
            <span data-ttu-id="55c06-103">クライアント要求 id を生成するために使用する関数。この関数は、再試行のため、指定した操作で複数回呼び出される場合があります。</span><span class="sxs-lookup"><span data-stu-id="55c06-103">A function used to generate the client request id.  This function may be called more than once for any given operation due to retries.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55c06-104">新しい初期化<see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" />要求の要求 id を設定するには、クライアントで使用するためです。</span><span class="sxs-lookup"><span data-stu-id="55c06-104">Initializes a new <see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" /> for use in setting the client request id of a request.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>