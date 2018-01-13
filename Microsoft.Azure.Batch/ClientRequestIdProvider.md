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
            として設定するクライアント要求 id の生成に使用される関数を含むインターセプター<see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />です。
            これの複数のインスタンスがある場合、最後は wins を設定します。
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
            クライアント要求 id を生成するために使用する関数。この関数は、再試行のため、指定した操作で複数回呼び出される場合があります。
            </param>
        <summary>
            新しい初期化<see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" />要求の要求 id を設定するには、クライアントで使用するためです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>